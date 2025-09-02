# Vietnamese License Plate Recognition

Dự án này train mô hình YOLOv8 để nhận diện biển số xe và sử dụng VietOCR pre-trained để đọc ký tự trên biển số xe Việt Nam. Mục tiêu là xây dựng hệ thống tự động nhận diện và trích xuất thông tin biển số từ ảnh xe trong các điều kiện khác nhau.


Dưới đây là minh họa đánh giá nhận diện và đọc biển số:

<img width="765" height="399" alt="image" src="https://github.com/user-attachments/assets/846b40f6-6943-4cdc-beff-15f1cd04ac1e" />


Biển số xe chỉ có trên 1 hàng

YOLOv8 nhận diện thành công

VietOCR đọc chính xác biển số xe: 30E-922.91

<img width="348" height="236" alt="image" src="https://github.com/user-attachments/assets/dc3b10d4-e119-4f04-a428-6ce027195455" />


Biển số xe có 2 hàng

YOLOv8 nhận diện thành công

VietOCR đọc biển số xe: 2752. chưa tốt do định dạng nhiều hàng


Lưu ý: Các ảnh đánh giá bạn có thể thêm trực tiếp vào repo ở thư mục results/ và cập nhật link ở trên.
