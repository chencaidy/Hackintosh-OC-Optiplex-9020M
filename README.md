# Hackintosh-OC-Optiplex-9020M

## 平台配置
* 准系统：Dell Optiplex 9020M
* CPU：Intel Core i7-4860EQ (Crystal Well)
* GPU：Intel Iris Pro Graphics 5200
* 网卡：Dell DW1820A
* 内存：16GB

## 特性
* 仿冒机型：Macmini7,1（SN已去除，需自行补充）
* 系统版本：Big Sur 11.2.2
* 显示正常，显卡FB：0D220003，VRAM：1536MB，端口限制：2（去除不存在的0105端口防止开机卡顿）
* 内置扬声器正常，前置耳机输出正常，声卡ID：27
* WiFi正常，使用#a地区
* 蓝牙正常，支持接力
* 睡眠正常，支持电能小憩
* USB端口正常，去除无效端口，端口属性正确修正
* EC（SMC）正常，支持风扇转速报告
* CPU电源管理正常，支持功率报告
* 支持开机音效
* 电源按钮正常，短按1S睡眠，长按>3S弹出关机对话框

## BIOS配置（版本：A19）
* 恢复出厂设置：Load Defaults
* 关闭VT-d
* 关闭CFG Lock：0xD9F 0x0
* 设置64M预分配显存：0x263 0x2

## 更新日志
### 2021-3-8
* 修复电源按钮
### 2021-3-6
* 更新OpenCore 0.6.7
* 更新AppleALC 1.5.8
* 更新BrcmPatchRAM 2.5.7
* 更新VirtualSMC 1.2.1
* 更新WhateverGreen 1.4.8
### 2021-2-28
* 更新到OpenCore 0.6.6
* 支持Big Sur
