# Predicting-Cinema-Hall-Revenue
## Tổng quan
Dự án này tập trung vào việc dự đoán doanh thu phòng vé của các bộ phim bằng cách sử dụng các kỹ thuật học máy và phân tích dữ liệu từ tập dữ liệu TMDB 5000 Movies Dataset. Tập dữ liệu này chứa thông tin chi tiết về hơn 5000 bộ phim, bao gồm các đặc trưng như ngân sách, doanh thu, thể loại, diễn viên, đạo diễn, đánh giá, thời gian phát hành, và các yếu tố khác. Mục tiêu chính của dự án là xây dựng các mô hình dự đoán doanh thu phòng vé dựa trên các đặc trưng này, từ đó cung cấp những hiểu biết chiến lược về các yếu tố ảnh hưởng đến doanh thu.


## Mục tiêu nghiên cứu
1. Khám Phá Dữ Liệu và Trực Quan Hóa:
Thực hiện phân tích dữ liệu khám phá (EDA) để tìm ra các mối quan hệ và xu hướng giữa doanh thu phòng vé và các đặc trưng của bộ phim, như diễn viên, đạo diễn, đánh giá, thể loại, và ngân sách.
Trực quan hóa các yếu tố quan trọng để hiểu rõ mối liên hệ giữa chúng với doanh thu phòng vé.

2.Phát Triển Mô Hình:
Áp dụng nhiều mô hình học máy để dự đoán doanh thu phòng vé, bao gồm:
Hồi quy tuyến tính (Linear Regression)
Rừng ngẫu nhiên (Random Forest)
Gradient Boosting Machines (XGBoost, LightGBM)

3. Đánh Giá Mô Hình:
So sánh hiệu suất của các mô hình sử dụng các chỉ số đánh giá như RMSE (Căn bậc hai trung bình bình phương lỗi), MAE (Sai số tuyệt đối trung bình), và R² (R-squared).
Mục tiêu là xác định mô hình dự đoán hiệu quả nhất dựa trên dữ liệu thực tế từ TMDB.

4. Phân Tích Tầm Quan Trọng của Các Đặc Trưng:
Sử dụng các kỹ thuật như SHAP (Shapley Additive Explanations) để hiểu rõ các đặc trưng nào có tác động lớn nhất đến dự đoán doanh thu.
Các đặc trưng như diễn viên chính, đạo diễn, thể loại phim, và đánh giá sẽ được phân tích để xác định mức độ ảnh hưởng của chúng đến doanh thu phòng vé.
## Ý nghĩa
Dự đoán chính xác doanh thu phòng vé là một phần quan trọng trong việc tối ưu hóa chiến lược phân phối phim, đặc biệt trong việc quản lý ngân sách, tiếp thị và quản lý khán giả. Các nhà sản xuất và nhà phân phối phim có thể sử dụng mô hình dự đoán này để đưa ra các quyết định về việc chọn diễn viên, đạo diễn, thể loại phim, và chiến lược phát hành phù hợp.

Dự án này không chỉ giúp xác định yếu tố quan trọng nhất ảnh hưởng đến doanh thu mà còn cung cấp công cụ hỗ trợ ra quyết định cho ngành công nghiệp điện ảnh. Những thông tin này có thể giúp các nhà làm phim dự báo chính xác và tối ưu hóa chiến lược sản xuất và phân phối, từ đó tăng trưởng doanh thu cho các bộ phim.


