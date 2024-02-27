## About RainCandy Technology Root CA certificates
关于雨糖科技自签证书（[中文介绍请看这里](http://raincandy.1337.moe/zrootca/)）。

## Notice
The "New RainCandy Technology Primary Root CA" (New_RCRoot.cer) is now deprecated, because it has been blacklisted by Microsoft Defender.<br>
(Microsoft Defender will report all files with digital signature signed by certificates issued by this Root CA as "potentially unwanted application" or "PUA".)<br>
This CA has been replaced by our "Modern Root Certificate Authority" (RainCandy_RootCA.cer)

## Introduction
We created these self-signed certificates for certain purposes.
* Add digital signatures to the binary files of our software development projects
* Encrypt Remote Desktop Protocol (RDP) connections
* Adjustable fake timestamp service for modified version of Windows Drivers

## List of our Root CA certificates
* BloodSnow_RootCA.cer - BloodSnow Studio Primary Root CA, used before 01/01/2017.
* MiracleNetwork_RootCA.cer - Miracle Network! Primary Root CA, used before 10/01/2022.
* Legacy_RCRoot.cer - Legacy RainCandy Technology Primary Root CA, used before 10/01/2022.
* New_RCRoot.cer - New RainCandy Technology Primary Root CA, used from 10/01/2022 to 02/12/2024.
* RainCandy_RootCA_Win_Legacy.cer - RainCandy Technology Root Authority for Windows, used before 10/01/2022.
* RainCandy_RootCA_Win.cer - RainCandy Technology Root Authority for Windows, used before 12/31/2022.
* RainCandy_RootCA_WinDrv.cer - RainCandy Technology Root CA For Windows Drivers, used before 01/06/2024.
* RainCandy_RootCA.cer - Modern RainCandy Technology Root Certificate Authority, used from 01/06/2024.
