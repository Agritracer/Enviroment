# Hướng dẫn cấu hình file `.env`

Dưới đây là danh sách các biến môi trường cần thiết để chạy dự án. Bạn hãy tạo file `.env` trong thư mục gốc của dự án và điền các giá trị tương ứng.

---

## Các biến môi trường và ý nghĩa

| Biến môi trường        | Mô tả                                                                                     | Ví dụ / Ghi chú                            |
|-----------------------|-------------------------------------------------------------------------------------------|--------------------------------------------|
| `API_KEY`             | Khóa API dùng để xác thực (nếu có)                                                        | Có thể để trống nếu không dùng             |
| `RPC_URL`             | Đường dẫn RPC của mạng Ethereum, dùng để kết nối blockchain                                | `https://sepolia.infura.io/v3/XXXXXXXXX`  |
| `PRIVATE_KEY`         | Khóa riêng của ví Ethereum dùng để ký giao dịch trên blockchain                           | **Không chia sẻ khóa này cho người khác**  |
| `API_PORT`            | Cổng mà dịch vụ API sẽ chạy trên máy chủ                                                 | Mặc định: `8080`                            |
| `ETHERSCAN_API_KEY`   | Khóa API của Etherscan để gọi các API tra cứu giao dịch hoặc trạng thái blockchain       | Lấy từ [https://etherscan.io/apis](https://etherscan.io/apis) |
| `TRACE_WALLET_ADDRESS`| Địa chỉ ví Ethereum mà hệ thống sẽ theo dõi hoặc thu thập dữ liệu                         | Ví dụ: `0x1234...abcd`                      |
