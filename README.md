# Open-Source-Leg Redesign

Welcome to the Open-Source Leg v2.0 [(OSL 2.0)](https://www.opensourceleg.org/) **Redesign** project! This README provides an overview of the redesigned hardware components, highlights the key changes made to improve manufacturability, cost-effectiveness, and functionality.

## Table of Contents

- [Project Overview](#project-overview)
- [Key Hardware Design Changes](#key-hardware-design-changes)
  - [Modular Design](#modular-design)
  - [Standardized Components](#standardized-components)
  - [Manufacturability Enhancements](#manufacturability-enhancements)
  - [Material Optimization](#material-optimization)
  - [Cost Reduction Strategies](#cost-reduction-strategies)
  - [Durability and Safety Improvements](#durability-and-safety-improvements)
- [Compliance with CERN-OHL-P-2.0](#compliance-with-cern-ohl-p-20)
- [Getting Started & Contributing](#getting-started-&-contributing)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Project Overview

The Open-Source Leg Prosthesis v2.0 (OSL 2.0) is an academic-level, highly modular prosthetic leg designed to enhance accessibility, reduce costs, and improve functionality in prosthetic technology. Building upon the original OSL 2.0 design, this version introduces significant hardware modifications aimed at simplifying manufacturing processes, utilizing standard components.

## Key Hardware Design Changes

### Modular Design

- **Flexible Configurations:** The redesigned OSL 2.0 supports both left and right leg amputations as well as dual transtibial applications. This is achieved through a unified housing design and adjustable components, allowing for easy reconfiguration without the need for distinct left and right versions.
- **Adjustable Range of Motion (ROM):** Both ankle and knee joints now feature an adjustable ROM of 240°, up from the fixed 60° and 120° in the original design. Brass inserts facilitate this adjustability, enhancing adaptability to various user needs.

### Standardized Components

- **Metric System Adoption:** All components are converted to metric measurements, aligning with global manufacturing standards. This simplifies procurement and reduces costs associated with sourcing specialized parts.
- **Off-the-Shelf Parts:** Complex, custom components such as the Pyramid Adapter and Serial Elastic Actuator (SEA) have been replaced with standardized, commercially available parts. For example, the SEA has been substituted with a rigid module, and ultra-thin ball bearings have been replaced with standard DIN 625 SKF 61805 bearings.

### Manufacturability Enhancements

- **Simplified Geometry:** Key components have been re-engineered to feature flat surfaces, rectangular corners, and toolpath-friendly roundings. Complex features like slanted walls and rounded edges have been eliminated to streamline CNC machining processes.
- **Design for Manufacturing (DFM):** Implemented DFM principles to reduce geometric complexity, minimize machining time, and simplify assembly procedures. Features such as pillars and end-stops are integrated into the housing to enhance manufacturing efficiency.

### Material Optimization

- **Increased Material Variety:** The redesign incorporates a broader range of readily available materials, balancing durability and cost-effectiveness. Titanium adapters replace aluminum components where greater strength is required.
- **Wall Thickness Adjustments:** Wall thickness has been increased in necessary areas to ensure structural integrity while allowing for the use of less expensive materials like Al 5055 instead of higher-grade alloys.

### Cost Reduction Strategies

- **Reduced Manufacturing Time:** Simplifying component geometries and standardizing parts have led to a 40-70% reduction in manufacturing time and costs.
- **Minimized Labor Costs:** By replacing complex assemblies with simplified, all-in-one solutions, labor costs associated with machining and assembly have been significantly reduced.
- **Affordable Bearings and Maintenance:** Standard bearings are used instead of ultra-thin variants, lowering initial costs. Design features facilitate easier bearing replacement, promoting a maintenance strategy that prioritizes long-term cost-efficiency.

### Durability and Safety Improvements

- **Enhanced FEA Safety Factors:** Finite Element Analysis (FEA) confirms a safety factor of at least 1.107 under static loads, a substantial improvement over the original OSL 2.0 design. This ensures the prosthesis maintains structural integrity under expected usage conditions.
- **Robust Housing Design:** The housing has been redesigned to eliminate failure points identified in the original model, incorporating features that distribute loads more effectively and enhance overall durability.

## Compliance with CERN-OHL-P-2.0

The OSL 2.0 hardware design complies with the CERN Open Hardware License Permissive version 2.0 (CERN-OHL-P-2.0), ensuring that:

- **Open Access:** All design files, schematics, and documentation are openly available for use, modification, and distribution.
- **Attribution:** Proper attribution is maintained, acknowledging the original creators and contributors to the project.
- **No Additional Restrictions:** The design does not impose any additional restrictions beyond those specified in the CERN-OHL-P-2.0, promoting free and open collaboration.

For full details on licensing terms, please refer to the [LICENSE](LICENSE) file included in this repository.

## Getting Started & Contributing

To build or modify the OSL 2.0 prosthesis, follow the instructions from the [OSL Community](https://www.opensourceleg.org/).
Contributions to the OSL 2.0 project are welcome, following the community guidelines!
Please adhere to the [CERN-OHL-P-2.0](https://www.ohwr.org/project/cernohl) licensing terms when contributing.

## Acknowledgments

We extend our gratitude to the personnel of the Mechanics Workshop of the Faculty of Engineering at Friedrich-Alexander-Universität Erlangen-Nürnberg for their support and expertise. Special thanks to our research collaborators and the open-source community for their invaluable feedback and contributions.

## License

This project is licensed under the [CERN Open Hardware License Permissive version 2.0](https://www.ohwr.org/project/cernohl). See the [LICENSE](LICENSE) file for more details.

---

For any questions or further information, please contact the corresponding author at [marc.scheidl@fau.de](mailto:marc.scheidl@fau.de).
