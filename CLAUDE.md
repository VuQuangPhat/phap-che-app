# phap-che-app: BẢN SINH TỰ ĐỘNG, KHÔNG SỬA TAY

`index.html` ở đây được dựng từ repo `khung-nha-core` bằng `tools/phat_hanh.py`.
Mọi thay đổi về giao diện, logic, cách xuất docx đều làm ở `khung-nha-core`, rồi phát hành lại.

## Quy tắc cho mọi chat / người dùng repo này
1. KHÔNG sửa `index.html`, KHÔNG commit hay đẩy (`git push`, `--force`, `reset`) trên nhánh `main` của repo này, trừ khi chủ dự án (Vũ Quang Phát) nói rõ "sửa lên app" và việc đó là phát hành từ `khung-nha-core`.
2. Chat chỉnh dữ liệu (Google Sheet `mau_bc`, `prof_*`, `quy_tac`...): chỉ sửa Sheet. Cần đổi app thì mô tả yêu cầu để chuyển sang chat dựng khung.
3. Chỉ cần đọc mã để tìm nguyên nhân: dùng `git fetch && git checkout --detach origin/main` (bản đang chạy), không tạo commit.
4. Bản `main` cục bộ lệch `origin/main` thì không ghi đè, báo chủ dự án.
