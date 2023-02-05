# WAIS

Windows/Arch Installation Script for T510

Integrated:

* Cryptography support (LVM in LUKS)
* [Thinkpad T510](T510.md) support
* Rescue support [waiser](#WAISER)
* AUR support (paru)
* [Usage](#Usage1)
* [Usage](#Usage2)

## License

CC0-1.0 (Creative Commons Zero 1.0 Universal)

#### Windows Installation

-> Accept EULA
-> Activation Code <= Windows 8.1
-> Custom Installation (Save room for Arch Linux)
-> [Disable fast boot](#Disable fast boot)
#### Arch Linux Installation

-> WAIS
### Usage1 (Command line options)

> wais [-h|help] [-L|license] [-u|update] [-r|rescue] [-i|install] [-d|drive]

### Usage2 (Interactive menu)

> wais

![image](preview.mkv)

## Table of Contents

1. [T510 System](T510.md)
1. [References](references.md)

#### Windows notes

* Installing Windows first is highly __recommended__. You'll need an Activation Code if you're on an earlier version than Windows 10.
* Set up [BitLocker](#BitLocker) after the [WAIS](#WAIS) has set up [Arch Linux](https://archlinux.org).

##### BitLocker

__Windows BitLocker__ uses ? characters.

* Higher encryption can be set.
* You can save the key to a __printer__, a __usb device__ or onto a connected __drive__ other than the BitLocker Drive.
* BitLocker needs TPM (Trusted Platform Module) for hardware encryption to function. Software encryption can be enabled.

###### Disable fast boot.

-> Win+Q -> Search for "Power Management" -> Fast Boot -> Uncheck 

#### Arch Linux notes

#### WAISER

	Windows Arch Installation Script Encryption Rescue

* waiser is a cryptsetup wrapper and can decrypt a wais set up. It's hardcoded, so check the script.

See also [BitLocker](#BitLocker) for more information.
