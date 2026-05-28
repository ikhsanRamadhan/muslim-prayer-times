# 🕋 Muslim Prayer Times Project

[![StackUp Winner](https://img.shields.io/badge/StackUp%20Challenge-Top%2010%20Winner%20%F0%9F%8F%86-purple)](https://github.com/ikhsandadan/muslim-prayer-times)
[![Tauri](https://img.shields.io/badge/Tauri-Desktop%20App-blue?logo=tauri)](https://tauri.app/)
[![Rust](https://img.shields.io/badge/Backend-Rust-black?logo=rust)](https://www.rust-lang.org/)
[![Next.js](https://img.shields.io/badge/Frontend-Next.js%20%2F%20React-white?logo=nextdotjs)](https://nextjs.org/)

## 🏆 Hackathon Achievement

We are thrilled to announce that this project was selected as one of the **Top 10 Submissions** globally in the **StackUp August Coding Challenge**, organized by **StackUp** and **AngelHack**. 

The judging panel highly commended the project for its innovative architecture, robust cross-platform desktop execution, and excellent backend code quality written in Rust.

<details>
  <summary>🔍 View Official Winner Notification Email</summary>
  <br>
  <p><i>Project recognized for outstanding implementation and code quality among a highly competitive global talent pool.</i></p>
  <img width="1637" height="753" alt="Muslim-prayer-email-win" src="https://github.com/user-attachments/assets/0c997e67-866c-4bbf-bc77-a8950c7c9a17" />
  <img width="1080" height="2460" alt="Muslim-prayer-email-win2" src="https://github.com/user-attachments/assets/1747c9e9-f340-4eef-9bd1-86711b118619" />
</details>

---

For the StackUp August Coding Challenge, I have created an application to assist Muslim worshippers in performing their religious duties more conveniently.

This project is built using a high-performance **Rust** backend, seamlessly bound to a modern **Next.js** frontend via **Tauri** for a native desktop experience.

Below is a detailed breakdown of the application features:

![1](https://github.com/user-attachments/assets/46f133e5-8d82-49e4-ab98-f101992dc90a)

## 🏡 1. Home

On this page, the user can see the current Gregorian date alongside the Hijri (Islamic) calendar date. It dynamically displays the nearest upcoming prayer time based on the user's location coordinates, paired with an inspiring translation of a verse from the Quran. Additionally, users can log their prayers directly via an interactive check-in button to track adherence.

![2](https://github.com/user-attachments/assets/5627e19d-65e6-4cb3-8ae0-afa063f26d99)
![3](https://github.com/user-attachments/assets/c18dd382-24e0-4fc2-85ca-361729622680)

## 📖 2. Quran

This module allows users to browse and read the entire Holy Quran, complete with detailed surah listings, individual verses, and high-quality translations. Users can also stream live audio recitations for each verse on demand.

![6](https://github.com/user-attachments/assets/009d352f-de2e-43c4-a20f-94b4a4aa9d13)
![4](https://github.com/user-attachments/assets/e78aae88-7954-42a5-8b29-64d574d17972)
![5](https://github.com/user-attachments/assets/ed065c51-6c9a-4fa8-aaa2-61016233ee92)

## 📅 3. Calendar

This section overlays historical prayer records onto a standardized calendar interface. Users can track their daily habits, analyze prayer consistency over past dates, and stay informed about upcoming major Islamic holidays and events.

![7](https://github.com/user-attachments/assets/ac3ffb96-9f90-4ea3-b624-176ae991f482)
![8](https://github.com/user-attachments/assets/5c8b1331-8a4a-4786-9f7d-c07ff045aac4)
![9](https://github.com/user-attachments/assets/c664b2ad-57c0-4031-b06d-4069a6f037c6)

## 📊 4. Statistics

This analytical dashboard aggregates user prayer logs stored in the local database. The historical telemetry can be filtered dynamically by custom ranges or standard periods (Today, Yesterday, Current Week, Last Week, Current Month, Last Month).

---

## 🛠️ Architecture & Technical Implementation

The entire core logic and heavy computation of this application are handled natively by **Rust**, exposed securely to the Next.js frontend runtime using Tauri's command bridge interface:

![kode](https://github.com/user-attachments/assets/c3da3a5a-c992-4ed6-abbd-61816472270f)

### 📈 Native Rust SVG Generation
Rather than relying on heavy client-side JavaScript charting libraries, the prayer history heatmap charts on the Statistics page are **rendered directly from the Rust backend as raw SVG vectors**, ensuring sub-millisecond execution speeds and minimal memory overhead.

*   The full Rust implementation can be reviewed under the [`src-tauri/src`](https://github.com/ikhsandadan/muslim-prayer-times/tree/main/src-tauri/src) directory.

---

## 🚀 Installation & Downloads

This desktop application is compiled natively for Windows architecture. You can instantly acquire the fully functional `.exe` executable file directly from our [Releases Page](https://github.com/ikhsandadan/muslim-prayer-times/releases/tag/app).

## 📹 Video Demonstration

Watch the step-by-step walkthrough showcasing the installation, UI flows, and active feature operations:

[![muslim-prayer-times-demo](https://img.youtube.com/vi/r55FrQ3CvtU/0.jpg)](https://www.youtube.com/watch?v=r55FrQ3CvtU)

---

Built with ❤️ by [@Nashki](https://x.com/Ikhsan_dadan)
