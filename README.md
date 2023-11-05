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
mở Terminal lên rồi dùng lệnh ``git init`` để khởi tạo repo 
sau đó dùng ``git add.`` để add tất cả file lên repo 
tiếp đến là dùng ``git commit -m 'mô tả rõ cho mn là mày thay đổi cái gì'``
trên đó là phần cơ bản nhưng để đẩy file lên github phải dùng ``git remote add orgin 
