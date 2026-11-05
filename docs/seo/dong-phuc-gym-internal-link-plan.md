# Kế hoạch liên kết nội bộ về pillar /dong-phuc-gym

> Ngày lập: 05/11/2026 · Phạm vi: bài viết lưu trong MongoDB, sửa qua Dashboard (không sửa bằng source code).
> Nguồn dữ liệu: truy vấn chỉ đọc collection `posts` (isDraft = false), đối chiếu `docs/knowledge/23-internal-links.md` và `22-quy-tac-seo.md` mục 4.

## 1. Nguyên tắc

- Pillar: `https://dongphucunivi.com/dong-phuc-gym` (URL tuyệt đối theo AGENTS §15.1).
- Mỗi bài chèn **1 link** về pillar, đặt trong thân bài (không đặt ở mục "Bài viết liên quan").
- Anchor đa dạng, không lặp cùng một exact-match ở nhiều bài. Không dùng anchor "đồng phục PT" hay "đồng phục Fitness Center" để trỏ về pillar Gym (hai cụm này thuộc `/dong-phuc-pt` và `/dong-phuc-fitness-center`).
- Ưu tiên gắn link vào cụm chữ **đã có sẵn** trong bài; chỉ thêm câu mới khi bài chưa có ngữ cảnh phù hợp.

## 2. Danh sách chèn link

| # | Bài viết | Vị trí chèn | Anchor đề xuất | Câu gợi ý / cách làm |
|---|---|---|---|---|
| 1 | https://dongphucunivi.com/bai-viet/quan-ao-tap-gym-univi | H2 "3. Chọn Quần Áo Gym Theo Đúng Người Mặc", cuối đoạn mở | áo tập Gym cho phòng tập | "Xem các mẫu **áo tập Gym cho phòng tập** được chia theo kiểu cổ và vai trò nhân sự." |
| 2 | https://dongphucunivi.com/bai-viet/ao-gym-chuyen-dung-cho-phong-tap-pt-and-fitness | Đoạn đang có cụm "đồng phục Gym B2B" (phần mở bài) | đồng phục Gym B2B | Gắn link vào cụm chữ có sẵn, không thêm câu. |
| 3 | https://dongphucunivi.com/bai-viet/feedback-the-one-kickfit-ao-gym-pt-thoang-nhe-univi | Câu "…nên xem đồng phục Gym như một phần của trải nghiệm dịch vụ" | đồng phục Gym | Gắn link vào cụm chữ có sẵn. |
| 4 | https://dongphucunivi.com/bai-viet/polo-hay-ao-thun-the-thao-phong-tap-univi | H2 "5. Giải Pháp Thực Tế: Phòng Tập Hiện Đại Kết Hợp Cả Hai" | đồng phục phòng Gym | "Có thể tham khảo cách phối polo và áo thun theo vị trí trong hệ **đồng phục phòng Gym** của Univi." |
| 5 | https://dongphucunivi.com/bai-viet/dong-phuc-phong-tap-theo-yeu-cau | H2 "5. Tùy Biến Đồng Phục Phòng Tập Theo Yêu Cầu Theo Nhận Diện" | mẫu đồng phục Gym có sẵn | "Nếu muốn bắt đầu nhanh, phòng tập có thể chọn từ các **mẫu đồng phục Gym có sẵn** rồi tùy biến màu và logo." |
| 6 | https://dongphucunivi.com/bai-viet/bao-gia-may-dong-phuc-phong-tap | H3 "3.2 Phương Án Tùy Chỉnh Trên Form Có Sẵn" | các mẫu áo Gym có sẵn | "Danh sách **các mẫu áo Gym có sẵn** để làm form gốc." |
| 7 | https://dongphucunivi.com/bai-viet/dia-chi-dat-may-ao-pt-gym-tai-ha-noi-chat-luong | H2 "3. Địa Chỉ May Áo PT Gym Tại Hà Nội – Năng Lực Xưởng Univi" | bộ sưu tập đồng phục Gym | "Xem **bộ sưu tập đồng phục Gym** gồm áo thun Fit Body và polo thể thao cho HLV, PT." |
| 8 | https://dongphucunivi.com/bai-viet/dong-phuc-phong-tap-the-duc-univi | H2 "5. Giải Pháp 2S Uniform…", cuối đoạn | đồng phục cho phòng tập Gym | "Các mẫu Staff Uniform hiện có nằm trong trang **đồng phục cho phòng tập Gym**." |
| 9 | https://dongphucunivi.com/bai-viet/feedback-dong-phuc-a100-gym-dabaco-tu-son | H2 "5. Đồng Phục Univi đồng hành cùng các phòng Gym xây dựng đồng phục" | giải pháp đồng phục Gym | "Ngoài AG1 và AG29, phòng tập có thể xem toàn bộ **giải pháp đồng phục Gym** của Univi." |

## 3. Không chèn link ở đợt này

| Bài viết | Lý do |
|---|---|
| /bai-viet/ao-gym-hlv-ha-noi-vi-sao-80-phong-tap-chon-univi | URL và nội dung chứa claim "80%", "20.000 chiếc" chưa kiểm chứng (23-internal-links mục 7). Sửa nội dung trước. |
| /bai-viet/may-quan-legging-dong-phuc-phong-tap-cao-cap-univi | Chủ đề quần legging, gần Yoga/Pilates hơn Gym; đã có link tới trang sản phẩm Gym. |

## 4. Lỗi nội dung phát hiện khi rà (nên sửa cùng lúc chèn link)

| Bài viết | Vấn đề | Căn cứ |
|---|---|---|
| quan-ao-tap-gym-univi | H3 "4.3 UNI BLENDED Và Công Nghệ UNI DRY"; tên "UNI SUPER COOL", "UNI QUICK DRY" | 27 #2; 05 mục 2 |
| dong-phuc-phong-tap-theo-yeu-cau | H3 "4.3 Dòng Blended"; số H2 nhảy từ 1 sang 4 | 27 #2 |
| dia-chi-dat-may-ao-pt-gym-tai-ha-noi-chat-luong | H3 "Lựa Chọn Số 1 Cho Áo PT Gym" | AGENTS §2.5 (từ cấm "số 1") |
| dong-phuc-phong-tap-the-duc-univi | "hơn 13 chuỗi phòng tập lớn" | 27 #8 (số khách hàng chưa chốt) |
| bao-gia-may-dong-phuc-phong-tap | "chênh nhau gấp đôi" ở mở bài | AGENTS §2.5 |
| ao-gym-chuyen-dung-cho-phong-tap-pt-and-fitness | Tên "UNI QUICK DRY", "UNI SUPER COOL" | 05 mục 2 |

## 5. Kiểm tra sau khi chèn

- Mở từng bài, xác nhận link trỏ đúng `https://dongphucunivi.com/dong-phuc-gym` và trả về 200.
- Không có hai bài dùng cùng anchor.
- Chạy lại truy vấn kiểm tra: tất cả bài Gym đang xuất bản (trừ mục 3) có ít nhất 1 link về pillar.
