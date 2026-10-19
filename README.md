# MicAmp-扩音器

[中文](#中文说明) · [English](#english)

---

## 中文说明

**MicAmp-扩音器** 是一个手机网页应用：用手机麦克风或外接麦克风（如 DJI Mic）收音，通过蓝牙音箱实时外放，相当于一台便携扩音机。

### 使用步骤
1. 用手机 Chrome（或 Edge）打开本页网址，必须是 HTTPS。可以“添加到主屏幕”，像 App 一样使用。
2. 在手机系统设置里先连接蓝牙音箱。
3. 在 **录音来源** 选择手机麦克风，或已插入手机的 DJI Mic 接收器。设备名称在第一次授权麦克风后才会显示。
4. 在 **输出设备** 选择蓝牙音箱。如果浏览器不支持在网页内切换，声音会自动从系统已连接的蓝牙音箱输出。
5. 点 **开始**，允许麦克风权限，即可扩音。再点一次停止。

### 功能
| 功能 | 说明 |
|---|---|
| 音量 | 0–300%，内置限幅，防止爆音 |
| 噪声门 | 安静时压低底噪，说话声被吞字时调低 |
| 回声消除 / 降噪 / 自动增益 | 使用浏览器自带处理，可单独开关（扩音中切换会重新打开麦克风，声音会断一下） |
| 啸叫抑制 | 检测到持续尖叫的频率后，自动陷波并短暂降低音量 |
| 低切滤波 | 去除 120Hz 以下的低频嗡嗡声 |
| 折叠屏 | 合上的方形小屏自动使用紧凑排版 |
| 常亮屏幕 | 扩音期间保持亮屏，切回前台自动恢复 |

### 防啸叫建议
- 麦克风离音箱远一些，音箱不要朝向麦克风。
- 音量从小往大调。
- 蓝牙有延迟，回声比有线更明显；想要更低延迟，可使用有线连接。

### 常见问题
- **提示不支持录音：** 页面不是 HTTPS，或浏览器不支持。请使用 HTTPS 网址。
- **列表里没有 DJI Mic：** 确认接收器已插好，点 ↻ 刷新。
- **没有声音：** 检查音箱音量和蓝牙连接，并确认浏览器已允许麦克风。
- 设置保存在本机浏览器里，不会上传；所有音频只在手机内处理，不经过任何服务器。

---

## English

**MicAmp** is a mobile web app that turns your phone into a portable PA: it captures sound from the phone mic or an external mic (such as a DJI Mic) and plays it live through a Bluetooth speaker.

### Quick start
1. Open the page in Chrome or Edge on your phone. It must be served over HTTPS. You can add it to your home screen to use it like an app.
2. Connect your Bluetooth speaker in the phone's system settings first.
3. Under **录音来源 (Input)**, choose the phone mic or the DJI Mic receiver plugged into the phone. Device names appear only after you grant mic permission once.
4. Under **输出设备 (Output)**, choose the Bluetooth speaker. If your browser cannot switch outputs inside a page, audio follows the system's connected Bluetooth speaker automatically.
5. Tap **开始 (Start)** and allow the microphone. Tap again to stop.

### Features
| Feature | Details |
|---|---|
| Volume | 0–300% with a built-in limiter against clipping |
| Noise gate | Lowers background hiss when silent; reduce it if words get clipped |
| Echo cancellation / noise suppression / auto gain | Browser processing, each toggleable (changing them while running reopens the mic, with a brief gap) |
| Feedback suppression | Detects a sustained howl frequency, notches it out and briefly lowers the volume |
| Low-cut filter | Removes rumble below 120 Hz |
| Foldables | The small square cover screen uses a compact layout |
| Screen wake lock | Keeps the screen on while amplifying |

### Avoiding feedback
- Keep the mic away from the speaker and do not point the speaker at the mic.
- Raise the volume gradually.
- Bluetooth adds latency, which makes echo more noticeable than a wired setup.

### Troubleshooting
- **"Recording not supported":** the page is not HTTPS, or the browser lacks support.
- **DJI Mic missing from the list:** make sure the receiver is plugged in, then tap ↻.
- **No sound:** check speaker volume, the Bluetooth connection, and the browser's mic permission.
- Settings are stored only in your browser. All audio is processed on the phone and never sent to any server.
