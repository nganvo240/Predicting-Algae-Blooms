# Predicting-Algae-Blooms

  Sự xuất hiện dày đặt của tảo ( mật độ tảo tăng nhanh chóng- gọi là “nở hoa”), ảnh tưởng đến môi trường sống của sinh vật dưới nước và chất lượng nguồn nước. Việc theo dõi và thực hiện dự báo sớm về sự nở hoa của tảo là cần thiết để nâng cao chất lượng các dòng sông, cũng như đời sống các sinh vật dưới nước.Với mục tiêu giải quyết vấn đề dự đoán này, một số mẫu nước được thu thập ở các con sông khác nhau ở Châu Âu vào những thời điểm khác nhau trong một năm. 
  
  Trước hết, đây là một bài toán hồi quy nên ta chỉ sử dụng các mô hình, thuật toán liên đến nội dung này. Dữ liệu sẽ được thực hiện tiền xử lí do chứa các giá trị chưa biết ‘NA’. Sau đó, ta tiến hành huấn luyện dữ liệu trên Multiple linear regression, Regression tree và RandomForest. Tiếp theo, ta sử dụng k-fold cross-validation để đánh giá hiệu suất mô hình theo độ đo NMSE và đưa ra lựa chọn phù hợp cho từng loại tảo. Cuối cùng, quá trình dự đoán kết quả được thực hiện.
