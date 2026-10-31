## Phần A: Giá trị mặc định

Ghi nhận trên Microsoft Edge khi chưa áp dụng style.css, cỡ chữ mặc định 16px.

| Thẻ | Margin | Font-size | Display | Padding |
| --- | --- | --- | --- | --- |
| body | 8px ở cả bốn phía | 16px | block | 0 |
| h1 | 21.44px trên/dưới, 0 trái/phải | 32px | block | 0 |
| p | 16px trên/dưới, 0 trái/phải | 16px | block | 0 |
| a | 0 | 16px | inline | 0 |
| ul | 16px trên/dưới, 0 trái/phải | 16px | block | 40px bên trái, các phía khác 0 |

## Phần B: Đơn vị

- h1: 2rem = 32px. h3: 1.5rem = 24px. Đoạn văn: 1rem = 16px.
- Thẻ sản phẩm rộng 50% phần tử cha, tối đa 400px; padding 1.5em = 24px vì cỡ chữ của thẻ là 16px.
- Dòng giá: 1.25 × 16 = 20px. Số tiền: 1.5 × 20 = 30px.
- 100vw và 20vh thay đổi theo kích thước cửa sổ; chiều rộng tiêu đề bằng chiều rộng màn hình, chiều cao bằng 20% chiều cao màn hình.

## Phần C: Kế thừa và giá trị ban đầu

- Link dùng color: inherit nên nhận màu xanh dương từ thẻ sản phẩm.
- h3 dùng color: initial nên trở về màu chữ ban đầu của CSS, không kế thừa màu xanh. Trên trình duyệt đang kiểm tra, màu này là đen.
- list-style-type: initial đưa kiểu đánh dấu của ul về disc. Reset margin và padding không xóa list-style-type, vì vậy kiểu đánh dấu vẫn là disc từ trước. Do padding bên trái đã bằng 0 và dấu chấm nằm ngoài hộp danh sách, dấu chấm có thể nằm ngoài mép nhìn thấy của trang.
