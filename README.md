<h1 align="center">Hi, I'm Akash Singh 👋</h1>

<h3 align="center">Software engineer building reliable mobile and backend systems, end to end</h3>

<!-- <p align="center">
  Software Engineer at <strong>Radixweb</strong> · M.Sc IT, DA-IICT · India 🇮🇳
</p> -->

<div align="center">
  <a href="mailto:akashsingh7202@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://www.linkedin.com/in/akashsingh0/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/akash--singh/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
</div>

<br/>

## About

I'm a software engineer who likes owning a problem from the phone screen to the database to production.

- 🧩 **Hard problems, root-caused.** On the RealSafe app I tracked down why users were being clocked out while still on site, and fixed it with a polygon geofence built on computational geometry. The Android team later reused the logic.
- 📱 **Mobile.** Production apps in Swift/UIKit and Flutter, including on-device ML with Core ML.
- 🖥️ **Backend and infrastructure.** Node.js, PostgreSQL and MongoDB services running in production on Windows Server and AWS EC2, including debugging real outages and reliability issues.
- 🤖 **Applied ML.** Shipping YOLOv12 models to run offline on-device.
- ⚡ Outside code: public speaking, volleyball and badminton.

**Open to software engineering roles** (mobile, full-stack or backend). The best way to reach me is LinkedIn or email.

---

## Featured Projects

### 📍 RealSafe: polygon geofencing for clock-in / clock-out
In the [RealSafe iOS app](https://apps.apple.com/us/app/realsafe-app/id6689494688), users were being clocked out while still on site. I found the cause and replaced the circular geofence with a polygon geofence: ray-casting point-in-polygon, equirectangular projection to work in meters, polygon buffering (Minkowski sum) to absorb GPS noise, and proper background handling.

`Swift` `Core Location` `Computational geometry`

### 🛡️ Anzenn Safety: AI-powered inspection app
Workplace safety inspection app with real-time, on-device hazard and PPE detection (YOLOv12 + Core ML). Reduced manual inspection time by **60%**. Built at Injala Pvt Ltd.

`Swift` `Core ML` `YOLOv12` `Firebase`

[View on the App Store](https://apps.apple.com/us/app/anzenn-safety/id1573398822)

### 🖼️ Pixposh: photo and print workflow app
App for photographers, modeling agencies and creative professionals that turns raw shoot images into finished modeling comp cards and physical prints. I revamped existing features and built new ones: better PDF generation, proper templates and their design, a logger, and the order flow. I also worked on the Node.js backend and its deployment on AWS EC2.

`Flutter` `Node.js` `MongoDB` `AWS EC2`

[View on the App Store](https://apps.apple.com/us/app/pixposh/id6479634201)

### 🏭 Industrial safety platform: Permit-to-Work and Truck Loading / PPE systems
Web applications for workplace safety, with two Node.js/Express backends and a shared frontend. I handle the full production setup: PostgreSQL, Windows Server deployment with PM2 as a Windows service, rate limiting behind a proxy, and diagnosing issues such as 502 errors and silent notification failures.

`Node.js` `Express` `PostgreSQL` `PM2` `IIS`

### 💬 Injala Messenger: cross-platform chat
Secure real-time chat app with audio/video calling, file sharing, group management, OTP login and screen lock.

`Flutter` `WebRTC` `Firebase` `Riverpod`

### 🎵 Sangeet: music streaming app
Spotify-style app with offline playback and playlists, built on a custom FastAPI backend, MVVM architecture and an offline-first Hive cache.

`Flutter` `FastAPI` `PostgreSQL` `Hive`

---

## Tech Stack

**Languages:** Swift · Dart · JavaScript · TypeScript · Python<br/>
**Backend:** Node.js · Express · FastAPI · PostgreSQL · MongoDB · REST APIs<br/>
**Mobile:** iOS (UIKit, Core Location, Core Data, Core ML) · Flutter · Firebase<br/>
**Infrastructure:** AWS EC2 · Windows Server · IIS · PM2 · Git<br/>
**ML:** TensorFlow → Core ML conversion · YOLO · OpenCV<br/>
**Tools:** Xcode · Postman · Figma

<br/>

<p align="center">
  <em>Always happy to collaborate. Shoot me a message on LinkedIn.</em>
</p>
