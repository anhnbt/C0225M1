# Tổng Quan Về JavaScript

## Mục Lục

1. [JavaScript là gì?](#javascript-là-gì)
2. [Ý nghĩa của JavaScript](#ý-nghĩa-của-javascript)
3. [Mục tiêu của JavaScript](#mục-tiêu-của-javascript)
4. [Tại sao nên học JavaScript?](#tại-sao-nên-học-javascript)
5. [Cú pháp JavaScript](#cú-pháp-javascript)
6. [Các cách nhúng JavaScript vào trang web](#các-cách-nhúng-javascript-vào-trang-web)
7. [Chương trình JavaScript đơn giản](#chương-trình-javascript-đơn-giản)
8. [Quy tắc đặt tên file](#quy-tắc-đặt-tên-file)

## JavaScript là gì?

JavaScript là một ngôn ngữ lập trình dựa trên script, được sử dụng để phát triển các ứng dụng trên cả phía client-side và server-side.

- **Client-side**: Các script được thực thi trực tiếp trên trình duyệt.
- **Server-side**: Các script được thực thi trên máy chủ.

JavaScript được phát triển bởi Netscape và Sun Microsystems nhằm cung cấp khả năng tạo ra các trang web động và tương tác, cải thiện trải nghiệm người dùng.

## Ý nghĩa của JavaScript

Ban đầu, HTML được phát triển để tạo ra tài liệu tĩnh. Tuy nhiên, với sự phổ biến của Internet, nhu cầu tạo ra các trang web sáng tạo, tương tác và dễ sử dụng ngày càng tăng. JavaScript ra đời để:

- **Thêm khả năng tương tác**: Người dùng có thể thao tác với các phần tử trên trang.
- **Cải thiện tính động**: Cho phép thay đổi nội dung mà không cần tải lại trang.
- **Tăng khả năng xác thực dữ liệu**: Hỗ trợ kiểm tra dữ liệu người dùng nhập vào trước khi gửi về server.

## Mục tiêu của JavaScript

- Cung cấp cho các nhà phát triển khả năng điều khiển nội dung và chức năng của trang web.
- Nhúng mã JavaScript vào tài liệu HTML để tạo các trang web thông minh.
- Giúp kiểm tra và xác thực dữ liệu nhập từ người dùng.
- Tăng khả năng phát triển ứng dụng Internet dựa trên client và server.

## Tại sao nên học JavaScript?

JavaScript có tính ứng dụng rộng rãi trong nhiều lĩnh vực phát triển phần mềm:

- **Lập trình Web Front-End**: Sử dụng các framework như ReactJS, Angular, VueJS để tạo giao diện người dùng.
- **Lập trình Backend**: Dùng NodeJS cùng các framework như Express, NestJS để xây dựng hệ thống phía server.
- **Lập trình ứng dụng di động**: Dùng React Native, Ionic, hoặc NativeScript để phát triển ứng dụng đa nền tảng.
- **Phát triển game**: Các thư viện như Phaser, Kiwi.js hỗ trợ lập trình game.
- **Đồ họa và hoạt họa**: Sử dụng two.js (2D), three.js (3D) để phát triển đồ họa động.
- **Machine Learning**: Các thư viện như Brain.js, TensorFlow.js cho phép tích hợp học máy vào ứng dụng web.

Xu hướng lập trình hiện nay là trở thành một full-stack developer, và JavaScript là lựa chọn tối ưu nhờ khả năng phát triển cả front-end và back-end.

## Cú pháp JavaScript

Cú pháp JavaScript là tập hợp các quy tắc để viết mã JavaScript. Một số thành phần cơ bản:

- **Câu lệnh (Statement)**: Được phân tách bằng dấu chấm phẩy `;`.
- **Giá trị (Value)**: Bao gồm giá trị cố định (literal) và giá trị có thể thay đổi (biến).
- **Biến (Variable)**: Được khai báo bằng từ khóa `let` hoặc `var`.
- **Toán tử (Operator)**: Sử dụng để thực hiện các phép tính hoặc so sánh.
- **Biểu thức (Expression)**: Sự kết hợp của giá trị, biến và toán tử.
- **Từ khóa (Keyword)**: Các từ được định nghĩa sẵn trong JavaScript, như `let`, `const`, `if`, `return`.
- **Chú thích (Comment)**: Sử dụng `//` cho chú thích một dòng và `/* ... */` cho chú thích nhiều dòng.
- **Quy tắc đặt tên**: Tên phải bắt đầu bằng chữ cái, dấu gạch dưới `_` hoặc dấu `$`, và phân biệt chữ hoa và chữ thường.

## Các cách nhúng JavaScript vào trang web

Có một số cách để nhúng mã JavaScript vào trang web:

1. **Sử dụng thẻ `<script>` bên trong mã HTML**:

   ```html
   <script>
       document.getElementById("demo").innerHTML = "My First JavaScript";
   </script>
   ```

2. **Sử dụng file JavaScript riêng biệt**:

   Tạo file `myScript.js`:

   ```javascript
   function myFunction() {
       document.getElementById("demo").innerHTML = "Paragraph changed.";
   }
   ```

   Nhúng vào trang HTML:

   ```html
   <script src="myScript.js"></script>
   ```

3. **Viết mã JavaScript ngay trong các thẻ HTML**:

   ```html
   <button onclick="this.innerHTML='Hello World!'">Click me</button>
   ```

   *Lưu ý*: Việc viết mã JavaScript trực tiếp trong các thẻ HTML không được khuyến khích.

## Chương trình JavaScript đơn giản

JavaScript có thể:

- **Thay đổi nội dung HTML**: Sử dụng phương thức `getElementById()` để thay đổi nội dung của một phần tử.

  ```html
  <p id="demo">Hello World!</p>
  <script>
      document.getElementById("demo").innerHTML = "Hello JavaScript";
  </script>
  ```

- **Thay đổi thuộc tính thẻ HTML**: Thay đổi thuộc tính `src` của thẻ `<img>`.

  ```html
  <img id="myImage" src="pic1.jpg">
  <script>
      document.getElementById("myImage").src = "pic2.jpg";
  </script>
  ```

## Quy tắc đặt tên file

Khi đặt tên và lưu file, cần tuân thủ các quy tắc sau:

1. **Sử dụng ký tự hợp lệ**: Chỉ sử dụng chữ cái thường (a-z), chữ số (0-9), dấu gạch dưới `_` hoặc dấu gạch ngang `-`. Tránh sử dụng ký tự đặc biệt như `?`, `%`, `#`, `/`, `:`, `;`, `*`, `@`,...

2. **Không sử dụng dấu cách**: Thay vì dấu cách, sử dụng dấu gạch ngang `-` hoặc dấu gạch dưới `_`.

    - Không hợp lệ: `my website.html`
    - Hợp lệ: `my-website.html` hoặc `my_website.html`
