# 🚀 Raksha Ecosystem — Releases & Distribution Artifacts

This repository is the dedicated release vault containing all production-ready APKs and complete ZIP deliverables for the **Raksha Ecosystem** (Raksha Video + RakshaCall + Shared Backend).

Main source repository: [https://github.com/gangesh987/Raksha-Ecosystem](https://github.com/gangesh987/Raksha-Ecosystem)

---

## 📱 Mobile APK Deliverables (`apks/`)

| File Name | Description | Size | SHA-256 Checksum |
| :--- | :--- | :--- | :--- |
| [`RakshaCall-debug.apk`](apks/RakshaCall-debug.apk) | RakshaCall Debug APK (AI Scam Defense & Safety Brake, com.rakshacall.safety) | 32.6 MB | `0501C1A3099C8BC3FD0167FF1103613B70A6322BF3C6109FC1A1E483F599638E` |
| [`RakshaCall-release.apk`](apks/RakshaCall-release.apk) | RakshaCall Signed Release APK | 20.0 MB | `EA2A666907AB27859F1621CF31011E18549720AB795AD36DFCAC4F7B14061754` |
| [`RakshaVideo-debug.apk`](apks/RakshaVideo-debug.apk) | Raksha Video Debug APK (WebRTC Calling, com.raksha.video.debug) | 59.6 MB | `A65FDA42B1C3F0B5DDCE9DBC44C7E9B47C2C824E737FF42DD4589703A9CEA2D8` |

### Installing on Mobile Devices
1. Download the desired APK (`RakshaCall-debug.apk` or `RakshaVideo-debug.apk`) directly to your Android device.
2. Enable "Install Unknown Apps" for your browser / file manager if prompted.
3. Tap the file to install.
4. Ensure both phones are connected to the same Wi-Fi network as the laptop running `start_demo_backend.bat`.

---

## 📦 Project ZIP Archives (`zips/`)

| File Name | Description | Size | SHA-256 Checksum |
| :--- | :--- | :--- | :--- |
| [`Raksha-Ecosystem-Final.zip`](zips/Raksha-Ecosystem-Final.zip) | Complete Master Ecosystem ZIP (Both Android apps + Backend + Launchers + Docs) | 114.1 MB | `D2F9A0D37C1A59F54BB29EBA0BFF789B043888AF06513E2125AEAF796AFB8192` |
| [`RakshaCall_FINAL_FULL_PROJECT.zip`](zips/RakshaCall_FINAL_FULL_PROJECT.zip) | RakshaCall Standalone Full Project Archive | 121.7 MB | `24BC7BE2554AE684B5397EA6CAE57CE58DBB2F7E9C7FFDC6B558B01A7ED2AA26` |
| [`RakshaCall_Overall_Project_Step3.zip`](zips/RakshaCall_Overall_Project_Step3.zip) | RakshaCall Overall Project Step 3 Archive | 92.4 MB | `14F70FF51A4CA4B9D38DB5C8A9DA73228E27FCA5B7ADE3DDEBB5EEAFF46F048A` |
| [`RakshaCall_FINAL_OVERALL_PROJECT.zip`](zips/RakshaCall_FINAL_OVERALL_PROJECT.zip) | RakshaCall Final Overall Project Archive | 10.8 MB | `9484DB4EA9571E7651006F64C345A87E62BDE67C223414724E282C6729880764` |
| [`RakshaVideo-Final.zip`](zips/RakshaVideo-Final.zip) | Raksha Video Standalone Final Archive | 0.1 MB | `2DC8FFC4B9A781E798869528E9C240A3D99A9ECB0251B4606D144281E2E99646` |
| [`RakshaCall_FINAL_REALTIME_PROTOTYPE.zip`](zips/RakshaCall_FINAL_REALTIME_PROTOTYPE.zip) | RakshaCall Realtime Prototype Archive | 0.1 MB | `5420DFE27F8EB716BB4281557036291B42B1C343A0BD3CC9FA338FEE78C5207D` |
| [`APP OF RAKSHA.zip`](zips/APP OF RAKSHA.zip) | APP OF RAKSHA Full Bundle Archive | 23.2 MB | `E53583AD4D67E755E17AA86D7665A8C9FBBA9AD8CF5B46E0283B215352052EF7` |

### Master Deliverable Overview
- **`Raksha-Ecosystem-Final.zip`**: Contains the complete project hierarchy including both independent Android app codebases (`RakshaVideo/`, `RakshaCall/`), the unified FastAPI backend (`server/`), launcher scripts (`start_demo_backend.bat`, `start_demo_backend.sh`), automated diagnostics suite (`demo_diagnostics.py`), and setup runbooks.
- **`RakshaCall_FINAL_FULL_PROJECT.zip`**: Complete standalone project archive for the RakshaCall AI Scam Defense application.

---

## 🔒 Verification & Integrity
To verify the integrity of any downloaded file on Windows PowerShell:
```powershell
Get-FileHash -Algorithm SHA256 <filename>
```
Compare the output against the SHA-256 hashes listed in the tables above.
