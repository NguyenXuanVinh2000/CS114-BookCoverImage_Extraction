#Thông tin bộ dữ liệu: 
Số lượng ảnh: 979 ảnh
Định dạng ảnh: Đuôi .jpg
Kích thước ảnh: 961 x 1280
Các ảnh được chụp chính diện, một số ảnh được chụp nghiêng ở hai bên trái và phải. Ảnh chụp đa số rõ ràng các văn bản có trong bìa sách.
#Train - Validation - Test
Bộ dữ liệu ra thành 3 tập train, val và test. Việc chia dữ liệu hoàn toàn ngẫu nhiên và theo tỉ lệ train:val:test = 8:1:1
Tập train: 800 ảnh 
Tập val: 89 ảnh
Tập test: 90 ảnh
#Sơ đồ phân bố dữ liệu

+---Train
|	classes.txt
|	photo_283@13-01-2022_22-53-59.jpg
|	photo_283@13-01-2022_22-53-59.txt
|	..............
|	photo_312@13-01-2022_22-54-28.jpg
|	photo_312@13-01-2022_22-54-28.txt
+---Val
|	classes.txt
|	photo_326@13-01-2022_22-54-29.jpg
|	photo_326@13-01-2022_22-54-29.txt
|	..............
|	photo_81@13-01-2022_22-51-36.jpg
|	photo_81@13-01-2022_22-51-36.txt
+---Test
|	classes.txt
|	photo_268@05-01-2022_08-43-53.jpg
|	photo_268@05-01-2022_08-43-53.txt
|	..............
|	photo_175@05-01-2022_08-43-03.jpg
|	photo_175@05-01-2022_08-43-03.txt
+---Label
|	Val_Lavel.txt
|	Test_Lavel.txt
|	Train_Lavel.txt

#Giải thích sơ đồ cây dữ liệu:
- Ở các thư mục Train, Val, Test sẽ gồm file classes.txt chứa tên các class, ảnh và các file nhãn txt của Yolo.  tên ảnh trùng với tên file txt. Được gán bằng LabelImg tool.
- Ở thư mục Label chứa nhãn OCR, được gán nhãn bằng PPOCRLabe.