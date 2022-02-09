# Thông tin bộ dữ liệu: 
- Số lượng ảnh: 979 ảnh
- Định dạng ảnh: Đuôi .jpg
- Kích thước ảnh: 961 x 1280
- Các ảnh được chụp chính diện, một số ảnh được chụp nghiêng ở hai bên trái và phải. Ảnh chụp đa số rõ ràng các văn bản có trong bìa sách.
# Train - Validation - Test
- Bộ dữ liệu ra thành 3 tập train, val và test. Việc chia dữ liệu hoàn toàn ngẫu nhiên và theo tỉ lệ train:val:test = 8:1:1
- Tập train: 800 ảnh 
- Tập val: 89 ảnh
- Tập test: 90 ảnh
# Sơ đồ phân bố dữ liệu

![image](https://user-images.githubusercontent.com/51904291/153196532-c252700b-5a13-4364-91cc-5ea75b0a64ca.png)
# Giải thích sơ đồ cây dữ liệu:
- Ở các thư mục Train, Val, Test sẽ gồm file classes.txt chứa tên các class, ảnh và các file nhãn txt của Yolo.  tên ảnh trùng với tên file txt. Được gán bằng LabelImg tool.
- Ở thư mục Label chứa nhãn OCR, được gán nhãn bằng PPOCRLabe.
