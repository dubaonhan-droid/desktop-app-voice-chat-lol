# 🎙️ VoiceLoL — Tự Động Kết Nối Đàm Thoại LMHT

<p align="center">
  <img src="./icon.ico" alt="VoiceLoL Logo" width="96" height="96" />
</p>

<p align="center">
  <b>Ứng dụng voice chat tự động kết nối đồng đội trong trận Liên Minh Huyền Thoại (LoL)</b><br />
  Độ trễ siêu thấp • Không cần kết bạn • An toàn tuyệt đối cùng Riot Vanguard
</p>

<p align="center">
  <a href="https://github.com/dubaonhan-droid/desh-top-app-voice-chat-lol/releases/latest"><img src="https://img.shields.io/github/v/release/dubaonhan-droid/desh-top-app-voice-chat-lol?color=0AC8B9&label=Download%20Latest" alt="Latest Release" /></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2B-0078D6?logo=windows" alt="Platform Windows" />
  <img src="https://img.shields.io/badge/Electron-31.x-47848F?logo=electron" alt="Electron 31" />
  <img src="https://img.shields.io/badge/React-18-61DAFB?logo=react" alt="React 18" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License MIT" />
</p>

---

## ✨ Điểm nổi bật (Key Features)

- ⚡ **Tự động 100% (Zero Configuration):** Bạn chỉ cần bật VoiceLoL và vào trận LMHT, ứng dụng sẽ tự động nhận diện trận đấu (`Match ID`) và đội hình (`Team ID: 100 - Xanh / 200 - Đỏ`) để đưa bạn vào phòng thoại với đồng đội.
- 🛡️ **An toàn tuyệt đối (Vanguard Safe):** Ứng dụng **hoàn toàn không can thiệp** vào bộ nhớ trò chơi, không hook DLL, không can thiệp gameplay. Ứng dụng chỉ đọc trạng thái thông qua cổng kết nối cục bộ chính thức (LCU API localhost) do chính Riot Games cung cấp.
- 🔒 **Cách ly âm thanh hai đội (Team Isolation):** Tuyệt đối không để lộ kênh thoại cho đối thủ. Mỗi đội sở hữu một kênh truyền tín hiệu riêng biệt (`match_{matchId}_team_{teamId}`).
- 🌐 **WebRTC Mesh P2P Audio:** Âm thanh truyền trực tiếp ngang hàng giữa các người chơi, độ trễ cực thấp (< 50ms), chất lượng âm thanh trong trẻo, không lưu trữ giọng nói người dùng trên máy chủ.
- 🎛️ **Điều khiển âm thanh linh hoạt:**
  - Bật/Tắt Microphone cá nhân (Mute/Unmute).
  - Tắt âm lượng từng đồng đội (Local Mute).
  - Chặn đàm thoại hai chiều (Bilateral Block) khi gặp đồng đội toxic.
  - Bộ đo âm lượng Micro trực tiếp (Live Mic Meter) & nút phát âm thanh thử loa/tai nghe trong Cài đặt.
- 🎨 **Giao diện Hextech cao cấp:** Thiết kế mang đậm phong cách League Client Dark Theme cùng hoạt ảnh nước Hextech trồi lên ấn tượng (GSAP Underwater Surfacing).
- 🌍 **Đa ngôn ngữ:** Hỗ trợ sẵn Tiếng Việt 🇻🇳 và English 🇺🇸.

---

## 🚀 Tải Về & Cài Đặt (Download & Install)

1. Tải bản cài đặt mới nhất từ trang phát hành chính thức:
   👉 **[Tải VoiceLoL Bản Mới Nhất (.exe)](https://github.com/dubaonhan-droid/desh-top-app-voice-chat-lol/releases/latest)**
2. Chạy file `VoiceLoL Setup 1.0.0.exe` để cài đặt.
3. Mở **VoiceLoL**, sau đó mở **League of Legends** và bắt đầu trận đấu!

> 💡 **Mẹo (Windows SmartScreen):** Nếu Windows hiện thông báo bảo vệ màu xanh trong lần đầu mở, bạn chỉ cần bấm **"More info"** (Thông tin khác) rồi chọn **"Run anyway"** (Vẫn chạy).

---



## 🔒 Cam Kết Bảo Mật & An Toàn (Safety & Privacy)

| Tiêu chí | Cơ chế thực hiện |
| :--- | :--- |
| **Không vi phạm Vanguard** | Không inject code, không đọc ghi bộ nhớ tiến trình, chỉ giao tiếp qua REST API cục bộ được Riot tài liệu hóa. |
| **Bảo mật dữ liệu** | Mật khẩu LCU và thông tin nội bộ không bao giờ được gửi ra ngoài hoặc truyền xuống Renderer process. |
| **Quyền riêng tư giọng nói** | Luồng âm thanh được mã hóa P2P WebRTC trực tiếp giữa các máy người chơi, không lưu trữ trên bất kỳ máy chủ nào. |

---

## 👨‍💻 Tác Giả & Đóng Góp (Author & Credits)

- **Creator & Lead Architect:** **Eric Du**
- **Repository:** [dubaonhan-droid/desh-top-app-voice-chat-lol](https://github.com/dubaonhan-droid/desh-top-app-voice-chat-lol)
- Mọi góp ý hoặc báo lỗi, vui lòng sử dụng tính năng **"Góp ý & Báo lỗi"** ngay bên trong ứng dụng hoặc tạo [GitHub Issue](https://github.com/dubaonhan-droid/desh-top-app-voice-chat-lol/issues).

---

<p align="center">
  Phát triển với ❤️ dành riêng cho cộng đồng game thủ Liên Minh Huyền Thoại.
</p>
