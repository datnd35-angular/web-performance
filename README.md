# I. Kỹ thuật

[Video](https://www.youtube.com/watch?v=WE2N07bd8ro&t=315s)

## Size

***1. Tree shaking***

***2. Tối ưu size (vd: dùng webpack)***

***3. Code Split***

***4. Compress (nén)***
- Gzip

## Cache 
***áp dụng cơ chế CDN***
- Cache trêb máy tính local
- sử dụng ***IndexDB***
      
## Wait (xử lý bất đồng bộ)
***1. Async + Defer***

***2. Lazy loading***

***3. Web worker***

***4. Preload, Prefretch***

# II. Công cụ

## Lighthouse

## Coverage 

## Request blocking

## npm
- https://bundlephobia.com (check tree sharking và size trước khi install)

## Browser support




# [link video](https://www.youtube.com/watch?v=KUdqbIHn8Ic)

***Thời gian tải trang (loading time) và tốc độ giao diện người dùng (UI speed). Đây là hai yếu tố chính quyết định một ứng dụng web có "nhanh" hay không.***

📌 1. Web performance gồm hai phần chính:

Thời gian tải trang (Loading Time): ảnh hưởng đến trải nghiệm ban đầu và tỷ lệ chuyển đổi (conversion).

Tốc độ UI (UI Speed): quan trọng cho ứng dụng nhiều tương tác như Figma, Google Sheets...

📌 2. Khi nào ưu tiên loading time?

Cạnh tranh thị trường (e.g., e-commerce như Amazon).

Người dùng di động (kết nối yếu).

Tăng tỷ lệ chuyển đổi.

Số lượng người dùng lớn.

📌 3. Khi nào ưu tiên UI speed?

Ứng dụng thao tác nhiều (Figma, Canva).

Thời gian phiên làm việc dài.

Ứng dụng B2B nơi hiệu suất ảnh hưởng trực tiếp đến hiệu quả công việc.

📌 4. Các chỉ số quan trọng:

TTFB (Time to First Byte) < 200ms

FCP (First Contentful Paint) < 1.8s

LCP (Largest Contentful Paint) < 2.5s

TTI (Time to Interactive) < 3.8s

📌 5. Kỹ thuật tối ưu hóa loading time:

Sử dụng CDN và cache thông minh.

Nén dữ liệu (Brotli, Gzip).

Prefetch, Preload, và Lazy Loading.

Tối ưu server-side: DB indexing, caching (Redis), autoscaling...

📌 6. Kỹ thuật tối ưu UI speed:

Ưu tiên GPU rendering với transform, opacity.

Tránh animation dùng width, height, gây reflow/repaint.

Sử dụng Web Workers, chia nhỏ tác vụ JS lớn.

Hạn chế thao tác DOM và tránh layout thrashing.
