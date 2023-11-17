# MSI_GF63_EFI_OpenCore
 Opencore config for Hackintosh on MSI GF63 thin 10

Works:

- Video (integrated. Nvidia RTX is fully disabled)
- Backlight control
- HDMI output(only video, sound is not working)
- Fan control (automatic on high load) - use MSI Fan Control to set spin of fan depending on load.
(I've to compile it myself with Xcode). Here's the link: https://github.com/kykc/MsiFanControl
- sound (in and out)
- Wi-Fi (Intel)
- Bluetooth (partly working,- JBL acoustic connects and plays flawlessly, but connecting with the phone with bluetooth does not work)
- Trackpad (with multitouch gestures working absolutely fine)
- Battery


Other comments:
Well, I myself switched wifi to Broadcom with an adapter. But this EFI works good with native one (intel ax201).

You need to put your model and other sensitive data to config.plist before booting with this EFI.

I recommend using OCAT - open core auxiliary tools. Just a great thing!!!





