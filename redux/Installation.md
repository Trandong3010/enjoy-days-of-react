# Getting Started with Redux

## GIỚI THIỆU

Redux là một thư viện quản lý trạng thái (state management library) cho các ứng dụng web được viết bằng ReactJS. Redux cung cấp một giải pháp cho vấn đề quản lý trạng thái (state) trong ứng dụng ReactJS khi ứng dụng trở nên phức tạp và trạng thái cần được chia sẻ giữa các thành phần.

Redux giúp bạn quản lý trạng thái của ứng dụng bằng cách tạo ra một "store" (kho lưu trữ) để lưu trữ trạng thái của ứng dụng. Store là một đối tượng trung tâm cho phép các thành phần của ứng dụng truy cập và thay đổi trạng thái.

### Một số khái niệm quan trọng trong Redux bao gồm:

- `Action:` là một đối tượng mô tả hành động (action) sẽ được thực hiện trong ứng dụng. Mỗi action cần phải có một thuộc tính "type" để mô tả loại hành động đó.

- `Reducer:` là một hàm xử lý các action và trả về một phiên bản mới của trạng thái (state) của ứng dụng

- `Dispatch:` là một phương thức để gửi action tới store. Khi một action được gửi đi, store sẽ tự động chạy qua tất cả các reducer để xử lý action đó và cập nhật lại trạng thái của ứng dụng.

- `Subscribe:` là một phương thức để để đăng ký các hàm được gọi mỗi khi trạng tháu của store thay đổi.

### Một số lợi ích khi sử dụng Redux:

- `Quản lý trạng thái:` Redux giúp quản lý trạng thái của ứng dụng một cách hiệu quả, cho phép ta dễ dàng tìm kiếm và chỉnh sửa trạng thái một cách đồng bộ.

- `Dễ dàng debug:` Khi xảy ra lỗi, Redux cho phép ta dễ dàng theo dõi và phân tích các hành động (actions) và trạng thái (state) của ứng dụng.

- `Tái sử dụng code:` Redux cho phép ta tái sử dụng các hàm xử lý trạng thái (reducers) và các hành động (actions) trong nhiều thành phần khác nhau của ứng dụng, giúp giảm thiểu việc lặp lại code.

- `Đơn giản hóa kiến trúc ứng dụng:` Redux cung cấp một cách thức chuẩn để quản lý trạng thái của ứng dụng, giúp cho việc xây dựng và bảo trì ứng dụng trở nên đơn giản hơn.

- `Phát triển mở rộng:` Redux cho phép ta dễ dàng mở rộng các tính năng của ứng dụng, như thêm các Middleware hoặc kết hợp với các thư viện khác.

## TIẾN HÀNH

### NODEJS

Đầu tiên các bạn vào trạng https://nodejs.org/en/download/ để tải về Nodejs và cài đặt vào máy. Các bạn có thể tải về bản Long Term Support (LTS) hoặc Current đều được. Hiện tại bản LTS mới nhất là version 18.17.1.
Đối với bạn nào quen thuộc với terminal thì mình khuyến cáo sử dụng nvm để cài đặt và quản lý nhiều phiên bản của NodeJs trên cùng 1 máy. Như vậy các bạn sẽ linh động khi làm việc với nhiều dự án khác nhau có đòi hỏi khác nhau về version của NodeJs.
Sau khi cài đặt thành công các bạn có thể verify lại bằng cách mở Terminal/PowerShell/CMD (mình sẽ gọi chung là Terminal) và gõ các lệnh sau, nếu nó hiển thị ra được version thì đã cài đặt thành công.

```bash
node -v
npm -v
```

### REDUX CLI

Để sử dụng redux trong dự án, chúng ta sẽ sử dụng đến các lệnh từ Terminal, và chúng ta sẽ cài đặt thông qua NPM hoặc YARN bằng câu lệnh sau:

npm:

`npm install --save redux`

yarn 

`yarn add redux`


Để sử dụng Redux với react, bạn nên cài thêm package react-redux bằng câu lệnh sau:

npm

`npm install --save react-redux`

yarn

`yarn add react-redux`

Để cài đặt developer tools đối với Redux, bạn nên cài Redux dev-tools bằng câu lệnh sau:

npm 

`npm install --save-dev redux-devtools`

yarn

`yarn add -d redux-devtools`

## HASHTAG

`#EnjoyDaysOfCodeReact` `#EnjoyDaysLerningRedux` `#Redux tutorial` `Redux course`

## Link tham khảo

- https://redux.js.org/introduction/getting-started

## Author

[Tran Dong (Uno Tran)](https://github.com/Trandong3010)
