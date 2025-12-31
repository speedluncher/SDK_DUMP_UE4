<h1 align="center">
  <span style="color:#7F5AF0;">UE4 SDK Dump</span>
  <br/>
  <sub style="font-size:16px; color:#999;">Android · Runtime Analysis · SDK Extraction</sub>
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Engine-UE4-7F5AF0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Language-C%2FC%2B%2B-00599C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Early%20Stage-F5A524?style=for-the-badge"/>
</p>

---

## 🧠 Overview
This repository provides a **UE4 SDK dumping setup for Android applications**, based on  
<strong style="color:#7F5AF0;">AndUE4Dumper</strong>.

It focuses on **runtime memory analysis** to extract Unreal Engine 4 internal structures for  
<span style="color:#3DDC84;"><b>educational and research purposes</b></span>.

---

## ✨ Features
- Runtime SDK dumping for **UE4 Android games**
- Extracts:
  - Classes
  - Structs
  - Enums
  - Functions
- Resolves core UE4 globals:
  - <code>GWorld</code>
  - <code>GUObjectArray</code>
  - <code>GNames / NamePool</code>
- Produces readable SDK output for analysis tools

---

## 🛠 Tech Stack
<p>
  <img src="https://img.shields.io/badge/UE4-Engine-7F5AF0?style=flat-square"/>
  <img src="https://img.shields.io/badge/Android-ARM%2FARM64-3DDC84?style=flat-square"/>
  <img src="https://img.shields.io/badge/NDK-C%2FC%2B%2B-00599C?style=flat-square"/>
  <img src="https://img.shields.io/badge/Analysis-Memory%20Scanning-FF6F61?style=flat-square"/>
</p>

---

## 🚧 Project Status
> <span style="color:#F5A524;"><b>Early Stage</b></span>

- Currently mirrors the original **AndUE4Dumper**
- No core logic has been modified yet
- Planned updates:
  - Code cleanup
  - Offset improvements
  - Stability updates
  - Documentation

---

## 🙏 Credits
This project is based on  
<strong><a href="https://github.com/AndUE4Dumper" target="_blank">AndUE4Dumper</a></strong>

All original dumping logic belongs to the respective authors.  
This repository serves as a **foundation for future enhancements**.

---

## ⚠️ Disclaimer
- Educational & research use only
- No copyrighted assets included
- Focused strictly on **engine internals and runtime behavior**
