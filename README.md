# LAITSPORT
project của nhóm 3 để thiết kế web

cách để sử dụng git và github 
-- cách tải git và thiết lập biến môi trường

B1: Tải git về máy dưới đường link sau :https://git-scm.com/downloads
    (Thiệc lòng mà nói thì tau mới tìm hiểu nên chả rành nên cứ next đê ko sao đâu) 
    sau đó vô vscode mở Terminal (Ctrl + Shift + `) ấn ``git --version`` nến báo lỗi thì Bước 2 :<
    *Lưu ý nên dùng luôn cmd của window tau nói ở trên là do biến môi trường của win vs vscode đôi khi chưa liên kết với nhau

B2: Thiết lập biến môi trường cho git trên win (kiểm tra tại bth cài git là có ròi)
    ấn cái kính lúp r ấn 'ENVIROMENT VARIABLES' r enter nó sẽ hiện lên 1 cái bảng r vào trong mục 'Advance' chọn tiếp dòng 'ENVIROMENT VARIABLES'
    ở mục 'SYSTEM VARIABLES' tìm dòng có tên Path r ấn vào edit check xem nếu có dùng ..\....\Git\cmd là okela
    Nếu kiểm tra xong mà dùng lệnh ``git --version`` ở vscode vẫn lỗi thì liên hệ tau, tau cx bị mà quên bà nó r 


-- cách dùng github để lấy file về or push file lên github 
Đương nhiên phải đăng nhập github ròiiiiiiiiiiii
- mở Terminal lên rồi dùng lệnh ``git init`` để khởi tạo repo, 
sau đó dùng ``git add .`` để add tất cả file lên repo, 
tiếp đến là dùng ``git commit -m 'mô tả rõ cho mn là mày thay đổi cái gì'``, 
trên đó là phần cơ bản nhưng để đẩy file lên github phải dùng ``git remote add origin https://github.com/Khang1z2t/laitsport.git`` để liên kết vs github này, 
dùng lệnh ``git push -u origin main`` để đẩy file lên github này, 
nó sẽ bắt m nhập thông tin cứ điền theo đi như này ``git config --global user.name "Tên Của Bạn"`` và ``git config --global user.email "địa chỉ email của bạn"``, 
dùng ``git status`` để check file.


vì tau đã làm chủ cái repo này (hhahahahahahha) nên là bọn m phải lấy file về sửa r đẩy lên lại
lệnh lấy file về ``git pull origin main``
lm xong thì add rồi commit rồi ``git push origin main``


nếu đọc lần thứ N rồi nma vẫn chưa nhớ lệnh thì đây:
- ``git init``  
- ``git status``
- ``git add .`` or add + 'filename.html/js'
- ``git commit -m 'mô tả rõ cho mn là mày thay đổi cái gì'`` nhớ ghi mô tả trc khi push lên git 
- ``git pull origin main``
- ``git push -u origin main`` or ``git push origin main``
- ``git remote add origin https://github.com/Khang1z2t/laitsport.git``

that's all nma mới chỉ là cơ bản thôi 
# vô file xem cho dễ

xem vid cho đễ hiểu 
https://www.youtube.com/watch?v=1JuYQgpbrW0
