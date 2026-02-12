# Bài 2_1: Transistor_PMOS_NMOS_Hệ thống số là gì_Cấu trúc máy tính
## Giới thiệu hệ thống số
$$\text{Giá trị} = \text{Số}\times\text{Cơ số}^{Mũ}$$
### Hệ thập phân (Decimal) - Cơ số 10
* Đặc điểm: Sử dụng 10 chữ số: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9.
* Ứng dụng: Là hệ thống số tự nhiên con người sử dụng để biểu diễn giá trị.
* Cách biểu diễn: $$345 = 3\times10^2 + 4\times10^1 + 5\times10^0$$


### Hệ nhị phân (Binary) - Cơ số 2:
* Đặc điểm: Chỉ sử dụng 0 và 1.
* Ứng dụng: Là hệ thống cơ bản của máy tính và các thiết bị kỹ thuật số vì chúng dễ dàng được biểu diễn bằng trạng thái điện áp cao (1) và thấp (0).
* Ví dụ:
$$1011_2 = 1\times2^3 + 0\times2^2 + 1\times2^1 + 1\times2^0 = 8+0+2+1 = 11_{10}$$
* Chuyển đổi: Hệ nhị phân có thể chuyển sang hệ thập phân và ngược lại.

### Hệ bát phân (Octal) - Cơ số 8
*   Đặc điểm: Sử dụng 8 chữ số: 0, 1, 2, 3, 4, 5, 6, 7.
*   Ứng dụng: Được sử dụng trong lập trình biểu diễn các nhóm 3 bit nhị phân, giúp rút gọn dữ liệu.
*   Ví dụ:
$$75_8 = 7\times8^1 + 5\times8^0 = 61_{10}$$
*   Chuyển đổi:
    + Từ **nhị phân** sang **bát phân**: Nhóm 3 bit thành một nhóm.
    + Từ **bát phân** sang **nhị phân**: Mỗi chữ số bát phân được biễu diễn bằng 3 bit
### Hệ thập lục phân (Hexadecimal) - Cơ số 16
*   Đặc điểm: sử dụng 16 **ký tự** 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F.
*   Ứng dụng: Sử dụng trong lập trình và thiết kế mạch để rút gọn dữ liệu nhị phân thành nhóm 4 bit.
*   Ví dụ:
$$2F_{16} =2\times16^1+15\times16^0 = 47_{10}$$
*   Chuyển đổi:
    + Từ **nhị phân** sang **thập lục phân**: Nhóm 4 bit thành 1 nhóm
    + Từ **thập lục** sang **nhị Phân**: Mỗi chữ số hex được biểu diễn bằng 4 bit.
>Hệ 8 sẽ không được sử dụng nhiều
>Hệ 16 mục đích để rút gọn cách biểu diễn từ hệ 2
## Kỷ nguyên số - máy tính - chip
![tham khảo kênh](xem3videodaulist.png)
**Tóm tắt**
Sơ khai là bảng tính (bảng tính Trung Quốc)
Tiếp theo là Kiến trúc von Neumann
## Transistor
![alt text](/image/transistorwork.png)
Đại diện 2 giá trị 0 và 1 (*Hệ nhị phân*)
Có 2 loại là PMOS và NMOS
![PMOS](/image/PMOS.png)
>PMOS có vòng tròn nhỏ ở cực (gate)

![NMOS](/image/NMOS.png)