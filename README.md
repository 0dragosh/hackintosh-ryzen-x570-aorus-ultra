# hackintosh-ryzen-x570-aorus-ultra

Hackintosh on Ryzen, hardware used:

* Ryzen 5900x

* Gigabyte Aorus X570 Ultra

* 5700XT

* Fenvi T919 for BT/WIFI

* ASUS XG-C100C 10G NIC with patch for Monterey

# READ THIS!

You'll need to go into config.plist and generate your own SMBios using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).

Really only attempt to run this if you have the **exact same hardware**, particularly the motherboard. If you don't have a 12 core Ryzen CPU you'll need to change the number of cores in the AMD Vanilla patch, google how to do that.
