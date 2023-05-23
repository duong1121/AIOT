# AIOT
Nội dung: Cách thu thập dữ liệu, khảo sát dữ liệu, thiết kế mô hình máy học, kinh nghiệm huấn luyện mô hình, đánh giá mô hình, 
cách triển khai mô hình lên thiết bị nhúng, và các thông tin liên quan đến việc phát triển và chạy thử nghiệm dự án này.

Thực hiện: Tự xây dựng một dataset riêng(trong bài này là chén và ly). Từ những dữ liệu này ứng dụng Edge Impulse để xây dựng 
tập dữ liệu train, test, và ứng dụng model để có thể deploy (ứng dụng nhận diện chén và ly) trên thiết bị ESP32-CAM:

![image](https://github.com/duong1121/AIOT/assets/75771867/4d87bf9f-72a4-4420-b93a-332cfb827798)

![image](https://github.com/duong1121/AIOT/assets/75771867/c1e4c61a-22c3-41c5-8f1e-9c60f84213a5)


Kết quả: 

Link Edge Impulse Project: https://studio.edgeimpulse.com/studio/155515

Khi hoàn thành build và kết nối thiết bị, chạy trên Adruino IDE:

Nếu ESP32-CAM capture lại được ảnh của ly, sẽ xuất ra được output là định vị của đồ vật và độ cao, rộng của bounding box:

![image](https://github.com/duong1121/AIOT/assets/75771867/d8ec51f3-8f6c-45da-80d9-c03b6194cb7a)


