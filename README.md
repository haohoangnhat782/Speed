Speed Project
   Đoạn mã này tập trung vào việc Theo dõi Đối tượng và Ước tính Tốc độ của các phương tiện di chuyển trên đường. 
   Góc quay của camera hướng từ trên xuống, nhìn xuống đường.
Video 
  Để sử dụng một video khác, bạn sẽ cần thay đổi một số thông số trong đoạn mã. Điều này là do sự thay đổi về cảnh quan sát, ước tính khoảng cách và độ nét của pixel.
  Đối với tệp interface.py, bạn sẽ cần thay đổi vùng quan tâm (region of interest), các đường thời gian màu đỏ (red timer lines) và ngưỡng diện tích được sử dụng để phát hiện các phương tiện.
  Đối với tệp trackers.py, số liệu được cung cấp trong các hàm update () và getsp () sẽ thay đổi để phù hợp với video khác.
Chạy code ta phải tải:
  pip install opencv-python
  pip install numpy
  pip install Pillow
