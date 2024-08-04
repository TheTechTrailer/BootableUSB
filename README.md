# The.TechTrailer.org Bootable USB

Welcome to the GitHub repository for creating a bootable USB drive, originally made for [Repair Share Foyle](https://repairsharefoyle.org/). This guide will help you create a versatile bootable USB drive using the Ventoy tool and the TechTrailer ISO.

## Requirements

- A USB drive with a capacity of more than 16GB.
- A computer to perform the setup.
- An internet connection to download necessary files.

## Steps to Create the Bootable USB

### Step 1: Prepare the USB Drive

1.1. **Download and Install Ventoy**

1.2 Follow the [Ventoy Guide](https://www.ventoy.net/en/doc_start.html) to download and install Ventoy on your USB drive. Ventoy allows you to boot multiple ISO files from a single USB drive.

### Step 2: Download the TechTrailer ISO

2.1. **Download the TechTrailer ISO File**

2.2  Download the TechTrailer ISO from the following link: [TechTrailer.iso]([https://raw.githubusercontent.com/TheTechTrailer/BootableUSB/main/TechTrailer.iso](https://drive.google.com/drive/folders/1YpXacUijN4KrSnng_Fzw2qPI0MYfmBB6?usp=sharing))

2.3  Save this ISO file to your Ventoy USB drive.

### Step 3: Create Your Own Windows Unattended ISO

3.1. **Prepare an Unattended Windows ISO**

3.2  ~~Use the provided `autounattend.xml` file to create a custom Windows unattended installation ISO. (Link will be provided here soon)~~
3.2  [Windows.iso]([https://raw.githubusercontent.com/TheTechTrailer/BootableUSB/main/TechTrailer.iso](https://drive.google.com/drive/folders/1YpXacUijN4KrSnng_Fzw2qPI0MYfmBB6?usp=sharing))
3.3  Copy your custom Windows unattended ISO to the Ventoy USB drive.

### Step 4: Boot and Follow the On-Screen Guide

4.1. **Boot from the USB Drive**

4.2  Insert the USB drive into the computer you wish to repair or install Windows on. Boot from the USB drive and follow the on-screen guide provided by Ventoy and first select the TechTrailer ISO. Once that has completed it's steps, one of which will copy the hardware report to the USB drive and then erase all 'fixed' drives (HHD/SSD)

4.3 Now reboot, and select the automated Windows Install.

## Additional Resources

- [Ventoy Official Documentation](https://www.ventoy.net/en/doc_start.html)
- [Repair Share Foyle](https://repairsharefoyle.org/)

## Contact

For support or questions, please contact us through our [GitHub Issues](https://github.com/TheTechTrailer/BootableUSB/issues) page or the usual groups.

---

Thank you for using The.TechTrailer.org Bootable USB guide!
