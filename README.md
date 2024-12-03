# Mạch mở rộng cổng kết nối MKE-M13 I2C/POWER port expander module

![](/image/MKE-M13_1.jpg)

## Giới thiệu

Mạch mở rộng cổng kết nối MKE-M13 I2C/POWER port expander module thuộc hệ sinh thái phần cứng Robotics MakerEdu với chuẩn kết nối connector XH2.54 thông dụng giúp mở rộng thêm cổng kết nối nguồn POWER+ hoặc cổng I2C để có thể cấp nguồn và giao tiếp với nhiều thiết bị, mạch còn được thiết kế thêm cổng mở rộng dạng Domino để có thể kết nối linh hoạt.

## Thông số kỹ thuật

- Cổng đầu vào INPUT:
  - 1 x Conector XH2.54 4Pins
- Cổng đầu ra OUTPUT:
  - 3 x Conector XH2.54 4Pins
  - 1 x Conector Domino 4P

- Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các mạch điều khiển trung tâm của MakerEdu và MakerEdu Shield.

## Kích thước

![](/image/MKE-M13_2.jpg)

## Các chân tín hiệu

![](/image/MKE-M13_3.jpg)
<table><thead>
  <tr>
    <th>MKE-M12</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>VIN (Domino)</td>
    <td>Cấp nguồn từ 6~30VDC</td>
  </tr>
  <tr>
    <td>VOUT (Domino)</td>
    <td>Nguồn đầu ra 5VDC/5A</td>
  </tr>
  <tr>
    <td>IN (EDU Shield)</td>
    <td>Nối với cổng POWER+ Out của MakerEdu Shield</td>
  </tr>
  <tr>
    <td>OUT (Load)</td>
    <td>Là cổng đầu POWER+ đã được bổ sung công suất cấp nguồn lên 5VDC/5A</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng với MakerEdu Shield

### Các phần cứng sử dụng

- Mạch mở rộng cổng kết nối MKE-M13 I2C/POWER port expander module
- Mạch Vietduino Uno (Arduino Uno Compatible)
- Mạch MakerEdu Shield for Vietduino

> **Lưu ý:**
Nếu không có mạch Vietduino Uno bạn vẫn có thể sử dụng mạch Vietduino Mega 2560, Arduino Uno, Arduino Mega 2560 hoặc các mạch phần cứng có cấu trúc các chân GPIO tương tự.

### Các bước tiến hành

1. Kết nối mạch MakerEdu Shield for Vietduino vào mạch Vietduino Uno.
1. Kết nối cổng (INPUT) của Mạch mở rộng cổng kết nối MKE-M13 I2C/POWER port expander module vào cổng (POWER+ (Out)) hoặc cổng (I2C) trên mạch MakerEDU Shield for Vietduino để mở rộng thêm kết nối.
1. Các cổng (OUTPUT) trên Mạch mở rộng cổng kết nối MKE-M13 I2C/POWER port expander module có các tín hiệu được nối song song với cổng (INPUT) nên sẽ có chức năng tương đương như cổng (INPUT) để có thể kết nối thêm nhiều thiết bị khác nhau.

## Nhà phân phối

Có thể mua Mạch mở rộng cổng kết nối MKE-M13 I2C/POWER port expander module tại các nhà phân phối sau:

- [Hshop.vn - Điện tử & Robot.](hshop.vn)
