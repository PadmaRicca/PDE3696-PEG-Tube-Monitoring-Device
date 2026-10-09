# MoTect: a PEG Tube Force-Monitoring Device

Developed an early-stage, non-invasive medical device concept intended to detect potentially hazardous pulling forces on Percutaneous Endoscopic Gastrostomy (PEG) feeding tubes, particularly in patients in coma whose involuntary movements may cause accidental tube displacement and associated complications.

The proposed system comprised a wearable sensing device, an individual bedside monitor and a central monitoring interface at the nurses' station. The investigation followed the Engineering Design Process (EDP), combining medical-device design considerations, mechanical engineering, embedded electronics and preliminary experimental testing to evaluate the concept's feasibility and technical limitations.

## Project information
**Author:** Padma Michela Ricca
**Student Number:** M00865397  
**Dissertation Title:** Design and test of a device detecting the potential movements of Percutaneous Endoscopic Gastrostomy tubes in order to prevent consequent complications in patients. 
**Dissertation Outcome:** 3 (First Class, Distinction)    
**Supervisors:** Vania Gomes de Almeida and Puja Varsani  
**Programme:** BEng (Hons) Biomedical Engineering  
**Institution:** Middlesex University London 
**Module Code:** PDE3696 
**Academic Year:** 2024/2025  

## Contributions

- Conducted clinical and market research, reviewed relevant UK medical-device legislation and technical standards, and developed a Product Design Specification (PDS) addressing functional, safety, ergonomic and regulatory considerations.
- Generated five alternative design concepts in SOLIDWORKS and applied a weighted decision matrix to select the preferred solution, considering functionality, feasibility, modularity, feeding-tube integrity, ergonomics and ease of use.
- Produced detailed three-dimensional CAD models, mechanical assemblies and engineering drawings following BS 8888 technical drawing principles.
- Designed, 3D-printed and iteratively refined experimental components for feeding-tube retention and load-cell mounting, identifying mechanical weaknesses, dimensional constraints and assembly limitations.
- Developed Arduino-based firmware using C++ and constructed a force-sensing circuit integrating an Arduino Uno, HX711 amplifier, single-point load cell, RGB LED and piezoelectric buzzer. Programmed force-dependent warning responses and serial monitoring of event severity, magnitude and duration.
- Conducted repeated static loading and unloading tests informed by ASTM E74, using Minitab to investigate sensor accuracy, repeatability, regression behaviour and measurement uncertainty. Critically evaluated the resulting measurement errors and limitations preventing reliable dynamic testing.
- Created the MoTect device identity, derived from "Movement Detection", and incorporated its name into the proposed mechanical design. Considered product differentiation, future commercialisation and potential intellectual property protection as part of the wider development strategy.
- Produced a technical dissertation and academic research poster, and delivered a viva presentation explaining the design decisions, experimental methodology, findings and opportunities for further development.

## Skills Demonstrated
- **Engineering Design and Regulatory Awareness:** Systematic application of the EDP, requirements development, technical trade-off evaluation and consideration of medical-device legislation and standards.
- **Mechanical Design and Fabrication:** SOLIDWORKS, 3D CAD modelling, mechanical assemblies, technical drawings, additive manufacturing and iterative prototyping.
- **Embedded Systems and Programming:** Arduino Uno, C++ programming, Arduino IDE, HX711 interfacing, electronic circuit development and sensor-based alarm logic.
- **Experimental Testing and Statistical Analysis:** Force-sensor calibration, repeated-load testing, Minitab, linear regression, measurement error and uncertainty analysis.
- **Technical Documentation and Communication:** Cirkit Designer, draw.io, engineering documentation, academic report writing, scientific poster development and viva presentation.
- **Innovation and Commercial Awareness:** Product identity development, design differentiation, intellectual property considerations and critical evaluation of further development requirements.

## Results and Limitations

The experimental investigation involved five complete loading and unloading runs across eight nominal force levels, evaluating the performance of the single-point load cell and its suitability for the proposed monitoring application.

The sensor demonstrated repeatable measurements at lower forces, with standard deviations below 0.01 N up to approximately 20 N. However, accuracy deteriorated at higher loads, producing a mean measurement error of approximately -1.8 N and an expanded uncertainty of approximately ±3.6 N across the tested range. These findings revealed systematic under-reading and insufficient measurement reliability for clinical use.

The Arduino-based alarm system demonstrated programmed visual and audible responses to predefined force thresholds. Nevertheless, mechanical slippage of the simulated feeding tube within the 3D-printed grip prevented reliable dynamic testing, while the complete three-component monitoring system remained at the conceptual stage.

The investigation therefore established an initial engineering framework and identified improvements required in sensor selection, mechanical retention, material suitability and further experimental validation. The device was not clinically validated or suitable for patient use.

## Use and Licensing

This repository is provided for academic review and documentation of the dissertation project. No open-source license has been selected, therefore, standard copyright applies.

## Report and Code Availability

The original academic dissertation, research poster, Arduino source code, engineering drawings and supporting materials are currently withheld from public access to uphold academic integrity.

This repository provides an overview of the project's objectives, engineering design approach, physical prototyping, experimental methodology, technical skills and principal findings.

The dissertation may be made available upon request, in accordance with the University's policy.
