# Asus X515J Ice Lake Hackintosh Opencore EFI

## Information

To use this EFI, you will need to generate your own SN/UUID using [GenSMBIOS](https://github.com/corpnewt/gensmbios) from CorpNewt, utilising [this](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html#platforminfo) guide for more information.

This EFI has support for Intel Wi-Fi, so if you have any other Wi-Fi card, you would need to tweak the EFI to your needs.

This EFI has support for Intel Bluetooth, so if you have any other Bluetooth card, you would need to tweak the EFI to your needs.

This EFI also does not have any Ethernet Kexts, so you would have to find those on your own.

My computer does not have a sound codec and it has internally USB connected speakers, if you have a codec, you would need to add the alcid=(number needed for your codec which you can find [here](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs)

# Laptop Specifications

Intel(R) Core(TM) i7-1065G7 (Ice Lake)

16GB RAM

500GB Storage (micron nvme)

Intel Wireless AC 8260

No ethernet controller

PS/2 Keyboard

ELAN 1200 Trackpad

Integrated GPU (Intel(R) Iris(R) Plus Graphics)

Internally connected USB Speakers


# What Works

Keyboard Backlight

Keyboard

Sleep

Intel Wi-Fi

Intel Bluetooth

Trackpad (with some caveats)

Sound

Graphics acceleration

All USB Type A Ports

USB-C Port

Battery readout

Brightness keys

# What doesen't work

Microphone (Mine is intel SST, which will never be supported in hackintoshing but yours might not be and you might need to experiment with applealc)

Camera (Yours also might work OOB)

HDMI (Will never work with any Ice Lake hackintoshes)



