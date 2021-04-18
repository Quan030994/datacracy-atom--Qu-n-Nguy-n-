# GitHub là gì?
Là sự kết hợp giữa Git và Hub. GitHub được sử dụng chủ yếu cho dự án có nhiều người cùng hợp tác và cần giám sát toàn bộ thay đổi của dự án. Bên cạnh đó, GitHub còn có khả năng khôi phục code khi cần thiết. 
- Git là một hệ thống quản lý phiên bản phân tán (Distributed Version Control System – DVCS) ra đời năm 2005 và hiện nay được dùng rất phổ biến. Git giúp máy tính lưu trữ nhiều phiên bản khác nhau của một mã nguồn được nhân bản từ kho lưu trữ. Tất cả những code đã được update và thông tin về người sửa đổi đều được lưu lại với Git.
- Hub là nơi biến những dòng lệnh trên Git thành mạng xã hội cho lập trình viên.
Khi sử dụng GitHub, ngoài các công việc chính như tạo Branch, tạo Pull Request và Fork một Repository, bạn có thể theo dõi, tương tác với người khác như một mạng xã hội thông thường.
# 1. Một số khái niệm trong GitHub.
## 1.1. GitHub Repository (kho lưu trữ)
- Đây là nơi lưu trữ, quản lý tất cả những thông tin cần thiết như: thư mục, tập tin, ảnh, video, bảng biểu, dữ liệu, ... cũng như tất cả những sửa đổi và lịch sử của toàn bộ dự án. Khi tạo mới repository nên tạo một tập tin README hoặc một tập tin để giới thiệu về dự án của bạn.
- Có hai loại repository là local repository và remote repository.
## 1.2. GitHub Snapshot
- **Snapshot** là ảnh chụp các bước commit của bạn trên kho lưu trữ nhằm lưu lại nội dung tập tin, thư mục để tham chiếu. Để hiệu quả hơn, nếu tập tin không có thay đổi, Git không lưu trữ tập tin đó lại. Mà nó chỉ tạo liên kết tới tập tin gốc đã tồn tại trước đó. Sau đó khi cần bạn hoàn toàn có thể khôi phục và sử dụng lại một snapshot. Đây cũng chính là lợi thế của Git khi nó không lưu dữ liệu mà sẽ lưu dạng snapshot. Công cụ này sẽ giúp người dùng tiết kiệm khá nhiều không gian lưu trữ.
![image](https://user-images.githubusercontent.com/55431344/115151608-d3de5000-a097-11eb-8999-c3daef13f128.png)
## 1.3. GitHub Commit.
- Commit là thao tác ghi lại việc thêm/thay đổi file hay thư mục vào kho lưu trữ. Theo đó, kho sẽ tạo thư mục commit hoặc revision để ghi nhận những thay đổi này. Các commit nối tiếp nhau theo thứ tự thời gian chỉnh sửa. Vì vậy, chỉ cần nhìn vào đây, bạn sẽ biết được lịch sử chỉnh sửa và thay đổi các file. Mỗi commit đều yêu cầu phải có commit message giúp ghi nhận sự thay đổi theo tiến trình update của lập trình viên.
## 1.4. Push
- Push là lệnh đưa nội dung mà bạn commit từ kho lưu trữ ở local lên kho lưu trữ server.
## 1.5. Fetch
- Fetch là lệnh sử dụng trên kho lưu trữ server, giúp bạn di chuyển toàn bộ dữ liệu trên kho này về máy tính để tích hợp dữ liệu vào branch.
## 1.6. Pull
-Pull là lệnh lấy dữ liệu trên kho lưu trữ server để tích hợp vào branch.
## 1.7. GitHub Branch
- **Branch** là một tính năng cho phép bạn tách riêng các phần của dự án. Dùng Branch để thử nghiệm các tính năng mới hoặc điều chỉnh, sửa lỗi project. Khi khởi tạo kho lưu trữ hoặc Clone, bạn sẽ được tạo lập một branch riêng. Branch riêng sẽ chứa toàn bộ mã nguồn trong kho. Như vậy mọi thành viên đều có thể phát triển nên các nội dung mới mà không sợ ảnh hưởng đến phần code hiện tại.
- **Branch master** là nhánh “mặc định” khi bạn tạo một kho lưu trữ và là nhánh chính của ứng dụng.
## 1.8. GitHub Fork Repository
- Kho lưu trữ Fork là một bản copy của kho chứa source code trên GitHub. Tạo một Fork repository sẽ giúp bạn dễ dàng chỉnh sửa, thay đổi source code mà không ảnh hưởng kho lưu trữ gốc. https://github.com/anhdanggit/dataCRACY.
