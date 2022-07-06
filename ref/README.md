## Mobile Testing Guide

(LICENSE: Still trying to decide - but not "open-source" for now.)

wip wip

***Disclaimer: I am not an expert. These are just random tidbits I gleaned from trial and error. Consult at your own peril.***


You need a lot of patience and a medium-high level of frustration tolerance, cos things can get very fiddly.


### Device Selection

Google devices commonly recommended, due to good dev support - ie firmware readily available, flashing friendly etc.
- Google dev firmware lacks Google Play... etc wip

Apparently some devices (eg HTC? Samsung?) are very locked down - need to request code from manufacturer to unlock bootloader etc. Avoid these


_WIP Note - Some Google devices lack some useful settings like specific WiFi settings etc... TBC_


#### Device Ideal Characteristics

- Massive screen 
- Removable external battery - provides a quick and surefire way to shutdown/reboot your phone, especially when the UI is not responsive.
- SD Card slot - easy and reliable way to transfer files to/from device

##### Nice to haves
-eSIM? Because... wip


### Useful Toolkit

- Bluetooh keyboard - ideally with multi-device support. Reduces much pain of entering strings by tapping on screen

- Preferably a Mac if doing iOS testing, preferable Intel

- A capable network switch/router
  - Port mirroring, VLANs, can set custom DHCP/Routing/DNS
  - Network Tap stars (alternatively an old-school non-switching network hub from your junk pile. Good luck finding one available retail)
  - General-purpose dumb switches (eg $20 TP-Links will do)
  - Ethernet patch cables of various lengths, or DIY crimping

- Faraday bag for all your devices (paranoid maybe, but good practice)


##### Recommended Networking/Switching Gear
- old good Ciscos (Fast Ethernet (ie 100Mbit) ok - no need for Gbe)
  - Not recommended unless you're a network engineer (which I'm admittedly not)
- old HP Procurves Layer-2 managed (insert models)
  - Cheaply available (US$30 on eBay now and then)
  - Quite easy to setup.
- Mikrotiks (***Highly Recommended***)
- wip....
- Or some old desktop w/ pfSense over ESXi and multiple NICs
  - Avoid running pfSense baremetal - reasons (WIP)
    - Limited hardware support on BSD, esp NICs/Radios
    - wip...
- Good WiFi AP/Bridge


You want to have the ability to toggle/tweak network routing on-the-fly. 
Various reasons
  - Some apps/OS won't work properly without internet access to certain sites, but due to various protections (HSTS/SSL pinning etc), can't interfere/intercept these ones via Burp...
  - You want fine-grained control of network access - Reasons: security, selective capturing/elimination, segregation
  - wip Add note on ThreatMetrix etc (TBC)

Note: 
this is why having eSIM support is handy - so you can flick mobile data on for internet access when required, until you've figured out the networking setup.


Pro-tips:
- Set up SSH server and authorized_keys on device, then you easily SSH into device over your internal network/wifi.
- Use SSHFS to mount device filesystem - so you can access/read/write as if it's a local drive (saves using adb push/pull etc)
- Caution: WiFi can be very unsteady, so whenever possible, physical cable is the gold standard
  - Use a good quality cable!!!!


##### Networking Voodoo Tricks

###### TCP/IP Primer
(Note to self: need to limit content here, too much to cover, and too much I don't fully understand...)

wip wip
 
- DHCP Option Sets
- ICMP Forward/Redirect
- 

###### Network Capture 

Several different approaches, depending on need:
- rouge DNS (pfSense unbound/BIND/Mikrotik setup guide)
- netwowrk gateway (ie DHCP Option 3)
- iptables
- wip... burp invisible proxy...
- Local OpenVPN server/or mitmproxy (latter lacking when cf burp)
- Port mirroring/network tap
- on-device proxy
- ....


##### Wireless Voodoo
wip

WPA PSK quirks on iPhones... wip


### Setup Steps
wip wip

- Install root CA cert (wip insert guide/steps/walkthrough...)

- Setup network captures ((wip insert guide/steps/walkthrough...)

- VMs, tools: mobsf, JADX etc...


### TBC topics
iptables
burp
mitmproxy
wireshark/tcpdump
objection
frida 
ios rvictl
new burp mobile app/extension?? (untested)
VMs - Genymotion, Android Emulator....


-----------
