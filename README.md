# Script này sẽ hỗ trợ tự động giải nén file số lượng lớn, phù hợp các bạn cần làm tự động hoá hàng nghìn file
- Các tính năng :
  ** Tự động unrar - zip các tệp có trong thư mục 
  ** Tự động xoá file rar - zip sau khi unrar - zip
  ** Tự động đi vào các thư mục sau khi unrar và xoá file theo yêu cầu hàng loạt
# Các Bước cài đặt chi tiết
## Cài đặt
```
git clone https://github.com/creyt2012/automation-unrar---zip.git
 ```
## Cài đặt thư viện
```
pip3 install patool
```
thay các path sau
```
folder_path = "/path chứa các tệp rar
password = "http://nhasachtinhoc.blogspot.com"
output_dir = "/thư mục nhận sau khi unrar"
files_to_delete = [
    "Nhà Sách Tin Học - chia sẻ tài liệu, khóa học.url",
```


Yêu cầu python
python 3.8 trở về
Sử dụng trên hệ thống linux - macos - windows đều được





