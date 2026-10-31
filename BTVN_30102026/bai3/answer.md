
- h1: 2rem = 32px. h3: 1.5rem = 24px. Đoạn văn: 1rem = 16px.
- Thẻ sản phẩm rộng 50% phần tử cha, tối đa 400px; padding 1.5em = 24px vì cỡ chữ của thẻ là 16px.
- Dòng giá: 1.25 × 16 = 20px. Số tiền: 1.5 × 20 = 30px.
- 100vw và 20vh thay đổi theo kích thước cửa sổ; chiều rộng tiêu đề bằng chiều rộng màn hình, chiều cao bằng 20% chiều cao màn hình.

- Link dùng color: inherit nên nhận màu xanh dương từ thẻ sản phẩm.
- h3 dùng color: initial nên trở về màu chữ ban đầu của CSS, không kế thừa màu xanh. Trên trình duyệt đang kiểm tra, màu này là đen.
- list-style-type: initial đưa kiểu đánh dấu của ul về disc. Reset margin và padding không xóa list-style-type, vì vậy kiểu đánh dấu vẫn là disc từ trước. Do padding bên trái đã bằng 0 và dấu chấm nằm ngoài hộp danh sách, dấu chấm có thể nằm ngoài mép nhìn thấy của trang.
