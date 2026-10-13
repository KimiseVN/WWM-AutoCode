<p align="center">
  <img src="logo.png" width="110" alt="WWM-AutoCode">
</p>

<h1 align="center">WWM-AutoCode</h1>

<p align="center">
  Auto gift-code redeemer for <b>Where Winds Meet</b> (PC) — redeems all active codes for you,
  at any window size/position, in <b>EN / RU / VI</b>, with a modern UI and auto-update.
</p>

---

## ✨ Features
- **Auto-redeem** every active gift code into the in-game *Exchange Code* dialog.
- **Codes from the cloud** — fetches the live code list automatically (same source as the website); marks each code **Used / Invalid / Expired**.
- **Resolution-independent** — works at any game window size/position, windowed or fullscreen-borderless (auto-detects the game window).
- **Multi-language game detection** — works whether the game UI is **English, Russian or Vietnamese**.
- **Modern UI** — tabs (All / Unused / Used / Expired), search, live status, glass theme.
- **UI language EN / RU / VI** — one flag button, remembered for next time.
- **One hotkey** `F6` to Start/Stop. Calibrate in one click.
- **Auto-update** — checks for a new version on every launch.

## 💻 Requirements
- **Windows 10/11 (64-bit).**
- **Edge WebView2 Runtime** — preinstalled on Win11; on Win10 install the free *Evergreen WebView2 Runtime* from Microsoft if the window is blank.
- **Administrator rights** — the game runs elevated, so the tool must too (Windows blocks input to an elevated game otherwise). The app asks for UAC and creates a Desktop shortcut that runs as admin.
- The game must be the **PC client**, running on your **primary monitor**.

## ⬇️ Download & Install
1. Download **`WWM-AutoCode.exe`** from the [**latest release**](../../releases/latest).
2. Put it in a normal folder (Desktop / Downloads — a writable location).
3. Double-click it. On first run a short notice explains the admin requirement → **Got it, continue** → accept the **UAC** prompt.
4. A **Desktop shortcut** is created for next time (already set to *Run as administrator*).

## 🚀 How to Use
1. Open the game and go to **Settings → Other** so the **Exchange Code** row is visible.
2. In WWM-AutoCode click **Calibrate Now** → confirm the game screen is open → it verifies the 3 points (open button / input box / confirm). You should reach **3/3**.
3. Click **▶ Run Auto (F6)** (or press **F6**). It will, for each code: open the panel → paste the code → confirm → mark the result, then move to the next one.
4. Watch the tabs update: **Used** = redeemed OK, **Expired/Invalid** = rejected. Press **F6** again to stop any time.

> Tip: if you press **Start** before calibrating, the app asks you to open the game screen, then calibrates and starts automatically.

## 🌐 Language
Click the **flag button** (top bar) to cycle **EN → RU → VI**. Your choice is saved. This only changes the **app** language — the game language is detected automatically.

## ⌨️ Hotkeys
- **F6** — Start / Stop auto-redeem (rebind in ⚙ Settings).

## 🔄 Auto-Update
On every launch the app checks GitHub Releases for a newer version. If one exists, it shows an update dialog → **OK** downloads the new version, closes the old one and restarts. If there's none (or you're offline), it just runs normally.

## 📁 Data location
Your code database and settings are stored in:
```
%APPDATA%\WWMAutoCode\
```

## 🛠️ Troubleshooting
- **Window is blank / white** → install the *Edge WebView2 Runtime* (Microsoft, free).
- **SmartScreen / antivirus warning** → the exe is unsigned; choose *More info → Run anyway*. (It injects input + self-updates, which AV may flag.)
- **Clicks land on the wrong row / panel won't open** → make sure the **Exchange Code** screen is fully visible and not covered; re-run **Calibrate**.
- **Nothing happens / input ignored** → the app must run **as administrator** (use the Desktop shortcut).
- **Exclusive fullscreen** can't be captured — use **borderless** fullscreen.

## ⚠️ Disclaimer
This tool automates keyboard/mouse input into your own game client to redeem gift codes. Use it at your own risk and follow the game's Terms of Service. It does not modify game files or memory.

## ❤️ Support / Credits
Made by **★ムKim · Trinity Guild WWM**.
- Discord: https://discord.com/users/1382397076889145444
- Ko-fi / PayPal: https://ko-fi.com/akim86

---

<h2 align="center">🇻🇳 Tiếng Việt</h2>

**WWM-AutoCode** — công cụ tự động nhập giftcode cho game **Where Winds Meet** (PC). Tự nhập toàn bộ code còn hạn, chạy đúng ở mọi kích thước/vị trí cửa sổ, hỗ trợ game tiếng **Anh / Nga / Việt**, giao diện hiện đại, tự cập nhật.

### Yêu cầu
- **Windows 10/11 (64-bit)**, có **Edge WebView2 Runtime** (Win11 có sẵn; Win10 nếu cửa sổ trắng thì cài "Evergreen WebView2 Runtime" miễn phí của Microsoft).
- **Quyền Administrator** — game chạy quyền Admin nên tool cũng phải chạy Admin (nếu không Windows chặn thao tác vào game). App tự xin UAC và tạo shortcut Desktop chạy Admin.
- Game là **client PC**, ở **màn hình chính**.

### Cài & chạy
1. Tải **`WWM-AutoCode.exe`** ở [**release mới nhất**](../../releases/latest), để vào thư mục ghi được (Desktop/Downloads).
2. Double-click → lần đầu hiện thông báo cần quyền Admin → **Got it, continue** → chọn **Yes** ở UAC.
3. App tạo **shortcut Desktop** (đã bật Run as administrator) cho lần sau.

### Cách dùng
1. Mở game vào **Cài đặt → Khác** để thấy dòng **Mã đổi thưởng (Exchange Code)**.
2. Bấm **Calibrate Now** → xác nhận đã mở màn hình → app kiểm 3 điểm, đạt **3/3**.
3. Bấm **▶ Chạy Auto (F6)** (hoặc nhấn **F6**). App sẽ: mở ô nhập → dán code → xác nhận → đánh dấu kết quả, lặp đến hết.
4. Theo dõi tab: **Đã dùng** = thành công, **Hết hạn/Lỗi** = bị từ chối. Nhấn **F6** để dừng bất cứ lúc nào.

> Mẹo: nếu bấm **Start** khi chưa Calibrate, app sẽ nhắc mở màn hình game rồi tự Calibrate và chạy.

### Ngôn ngữ · Phím tắt · Cập nhật
- Bấm **nút cờ** để đổi **EN → RU → VI** (lưu lại). Chỉ đổi ngôn ngữ **app**; ngôn ngữ game tự nhận diện.
- **F6**: Chạy/Dừng (đổi được trong ⚙ Settings).
- Mỗi lần mở app tự **kiểm tra bản mới**; có thì hiện dialog → **OK** để tải + chạy lại bản mới.

### Dữ liệu · Khắc phục sự cố
- Dữ liệu/cấu hình lưu ở `%APPDATA%\WWMAutoCode\`.
- Cửa sổ trắng → cài WebView2 Runtime. SmartScreen/antivirus cảnh báo → *More info → Run anyway* (exe chưa ký số).
- Click sai dòng / không mở bảng → để màn **Exchange Code** hiện rõ, không bị che; Calibrate lại.
- Không ăn gì → phải chạy **quyền Admin** (dùng shortcut). Fullscreen "exclusive" không chụp được → dùng **borderless**.

### Miễn trừ & Ủng hộ
Dùng với trách nhiệm của bạn, tuân thủ ToS của game (app không sửa file/memory game).
Tác giả **★ムKim · Trinity Guild WWM** — Discord: https://discord.com/users/1382397076889145444 · Ko-fi: https://ko-fi.com/akim86
