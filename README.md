# Fiber Coupled Laser Illumination


This project is an open source system for fiber coupled illumination in microscopy. This system features lasers with various wavelengths coupled in a single optic fiber, enabling easy digital selection without any structural modifications. The document includes a list of required materials, step-by-step assembly instructions, and configurations.

Our goal is to provide a fully functional, research-grade equipment that delivers excellent performance. The system is modular, allowing individual parts to be repurposed and improved in the open source hardware sense, and easily combined, exchanged, or used on their own.

## Table of Contents

1. General Description
2. Specifications
3. Materials
   - Lasers
   - Electronics
   - 3D models
4. Montage
5. Configurations
6. Usage

## General Description
Image of the entire montage with labels [This is not the final montage yet]
![This is an image](Images/montage.jpg)

## Specifications

[This section contains operation details]

## Materials
### Lasers

- **Fiber Combiner:** 4x1mm fiber combiner, multimode coupler to use with 400-700nm wavelength. 
   - Input fiber: 105um core diameter, 0.22 NA, FC/PC connectors, 1 meter length
   - Output fiber: 200um diameter,0.22 NA, FC/PC connectors, 1 meter length
   - https://www.lfiber.com/uv-vis-nir-fiber-combiner-optical-power/
   
- **Laser Drivers:** 
   - Laser Diode Driver GCF-D-R500A
   - Laser Diode Driver GCF-D-R800A
   - Laser Diode Driver GCF-D-R4000A
   - http://www.micost-optotech.com/products.asp?did=75
   
- **Laser Diodes:**
   - 405nm/300mW 105um Fiber Coupling Diode
   - 488nm/55mW 105um Fiber Coupling Diode
   - 638nm/700mW 105um Fiber Coupling Diode
   - 638nm/185mW 4um Fiber Coupling Diode
   - [supplier link]

- **12V Power Supply**

### Optomechanics 
3D models can be found in: Fiber-Coupled-Laser-Illumination/3D Models/

- **Driver Mounting Plate:** Plastic mounting plate to fix the drivers to the optic table.

![This is an image](Images/Drivers.png)

- **12V Power Supply Mounting Plate:**  Plastic mounting plate to fix the power supply to the optic table.

 ![This is an image](Images/powersupply.png)
 
 - **Fiber Trays:** Plastic trays to protect optic fiber from damage. This mountage uses four single trays and one double tray.
 
## Configurations

## Usage

## Contribute

As an open collaborative project, we warmly welcome your participation. Please feel free to leave comments, provide input, and make contributions. If you have any suggestions to improve it or add any additional functions make a pull-request or [open an issue](https://github.com/LIBREhub/fiber-coupled-laser-illumination/issues/new).
For interactions in our team and with the community applies the [GOSH Code of Conduct](https://openhardware.science/gosh-2017/gosh-code-of-conduct/).

## References

- Li, H., Krishnamurthy, D., Li, E., Vyas, P., Akireddy, N., Chai, C., & Prakash, M. (2020). Squid: Simplifying Quantitative Imaging Platform Development and Deployment. BioRxiv. https://doi.org/10.1101/2020.12.28.424613 
- P. (s. f.). GitHub - prakashlab/octopi-driver-board: Driver electronics for the Octopi and Squid microscope families. GitHub. https://github.com/prakashlab/octopi-driver-board

## License

[CERN OHL 2W](LICENSE) © Vicente Parot. This project is Open Source Hardware - please acknowledge us when using the hardware or sharing modifications.

