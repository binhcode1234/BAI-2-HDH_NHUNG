# BAI-2-HDH_NHUNG
# biên dịch và cài đặt u-boot 
1. Biên dịch thành công UBoot sử dụng Toolchain đã tạo (MLO + Uboot.img)
![Image](https://github.com/user-attachments/assets/418b611d-e318-4bfc-af32-7761dde887c3)

2.Tạo phân vùng Thẻ nhớ phù hợp và cài đặt Uboot thành công lên BBB (Black BeagleBone)
![Image](https://github.com/user-attachments/assets/f390919f-237a-4af6-86c0-89df93c1f734)

3. UBoot khởi tạo thành công (Sử dụng UART - Terminal để Debug)
- hiển thị phiên bản uboot
<img width="1322" height="175" alt="Image" src="https://github.com/user-attachments/assets/75b25a9b-3838-4961-9775-500fd575c4a7" />

- hiển thị thông tin phần cứng
<img width="1322" height="175" alt="Image" src="https://github.com/user-attachments/assets/75b25a9b-3838-4961-9775-500fd575c4a7" />

- Sử dụng các lệnh Uboot có phản hồi
<img width="1422" height="511" alt="Image" src="https://github.com/user-attachments/assets/7f12aa77-de1e-44c7-a627-25eee538ab47" 
# Biên dịch và cài Kernel
1. Biên dịch thành công Kernel cho BBB sử dụng Toolchain đồng nhất với với Uboot (ZImage + dtb file)
![Image](https://github.com/user-attachments/assets/fc4d1530-7f14-4230-b1d6-09fd5df1e2fc)

2. Đưa được 2 file vào thẻ nhớ
<img width="627" height="165" alt="Image" src="https://github.com/user-attachments/assets/7961d064-dc0a-404a-8334-c5a7c8f28190" />

3. Truy cập Uboot, gõ lệnh khởi động được kernel thông qua lệnh bootz
![Image](https://github.com/user-attachments/assets/9a495cff-d10e-4951-9c6e-b17b419b4628)

4. Kernel khởi động thành công:
![Image](https://github.com/user-attachments/assets/887e443e-3a81-4fba-879e-05b10ae51a80)
![Image](https://github.com/user-attachments/assets/1c411b31-6753-4d40-b6e5-ededc78f6f51)
