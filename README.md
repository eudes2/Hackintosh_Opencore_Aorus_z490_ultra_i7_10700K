<a href="https://dortania.github.io/OpenCore-Install-Guide/">
  <img src="https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Logos/OpenCore_with_text_Small.png" width="200" height="48"/>
</a>



## EFI folder made with Opencore release 0.7.1 and used to boot on an Aorus z490 Ultra motherboard with an i7-10700K CPU. Do not use this EFI folder if you don't have exactly the same setup.

### Installation

*  Mount USB drive EFI system partition. This is automatically made when you format with GUID but is unmounted by default, use CorpNewt's [MountEFI](https://github.com/corpnewt/MountEFI).

*  If you need to modify config.plist, use CorpNewt's [Propertree](https://github.com/corpnewt/ProperTree).

*  You have to change the SMBIOS info inside Root/PlatformInfo, use CorpNewt's [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS). Run GenSMBIOS, pick option 2 and drag your config.plist file then pick option 1 for downloading MacSerial and Option 3 for selecting out SMBIOS. It should be iMac20,1 for i7-10700K (and lower; for i9-10850K and higher use iMac20,2).

*  Follow the Opencore instruction for the UEFI BIOS settings [(Tutorial)](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#intel-bios-settings).

*  Enjoy! 



