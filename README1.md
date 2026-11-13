# StudyGuard · VinUni LAB5 · Track T2 Education

Bộ bài nộp dự thảo gồm `spec.md` (§1–§7) và prototype HTML 2 màn hình offline ở `prototype/index.html`.

## Chạy demo

Mở `prototype/index.html` bằng Chrome/Firefox/Edge; không cần cài, không dùng API key hay internet.

1. Chọn `R01 · §3.3 có câu sai` → xem nguồn và cảnh báo → `Gửi TA xác minh` → `Xác nhận gửi` → tab `Màn hình 2 · TA`.
2. Chọn `R02 · Xin đáp án bài 3` → `Xem bước gợi ý đầu` → `Dùng gợi ý bước đầu`; kiểm tra không xuất đáp số.
3. Chọn `R09 · Bài 2 đã đóng` để thấy bài đã có đáp án được giải thích đầy đủ.
4. Chọn `R03` hoặc nhập “Slide 12 giải p-value và đăng FAQ” để thấy thiếu nguồn/ngoài thẩm quyền.

> `chuyen_TA` là **mô phỏng tại trình duyệt**, không thông báo cho người thật. Không có lời gọi AI. Deadline và trạng thái bài 3 dùng fixture của đề, không tự thay đổi theo ngày máy.

## Cần làm trước khi nộp

- Điền tên và **đóng góp thật** của 2 thành viên còn lại; xác nhận lớp và zone.
- Thảo luận và điền các phiếu quyết định tool khó xếp nhất, xác nhận R01/R02.
- Chạy prototype và chụp `prototype/01-student.png` và `prototype/02-ta.png` (1–2 ảnh); các số [1]–[8] đã có sẵn trên UI.
- Sau demo, ghi ca lạ thực tế vào §7 (đừng điền trước).
- Tạo repo GitHub **mới, công khai, không fork repo đề**, theo `K5-L3B-Day05-T2-StudyGuard` nếu đúng lớp L3B.

## Gợi ý lệnh GitHub

```bash
git init
git add spec.md README.md prototype/
git commit -m "Add T2 StudyGuard spec and interactive prototype"
git branch -M main
git remote add origin https://github.com/<USERNAME>/<REPO>.git
git push -u origin main
```

Tạo repo trống trên GitHub trước khi chạy `git remote add`; thay `<USERNAME>/<REPO>` bằng repo thật. Không commit secret. Deadline L3A: 12/11/2026 23:59; L3B: 13/11/2026 23:59.
