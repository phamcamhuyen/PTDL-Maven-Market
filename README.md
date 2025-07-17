#  Phân Tích Doanh Số Bán Hàng Của Maven Market

##  Giới thiệu  
Dự án này nhằm phân tích doanh số bán hàng của **Maven Market** – một doanh nghiệp bán lẻ hiện đại.  
Mục tiêu là khám phá **xu hướng tiêu dùng**, đánh giá **hiệu quả kinh doanh** và đề xuất **giải pháp tối ưu hóa doanh thu** dựa trên dữ liệu thực tế.

##  Mục tiêu  
- Xác định **xu hướng doanh số** theo thời gian, địa điểm và sản phẩm.  
- Phân tích hành vi mua hàng để hỗ trợ **chiến lược marketing**.  
- Xây dựng **mô hình dự đoán** nhằm phân loại khách hàng và dự báo doanh số.  

##  Bộ dữ liệu  
- **Nguồn**: [Kaggle - Sales Data Analysis](https://www.kaggle.com/datasets/beekiran/sales-data-analysis)  
- **Quy mô**: `185.968 dòng × 7 cột`  
- **Thuộc tính chính**: Order ID, Product, Quantity Ordered, Price Each, Order Date, Purchase Address.  
- **Tiền xử lý**: Loại bỏ cột thừa, xử lý **NaN**, **trùng lặp** và **sai chính tả**.  

##  Các bước thực hiện  
1. **Chuẩn bị & tiền xử lý dữ liệu**  
2. **Phân tích mô tả & trực quan hóa**:  
   - Tháng & thành phố có doanh số cao nhất.  
   - Sản phẩm bán chạy & các sản phẩm thường được mua kèm.  
   - Xác định khung giờ vàng để quảng cáo.  
3. **Phân tích dự đoán (Machine Learning)**:  
   - **K-Means Clustering** – phân cụm khách hàng.  
   - **K-Nearest Neighbor (KNN)** – phân loại khách hàng (**Accuracy ~100%**).  
   - **Logistic Regression** – dự đoán doanh số (**Accuracy ~99%**).  
4. **So sánh mô hình** & đề xuất chiến lược kinh doanh.

##  Kết quả nổi bật  
- **Tháng 12** có doanh số cao nhất (ảnh hưởng lễ hội & khuyến mãi).  
- **San Francisco** là thị trường trọng điểm, theo sau là **Los Angeles** và **New York City**.  
- **AAA Batteries** và phụ kiện điện thoại là nhóm sản phẩm bán chạy nhất.  
- Khuyến nghị tập trung vào **khuyến mãi phụ kiện** và **quảng cáo khung giờ 10-11h & 18-19h**.

##  Công cụ sử dụng  
- **Ngôn ngữ**: Python  
- **Môi trường**: Google Colab  
- **Thư viện**: Pandas, Matplotlib, Seaborn, Scikit-learn, WordCloud  

## Thành viên thực hiện  
- Nguyễn Ánh Dương – 2154052015  
- Phạm Thị Cẩm Huyền – 2154052032  
- Trương Thị Thủy Tiên – 2154052081  

---
