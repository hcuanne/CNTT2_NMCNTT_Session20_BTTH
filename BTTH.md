


# Phần 1: Googling đúng cách

## 1. Vì sao Bad Query không hiệu quả?
Vì câu hỏi dài dòng, chứa nhiều từ thừa nên kết quả tìm kiếm không chính xác.

## 2. Bóc tách lỗi

| Thành phần | Nội dung |
|---|---|
| Phần mềm/HĐH | Node.js, npm, Windows 11 |
| Mã lỗi | 'npm' is not recognized |
| Thao tác | Gõ npm -v trong VS Code |

## 3. Ba câu truy vấn Google

- site: `site:stackoverflow.com npm not recognized Windows 11`
- Ngoặc kép: `"npm' is not recognized as an internal or external command, operable program or batch file."`
- Dấu trừ: `npm not recognized Windows 11 -windowsxp`

# Phần 2: Thẩm định StackOverflow

## 1. So sánh

| Tiêu chí | Câu A | Câu B |
|---|---|---|
| Vote & tích xanh | 186 vote, có tích xanh | 2 vote, không tích xanh |
| Thời gian | 2 năm trước | 9 năm trước |
| Tags | node.js, windows, npm | node.js, windows-xp |

## 2. Lựa chọn

Em chọn câu A vì có nhiều vote, tích xanh và phù hợp với lỗi hiện tại.

Câu B là bẫy vì hướng dẫn dành cho Windows XP đã cũ, không phù hợp Windows 11.

## 3. Quy trình đọc lướt 30 giây

1. Kiểm tra Tags.
2. Xem tích xanh và Upvote.
3. Kiểm tra thời gian đăng.
4. Đọc giải pháp và bình luận mới.

# Phần 3: Hỏi AI an toàn

## 1. Prompt 3 thành phần

**[Context]**
Tôi sử dụng Windows 11, đã cài Node.js và chạy npm -v trong VS Code. Tôi đã thêm PATH nhưng vẫn lỗi.

**[Raw Error]**
'npm' is not recognized as an internal or external command, operable program or batch file.

**[Instruction]**
Hãy giải thích nguyên nhân và hướng dẫn 3 bước sửa lỗi an toàn, dễ hiểu.

## 2. Đánh giá câu trả lời AI

**Không an toàn.**

- Lệnh AI đưa ra có thể xóa file hệ thống Windows.
- AI có thể bị Hallucination nên phải kiểm chứng.
- Không cung cấp mật khẩu, API Key hoặc Token cho AI.

**Tuyệt đối không chạy lệnh xóa System32.**

## 3. Hỏi lại AI

"Lệnh này có xóa file hệ thống không? Hãy đưa ra cách kiểm tra PATH và sửa lỗi npm an toàn, không xóa dữ liệu."

# Phần 4: Bug Report

## 1. Tin nhắn kém

"Thầy ơi máy em bị lỗi npm, giúp em với ạ!"

## 2. Tin nhắn chuẩn

| Thành phần | Nội dung |
|---|---|
| Context | Windows 11, Node.js, VS Code |
| Expected | Gõ npm -v hiển thị phiên bản npm |
| Actual | Máy báo npm is not recognized, đã thêm PATH và mở Terminal mới nhưng vẫn lỗi |
| Log & Screenshot | Đính kèm mã lỗi nguyên văn, ảnh màn hình nếu có |

**Tin nhắn gửi trợ giảng:**

"Thầy ơi, em dùng Windows 11 và đã cài Node.js. Khi chạy npm -v trong VS Code thì báo lỗi 'npm is not recognized'. Em đã thử thêm PATH và mở Terminal mới nhưng chưa được. Thầy hỗ trợ em với ạ!"

### 3. Chụp màn hình

- Phím tắt: `Windows + Shift + S`
- Lưu ý: Che mật khẩu, API Key và thông tin cá nhân trước khi gửi.


