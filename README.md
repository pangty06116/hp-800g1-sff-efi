hp惠普EliteDesk 800g1 sff sonoma 14.7.4 OpenCore efi
这是一个基与OpenCore9.0(https://github.com/acidanthera/OpenCorePkg)的引导的EFI文件， 驱动采用注入+OpenCore-Legacy-Patcher(https://github.com/dortania/OpenCore-Legacy-Patcher)
配置： CPU ntel(R) Xeon(R) CPU E3-1270 v3 @ 3.50GHz  显卡 amd rx560  内存 16G  网卡：博通Broadcom BCM43xx  硬盘 512G（国产)
关闭SIP,目前一切完美驱动。睡眠唤醒正常，声音正常。
注意事项：14系统蓝牙和我Wi-Fi无法驱动，需要注入OpenCore-Legacy-Patcher补丁
该efi文件可以完美升级到15版本系统，但需要重新注入OpenCore-Legacy-Patcher补丁。
仿冒机型：Mac Pro 2019  Macpro7.1
