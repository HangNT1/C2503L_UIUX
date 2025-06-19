# Output buổi 4: https://www.figma.com/design/AHfkUScYfolVGT2cJ4tStQ/Buoi4_RWD_ti%E1%BA%BFp?node-id=0-1&t=KwZ36lCFsHxazuyi-1

**Thời gian:**  
**Mục tiêu bài học:**

- Hiểu rõ về **breakpoints** và **navigation drawer** trong **Responsive Web Design (RWD)**.
- Áp dụng các khái niệm này để tối ưu hóa thiết kế trang web cho nhiều loại thiết bị.
- Nắm vững cách tùy chỉnh **breakpoints** và sử dụng **navigation drawer** hiệu quả trong các ứng dụng.

---

## **1. Giới Thiệu về Breakpoints trong RWD** (45 phút)

### **1.1. Breakpoint là gì?**

- **Breakpoint** là **điểm chuyển tiếp** trong thiết kế giao diện người dùng, nơi mà cấu trúc hoặc bố cục của trang web thay đổi tùy theo kích thước màn hình của thiết bị người dùng.
- Các **media queries** trong CSS giúp xác định các điểm này, giúp trang web điều chỉnh bố cục cho phù hợp với các kích thước màn hình khác nhau.

### **1.2. Các Loại Breakpoints:**

- **Major Breakpoints (Điểm Chuyển Tiếp Chính):**

  - **Định nghĩa:** Major breakpoints là những điểm chuyển tiếp chính trong thiết kế khi có sự thay đổi lớn về bố cục của trang web.
  - **Ví dụ:** Khi bố cục của trang web chuyển từ hai cột thành bốn cột, đây là một thay đổi lớn, có thể ảnh hưởng đến cách người dùng tương tác với nội dung và trang web.
  - **Lý do:** Major breakpoints thường được áp dụng khi có sự thay đổi rõ rệt về giao diện và bố cục của trang web để đảm bảo rằng nó sẽ hiển thị tối ưu trên các thiết bị khác nhau, chẳng hạn như chuyển từ bố cục nhiều cột sang một cột duy nhất trên điện thoại.

- **Minor Breakpoints (Điểm Chuyển Tiếp Nhỏ):**
  - **Định nghĩa:** Minor breakpoints là những điểm chuyển tiếp nhỏ khi có sự thay đổi nhẹ trong thiết kế.
  - **Ví dụ:** Một ví dụ điển hình là khi di chuyển nhãn của các trường form từ trên xuống bên trái của trường, nhưng phần còn lại của thiết kế không thay đổi. Điều này giúp người dùng dễ dàng tương tác với các form trên thiết bị nhỏ mà không cần phải thay đổi toàn bộ bố cục.
  - **Lý do:** Minor breakpoints thường được sử dụng để điều chỉnh các yếu tố cụ thể trong giao diện như vị trí của các trường nhập liệu mà không thay đổi toàn bộ cấu trúc trang.

---

## **2. Tùy Chỉnh Breakpoints** (45 phút)

### **2.1. Tạo Điểm Chuyển Tiếp Tùy Chỉnh**

- Việc tạo **custom breakpoints** là một quá trình hợp lý, chỉ cần bạn hiểu về cách sử dụng **media queries** để tạo ra các điểm chuyển tiếp phù hợp với thiết kế của mình.
- **Tầm quan trọng:** Tạo ra các **breakpoints tùy chỉnh** giúp bạn tối ưu hóa trải nghiệm người dùng khi trang web được hiển thị trên nhiều thiết bị có kích thước màn hình khác nhau, từ di động đến máy tính để bàn.

### **2.2. Các Quy Tắc Khi Tạo Điểm Chuyển Tiếp Tùy Chỉnh:**

- **2.2.1. Chọn Extension Trình Duyệt Phù Hợp (Choosing the Right Browser Extension)**

  - **Giải thích:** Khi tạo các điểm chuyển tiếp tùy chỉnh, bạn cần sử dụng **extensions** của trình duyệt để kiểm tra và điều chỉnh kích thước màn hình.
  - **Ví dụ:** Dùng **Resize Window for Chrome** là một sự lựa chọn tuyệt vời, vì công cụ này cho phép bạn thấy rõ các kích thước hiện tại của cửa sổ trình duyệt khi bạn thu nhỏ cửa sổ (hiển thị kích thước ở góc dưới bên phải của trình duyệt).

- **2.2.2. Khám Phá Giữa Các Breakpoints Tiêu Chuẩn (Explore Between Standard Breakpoints)**
  - **Giải thích:** Việc kiểm tra và thử nghiệm giữa các **breakpoints tiêu chuẩn** giúp bạn nhận ra các sự khác biệt trong giao diện và bố cục khi thiết kế.
  - **Ví dụ:** Các vấn đề không đồng nhất trong giao diện có thể xảy ra giữa các **breakpoints tiêu chuẩn**, và công cụ như **Resize Window** sẽ giúp nhận diện những vùng cần điều chỉnh sau khi kiểm tra mọi chiều rộng pixel của cửa sổ.

### **Tóm lại:**

- **Tùy chỉnh breakpoints** là một phần quan trọng trong **Responsive Web Design** để đảm bảo rằng trang web hiển thị đúng trên mọi thiết bị.
- Việc sử dụng **browser extensions** và khám phá các **breakpoints tiêu chuẩn** giúp tối ưu hóa thiết kế và khắc phục các vấn đề liên quan đến giao diện và bố cục khi trang web thay đổi kích thước màn hình.

---

## **3. Navigation Drawer là gì?** (30 phút)

### **3.1. Mô Tả Navigation Drawer**

- **Navigation Drawer** là một thành phần giao diện người dùng giúp điều hướng giữa các phần khác nhau của ứng dụng một cách nhanh chóng. Đây là một phần quan trọng trong thiết kế giao diện người dùng trên các thiết bị di động và web, đặc biệt khi ứng dụng có nhiều màn hình hoặc tính năng.

### **3.2. Các Yếu Tố Quan Trọng của Navigation Drawer:**

- **2.1. Dùng cho việc điều hướng cấp cao trong ứng dụng:**
  - **Mô tả:** Navigation Drawer giúp người dùng di chuyển giữa các phần khác nhau của ứng dụng mà không cần phải quay lại màn hình chính hoặc điều hướng phức tạp.
- **2.2. Được yêu cầu khi người dùng có thể di chuyển qua nhiều đường dẫn khác nhau:**

  - **Mô tả:** Trong một ứng dụng phức tạp, người dùng có thể cần di chuyển qua nhiều phần khác nhau của ứng dụng mà không cần có một màn hình khởi động cố định. Navigation Drawer giúp điều hướng nhanh chóng và linh hoạt giữa các phần của ứng dụng.

- **2.3. Được yêu cầu trong giao diện người dùng có hơn ba chế độ xem cấp cao:**

  - **Mô tả:** Khi ứng dụng có quá nhiều chức năng hoặc các mục menu, thanh điều hướng thông thường sẽ không đủ không gian. Lúc này, Navigation Drawer giúp tiết kiệm không gian màn hình và giữ cho giao diện gọn gàng.

- **2.4. Mẫu thiết kế của Navigation Drawer tương tự trên cả hai nền tảng iOS và Android:**
  - **Mô tả:** Navigation Drawer cung cấp một thiết kế duy nhất hoạt động tốt trên cả iOS và Android, giúp các nhà phát triển tiết kiệm thời gian và công sức khi thiết kế ứng dụng cho cả hai nền tảng.

### **Ví dụ về Navigation Drawer:**

- **Ứng dụng Gmail:** Trong ứng dụng Gmail trên điện thoại, Navigation Drawer hiển thị các mục như "Hộp thư đến," "Thư đã gửi," "Danh bạ," v.v. Khi người dùng vuốt hoặc nhấn vào biểu tượng menu, Navigation Drawer xuất hiện từ bên trái màn hình, giúp điều hướng nhanh chóng giữa các mục.
- **Ứng dụng Facebook:** Facebook cũng sử dụng Navigation Drawer để hiển thị các mục như "Trang cá nhân," "Thông báo," "Bạn bè," v.v., giúp người dùng dễ dàng chuyển đổi giữa các phần của ứng dụng mà không bị làm phiền bởi các menu phức tạp.

### **Tóm lại:**

- **Navigation Drawer** là một công cụ hữu ích trong thiết kế giao diện người dùng cho các ứng dụng có nhiều chức năng hoặc phần khác nhau. Nó giúp tối ưu hóa không gian và tạo ra một trải nghiệm người dùng mượt mà, dễ dàng chuyển đổi giữa các mục mà không làm mất đi tính thẩm mỹ của ứng dụng.
