# 🍜 Bún Bò Cô Hạnh — Website

Website chính thức cho quán **Bún Bò Cô Hạnh** tại 190–192 Hà Tôn Quyền, Phường 6, Quận 11, TP.HCM.

---

## 📁 Cấu trúc file

```
bunbo-cohanh/
├── index.html      ← Trang chủ
├── menu.html       ← Thực đơn
├── story.html      ← Câu chuyện
├── reviews.html    ← Đánh giá
├── contact.html    ← Liên hệ & Đường đi
├── style.css       ← Toàn bộ CSS
├── main.js         ← JavaScript (nav, animations)
└── README.md
```

---

## 🚀 Cách chạy

### Cách 1 — Mở trực tiếp
Chỉ cần mở file `index.html` bằng trình duyệt. Không cần cài đặt gì thêm.

### Cách 2 — Local server (khuyến nghị)
```bash
# Nếu có Python:
python -m http.server 3000

# Nếu có Node.js:
npx serve .

# Sau đó mở: http://localhost:3000
```

---

## 🌐 Deploy lên GitHub Pages

1. Tạo repo mới trên GitHub (vd: `bunbo-cohanh`)
2. Upload toàn bộ file vào repo
3. Vào **Settings → Pages → Source**: chọn `main` branch, thư mục `/ (root)`
4. Website sẽ live tại: `https://yourusername.github.io/bunbo-cohanh/`

---

## ✏️ Cách cập nhật nội dung

| Muốn thay đổi | Chỉnh file |
|---|---|
| Tên món, giá | `menu.html` |
| Giờ mở cửa, địa chỉ | Tất cả file (tìm `6:30`) |
| Màu sắc, font | `style.css` (phần `:root`) |
| Nội dung câu chuyện | `story.html` |
| Số điện thoại | `contact.html` |
| Đánh giá | `reviews.html` |

---

## 🎨 Tùy chỉnh màu sắc

Trong file `style.css`, thay đổi phần `:root`:
```css
:root {
  --red:   #C0392B;   /* Màu chủ đạo (đỏ) */
  --gold:  #D4A017;   /* Màu vàng nhấn */
  --brown: #5C3A1E;   /* Màu nền tối */
  --cream: #FDF6EC;   /* Màu nền sáng */
}
```

---

## 📱 Tính năng

- ✅ Responsive mobile / tablet / desktop
- ✅ 5 trang: Chủ, Thực đơn, Câu chuyện, Đánh giá, Liên hệ
- ✅ Menu filter tabs (Tất cả / Các tô / Thêm vào / Nước)
- ✅ Google Maps nhúng trang Liên hệ
- ✅ Nút đặt ShopeeFood & GrabFood
- ✅ Scroll reveal animations
- ✅ Mobile hamburger menu
- ✅ SEO meta tags
- ✅ Không cần framework, không cần build

---

© 2025 Bún Bò Cô Hạnh — 190–192 Hà Tôn Quyền, Quận 11, TP.HCM
