# INKROOM — Website đặt lịch xăm

Project cuối môn xây dựng bằng ReactJS và Vite. Website có trang chủ, giới thiệu, nghệ sĩ, bộ sưu tập, đặt lịch, liên hệ và trang xác nhận. Điều hướng dùng React Router; có thể truy cập trực tiếp `/about-us` và các URL khác khi chạy Vite.

## Chạy trên máy

Yêu cầu Node.js 20.19+ hoặc 22.12+.

```bash
npm install
npm run dev
```

Mở <http://localhost:3000>. Để kiểm tra bản build: `npm run build` rồi `npm run preview`.

## Các đường dẫn

| URL | Nội dung |
| --- | --- |
| `/` | Trang chủ |
| `/about-us` | Giới thiệu |
| `/artists` | Nghệ sĩ |
| `/gallery` | Bộ sưu tập và bộ lọc phong cách |
| `/booking` | Form đặt lịch |
| `/booking/success` | Xác nhận đặt lịch |
| `/contact` | Liên hệ |

Form đặt lịch là **bản demo frontend**. Dữ liệu được lưu trong `localStorage` của trình duyệt, không gửi đến studio, không đồng bộ giữa các thiết bị và không kiểm tra lịch trống. Thông tin studio và tác phẩm trên website là nội dung minh họa cho bài tập.

## Công nghệ

- ReactJS + Vite
- React Router (BrowserRouter, Routes, Route, Link, NavLink)
- CSS responsive riêng trong `src/styles.css`
- Lucide React icons
