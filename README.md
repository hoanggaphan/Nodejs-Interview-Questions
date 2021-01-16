# Phỏng vấn NodeJS

## Nguồn tham khảo
[edureka.co](https://www.edureka.co/blog/interview-questions/top-node-js-interview-questions-2016/#beginnerslevel)

## Mục lục
-   [Beginners Level](#beginner)
-   [Moderate Level](#moderate)
-   [Advanced Level](#advanced)

<a id="beginner"></a>
## Beginners Level

**1. Differentiate between JavaScript and Node.js.**
| Features | JavaScript |  Node  |
|--|--|--|
| **Type** | Ngôn ngữ lập trình | Trình thông dịch và môi trường cho JavaScript |
| **Utility** | Được sử dụng cho bất kì hoạt động client-side trong ứng dụng web | Được sử dụng để truy cập hoặc thực hiện bất kỳ hoạt động không chặn nào của bất kỳ hệ điều hành nào |
| **Running Engine** | Spider monkey (FireFox), JavaScript Core (Safari), V8 (Google Chrome), ... | V8 (Google Chrome) |

**2. What Is Node.js?**\
Node.js là một framework mạnh mẽ được phát triển trên công cụ JavaScript V8 của Chrome để biên dịch JavaScript trực tiếp thành mã máy gốc. Nó là một framework nhẹ được sử dụng để tạo các ứng dụng web phía server và mở rộng JavaScript API để cung cấp các chức năng phía server thông thường. Nó thường được sử dụng để phát triển ứng dụng quy mô lớn, đặc biệt là cho các trang phát trực tuyến video, trang đơn và các web khác.

**3. List down the major benefits of using Node.js?**
| Features | Description |
|--|--|
| **Fast** | Node.js được xây dựng trên Công cụ JavaScript V8 của Google Chrome, giúp thư viện của nó thực thi mã rất nhanh |
| **Asynchronous** | Server dựa trên Node.js không bao giờ đợi API trả lại dữ liệu, do đó làm cho nó không đồng bộ |
| **Scalable** | Nó có khả năng mở rộng cao vì cơ chế sự kiện của nó giúp máy chủ phản hồi theo cách không chặn |
| **Open Source** | Node.js có một cộng đồng mã nguồn mở rộng lớn đã góp phần tạo ra một số mô-đun tuyệt vời để bổ sung các khả năng cho các ứng dụng Node.js |
| **No Buffering** | Các ứng dụng Node.js chỉ xuất dữ liệu theo khối và không bao giờ đệm bất kỳ dữ liệu nào |

**4. What is the difference between Angular and Node.js?**
| Angular | Node.js |
|--|--|
| 1. Nó là một framework phát triển ứng dụng web mã nguồn mở | 1. Nó là một môi trường thời gian chạy đa nền tảng cho các ứng dụng |
| 2. Viết bằng TypeScript | 2. Viết bằng các ngôn ngữ C, C ++ và JavaScript |
| 3. Được sử dụng để xây dựng các ứng dụng web một trang phía client | 3. Được sử dụng để xây dựng các ứng dụng mạng phía server nhanh và có thể mở rộng |
| 4. Bản thân Angular là framework | 4. Node.js có nhiều framework khác nhau như Express.js, Nest.js, Meteor.js, ... |
| 5. Lý tưởng để tạo các ứng dụng web hoạt động và tương tác cao | 5. Lý tưởng để phát triển các dự án quy mô nhỏ |
| 6. Hữu ích trong việc tách một ứng dụng thành các MVC components | 6. Hữu ích trong việc tạo truy vấn cơ sở dữ liệu |
| 7. Thích hợp để phát triển các ứng dụng thời real-time | 7. Thích hợp trong các tình huống cần một thứ gì đó nhanh hơn và có thể mở rộng hơn |

**5. Why Node.js is single threaded?**\
Node.js sử dụng một mô hình luồng đơn để hỗ trợ xử lý không đồng bộ. Với xử lý không đồng bộ, ứng dụng có thể hoạt động tốt hơn và có khả năng mở rộng cao hơn khi tải web. Do đó, Node.js sử dụng cách tiếp cận mô hình đơn luồng thay vì triển khai dựa trên luồng điển hình.

**6. How do Node.js works?**\
Node.js là một máy ảo sử dụng JavaScript làm ngôn ngữ kịch bản và chạy trên môi trường v8. Nó hoạt động trên một vòng lặp sự kiện đơn luồng và một I/O không chặn cung cấp tốc độ cao vì nó có thể xử lý số lượng yêu cầu đồng thời cao hơn. Ngoài ra, bằng cách sử dụng mô-đun ‘HTTP’, Node.js có thể chạy trên bất kỳ máy chủ web độc lập nào.

**7. Where Node.js can be used?**\
Node.js có thể được sử dụng để phát triển:
+ Ứng dụng Web thời gian thực
+ Ứng dụng mạng
+ Hệ thống phân phối
+ Ứng dụng mục đích chung

**8. How many types of API functions are there in Node.js?**
Có hai loại API function trong Node.js:
+ Không đồng bộ, chức năng không chặn.
+ Đồng bộ, chức năng chặn.

**9. What is the difference between Asynchronous and Non-blocking?**
| Asynchronous | Non-blocking |
|--|--|
| **Asynchronous** nghĩa là không đồng bộ. Chúng có thể thực hiện các yêu cầu HTTP không đồng bộ mà không cần đợi server phản hồi. Các chức năng này tiếp tục phản hồi yêu cầu mà nó đã nhận được phản hồi từ server. | Các chức năng Non-blocking được sử dụng liên quan đến các hoạt động I/O. Chúng ngay lập tức phản hồi với bất kỳ dữ liệu nào có sẵn và tiếp tục chạy theo yêu cầu. Trong trường hợp không thể truy xuất bất kỳ câu trả lời nào thì API sẽ trả về ngay lập tức kèm theo lỗi. |

**10. What is package.json?**\
Tệp **package.json** trong Node.js là trung tâm của toàn bộ ứng dụng. Nó chứa siêu dữ liệu liên quan đến dự án và nó được sử dụng để quản lý các phần dependencies, script, version của dự án và nhiều hơn nữa.
![enter image description here](https://cdn1.bbcode0.com/uploads/2021/1/16/3cc5a5ddcee867d46f1240ce79bee143-full.png)

**11. What do you understand by Event-driven programming?**\
Event-driven programming (lập trình theo hướng sự kiện) là một cách tiếp cận lập trình sử dụng nhiều sự kiện để kích hoạt các chức năng khác nhau. Một sự kiện có thể là bất cứ thứ gì như nhấp chuột, nhấn phím, v.v. Khi một sự kiện xảy ra, một callback function đã được đăng ký với phần tử được thực thi. Cách tiếp cận này chủ yếu tuân theo mẫu publish-subscribe. Do lập trình theo hướng sự kiện, Node.js nhanh hơn khi so sánh với các công nghệ khác.

**12. What is an  _Event loop_  in Node.js and how does it work?**\
**Event loop (vòng lặp sự kiện)** trong Node.js xử lý tất cả các callback không đồng bộ trong một ứng dụng. Đây là một trong những khía cạnh quan trọng nhất của Node.js và lý do đằng sau Node.js có I/O không chặn. Vì Node.js là một ngôn ngữ hướng sự kiện, bạn có thể dễ dàng đính kèm một trình lắng nghe vào một sự kiện và sau đó khi sự kiện xảy ra, callback sẽ được thực thi bởi trình nghe cụ thể. Bất cứ khi nào các hàm như setTimeout, http.get và fs.readFile được gọi, Node.js sẽ thực thi **vòng lặp sự kiện (event loop)** và sau đó tiếp tục với mã tiếp theo mà không cần đợi kết quả. Khi toàn bộ hoạt động kết thúc, Node.js nhận đầu ra và sau đó thực hiện callback function. Đây là lý do tại sao tất cả các callback function được đặt trong một hàng đợi trong một vòng lặp. Khi phản hồi được nhận, chúng sẽ được thực thi từng cái một.
![](https://cdn1.bbcode0.com/uploads/2021/1/16/061e28385a33c44545257ffb4f67dc14-full.png)

**13. Explain REPL in the context of Node.js.**
REPL trong Node.js là viết tắt của Read, Eval, Print và Loop. Nó đại diện cho một môi trường máy tính như window console hoặc Unix/Linux shell nơi bất kỳ lệnh nào có thể được nhập vào và sau đó hệ thống có thể phản hồi với một đầu ra. Node.js đi kèm với môi trường REPL theo mặc định. REPL có thể thực hiện các tác vụ được liệt kê dưới đây:
+ **Read:**  Đọc thông tin đầu vào của người dùng, phân tích cú pháp thành cấu trúc dữ liệu JavaScript và sau đó lưu trữ trong bộ nhớ.
+ **Eval:**  Nhận và đánh giá cấu trúc dữ liệu.
+ **Print:** In kết quả cuối cùng.
+ **Loop:**  Lặp lại lệnh được cung cấp cho đến khi _CTRL + C_ được nhấn hai lần.

**14. List down the tasks which should be done asynchronously using the event loop?**
+ Hoạt động I/O
+ Tính toán nặng
+ Bất cứ điều gì yêu cầu blocking

**15. List down the steps using which “Control Flow” controls the function calls in Node.js?**
1.  Kiểm soát thứ tự thực hiện
2.  Thu thập dữ liệu
3.  Giới hạn đồng thời
4.  Gọi bước tiếp theo trong chương trình

<a id="moderate"></a>
## Moderate Level

<a id="advanced"></a>
## Advanced Level
