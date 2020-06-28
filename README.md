# nhan_dang_chu_so
Cách biên dịch

* Môi trường phát triển : Pycharm

1, Tải Pycharm
 Tham khảo tại trang : https://dangkyhosting.com/huong-dan-cai-dat-pycharm-tren-unbuntu-16-04.html

2, Cách biên dịch

* Trước khi biên dịch ta cần chú ý cài đặt các thư viện 
	- opencv-python : 4.2.0
	- numpy :  1.18.1
	- sklearn : 0.0
	- keras : 2.3.1
	- matplotlib : 3.1.3
	- tensorflow : 2.0.0
	- pickle : 0.6.7

- đây là sơ đồ thư mục bao gồm thư mục dataset là mydata, training.py - là file để dùng để train dữ liệu, test.py - dùng để test. Ngoài ra có file model_trained - là file dùng để lưu mô hình đã được train 

 

- khi muốn biên dịch ta bấm tổ hợp phím shift + F10

* Các bước thực hiện

- Đầu tiên ta build file trainning.py để lưu mô hình đã train vào file model_trained. Sau đó ta dùng file model_trained để có thể test dữ liệu thông qua biên dịch file test.py
==> Tuy nhiên, do em đã train xong rồi nên khi thầy test thầy không cần phải buid lại file trainning.py nữa mà thực hiện build luôn file test.py
