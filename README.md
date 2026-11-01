# Sense Vietnam's Heritage – Trang kiểm thử khả dụng

Trang tĩnh (HTML + JS), không cần build. Mở `index.html` là chạy.

## Deploy lên Vercel

### Cách 1 – Vercel CLI
1. Cài Node.js (bản 18 trở lên).
2. Mở Terminal tại thư mục này rồi chạy:
   ```
   npx vercel login
   npx vercel --prod
   ```
3. Khi được hỏi:
   - Set up and deploy? → **Y**
   - Link to existing project? → **N**
   - Project name → **sense-vietnam-heritage** (đây là phần tên trong link `.vercel.app`)
   - In which directory is your code located? → **./**
   - Các câu hỏi về build → để mặc định (Enter).
4. Link nhận được có dạng `https://sense-vietnam-heritage.vercel.app`. Nếu tên đã có người dùng, Vercel thêm hậu tố; có thể đổi tên ở Project → Settings → Domains.

### Cách 2 – GitHub
1. Tạo repo mới trên GitHub và đẩy toàn bộ thư mục này lên.
2. Vào vercel.com → Add New → Project → Import repo đó.
3. Framework Preset: **Other**; Build Command và Output Directory để trống → Deploy.

## Lưu ý
- Bản này không có kho lưu chung. Người làm xong sẽ nhận một **mã kết quả** (bắt đầu bằng `SVH1:`) để gửi lại cho người nghiên cứu.
- Trang kết quả: thêm `#ket-qua` vào cuối link, dán mã kết quả để xem tổng hợp (chỉ lưu trong trình duyệt đang mở).
- Prototype trong trang là đúng bản đã dùng ở vòng kiểm thử (trước khi sửa #17–#21).
