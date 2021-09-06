# ThinkPad-X1-Carbon-5th-gen-Hackintosh
ThinkPad X1 Carbon 5th gen EFI

Notice: The Monterey EFI will come without airportitlwn cuz github fails to upload the EFI with it inside (https://github.com/OpenIntelWireless/itlwm/releases/download/v2.0.0/AirportItlwm_v2.0.0_stable_Monterey.kext.zip) <---- official repo link to the monterey compatible kext

This is Mostly and effort of mine to actively backup my EFIs, though you're free to use them I can't guarantee everything will work correctly (Even if we have the exact same hardware),

#My Model:

My Model is Equipped with an I7-7600U, with HD 620 (not UHD 620) 16GB of RAM, a Toshiba NVMe drive, Intel WiFi & Bluetooth and Conexant CX8200 audio

I have tested this EFI in both macOS Big Sur (11.2 to make the USBmap that I subsequently lost, I'm gonna make it again, I promise) and macOS Monterey (Beta 6)

They both have varying degrees of annoyances (aka stuff I haven't fixed yet) and those are 

(macOS Big Sur)
![Capture_decran_2021-09-04_a_3 03 31_PM](https://user-images.githubusercontent.com/76212533/132252086-d36c3e65-43b0-491f-a2f3-179248bdbfb6.png)


What works:

Sound/Mic

Sleep/wake (hibernation turned off, pesky TB3 doesnt let it happen sadly)

iServices (I have a really loaded appleID, this might not work for you)

USB-A Hotplugging, (can only confirm in the USBmap that I lost)

HDMI Hotplugging

WiFi and Bluetooth (airportitlwn has working handoff and universal clipboard, which blew my mind)

Working Battery Percentage

Wired Sidecar (dunno why it times out when trying wireless) 

Internal Periferals behave gloriously with the combination of VoodooPS2 and VoodooRMI

Camera

(What Kinda works:

USB- C hotplugging, I have TB3 turned in the BIOS, this is most likely the reason why its so broken kekw

(What doesn't work:

Brightness control: I seriously can't figure it out, most i got as sign of my effort was that the display wasnt recognized as a generic monitor anymore, the slider did appear to work but it doesnt do anything sadly

Thunderbolt 3: I'm dumb so this is gonna take a while to be fixed (If i even attempt to do it at all)

Fingerprint reader: Not a surprise, (if only booting macOS, I would recommned you disable it in the BIOS, it'll help you save some battery life)




macOS Monterey (b6)
![Capture_decran_2021-09-05_a_2 54 10_PM](https://user-images.githubusercontent.com/76212533/132252022-39252a8c-8de8-4a5f-abac-d971d2b6977d.png)


So i'll just copy paste what works and just remove it according to what's broken lol 

What Works

Sound/Mic

Sleep/wake (hibernation turned off, pesky TB3 doesnt let it happen sadly)

iServices (I have a really loaded appleID, this might not work for you)

USB-A Hotplugging, (Kinda, it's really finicky)

WiFi (yes no BT on monterey, i have no idea why, i added BlueToolFixup and it still didnt work with the Fabled USBMap)

Working Battery Percentage

Wired Sidecar (dunno why it times out when trying wireless) 

(What Kinda works:

USB C only works when plugging the devices in before booting the computer kekw

(what doesnt work:

Camera

BT (and without bt the continuity features dont work

Brightness control: I seriously can't figure it out, most i got as sign of my effort was that the display wasnt recognized as a generic monitor anymore, the slider did appear to work but it doesnt do anything sadly

Thunderbolt 3: I'm dumb so this is gonna take a while to be fixed (If i even attempt to do it at all)

Fingerprint reader: Not a surprise, (if only booting macOS, I would recommned you disable it in the BIOS, it'll help you save some battery life


(little secret, french and spanish translations eta son)
