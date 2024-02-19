# Docker, docker-composer là gì?
`Docker` là một nền tảng cho phép các Developers có thể develop, deploy và run applications. Nó cho phép tạo các môi trường độc lập và tách biệt để khởi chạy và phát triển ứng dụng và môi trường này được gọi là container. Khi cần phải deploy ứng dụng thì chỉ cần chạy container thì application sẽ được khởi chạy ngay lập tức.

`Docker Compose` là một tool cho phép định nghĩa và run multi-container cho Docker application. Để sử dụng compose ta cần một file YAML để config các services cho applicatio, sau đó dùng command để create và run từ những config đó. Một ví dụ cần đến compose là khi ta thiết kế 1 web app, sẽ có thể cần các container riêng biệt, một cái đảm nhận front-end, cái khác đảm nhận back-end và cái đảm nhận database. 
# Linux, Unix, BSD hay *nix? macOS thuộc loại nào?
- `Linux` nói một cách chính xác thì chỉ là kernel (hạt nhân) của hệ điều hành. Còn hệ điều hành Linux mà ngày nay mọi người vẫn nhắc đến thì có tên đầy đủ là GNU/Linux. Sự kết hợp của các phần mềm thuộc GNU Project (dự án phát triển hệ điều hành miễn phí) và Linux Kernel đã tạo nên hệ điều hành này. Linux là open source nên được người dùng ưa chuộng vì tính linh hoạt và thoải mái.
- `Unix` là hệ điều hành được phát triển vào những năm đầu của thập kỷ 1970 bởi nhóm nghiên cứu Bell Labs. Nó là một trong những hệ điều hành đầu tiên được viết bằng ngôn ngữ lập trình C và đã đặt nền móng cho nhiều hệ điều hành hiện đại. Unix chia sẻ các đặc điểm cơ bản như cấu trúc Kernel-Shell, giao diện dòng lệnh mạnh mẽ và tính linh hoạt cao.
- `BSD`  là một phiên bản nổi bật của hệ điều hành Unix được phát triển và phân phối bởi tập đoàn Computer Systems Research (CSRG) từ Đại học California tại Berkeley giữa năm 1977 và 1995. BSD giữ các tính năng của Unix cơ bản và cung cấp các bản phân phối phổ biến như FreeBSD, OpenBSD và NetBSD. Trong đó FreeBSD hướng tới hiệu suất cao và dễ sử dụng, OpenBSD hướng tới tính bảo mật còn NetBSD hướng tới việc hỗ trợ nhiều kiến trúc hơn.
- `*nix` là thuật ngữ để chỉ các hệ điều hành và hệ thống tương tự Unix, bao gồm cả Unix chính thống và các biến thể phát triển từ Unix.
- macOS được tạo ra dựa trên FreeBSD
# Alpine và Ubuntu
Alpine và Ubuntu là hai bản phân phối phổ biến của Linux.
- `Alpine` là một bản phân phối Linux nhẹ và tối giản, được thiết kế để có kích thước nhỏ và tối ưu hóa hiệu suất. Với kích thước nhỏ, Alpine thích hợp cho việc triển khai trong các môi trường có hạn chế về tài nguyên như container và thiết bị nhúng. Alpine nổi tiếng với tính bảo mật cao và sử dụng các công nghệ như PaX và grsecurity để tăng cường bảo mật.

- `Ubuntu` là một bản phân phối Linux phổ biến, được phát triển và duy trì bởi Canonical Ltd., với sự hỗ trợ rộng rãi từ cộng đồng. Ubuntu có kích thước lớn hơn và cung cấp nhiều tính năng hơn so với Alpine, bao gồm giao diện đồ họa và một loạt các ứng dụng mặc định. Nó thích hợp cho cả các máy tính cá nhân và máy chủ, cũng như cho việc phát triển phần mềm và triển khai ứng dụng trong môi trường sản xuất.

# VNC 
`VNC`, hay `Virtual Network Computing`, là công nghệ cho phép người sử dụng điều khiển và truy cập một máy tính từ xa thông qua Internet. VNC hoạt động theo mô hình Client/Server. Máy tính bị điều khiển đóng vai trò là Server, đợi các kết nối từ Client. Còn máy tính local sử dụng từ xa sẽ sử dụng một trình xem VNC với vai trò là Client kết nối và sử dụng Server.
