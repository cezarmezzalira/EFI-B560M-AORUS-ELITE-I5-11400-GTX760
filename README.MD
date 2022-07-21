# EFI-Hackintosh- B560M Aorus Elite - i5 11400 OEM

Sucessful Big Sur installation with 11th Generation CPU and B560M Aorus Elite motherboard

## Current System Info
- MacPro7,1
- MacOS Big Sur 11.6.8

## Hardware

|       Type       | Item                                          |
| :--------------: | --------------------------------------------- |
|     **CPU**      | [ Intel Core i5 11400 OEM ]                   |
| **Motherboard**  | [ B560M Aorus Elite ]                         |
|     **RAM**      | [ Corsair Vengeance LPX @3000Mhz ]            |
|     **GPU**      | [ Gigabyte GTX 760 Windforce 2 OC 2GB GDDR5 ] |
|     **SSD**      | [ KingSpec NVME 512GB ]                       |
| **Power Supply** | [ Corsair CX650M ]                            |
|     **Wifi**     | [ Fenvi Intel AX201 with Bluetooth ]          |

## Working hardware

- Audio: ALC897 - `AppleALC.kext` with boot-args `alcid=12`
- Wifi: `itlwm.kext`
- GPU: native working
- USB: `USBMap.kext` with my needs

## Important thing if you use this EFI:
Update **config.plist** in PlatformInfo > Generic with YOUR informations.
<br><br>
*1. MLB (Board Serial)
<br>
2. ROM (Mac Address)
<br>
3. SystemSerialNumber (Serial)
<br>
4. SystemUUID (SmUUID)*

Please use [*genSMBIOS*](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) for generate values for above itens.
<br>
Please use [*ProperTree*](https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip) for configure/edit your config.plist.
