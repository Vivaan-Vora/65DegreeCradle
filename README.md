# 65DegreeCradle

## Overview

65DegreeCradle is a single-part parametric phone cradle designed in Onshape for desk use and FDM 3D printing. The geometry holds a phone at a fixed 65° viewing angle, routes a charging cable through the base, and keeps every major dimension tied to named variables so the design can be resized without rebuilding features manually.

The part was built around three engineering priorities: stable support under phone weight, usable cable routing during charging, and printable geometry with filleted edges and consistent wall thickness.

## Features

- Fixed 65° viewing angle for comfortable screen visibility
- Integrated cable cutout at the base for charging while seated
- Wide, weighted base for stability during use
- Filletted edges and printable wall thickness suitable for FDM output
- Fully parametric variable table for rapid design iteration

## Technical Specifications

| Parameter | Value | Description |
|-----------|-------|-------------|
| phone_width | 78 mm | Width of phone slot |
| phone_depth | 10 mm | Depth of phone slot |
| stand_angle | 65 deg | Cradle viewing angle |
| base_depth | 80 mm | Front to back depth of base |
| base_height | 12 mm | Height of base platform |
| fillet_radius | 3 mm | Edge fillet radius |
| cable_cutout_width | 20 mm | Width of cable cutout |
| cable_cutout_height | 14 mm | Height of cable cutout |

Full parameter notes are documented in [docs/parameters.md](docs/parameters.md).
