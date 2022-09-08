# TÌM HIỂU VỀ MÔ HÌNH OSI
## Người viết : Phùng Công Việt Anh
## Mail : pcvietanh.99@gmail.com

***
# Mục lục
## [I. Mô hình OSI là gì](https://github.com/vietanhtb/OSI#im%C3%B4-h%C3%ACnh-osi-l%C3%A0-g%C3%AC)

*  ### [1. Tầng vật lý(Physical layer) ](https://github.com/vietanhtb/OSI#1-t%E1%BA%A7ng-v%E1%BA%ADt-l%C3%BD-physical-layer)
   
*  ### [2. Tầng liên kết (Datalink) ](https://github.com/vietanhtb/OSI#2-t%E1%BA%A7ng-li%C3%AAn-k%E1%BA%BFt-datalink)
    
* ### [3. Tầng mạng (Network) ](https://github.com/vietanhtb/OSI#3-t%E1%BA%A7ng-m%E1%BA%A1ng-network)
    
* ### [4. Tầng vận chuyển (Transport) ](https://github.com/vietanhtb/OSI#4-t%E1%BA%A7ng-v%E1%BA%ADn-chuy%E1%BB%83n-transport)
    
* ### [5. Tầng phiên (Session) ](https://github.com/vietanhtb/OSI#5-t%E1%BA%A7ng-phi%C3%AAn-session)
    
* ### [6. Tầng trình diễn (Presentation) ](https://github.com/vietanhtb/OSI#6-t%E1%BA%A7ng-tr%C3%ACnh-di%E1%BB%85n-presentation)
    
* ### [7. Tầng Ứng dụng (Application)](https://github.com/vietanhtb/OSI#7-t%E1%BA%A7ng-%E1%BB%A9ng-d%E1%BB%A5ng-application-1)

    
 ## [II. Các giao thức trong OSI](https://github.com/vietanhtb/OSI#ii-c%C3%A1c-giao-th%E1%BB%A9c-trong-osi-1)
 
 ## [III. Phương thức hoạt động của mô hình OSI](https://github.com/vietanhtb/OSI#iii-ph%C6%B0%C6%A1ng-th%E1%BB%A9c-ho%E1%BA%A1t-%C4%91%E1%BB%99ng-c%E1%BB%A7a-m%C3%B4-h%C3%ACnh-osi-1)
 
* ### [1. Bên máy gửi](https://github.com/vietanhtb/OSI#1-b%C3%AAn-m%C3%A1y-g%E1%BB%ADi-1)
    
* ### [2. Bên máy nhận](https://github.com/vietanhtb/OSI#2-b%C3%AAn-m%C3%A1y-nh%E1%BA%ADn-1)
    
***
# ***I.	Mô hình OSI là gì***
* Mô hình kết nối các hệ thống mở OSI là mô hình căn bản về các tiến trình truyền thông, thiết lập các tiêu chuẩn kiến trúc mạng ở mức Quốc tế, là cơ sở chung để các hệ thống khác nhau có thể liên kết và truyền thông được với nhau. Mô hình OSI tổ chức các giao thức truyền thông thành 7 tầng, mỗi một tầng giải quyết một phần hẹp của tiến trình truyền thông, chia tiến trình truyền thông thành nhiều tầng và trong mỗi tầng có thể có nhiều giao thức khác nhau thực hiện các nhu cầu truyền thông cụ thể.
* Mô hình OSI được tạo ra với mục đích là cho phép sự tương giao (interoperability) giữa các hệ máy (platform) đa dạng được cung cấp bởi các nhà sản xuất khác nhau. Mô hình cho phép tất cả các thành phần của mạng hoạt động hòa đồng, bất kể thành phần ấy do ai tạo dựng. Vào những năm cuối thập niên 1980, ISO đã tiến cử việc thực thi mô hình OSI như một tiêu chuẩn mạng.
* Mô hình OSI gồm 7 tầng:
    1. Tầng vật lý (Physical layer)
    2. Tầng liên kết (Datalink) 
    3. Tầng mạng (Network) 
    4. Tầng vận chuyển (Transport)
    5. Tầng phiên (Session)
    6. Tầng trình diễn (Presentation) 
    7. Tầng Ứng dụng (Application) 
* Đi vào chi tiết các tầng sẽ như sau:
## ***1. Tầng vật lý (Physical layer)***
* Tầng vật lý là tầng thấp nhất trong mô hình dùng để xác định các chức năng, thủ tục về điện, cơ, quang để kích hoạt duy trì và giải phóng các kết nối vật lý giữa các hệ thống mạng. Nói đơn giản thì tầng vật lý định nghĩa tất cả các đặc tả về điện và vật lý cho các thiết bị. Trong đó bao gồm bố trí của các chân cắm, các hiệu điện thế, các đặc tả về cáp 
nối,…

* Các thiết bị tầng vật lý bao gồm Hub, bộ lặp, thiết bị chuyển đối tín hiệu, thiết bị tiếp hợp mạng, thiết bị tiếp hợp kênh máy chủ,…

* Chức năng căn bản của tầng vật lý:

    * Thiết lập hoặc ngắt mạch kết nối điện với một môi trường truyền dẫn phương tiện truyền thông.
    * Tham gia vào quy trình, trong đó các tài nguyên truyền thông được chia sẻ giữa nhiều người dùng.
    * Điều chế hoặc biến đổi giữa dữ liệu số của các thiết bị người dùng và các tín hiệu tương ứng được truyền qua kênh truyền thông.
## ***2. Tầng liên kết (Datalink)***
* Tầng liên kết dữ liệu có chức năng chính là thực hiện thiết lập các liên kết, hủy bỏ và duy trì các liên kết
* Phát hiện và có thể sửa chữa các lỗi trong tầng vật lý nếu có
* Tầng liên kết dữ liệu chính là nơi các thiết bị chuyển mạch hoạt động. Kết nối chỉ đượ cung cấp giữa các nút mạng được nối với nhau trong mạng nội bộ. 
## ***3. Tầng mạng (Network)***
* Tầng mạng cung cấp các chức năng và quy trình cho việc truyền các chuỗi dữ liệu từ  một nguồn tới 1 đích thông qua một hoặc nhiều mạng
* Tầng mạng chọn đường đi cho các gói tin. Ngoài ra chúng còn có chức năng điều kiển tắc nghẽn khi nhiều gói tin cùng lưu chuyển trên 1 đường và xảy ra nghẽn
## ***4. Tầng vận chuyển (Transport)***
* Tầng giao vận có nhiệm vụ chuyển dữ liệu giữa các giữa  các người dùng tại đầu cuối
* Kiểm soát độ tin cậy của một kết nối được cho trước
* Tầng giao vận thực hiện chia nhỏ các gói tin lớn trước khi gửi đi và đánh dấu thứ tự cho các gói tin để chúng được chuyển theo thứ tự. Ngoài ra còn theo dõi các gói tin và truyền lại các gói tin thất bại
* Đây là tâng cuối chịu trách nhiệm về độ an toàn trong truyền dữ liệu
## ***5. Tầng phiên (Session)***
* Có nhiệm vụ kiểm soát các phiên làm việc giữa các máy. Tầng này thiết lập, duy trì, đồng bộ hóa và quản lý các kết nối giữa trình ứng dụng.

## ***6. Tầng trình diễn (Presentation)***
* Tầng trình diễn có nhiệm vụ giải quyết các vấn đề liên quan đến các cú pháp và ngữ nghĩa của các thông tin được truyền đi. Tại máy truyền dữ liệu sẽ dịch dữ liệu được gửi từ tầng ứng dụng qua định dạng chung. Tại máy nhận thì chuyển từ định dang chung sang định dạng của tầng ứng dụng.
## ***7. Tầng Ứng dụng (Application)***
* Là tầng gần với người sử dụng nhất, giúp xác định giao diên giữa người dùng và môi trường OSI. Cung cấp phương tiện cho người dùng truy cập vào các thông tin và dữ liệu trên mạng thông qua chướng trình ứng dụng
# ***II. Các giao thức trong OSI***
# ***III. Phương thức hoạt động của mô hình OSI***
## ***1. Bên máy gửi***
* Tại tầng 7 (Tầng ứng dụng/Application) người dùng đưa thông tin vào máy tính dưới dạng văn bản, hình ảnh,...
* Tại tầng 6 (Tầng trình diễn/Presentation) tiếp nhận thông tin được chuyển đến từ tầng 7, thông tin sẽ được tiến hành mã hóa và nén dữ liệu. Sau khi được mã hóa và nén, dữ liệu được chuyển đến tầng 5.
* Tại tầng 5 (Tầng phiên/ Session) các dữ liệu sẽ được xử lý sau đó bổ sung thêm các thông tin cần thiết(Có thể hiểu đây là bước xác nhận các thông tin). Sau khi xác nhận xong thông tin được đẩy xuống tầng 4
* Tại tầng 4 (Tầng vận chuyển/Transport) các dữ liệu sẽ được chia thành nhiều phần nhỏ, đồng thời nó cũng được bổ sung thêm các thông tin như phương thức vận chuyển để đảm bảo tính bảo mật sau đó chuyển tới tầng 3.
* Tại tầng 3 (Tầng mạng/Network) các phần dữ liệu vừa được chia nhỏ lại tiếp tục được chia ra thành nhiều gói thông tin khác nhau. Sau đó các gói thông tin sẽ được vận chuyển theo đúng tuyến đường đi đã được định sẵn tới tầng 2.
* Tại tầng 2 (Tầng liên kết/Datalink) các gói thông tin nhỏ từ tầng 3 tiếp tục được cắt nhỏ thành những Frame tại đây, đồng thời được bổ sung thông tin kiểm tra các gói tin chứa dữ liệu này để có thể kiểm tra ở đầu máy nhận khi thông tin tới.
* Tại tầng cuối, tầng 1 (Tầng vật lý/Physical) các Frame khi được chuyển đến đây sẽ được chuyển thành các chuỗi bit nhị phân, sau đó được đưa lên, phát tin hiệu trên các công cụ truyền dẫn (dây cáp quang) để chuyển tới được máy nhận.
## ***2. Bên máy nhận***
* Dữ liệu từ máy gửi đến tiếp xúc đầu tiên với tầng 1 (Tầng vật lý/Physical) của máy nhận. Ở đây, các dữ liệu sẽ được kiểm tra đồng bộ và đưa các chuỗi bit nhị phân vào vùng đệm, sau đó là gửi thông báo cho Tầng 2 “dữ liệu đã được nhận).
* Tại tầng 2 (Tầng liên kết/Datalink) kiểm tra xem có lỗi nào đối với các Frame dữ liệu vừa gửi không. Khi phát hiện Frame bị lỗi thì sẽ hủy bỏ Frame đó. Tiếp đến là quá trình kiểm tra địa chỉ Data Link (địa chỉ MAC Address) có khớp với địa chỉ máy nhận hay không. Kiểm tra đúng, Data Link sẽ gỡ bỏ Header để chuyển dữ liệu đến tầng 3.
* Tại tầng 3 (Tầng mạng/Network) tiếp nhận và kiểm tra địa chỉ gói tin dữ liệu có phải là địa chỉ máy nhận không (địa chỉ ở tầng này là IP). Nếu đúng các gói tin dữ liệu tiếp tục được gỡ bở Header của tầng Network rồi được chuyển tới tầng 4.
* Tại tầng 4 (Tầng vận chuyển/Transport) sẽ được hỗ trợ phục hồi và xử lý lỗi bằng cách gửi các gói tin ACK, NAK là những gói tin dùng để phản hồi xem các gói chứa dữ liệu đã được gửi đến máy nhận hay chưa. Khi các gói tin đã được phục hồi xong sẽ được chuyển tiếp lên tầng 5
* Tại tầng 5 (Tầng phiên/ session) kiểm tra chắc chắn các gói tin toàn vẹn từ máy gửi tới máy nhận. tiếp tục gỡ bỏ header của tầng 5 và chuyển thông tin đi.
* Tại tầng 6 (Tầng trình diễn/Presentation) tiếp nhận, tiến hành chuyển đổi định dạng dữ liệu để xử lý gói tin đưa đến tầng 7
* Tại Tầng 7 (Tầng ứng dụng/Application) nhận dữ liệu, gỡ bỏ nốt header, kết thúc quá trhf nhận dữ liệu đến.
