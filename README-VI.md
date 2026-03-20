# https://github.com/OpenBMB/VoxCPM.git

````md id="voxcpn1"
# 🎙️ Clone giọng nói chỉ với vài giây audio

## 🔊 Giới thiệu VoxCPM

**VoxCPM** là một dự án **Text-to-Speech (TTS)** mới đang thu hút sự chú ý của cộng đồng AI nhờ cách tiếp cận khác biệt so với các mô hình TTS truyền thống.

---

## 🤔 VoxCPM khác gì các TTS thông thường?

Phần lớn các mô hình TTS hiện nay:

- Mã hoá giọng nói thành các **token rời rạc**
- Sau đó mới học cách sinh ra âm thanh

👉 Cách này tiện, nhưng có thể tạo ra **bottleneck**, khiến giọng đọc:
- Kém tự nhiên
- Thiếu độ mượt

---

## 💡 Cách tiếp cận của VoxCPM

VoxCPM **loại bỏ hoàn toàn bước tokenization**, thay vào đó:

- Mô hình hoá âm thanh trong **không gian liên tục**
- Sử dụng kiến trúc:
  - **Diffusion**
  - **Autoregressive**
- Pipeline **end-to-end** từ text → speech

🎯 Mục tiêu:
- Giọng nói **mượt hơn**
- **Tự nhiên hơn**
- **Giống người thật hơn**, đặc biệt với đoạn dài

---

## ✨ Các tính năng nổi bật

### ✅ Context-aware speech
- Hiểu nội dung văn bản
- Tự điều chỉnh:
  - Nhịp điệu
  - Ngữ điệu
  - Nhấn nhá

---

### ✅ Clone giọng zero-shot
- Chỉ cần **một đoạn audio ngắn vài giây**
- Có thể tái tạo:
  - Tông giọng
  - Accent
  - Nhịp nói
  - Sắc thái cảm xúc

👉 Kết quả: giọng clone khá sát với người gốc

---

### ✅ Dataset cực lớn (song ngữ Trung – Anh)
- Được train trên:
  - **~1.8 triệu giờ dữ liệu**
- Hỗ trợ tốt nhất:
  - 🇨🇳 Tiếng Trung
  - 🇺🇸 Tiếng Anh

---

### ❎ Hạn chế hiện tại
- Các ngôn ngữ khác:
  - Cần **fine-tune**
  - Chất lượng chưa ổn định

📌 Dự kiến:
- Bản **multilingual** có thể ra mắt trong tương lai gần

---

## 🚀 Phiên bản mới nhất: VoxCPM 1.5

- 🔢 **800M parameters**
- 🎧 **44.1 kHz sampling rate**
  - (So với nhiều model khác chỉ ~16 kHz)

👉 Kết quả:
- Âm thanh rõ hơn
- Tự nhiên hơn đáng kể

---

## 🧠 Tổng kết

```text
Continuous audio modeling + diffusion + autoregressive
→ TTS tự nhiên hơn & clone giọng tốt hơn
````

VoxCPM là một hướng đi đáng chú ý trong lĩnh vực **speech synthesis**, đặc biệt với:

* Voice cloning
* AI narrator
* Content automation

---

## 📌 Use cases tiềm năng

* 🎙️ Clone giọng cá nhân
* 📚 Audiobook tự động
* 🎬 Lồng tiếng AI
* 🤖 Trợ lý ảo có giọng tự nhiên

```

Nếu bạn muốn, mình có thể:
- Viết lại theo style **viral Facebook**
- Hoặc chuyển thành **README GitHub chuyên nghiệp + thêm link repo** 👍
```
