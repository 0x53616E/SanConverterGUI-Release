# 💚 SanConverter
![Version](https://img.shields.io/badge/version-2.1-blue) ![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows&logoColor=white) ![Language](https://img.shields.io/badge/language-C%23_WPF-239120?logo=csharp&logoColor=white) ![Framework](https://img.shields.io/badge/framework-.NET_4.8-512BD4?logo=dotnet&logoColor=white) 
<br></br>

## 💜 User-Interface
![](./assets/sanconverter.png)  

<br>*Build 02.2026 v2.1*</br>

---
## ♥️ Main Functions
- Modern UI
- HWID-Restricted License System
- Installation through SanInstallerGUI.exe
- Convert `.SM` and `.SSC` to `.SLK` *(Beat Up and One-Two Party)* 

## ✔️ Requirements
- .Netframework 4.8

## ✨ Charting Logic

### Beat Up 8 Structure
| Arrow Vortex Key | Beat Up .SLK Key | Comment |
|:---:|:---:|:---|
| 1 | 7 | n |
| 2 | 4 | n |
| 3 | 1 | n |
| 4 | 9 | n |
| 5 | 6 | n |
| 6 | 3 | n |
| 7 | Random Key* | Key Array {1,4,7,3,6,9} |
| 1 + 7 | Random Key | Key Array {1,4,7}* |
| 2 + 7 | Random Key | Key Array {3,6,9}* |
| 8 | s | Space |
| M* | Finish Move | Shift + 8 to make a Mine on 8th Lane |
| 7 + 8 | f | Finish Move without Space |
| n* + 7 + 8 | Note + Finish | Note Array {1,3,4,6,7,9} |
| n + M | Double Note (hidden) | M on lane 7 |
| n + M + M| Tripe Note (hidden) | M on lane 7 & 8 |

<br>*Random Key: A note stated as `n` in the .slk which Audition can read, randomly generated using a no Jack-Logic*</br>
<br>*n: a `Note` that can have the attribute of the key {1,3,4,6,7,9}*</br>
<br>*Key Array {1,4,7} and Key Array {3,6,9} stands for a random generated key on the `left` and on the `right` side*</br>
<br>*M: Mine*</br>
<br></br>
<u>Full guide of how to chart:</u> [PDF](https://drive.google.com/file/d/1WPG8JNApXb5hm2z1aH_Or6Bbe0liBLtV/view) [YouTube](https://www.youtube.com/watch?v=B5WxZ9Asc3M)

---

### Beat Up 4 Structure
| Arrow Vortex Key | Beat Up .SLK Key | Comment |
|:---:|:---:|:---|
| 1 | n | Random Generated Note |
| 2 | s | Space |
| 3 | Random Left | Hold* |
| 3 | Random Left no Jacks | Roll* |
| 4 | Random Right | Hold |
| 4 | Random Right no Jacks | Roll |
| 3 + 4 | Random Left-Right | Hold 3 + 4, Random Left-Right Pattern where AV Key = 1 |
| 3 + 4 | Random No Repeat | Roll 3 + 4, Random no repeat Pattern where AV Key = 1 |

<br>*Hold: Holding the key for the amount of arrows you want on a specific side*</br>
<br>*Roll: A rolled Hold*</br>

---

### One Two Party 4 Logic
| Arrow Vortex Key | One-Two Party .SLK Key | Comment |
|:---:|:---:|:---|
| 1 | n | Note |
| 2 | c | Change |
| 3 | d | Dance |
| 4 | s | Space |
| 1 + 2 + 3 + 4 | r | Rotation |

### One Two Party 8 Logic
| Arrow Vortex Key | One-Two Party .SLK Key | Comment |
|:---:|:---:|:---|
| 1 | n | Note |
| 2 | c | Change |
| 3 | s | Space |
| 4 | n | Note |
| 5 | c | Change |
| 6 | s | Space |
| 7 | d | Dance |
| 8 | r | Rotate |

<br>*One-Two Party is a very sensitive gamemode, this converter supports all rules from charting lvl 1 to lvl 9.*</br>

---

### Revert Logic
The Converter can revert all Audition BeatUp.`slk` and all Audition One-Two Party.`slk`into an Stepmania `.SSC` file which is fully editable.

---

## 📥 Installation
1. Download [SanInstallerGUI.exe](https://drive.google.com/file/d/1L4jUutmu57J8Fim4x41HjlfzeBR6PYbN/view)  
2. Execute the **SanInstallerGUI.exe**
-  installation checks for newest version
-  saves the **SanConverter.exe** in your local apps
-  creates a desktop shortcut

---

## ⚠️ Disclaimer
This tool is **HWID Restricted**.  
Reverse engineering or bypassing the HWID protection is strictly <ins>**prohibited**</ins>.

---

<div align="center">

  <img src="./assets/logo.png" alt="Logo" width="150">
  
  <br>

  **(C) 2026 Sanya**
  
  Created with ❤️

</div>
