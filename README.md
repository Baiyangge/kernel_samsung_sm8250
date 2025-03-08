# Samsung Galaxy S20 Series KernelSU Next+Susfs Source

Samsung Galaxy S20/S20+/S20U KernelSU Next + Susfs (Snapdragon 865, Korea)

* x1q = Galaxy S20, y2q = Galaxy S20+, z3q = Galaxy S20U

* KernelSU Next Version : 12430(1.0.5) / Susfs Veriosn : 1.5.5

* Linux Kernel Version : 4.19.113 (Non-GKI)

* Kernel Base : Android 13 + One UI 5.1 Stock rom

* Only Working On Snapdragon 865 AP model

* Do Not WOKRING Exynos Device

* This Kernel is disabled config_RKP/KDP, config_security_defex, config_proca, config_cfp

# Installtion
1. Unlock Bootloader in Download mode
2. Enable OEM unlock and USB Debuging in Develop Option, and go to Download mode
3. Flash TWRP and vbmeta_disabled with Samsung Odin
4. Go to Recovery (TWRP), Wipe Format Data -> go to Advanced -> Dalvik/Art Cache and Cache Wipe
5. Install "multidisabler-samsung-3.2.zip" and "x1q/y2q/z3q_ksun_susfs.zip" and reboot
6. After boot, Install KernelSU Next apk -> Install Susfs module in KSUN APP -> Check installed ksun root and susfs

More details : https://xdaforums.com/t/kernel-kernelsu-next-susfs-file-galaxy-s20-s20-s20u-for-snapdragon.4721495/

# Source
* Samsung Open Source : https://opensource.samsung.com/main
* KernelSU Next : https://github.com/KernelSU-Next/KernelSU-Next
* Susfs : https://gitlab.com/simonpunk/susfs4ksu/-/tree/kernel-4.19?ref_type=heads
* AnyKernel : https://github.com/osm0sis/AnyKernel3
* Clang : https://github.com/droidian/android-platform-prebuilts-clang-host-linux-x86-29.git
* Integrity for Non-GKI Kernel : https://kernelsu.org/guide/how-to-integrate-for-non-gki.html
