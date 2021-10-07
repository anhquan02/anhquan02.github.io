---
layout: post
title:  "Activity diagram"
date:   2021-09-30 15:48:33 +0700
categories: jekyll update
---
# Activity diagram

## Activity diagram là gì?

•Là một sơ đồ dung để mô hình hóa các hoạt động trong một quy trình nghiệp vụ.

•Biểu diễn mối liên hệ giữa các đối tượng theo trình tự.

•Được sử dụng để biểu diễn cho hoạt động của một use case.

•Làm rõ quy trình xử lý nghiệp vụ.

•Làm rõ sự luân chuyển dữ liệu trong hệ thống.

•Mô tả thuật toán

Các thành phần:

* Điểm bắt đầu( Start node): Thể hiện cho 1 việc bắt  đầu luồng chạy. Trong activity diagram chỉ được phép có 1 Start node duy nhất. Trước Start node không được xuất hiện bất kì một node nào.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/1.png)  

* Điểm kết thúc(End node): Thể hiện cho việc kết thúc luồng chạy . Trong 1 actitvy diagram chỉ có 1 End node. Sau End node sẽ không được xuất hiện bất kì một node nào.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/2.png)

* Action node: Đại diện cho 1 thao tác cần thực hiện.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/3.png)

* Object node: Đại diện cho 1 đối tượng trong luồn xử lý.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/4.png)

* Control flow: Thể hiện cho luồng chạy của Activity.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/5.png)

* Decision node: Thể hiện cho điều kiện, rẽ nhánh. Đảm bảo luồng hoạt động theo 1 nhánh duy nhất.
![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/6.png)

\*Merge node: Chiều ngược lại của Decision node. Gộp các nhánh con của Decision node thành 1 luồng duy nhất.
![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/7.png)

\*Fork node: Tách luồng xử lý thành nhiều nhánh con chạy song song. Thể hiện cho việc đồng thời xảy ra.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/8.png)

\*Join node: Chiều ngược lại của Fork node. Sau khi hành động song song kết thúc, gom các luồng xử lí về 1 luồng chính.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/9.png)

\*Swimlane: Phân làn trong biểu đồ sử dụng. Phần kí hiệu này thường được sử dụng để làm rõ luồng hoạt động của các đối tượng riêng biệt.

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/10.png)



## Cách xây dựng Actitvity diagram

**Bước 1: Xác định các nghiệp vụ cần mô tả**

Xem xét bản vẽ Use Case  để xác định nghiệp vụ nào bạn cần mô tả.

**Bước 2: Xác định trạng thái đầu tiên và trạng thái kết thúc**

**Bước 3: Xác định các hoạt động tiếp theo**

Xuất phát từ điểm bắt đầu, phân tích để xác định các hoạt động tiếp theo cho đến khi gặp điểm kết thúc để hoàn tất bản vẽ này.

Ví dụ:

![](https://raw.githubusercontent.com/anhquan02/anhquan02.github.io/anhquan02/docs/img/Activity/11.png)

Dựa vào sơ đồ trên, ta phân tích như sau:
* Bước 1: Người dùng chọn chức năng đổi mật khẩu.
* Bước 2: Hệ thống sẽ hiển thị form đổi mật khẩu cho người nhập dữ liệu.
* Bước 3: Người dùng điền đầy đủ thông tin có thể chọn xác nhận hoặc huỷ( kết thúc). Nếu xác nhận thì tiếp bước 4.
* Bước 4: Hệ thống kiểm tra các thông tin về mật khẩu bảo mật, mật khẩu xác nhận có trùng khớp không. Nếu trùng tiếp đến bước 5 còn không hệ thống sẽ quay lại bước 2.
* Bước 5: Hệ thống sẽ thay đổi thông tin của người dùng.
* Bước 6: Thông báo thay đổi cho người dùng rồi kết thúc.

Link tham khảo: [What is Activity Diagram? (visual-paradigm.com)](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-activity-diagram/)
