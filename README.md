# 📊 Phân Tích Kinh Tế Đơn Vị - Streamline Pro

## 🎯 Tổng quan dự án

Dự án này thực hiện phân tích chuyên sâu về **kinh tế đơn vị (Unit Economics)** cho sản phẩm **Streamline Pro** - một nền tảng Software as a Service (SaaS) của công ty TechStream Solutions. 

**Mục tiêu:** Đánh giá khả năng sinh lời và hiệu quả của các chiến lược thu hút và giữ chân khách hàng dựa trên dữ liệu tháng 3/2023.

**Công nghệ sử dụng:**
- **Python** trong môi trường Google Colab
- **Pandas** để xử lý và phân tích dữ liệu
- **Matplotlib/Seaborn** để trực quan hóa kết quả

## 📂 Nguồn dữ liệu

Dữ liệu được lấy từ Google Drive và bao gồm các tệp:

| Tệp tin | Mô tả |
|---------|-------|
| `daily_marketing_spending.xlsx` | Chi phí marketing theo ngày và kênh |
| `customer_lifespan_data.xlsx` | Dữ liệu vòng đời khách hàng (ngày bắt đầu, ngày rời bỏ) |
| `receipts_history.xlsx` | Lịch sử doanh thu từ các giao dịch |
| `Monthly expenses.xlsx` | Các chi phí hoạt động hàng tháng |
| `Payroll.xlsx` | Chi phí lương nhân viên theo tháng và phòng ban |

## 📈 Các chỉ số kinh tế đơn vị

### Kết quả phân tích tháng 3/2023:

| Chỉ số | Tên tiếng Anh | Giá trị |
|--------|---------------|---------|
| Chi phí thu hút khách hàng | CAC | $50 |
| Doanh thu trung bình/người dùng | ARPU | $75 |
| Giá vốn hàng bán | COGS | $25 |
| Lợi nhuận gộp | Gross Margin | $50 |
| Tỷ lệ lợi nhuận gộp | Gross Margin % | 66.67% |
| Giá trị trọn đời khách hàng | LTV | $2,000 |
| **Tỷ lệ LTV/CAC** | **LTV/CAC Ratio** | **40** |

> ⚠️ **Lưu ý:** Các giá trị trên là ví dụ minh họa. Vui lòng tham khảo file `Unit_Economics_with_Python.ipynb` để xem tính toán chi tiết và kết quả thực tế.

🚀 Cách sử dụng

Chuẩn bị dữ liệu:

Đảm bảo các file Excel đã được upload lên Google Drive
Kiểm tra đường dẫn truy cập dữ liệu


Mở Google Colab:

Truy cập Google Colab
Upload file Unit_Economics_with_Python.ipynb
Kết nối với Google Drive chứa dữ liệu


Chạy phân tích:

Thực thi từng cell trong notebook theo thứ tự
Xem kết quả trực quan hóa và báo cáo chi tiết

## 🎯 Kết quả và Insights

### ✅ Kết luận chính

Streamline Pro thể hiện một **mô hình kinh doanh mạnh mẽ và bền vững**:

- **Tỷ lệ LTV/CAC = 40** (vượt xa mức lý tưởng là 3)
- **Chi phí thu hút khách hàng thấp** với hiệu quả marketing cao
- **Tỷ lệ churn thấp** cho thấy chất lượng sản phẩm tốt
- **Tỷ lệ lợi nhuận gộp 66.67%** thể hiện khả năng sinh lời cao

### 💡 Đề xuất chiến lược

1. **Tối ưu hóa marketing:**
   - Phân tích sâu các kênh marketing để xác định CAC thấp nhất
   - Tập trung ngân sách vào kênh hiệu quả nhất

2. **Mở rộng quy mô:**
   - Tận dụng nền tảng tài chính vững chắc để mở rộng hoạt động
   - Tăng ngân sách marketing để chiếm lĩnh thị phần

3. **Tăng cường retention:**
   - Đầu tư cải thiện sản phẩm và dịch vụ hỗ trợ
   - Duy trì tỷ lệ churn thấp để tối đa hóa LTV

**BIỂU ĐỒ PHÂN TÍCH**
<img width="869" height="594" alt="{244790F7-A899-47A2-937A-E2D5A2857654}" src="https://github.com/user-attachments/assets/7c59fa88-413a-4b63-b9d8-9978432f60f5" />


## 👨‍💻 Thông tin tác giả

**Tác giả:** Max
**Email:** baolong.indo@gmail.com
**Ngày hoàn thành:** 03.08.2025 

## 📋 Yêu cầu hệ thống

- Python 3.7+
- Google Colab & File Jupyter Notebook
- Truy cập Google Drive

### Thư viện cần thiết:
```python
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
numpy>=1.21.0
openpyxl>=3.0.0  # Để đọc file Excel
```

*Dự án này là một phần của phân tích kinh doanh cho TechStream Solutions. Mọi câu hỏi và góp ý xin liên hệ qua email hoặc tạo issue trong repository.*
