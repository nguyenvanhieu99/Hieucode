---
layout: post
title:  "Powershell dễ như ăn kẹo"
date:   2020-05-07 19:39:02 +0700
categories: [bash,powershell]
---

### Poweshell là gì ăn được không

"là một framework quản lý cấu hình và tự động hóa mạnh mẽ cho phép quản trị viên hệ thống làm việc hiệu quả hơn bằng cách tự động hóa các tác vụ lặp đi lặp lại một cách tẻ nhạt."

và đây là ảnh :![::](.\static\img\powshell1.png)

cách bật :**window** rồi gõ powershell  chọn nó rồi mở thôi

Dưới đây là 1 số lệnh powershell cơ bản

### cd 

+ dùng để di chuyển thư thư mục hiện tại

  ```shell
  cd "ten thu muc muon vao"
  cd .. // trở lại thư mục cha
  cd f: //vào thư mục f
  ```



### ls hay dir

+ Liệt kê danh sách các file và thư mục có trong thư mục hiện tại

### cls hay clear

+ màn hình hiện lên quá nhiều nhìn rối mắt gõ cls để "em " nó lại trắng tinh

### ni hay touch

+ dùn để tạo file mới

+ ``` shell
  ni "tenfilemoi.txt"
  touch "tenfilemoi.md"
  ```

### rm hay del 

xóa file hay thư mục

### md hay mkdir

+ tạo file mới

  ```shell
  md "thumucmoi"
  ```

### ps 

+ hiện các tiến trình

### cat

+ lấy nội dung của tập tin

### clc 

+ xóa nội dung mục nhưng không xóa thư mục

### ac 

+ bổ sung thêm nội dung

### sc 

+ thay thế nội dung bằng nội dung chỉ định

### sal hay set-Alias

+ thay đổi nickname lệnh 

+ ```shell
  Set-Alias MyApp "C:\Path\To\Program.exe"
  ```

### Invoke-Item hay start 

+ mở file chỉ định bằng pm mặc định

### man 

+ xem chi tiết lệnh

+ ```shell
  man ls
  ```

### exit

+ thoát powershell