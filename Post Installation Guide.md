## Now you're in macOS

#### 1. Go to download [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) & [Opencore Configuator](https://mackie100projects.altervista.org/download-opencore-configurator/)
#### 2. Use GenSMBIOS to generate a **"MacBookPro14,3"** config
--------------------
### 3. Use Opencore Configuator to enter the different values [(Tutorial)](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios)
### (**** Make Sure you have an "INVALID" Serial number)
--------------------
#### 4. Download [CodecCommander](https://github.com/Sniki/EAPD-Codec-Commander/releases/tag/v2.7.3)
#### Install hda-verb inside /usr/local/bin/
#### 
#### 5. Run this command [(Thx tunglamvghy)](https://github.com/tunglamvghy/AcerSpin5-SP513-54N-hackintosh)

<details><summary>CLICK ME</summary>
<p>

```ruby
hda-verb 0x19 0x707 0x20
```

</p>
</details>

#### 6. Fixing ROM [(Just follow this guide)](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#fixing-rom)

#### 7. Copy AppleALC.kext from EFI/OC/Kexts into /Library/Extension/

#### 8. Download [MountEFI](https://github.com/corpnewt/MountEFI) and copy the EFI Folder from USB into EFI partition

#### 9. Reboot and your macOS is completed

## [Windows Installation Guide](https://github.com/Bug-nana/Hackintosh-Acer-Spin5-54N/blob/main/Windows%20Installation%20Guide.md)
