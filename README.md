<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0F2027,50:203A43,100:2C5364&text=Hemios&fontColor=FFFFFF&fontSize=64&fontAlignY=36&desc=Embedded%20%C2%B7%20Display%20%C2%B7%20Edge%20AI&descAlignY=58&descSize=18" alt="Hemios" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1200&color=2F81F7&center=true&vCenter=true&width=560&lines=Embedded+Lead+%40+SlashVibe;Firmware+%C2%B7+on-device+UI+%C2%B7+device%E2%80%93host+links;Bringing+AI+models+onto+NPUs;SEIT%2C+Sun+Yat-sen+University" alt="Typing intro" />
</p>

<p align="center">
  <a href="https://slashvibe.ai/"><img src="https://img.shields.io/badge/SlashVibe-Embedded_Lead-111827?style=for-the-badge" alt="SlashVibe Embedded Lead" /></a>
  <a href="https://www.kickstarter.com/projects/loda/slashvibe"><img src="https://img.shields.io/badge/Kickstarter-Back_the_project-05CE78?style=for-the-badge&logo=kickstarter&logoColor=white" alt="Kickstarter" /></a>
  <img src="https://img.shields.io/badge/SYSU-SEIT-005826?style=for-the-badge" alt="SYSU SEIT" />
</p>

I build embedded systems where firmware, displays and on-device AI meet — MCU drivers and LVGL interfaces on one end, NPU model deployment and the host software that talks to the hardware on the other.

<details>
<summary><b>中文简介</b></summary>
<br>
SlashVibe 嵌入式负责人（Embedded Lead），就读于中山大学电子与信息工程学院（SEIT）。关注嵌入式固件、屏幕交互与端侧 AI：一端是 MCU 驱动和 LVGL 界面，另一端是 NPU 模型部署，以及与硬件通信的主机端软件。
</details>

## SlashVibe

<table>
<tr>
<td width="44%" align="center" valign="middle">
<a href="https://slashvibe.ai/"><img src="assets/slashvibe.png" alt="SlashVibe agent display, action keys and joystick" width="100%" /></a>
</td>
<td width="56%" valign="top">
<b>A physical controller for AI coding agents.</b>
<br><br>
Its display keeps every agent session in view, a joystick flicks between them, and action keys plus a built-in mic let you record, send or cancel a prompt without leaving the editor. It works alongside Claude Code, Codex, Cursor and other agent tools.
<br><br>
I lead the embedded team and own the device side of the product:
<ul>
<li>Device firmware</li>
<li>On-device display UI</li>
<li>Device–host protocol</li>
</ul>
<a href="https://slashvibe.ai/"><img src="https://img.shields.io/badge/Website-slashvibe.ai-2F81F7?style=flat-square" alt="Website" /></a>
<a href="https://www.kickstarter.com/projects/loda/slashvibe"><img src="https://img.shields.io/badge/Kickstarter-campaign-05CE78?style=flat-square&logo=kickstarter&logoColor=white" alt="Kickstarter" /></a>
</td>
</tr>
</table>

> [!NOTE]
> The product code is closed-source. Reusable components may be open-sourced later and will be listed here.
> 产品代码暂不开源，后续拆出的通用组件会在这里列出。

## Selected projects

<table>
<tr>
<td width="40%" valign="middle">
<a href="https://github.com/skyswordx/ESP32-S3-ELECTRONIC-LOAD"><img src="https://raw.githubusercontent.com/skyswordx/ESP32-S3-ELECTRONIC-LOAD/main/assets-of-README/image-demo.png" alt="ELEVOURER portable electronic load" width="100%" /></a>
</td>
<td width="60%" valign="top">
<a href="https://github.com/skyswordx/ESP32-S3-ELECTRONIC-LOAD"><b>ELEVOURER · ESP32-S3 electronic load</b></a>
<br><sub>skyswordx/ESP32-S3-ELECTRONIC-LOAD · core contributor</sub>
<br><br>
Portable smart electronic load with CC / CP / CR modes, real-time power monitoring and a touchscreen GUI, built for the SYSU SEIT engineering practice course.
<br><br>
<b>My part:</b> closed-loop current PID control, INA226 sensor calibration, DAC output and over-voltage protection, load-regulation testing, the LVGL waveform UI, LCD multi-buffering and the IPS panel driver.
<br><br>
<img src="https://img.shields.io/github/stars/skyswordx/ESP32-S3-ELECTRONIC-LOAD?style=flat-square&color=F1C40F" alt="Stars" />
<img src="https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32-S3" />
<img src="https://img.shields.io/badge/FreeRTOS-5C8A3A?style=flat-square" alt="FreeRTOS" />
<img src="https://img.shields.io/badge/LVGL-343839?style=flat-square" alt="LVGL" />
</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Triwalt/Viewterbi"><b>Viewterbi</b></a>
<br><sub>Web · teaching tool</sub>
<br><br>
Interactive visualizer that steps through convolutional encoding and Viterbi / BCJR decoding on a live trellis, built for teaching channel coding.
<br><br>
<a href="https://viewterbi.vercel.app"><img src="https://img.shields.io/badge/live_demo-000000?style=flat-square&logo=vercel&logoColor=white" alt="Live demo" /></a>
<img src="https://img.shields.io/github/stars/Triwalt/Viewterbi?style=flat-square&color=F1C40F" alt="Stars" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
</td>
<td width="50%" valign="top">
<a href="https://github.com/Triwalt/FlyKylin"><b>FlyKylin</b></a>
<br><sub>Desktop + embedded Linux · on-device AI</sub>
<br><br>
LAN peer-to-peer messenger for Windows and RK3566, with NSFW image detection and semantic chat search running on-device through ONNX Runtime and the RKNN NPU.
<br><br>
<img src="https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++17" />
<img src="https://img.shields.io/badge/Qt_/_QML-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt / QML" />
<img src="https://img.shields.io/badge/RKNN-RK3566-3B6EA5?style=flat-square" alt="RKNN" />
</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>
<table>
<tr>
<td width="30%"><a href="https://github.com/Triwalt/RAPID-FOC_MEA"><b>RAPID-FOC_MEA</b></a><br><sub>C · STM32H7 · Python</sub></td>
<td>Firmware and host tools for high-rate three-phase current sampling in FOC motor experiments</td>
</tr>
<tr>
<td><a href="https://github.com/skyswordx/Gesture-DetectionRecognition"><b>Gesture-DetectionRecognition</b></a><br><sub>Python · contributor</sub></td>
<td>Camera gesture recognition; I worked on fisheye correction, the recognizer and the on-screen visualizer</td>
</tr>
<tr>
<td><a href="https://github.com/Triwalt/codex-provider-sync-mac"><b>codex-provider-sync-mac</b></a><br><sub>Swift · macOS</sub></td>
<td>Small macOS utility that restores Codex history hidden after switching <code>model_provider</code></td>
</tr>
</table>
</details>

## Upstream contributions

| Project | Contribution | Status |
| --- | --- | --- |
| <img src="https://github.com/lvgl.png?size=40" width="20" align="center" /> [lvgl/lvgl](https://github.com/lvgl/lvgl) | [Skip fully transparent ARGB8888 additive blends onto RGB565](https://github.com/lvgl/lvgl/pull/10309) | ![Open](https://img.shields.io/badge/open-2F81F7?style=flat-square) |
| <img src="https://github.com/espressif.png?size=40" width="20" align="center" /> [espressif/esp-iot-solution](https://github.com/espressif/esp-iot-solution) | [Add init control flags to the ST7701 MIPI LCD driver](https://github.com/espressif/esp-iot-solution/pull/743) | ![Open](https://img.shields.io/badge/open-2F81F7?style=flat-square) |
| <img src="https://github.com/espressif.png?size=40" width="20" align="center" /> [espressif/esp-idf](https://github.com/espressif/esp-idf) | Reported two PPA scale-rotate-mirror bugs and tested fixes on hardware ([#18768](https://github.com/espressif/esp-idf/pull/18768), [#18780](https://github.com/espressif/esp-idf/pull/18780)) | ![Fixed](https://img.shields.io/badge/fixed_upstream-8957E5?style=flat-square) |

<sub>Also contributed exam recaps to SYSU SEIT course repositories: [SYSU_SEIT_Exam](https://github.com/baceoog/SYSU_SEIT_Exam) · [SEITNoteBook](https://github.com/gear0803/SEITNoteBook)</sub>

## Toolbox

<table>
<tr>
<td width="22%"><b>Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=c,cpp,python,swift,js,matlab" alt="C, C++, Python, Swift, JavaScript, MATLAB" /></td>
</tr>
<tr>
<td><b>Embedded</b></td>
<td><img src="https://skillicons.dev/icons?i=arduino,raspberrypi,linux,cmake" alt="Arduino, Raspberry Pi, Linux, CMake" /><br><code>ESP-IDF</code> <code>STM32</code> <code>LVGL</code> <code>FreeRTOS</code> <code>RT-Thread</code> <code>BLE</code> <code>FOC</code></td>
</tr>
<tr>
<td><b>AI &amp; robotics</b></td>
<td><img src="https://skillicons.dev/icons?i=ros" alt="ROS" /><br><code>RKNN</code> <code>ONNX Runtime</code> <code>RealSense</code></td>
</tr>
<tr>
<td><b>Apps &amp; tools</b></td>
<td><img src="https://skillicons.dev/icons?i=apple,qt,react,vite,tailwind,latex,git,githubactions" alt="Apple, Qt, React, Vite, Tailwind, LaTeX, Git, GitHub Actions" /></td>
</tr>
</table>

## Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Triwalt&theme=transparent" alt="Contribution history" width="100%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Triwalt&theme=transparent&hide_border=true&ring=2F81F7&fire=F78166&currStreakLabel=2F81F7" alt="Contribution streak" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Triwalt/Triwalt/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Triwalt/Triwalt/output/github-snake.svg" alt="Contribution snake" width="100%" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:0F2027,50:203A43,100:2C5364" alt="" width="100%" />
