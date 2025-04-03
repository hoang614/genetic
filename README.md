Tổng quan
Dự án này triển khai một trò chơi Sudoku với giao diện đồ họa sử dụng Pygame và một thuật toán giải Sudoku dựa trên thuật toán di truyền (Genetic Algorithm). Người dùng có thể:

- Nhập bảng Sudoku bằng cách click chuột và nhập số.
- Giải bảng Sudoku tự động bằng thuật toán di truyền.
- Xóa bảng để bắt đầu lại.

Tính năng
- Giao diện đồ họa: Lưới Sudoku 9×9, mỗi ô 3×3 được phân cách rõ ràng.
- Tương tác:
    + Click chuột để chọn ô.
    + Nhập số từ 1-9 bằng bàn phím.
    + Xóa ô bằng phím Delete.
    + Xóa toàn bộ bảng bằng phím Space.
    + Giải bảng bằng phím Enter.

- Thuật toán giải:
Sử dụng thuật toán di truyền với các bước: khởi tạo quần thể, lai ghép (crossover), đột biến (mutation), và chọn lọc.
Tối ưu hóa tỷ lệ đột biến dựa trên hiệu suất.

- Yêu cầu
  + Python: Phiên bản 3.x.
  + Pygame: Thư viện đồ họa (pip install pygame).
  + NumPy: Thư viện tính toán (pip install numpy).

Cách sử dụng
- Mở terminal, di chuyển đến thư mục dự án và chạy:
  ```bash
      python genetic_sudoku.py
  ```
  
