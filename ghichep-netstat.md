# Sử dụng lệnh netstat

Tài liệu sẽ được cập nhật thêm...

### Sử dụng netstat để lọc các port udp
```sh
netstat -au
```
<ul>
<li>a: all - tất cả các kết nối trên hệ thống</li>
<li>u: udp - các kết nối sử dụng giao thức udp</li>
</ul>

<img src="http://i.imgur.com/EocoKGu.png">

### Sử dụng netstat để lọc các port tcp
```sh
netstat -at
```
<ul>
<li>a: all - tất cả các kết nối trên hệ thống</li>
<li>t: tcp - các kết nối sử dụng giao thức tcp</li>
</ul>

<ul>
<li>Proto: Tên giao thức</li>
<li>Recv-Q:</li>
<li>Send-Q:</li>
<li>Local Address: Địa chỉ IP của hệ thống và port kết nối</li>
<li>Foreign Address: Địa chỉ dịch vụ đang được kết nối đến và số port</li>
<li>State: Trạng thái port</li>
</ul>


<img src="http://i.imgur.com/9qd8IsP.png">

### Sử dụng netstat để lọc các port tcp&udp
```sh
netstat -atu
```
<img src="http://i.imgur.com/dUEnSDp.png">

### Sử dụng lệnh netstat để lọc các port đang trong trạng thái `LISTEN`
```sh
netstat -l
```

<img src="http://i.imgur.com/dawOJvD.png">

### Kiểm tra các dịch vụ kết nối đến các port của hệ thống
```sh
netstat -tulnp
```

<ul>
<li>l: listen - các port của hệ thống đang mở cho phép các kết nối đến</li>
<li>n: numeric - output trả về các số</li>
<li>t: tcp - các kết nối dùng giao thức tcp</li>
<li>u: udp - các kết nối dùng giao thức udp</li>
<li>p: program - các chương trình đang kết nối đến</li>
</ul>

<img src="http://i.imgur.com/IZpsDF2.png">

### Kiểm tra các port 

