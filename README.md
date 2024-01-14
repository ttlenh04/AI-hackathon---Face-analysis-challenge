Dự án của chúng tôi nhằm giải quyết bài toán nhận diện tất cả các yếu tố trên khuôn mặt, với mô hình Faster R-CNN là trọng tâm. Chúng tôi đã tổng hợp dữ liệu từ cuộc thi của BTC và thêm vào đó một lượng dữ liệu tăng cường để đảm bảo sự đa dạng và độ chính xác cao của mô hình. Quá trình huấn luyện được thực hiện trên nền tảng Google Colab, tận dụng sức mạnh tính toán của đám mây để đạt được hiệu suất tốt nhất.

Đoạn code này được thực hiện trên Google colab. 

**Bước 1: Chuẩn bị Dữ Liệu trên Google Drive**

Trên Google Drive của bạn, tạo một thư mục chứa tất cả dữ liệu cần thiết, bao gồm :
 + Thư mục ảnh chứa các ảnh test
 + Bộ dữ liệu huấn luyện với định dạng COCO
 + File json file_name_to_image_id.

![image](https://github.com/ttlenh04/AI-hackathon---Face-analysis-challenge/assets/156582899/dd4cbb29-9bd0-441a-b262-57170747ca31)


