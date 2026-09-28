# JavaScript String

## 1. Bản chất chuỗi & Tính bất biến

- Primitive
  - String là kiểu dữ liệu nguyên thủy
- Immutability
  - Phương thức chuỗi không thay đổi chuỗi gốc
  - Cần gán kết quả vào biến mới
- Indexing
  - Index bắt đầu từ 0
  - Index cuối là `length - 1`
  - Index âm được hỗ trợ bởi `slice()`
- `.length`
  - Trả về số lượng ký tự

## 2. Tìm kiếm & Kiểm tra

- `.indexOf()`
  - Trả về vị trí xuất hiện đầu tiên
  - Không tìm thấy trả về `-1`
- `.includes()`
  - Kiểm tra chuỗi có chứa nội dung
  - Kết quả là `true` hoặc `false`
- `.startsWith()`
  - Kiểm tra chuỗi bắt đầu bằng nội dung
- `.endsWith()`
  - Kiểm tra chuỗi kết thúc bằng nội dung

## 3. Biến đổi & Trích xuất

- `.slice()`
  - Trích xuất chuỗi theo vị trí
  - Hỗ trợ chỉ số âm
  - Không thay đổi chuỗi gốc
- `.substring()`
  - Trích xuất chuỗi theo vị trí
  - Không hỗ trợ chỉ số âm
- `.trim()`
  - Xóa khoảng trắng đầu và cuối
- `.toUpperCase()`
  - Chuyển toàn bộ thành chữ hoa
- `.toLowerCase()`
  - Chuyển toàn bộ thành chữ thường
- `.split()`
  - Tách chuỗi thành các phần tử

## 4. Thay thế & Căn lề

- `.replace()`
  - Thay thế lần xuất hiện đầu tiên
- `.replaceAll()`
  - Thay thế tất cả lần xuất hiện
- `.repeat()`
  - Lặp lại chuỗi theo số lần
- `.padStart()`
  - Thêm ký tự vào đầu chuỗi
- `.padEnd()`
  - Thêm ký tự vào cuối chuỗi

## 5. Template Literals

- Backticks
  - Sử dụng dấu `` `...` ``
- Nội suy
  - Dùng `${expr}` để chèn biểu thức
- Multiline
  - Hỗ trợ chuỗi nhiều dòng
- Ứng dụng
  - Tạo nội dung phiếu Kiosk
  - Hiển thị thông tin động
  - Định dạng thông báo
