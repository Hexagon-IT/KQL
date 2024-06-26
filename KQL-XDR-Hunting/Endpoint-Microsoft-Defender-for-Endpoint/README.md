# Endpoint-related KQL queries
<a href="https://twitter.com/kj_ninja25"><img alt="X (formerly Twitter) Follow" src="https://img.shields.io/twitter/follow/kj_ninja25"></a>
<a href="https://www.linkedin.com/in/kijo-girardi/"><img src="https://img.shields.io/badge/-Linkedin-0077B5.svg?logo=linkedin&style=popout"></a>
<a href="https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/"><img src="https://img.shields.io/badge/Azure-KQL-00B2FF.svg?logo=microsoftazure&style=popout"></a>
<a href="https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/"><img src="https://img.shields.io/badge/Azure%20Data%20Explorer-%230078D4.svg?&style=popout&logo=azure%20data%20explorer&logoColor=white"/></a>

Thank you for visiting @LearningKijo KQL repository. 
In this repository, I am excited to share email-based out-of-the-box queries related to ***Microsoft Defender for Endpoint (MDE)*** and ***Microsoft Defender Antivirus (AV)***.

| Product | Feature   | KQL query |
|:--------|:----------|:----------|
| AV      | Detection | [01-AV-Detection-ThreatInsightWithFilenameByDeviceList.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-AV-Detection-ThreatInsightWithFilenameByDeviceList.md) |
| AV      | ScanTime  | [02-AV-LastCompletedAVScanTime-For-EachDevice.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/02-AV-LastCompletedAVScanTime-For-EachDevice.md) |
| MDE     | ASR Rules | [01-MDE-ASR-Rules-Detections-Block-Audit.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-MDE-ASR-Rules-Detections-Block-Audit.md) |
| MDE     | ASR Rules | [02-MDE-ASR-Rules-VisualizingDetectionWithPieChart.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/02-MDE-ASR-Rules-VisualizingDetectionWithPieChart.md) |
| MDE     | ASR Rules | [03-MDE-ASR-Rules-DetectionAcrossAllDevices.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/03-MDE-ASR-Rules-DetectionAcrossAllDevices.md) |
| MDE     | ASR Rules | [04-MDE-ASR-Rules-CategorizedDetection-Graph.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/04-MDE-ASR-Rules-CategorizedDetection-Graph.md) |
| MDE     | Controlled Folder Access | [01-MDE-CFA-Detections-Block-Audit.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-MDE-CFA-Detections-Block-Audit.md) |
| MDE     | Indicators "Block" | [01-MDE-URL-Indicators-Block.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-MDE-URL-Indicators-Block.md) | 
| MDE     | Indicators "Warn"  | [02-MDE-URL-Indicators-Bypass.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/02-MDE-URL-Indicators-Bypass.md) |
| MDE     | Network Protection | [03-MDE-NetworkProtection-Detection.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/03-MDE-NetworkProtection-Detection.md)
| SS      | Defender SmartScreen  | [04-SS-DefenderSmartScreen-Detection.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/04-SS-DefenderSmartScreen-Detection.md)
| MDE     | Web Content Filtering | [05-MDE-WebContentFiltering-Detection.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/05-MDE-WebContentFiltering-Detection.md)
| MDE     | Troubleshooting mode  | [01-MDE-TamperProtection-TSmode-AVver-DeviceList.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-MDE-TamperProtection-TSmode-AVver-DeviceList.md) |
| MDE     | Vulnerability Management | [01-MDE-TVM-InstalledSoftware-List-Windows.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-MDE-TVM-InstalledSoftware-List-Windows.md) |
| MDE     | Vulnerability Management | [02-MDE-TVM-RiskyBrowserExtensions-List-Windows.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/02-MDE-TVM-RiskyBrowserExtensions-List-Windows.md) |
| MDE     | Exposure Management      | [01-ExposureManagement-DeviceExposureLevels .md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-ExposureManagement-DeviceExposureLevels%20.md) |

### X-plat - Linux & MacOS
***Update 2024 !!***
| Product | Feature   | KQL query |
|:--------|:----------|:----------|
| AV      | Configuration | [01-MDE-TVM-Linux-AntivirusConfig.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/01-MDE-TVM-Linux-AntivirusConfig.md) |
| AV      | Configuration | [02-MDE-TVM-MacOS-AntivirusConfig.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/02-MDE-TVM-MacOS-AntivirusConfig.md) |
| MDE     | Vulnerability Management | [03-MDE-TVM-InstalledSoftware-List-Linux.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/03-MDE-TVM-InstalledSoftware-List-Linux.md) |
| MDE     | Vulnerability Management | [04-MDE-TVM-InstalledSoftware-List-MacOS.md](https://github.com/LearningKijo/KQL/blob/main/KQL-XDR-Hunting/Endpoint-Microsoft-Defender-for-Endpoint/MDE-Query-Repository/04-MDE-TVM-InstalledSoftware-List-MacOS.md)|

> [!Note]
> - SS : Microsoft Defender SmartScreen
> - AV : Microsoft Defender Antivirus
> - MDE : MicrosoftDefender for Endpoint

#### Disclaimer
The views and opinions expressed herein are those of the author and do not necessarily reflect the views of company.
