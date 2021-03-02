
# [Robot-SUMO  UTC2 - Đại Học Giao Thông Vận Tải - Phân Hiệu Tại TP.HCM | Mã Tuyển Sinh: GSA](https://utc2.edu.vn)
<img src="https://utc2.edu.vn/upload/company/logo-15725982242.png">

# Phần mềm cần thiết 

- Arduino IDE | [Windows](https://www.microsoft.com/store/apps/9nblggh4rsd8?ocid=badge) | [MacOS](https://downloads.arduino.cc/arduino-1.8.13-macosx.zip) | [Linux](https://downloads.arduino.cc/arduino-1.8.13-linux32.tar.xz)
- Phần mềm giải nén tập tin * .zip
# Sơ đồ kết nối phần cứng .
 - Có thể xem ở file "sơ đồ mạch .pdf"
 <img src="https://github.com/vanminh1310/robot_sumo_UTC2/blob/main/s2_sumo/sumo_bb.png">

# Cài đặt và thiết lập  
1. Khởi động Arduino IDE lần đầu tiên để cài các driver và thư viện cần thiết

2. Tải xuống mã nguồn đầy đủ của chương trình [tại đây](https://github.com/vanminh1310/robot_sumo_UTC2.git) 

3. Giải nén file robot_sumo_UTC2-main.zip vừa tải về

4. Khởi động Arduino IDE chọn File >> Open và trỏ đường dẫn đến file s2_sumo.ino trong thư mụcrobot_sumo_UTC2-main vừa giải nén

5. Cắm cáp kết nối ArduinoUno và PC

6. Tại giao diện phần mềm ArduinoIDE. Chọn board: Tools >> Board >> Arduino Uno

7. Chọn cổng giao tiếp: Tools >> Port >> COMxx

8. Nạp chương trình đầu tiên từ PC xuống Arduino: Sketch >> Upload

9. Chờ phần mềm báo Done Uploading là đã nạp thành công code xuống ArduinoUno done-uploading

# Kiểm tra các cảm biến 
 Sau khi nạp chương trình vào robot thành công để kiểm tra các cảm biến có hoạt động chính xác hay không ta cần kiểm tra các cảm biến đó bằng cách 
  - Tắt nguồn động cơ robot
  - Cắm cáp kết nối ArduinoUno và PC
  - Nhấn vào biểu tượng kính lúp ở góc trên bên phải phần mềm ArduinoIDE để bật màn hình Serial Monitor <img src="http://making.do/alc-makerspace/console-icon.png">
  - Quan sát các giá trị cảm biến được trả về ở màn hình  Serial Monitor ![image](https://user-images.githubusercontent.com/53778428/109662792-055d9380-7b9e-11eb-9603-88b918ac1cbb.png)

 - Nếu đúng các giá trị của cảm biến sẽ thay đồi tùy thuộc vào khoảng cách và môi trường .
 - Sau khi kiểm tra xong rút cáp kết nối .
 
 # Một số lưu ý !
- **KHÔNG ĐƯỢC PHÉP LẮP NGƯỢC CỰC DƯƠNG(+) ÂM(-) CỦA PIN VÀO MẠCH SẠC CŨNG NHƯ MẠCH ĐỘNG CƠ PIN NẾU CẮM NGƯỢC CỰC NGAY CẢ KHI CHƯA BẬT NGUỒN CŨNG SẼ GÂY CHÁY NỔ**
- **SỐ LƯỢNG PIN, MẠCH CÓ HẠN**
- Nếu cắm cáp kết nối Arduino sáng đèn nguồn nhưng không tìm thấy port trong Tools >> Port >> COMxx thì tải xuống và cài đặt [Driver mạch nạp CH340C](https://sparks.gogo.co.nz/assets/_site_/downloads/CH34x_Install_Windows_v3_4.zip)
- Nếu gặp tình trạng Serial Monitor nhảy ký tự linh tinh hoặc không hiện bất kỳ ký tự nào ![image](https://user-images.githubusercontent.com/53778428/109663457-b5330100-7b9e-11eb-840e-9b3954fbfd54.png) thì chỉnh lại bên dưới thành 9600 ![image](https://user-images.githubusercontent.com/53778428/109663602-e27faf00-7b9e-11eb-94b5-24c30d8665cf.png)
- Khi nạp chương trình hãy tắt nguồn của động cơ đi nhé !
- Để test robot ta có thể dùng các cách sau: Dùng băng keo đen dán các cảm biến hồng ngoại để kiểm tra cảm biến siêu âm có hoạt động tốt không nếu như có vật cản 2 động cơ sẽ quay thuận về phía trước trường hợp không có vật cản hai động cơ sẽ quay ngược chiều nhau. 
- Test cảm biến hồng ngoại(dò line): Trường hợp hai cảm biến trước nhận vạch trắng hai động cơ sẽ quay thuận về phía sau . Cảm biến sau nhận vạch trắng hai đọng cơ sẽ quay thuận về phía trước . Trường hợp trong sân hai độn cơ quay ngược chiều nhau để tìm đối thủ.
- Code trên mang tính tham khảo các bạn có thể sáng tạo thêm nhiều trường hợp hay nữa nhé 😁😁

# Video hướng dẫn 
https://www.youtube.com/watch?v=IfP8a8gpUGI

# Gallery
https://www.youtube.com/watch?v=Y2vIJftWwnI

![image](https://user-images.githubusercontent.com/53778428/109665891-3b504700-7ba1-11eb-9833-685c5e285aed.png)

![image](https://user-images.githubusercontent.com/53778428/109665936-473c0900-7ba1-11eb-9327-74e5dd38e7dc.png)

![image](https://user-images.githubusercontent.com/53778428/109665983-5753e880-7ba1-11eb-8f58-4c6f87f31816.png)

![image](https://user-images.githubusercontent.com/53778428/109666093-70f53000-7ba1-11eb-8b84-0ae2963a439e.png)

![image](https://user-images.githubusercontent.com/53778428/109666206-8ec29500-7ba1-11eb-9ef9-677565367ef5.png)

# Built With

# Contributors
 - Tạ Văn Minh [Facebook](https://www.facebook.com/taminh1310) [Email](taminh39@gmail.com)
# Ban tổ chức 
Trường Đại học Giao Thông Vận Tải - Phân hiệu tại TP. Hồ Chí Minh | Mã tuyển sinh: GSA

 - [Robot Sumo](https://github.com/vanminh1310/robot_sumo_UTC2)
 - [Robot dò line](https://github.com/spiderock98/XeDoLineUTC2#xe-d%C3%B2-line-utc2---%C4%91%E1%BA%A1i-h%E1%BB%8Dc-giao-th%C3%B4ng-v%E1%BA%ADn-t%E1%BA%A3i---ph%C3%A2n-hi%E1%BB%87u-t%E1%BA%A1i-tphcm--m%C3%A3-tuy%E1%BB%83n-sinh-gsa)





