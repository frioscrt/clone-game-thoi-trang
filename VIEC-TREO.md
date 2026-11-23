# Việc treo — Game tiệm làm đẹp

Việc đã bàn mà chưa làm, và phần bàn giao giữa các phiên. Clair nói "ghi lại" hay "để sau" thì Claude thêm một dòng `- [ ]` vào mục Đang treo (ngày, việc, ai đưa ra). Làm xong thì đổi thành `- [x]` và chuyển xuống Đã xong. Đầu mỗi phiên, Claude đọc file này trước.

## Đang treo

- [ ] 23/11 · **Bước 0: thử hình.** Clair tạo 1 khuôn mặt khách + 1 cảnh tiệm bằng Gemini (câu lệnh ở `CAU-LENH-VE.md`), gửi vào phiên. Claude tách nền, vẽ thử tóc bằng code chồng lên mặt, cho Clair xem tóc code có hợp nét hình AI không. Hợp thì mới vẽ cả bộ · Clair
- [ ] 23/11 · Đợt 1: tiệm tóc chơi được trọn vẹn (xem "Phương án đã chốt") · Clair
- [ ] 23/11 · Các tiệm sau, mỗi tiệm một đợt: móng, spa, phối đồ, nấu ăn, thú cưng. Thứ tự Clair chốt sau · Clair
- [ ] 23/11 · Đặt tên game, tên tiệm, tên nhân vật: Clair tự đặt hoặc Claude đưa 3–5 tên để chọn · Clair

## Phương án đã chốt (23/11)

Nguồn cảm hứng: series game Judy của E&I Studio (đã biến mất khỏi kho ứng dụng). Chỉ lấy **thể loại và kiểu chơi** (tiệm làm đẹp, làm từng bước cho khách). Không chép tên, nhân vật, hình, giao diện của series đó.

- **Dự án riêng**, không gộp vào game phối đồ chibi.
- **Hình: trộn hai cách (Clair chốt 23/11).** Claude không tự tạo ảnh được.
  - **Tóc vẽ bằng code** (Claude làm): để cắt dài ngắn thật, uốn, duỗi, nhuộm màu nào cũng được, mượt khi thao tác. Nét tóc phải hợp nét hình AI (viền đậm, màu kẹo ngọt).
  - **Hình AI** (Clair tạo bằng app Gemini, Claude soạn câu lệnh): khuôn mặt khách (tóc buộc sát đầu, nhìn thẳng, cùng tư thế và cỡ), cảnh tiệm, dụng cụ (kéo, lược, máy sấy, máy uốn, bát thuốc nhuộm, vòi gội). Claude tách nền, căn khớp, ghép vào game.
- **Nét vẽ:** hoạt hình mắt to tròn, màu kẹo ngọt.
- **Nơi chơi:** trang web riêng tư trên claude.ai (Artifact), ưu tiên màn hình dọc điện thoại/iPad. Tiến độ phải lưu qua các lần mở (nạp skill `artifact-capabilities` trước khi viết). Hình đưa lên kho hình của Artifact.
- **Đợt 1, tiệm tóc:** khách lần lượt vào, đưa hình kiểu tóc muốn làm. Người chơi làm từng bước: gội (kéo vòi, nổi bọt) → cắt → uốn hoặc duỗi → nhuộm → gắn kẹp, nơ. Xong được chấm sao theo độ giống yêu cầu, có tiền để mở thêm màu nhuộm và phụ kiện.
- Mỗi đợt xong phải chơi được trọn vẹn. Gửi link cho Clair thử rồi mới sang đợt sau.

## Bàn giao gần nhất

- 23/11 · Phiên bàn ý tưởng. Đã chốt phương án ở trên, tạo khung repo, soạn câu lệnh vẽ cho bước 0. **Chưa có hình, chưa có code.** Phiên sau: Clair gửi hình bước 0 vào, Claude xử lý và ghép thử.

## Đã xong

- [x] 23/11 · Bàn và chốt phương án, tạo khung repo, file Việc treo, câu lệnh vẽ bước 0.
