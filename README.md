Dự án của chúng tôi nhằm giải quyết bài toán nhận diện tất cả các yếu tố trên khuôn mặt, với mô hình Faster R-CNN là trọng tâm. Chúng tôi đã tổng hợp dữ liệu từ cuộc thi của BTC và thêm vào đó một lượng dữ liệu tăng cường để đảm bảo sự đa dạng và độ chính xác cao của mô hình. Quá trình huấn luyện được thực hiện trên nền tảng Google Colab, tận dụng sức mạnh tính toán của đám mây để đạt được hiệu suất tốt nhất.

Đoạn code này được thực hiện trên Google colab. 


**Bước 1: Tải các bộ dữ liệu cần thiết** :
 Bộ dữ liệu của bài toán phân tích các yếu tố trên khuân mặt gồm tất cả 6 yếu tố. Bộ dữ liệu của bài toán được lưu trữ trên nền tảng Roboflow. Roboflow là một nền tảng học máy và thị giác máy tính được thiết kế để hỗ trợ quá trình xử lý ảnh và triển khai mô hình học máy trên ứng dụng thực tế.
 Để tải bộ dữ liệu tương ứng với folder drive dưới đây : 
 https://drive.google.com/drive/folders/1haOG5tZlhI4f9pkHFsjB4EeOJGVtJ0Ei?usp=sharing


 Thông tin về tập data : 
 + Gồm hình ảnh từ tập của btc và ảnh tăng cường dựa trên tập gốc của btc
 + Định dạng annotations của tập data là định dạng COCO

**Bước 2: Chuẩn bị Dữ Liệu trên Google Drive**

Trên Google Drive của bạn, tạo một thư mục chứa tất cả dữ liệu cần thiết, bao gồm :
 + Thư mục ảnh chứa các ảnh test
 + Bộ dữ liệu huấn luyện với định dạng COCO
 + File json file_name_to_image_id.

![image](https://github.com/ttlenh04/AI-hackathon---Face-analysis-challenge/assets/156582899/dd4cbb29-9bd0-441a-b262-57170747ca31)


