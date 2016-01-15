#Screen-Devstack-Openstack

##I. Screen command

Về câu lệnh screen các bạn có thể tìm hiểu theo link sau:

    https://github.com/ducnc/screen-command-linux

##II. Lệnh screen trong openstack

Trong môi trường DevStack, mọi tiến trình làm việc đều được thực hiện trong 1 cửa sổ làm việc của Linux bằng câu lệnh screen. Chúng ta có thể hiểu lệnh screen là 1 cửa sổ làm việc trong cửa sổ của bạn, tức chúng ta có thể mở nhiều cửa sổ làm việc với lệnh screen, mỗi screen trong Devstack sẽ chạy 1 tiến trình, khi chúng ta tắt screen thì tiến trình đó không hẳn sẽ bị tắt, nên chúng ta hoàn toàn có thể kết nối lại

Mỗi Screen chạy 1 dịch vụ đặc biệt của OpenStack, hay có thể hiểu mỗi log sẽ chạy trên 1 cửa sổ Screen tương ứng. 

Chúng ta sẽ thực hành 1 số thao tác với lệnh screen:
    
    CTRL+A " 
để xem toàn bộ danh sách các cửa sổ đang chạy.
Có thể thấy được như sau.


<img src="http://i.imgur.com/2O5eFaq.png">

Đây là cửa sổ làm việc, ở phía dưới chúng ta có thể thấy được tên của các cửa sổ làm việc, và cửa sổ hiện tại đang làm việc là cửa sổ có dấu * ở cạnh tên. Ở đây là designate-mdns

<img src="http://i.imgur.com/2O5eFaq.png">

Để chuyển cửa sổ làm việc chúng ta ấn tổ hợp phím

<img src="http://i.imgur.com/RgdvlDN.png">

    CTRL+A N

hoặc 
    
    CTRL+A P 

để chuyển về cửa sổ làm việc trước đó

Để chọn 1 cửa sổ làm việc bất kỳ, ta có thể ấn CTRL+A và số thứ tự cửa sổ đó hiện ra khi list danh sách cửa sổ

