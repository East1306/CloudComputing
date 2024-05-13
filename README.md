# CloudComputing
## Cloud Computing and Comparision based on Service and Performance between Amazon AWS, Microsoft Azure, and Google Cloud
Abstract – Cloud Computing là yêu cầu nguồn từ web với cái phí bạn trả tương ứng việc sử dụng. Thay vào đó mua, vận hành và bảo trì máy tính vật lý, phần cứng và servers, đám mây giải quyết cung ứng như Microsoft
Azure, Amazon Web Service, Google Platform như là tiến trình năng lượng, bộ nhớ và có sở dữ liệu trên một cơ sở khi cần thiết.\
Chủ đề này sẽ nghiên cứu mô tả kiến trúc và loại dịch vụ cloud computing. Cũng như kết hợp hiệu suất và dịch vụ của 3 nền tảng cloud computing chính. Tất cả hệ thống được đánh giá trong môi trường ảo giống hệt nhau.\
IAAS được sử dụng rộng rãi nhờ các nhà cung cấp Memset, Amazon, Google,…\
IAAS sẽ cung cấp một loạt các dịch vụ đi kèm với các thành phần cs hạ tầng như billing, giám sát, truy cập nhật ký, bảo mật, cân bằng tải và phân cụm hay sao lưu và phục hồi.\
Iaas cho phép người dùng có thể dễ dàng và linh hoạt hơn trong việc mở rộng máy chủ.\
Linh hoạt trong việc lựa chọn các thông số kỹ thuật về hệ điều hành, phần cứng cho dịch vụ và sử dụng từ hệ thống mạng.

CloudComputing thì cần điện 24/24 để chạy và làm mát và cần quản lý hệ thống bởi các chuyên gia CNTT.\
Các giải pháp điện toán đám mây là tự phục vụ và theo yêu cầu ngay cả khối lượng lớn tính toán cũng được cung cấp. Hầu hết các dịch vụ đám mây sẽ cung cấp các điều khoản để tránh tăng tổng thế người dùng tư thế bảo mât, hỗ trợ bảo vệ dữ liệu, ứng dụng và kiến trúc từ mối đe dọa mạng.

Một hệ thống thống đám mây, dựa trên lựa chọn dịch vụ và sản phẩm của người bán về mặt lý thuyết nó có khả năng vô hạn.

Nhược điểm là người dùng không có nhiều quyền như ở trung tâm dữ liệu vì được quản lý bởi một bên thứ ba.


<https://viettelidc.com.vn/tin-tuc/iaas-la-gi-tat-tan-tat-nhung-dieu-ve-iaas-ma-nguoi-dung-khong-nen-bo-qua>

III. KIẾN TRÚC VÀ LOẠI CLOUD SERVICE:
Cơ sở hạ tầng của Điện toán dựa vào một loạt các công nghệ ứng dụng khác nhau để thực thi sự trừu tượng hóa của các tài nguyên vật lý thông qua ảo hóa và sự phân phối của chúng cho người dùng, là nền tảng của điện toán đám mây. Hai yếu tố này phục vụ làm nền tảng của mô hình kiến trúc Điện toán đám mây.

A. Frontend – Phía client (cơ sở hạ tầng khách hàng) của điện toán đám mây được gọi là phía frontend của kiến trúc đám mây. Nó bao gồm tất cả giao diện người dùng và ứng dụng mà khách hàng sử dụng để truy cập tài nguyên đám mây. Ví dụ, để truy cập nền tảng đám mây, bạn có thể cần sự trợ giúp của một trình duyệt web.

B. Backend - Đám mây chính, được sử dụng bởi nhà cung cấp dịch vụ. Nó giữ các tài nguyên, duy trì chúng và tích hợp các quy trình bảo mật. Nó cũng chứa lưu trữ lớn, ứng dụng ảo, máy tính ảo, các kỹ thuật quản lý lưu lượng, các mô hình triển khai, v.v.
	1. Ứng dụng – Đây là nền tảng cung cấp dịch vụ đám mây cho người dùng theo yêu cầu của họ.
	2. Lưu trữ - Cung cấp dịch vụ lưu trữ có thể mở rộng và quản lý dữ liệu trong đám mây theo yêu cầu của người dùng.
	3. Dịch vụ - Có ba loại dịch vụ chính của đám mây là IaaS, PaaS và SaaS.
		a. IaaS – Infrastructure as a Service (IaaS) là một mô hình cung cấp giải pháp mà bao gồm việc thuê phần cứng của một công ty để hỗ trợ hoạt động kinh doanh của các khách hàng khác, bao gồm không gian lưu trữ, phần cứng, máy chủ và các thành phần mạng. Người dùng của IaaS thường chi tiêu tiền cho dịch vụ dựa trên việc sử dụng. Các máy tính ảo, không gian lưu trữ, tường lửa và cân bằng tải đều có sẵn từ các nhà điều hành. Các thứ này có thể được thuê theo yêu cầu, và người dùng không kiểm soát hoặc duy trì kiến trúc đám mây, chỉ quản lý hệ điều hành trên chỗ, nâng cấp phần mềm và ứng dụng được sử dụng bởi người dùng.
		b. PaaS - Platform as a Service (PaaS) là một mô hình cung cấp giải pháp cho phép người dùng thuê máy ảo cùng với các cơ sở hạ tầng liên quan để sử dụng phần mềm hiện tại cũng như cho sản xuất, kiểm tra chất lượng và sử dụng phần mềm mới. Tuy nhiên, khác với hệ thống truyền thống, PaaS cung cấp một môi trường để tạo ra các ứng dụng có thể mở rộng với giá rẻ.
		c. SaaS - Software as a Service (SaaS) là một mô hình phần mềm được sử dụng để phân phối phần mềm dựa trên sự có sẵn và khả năng truy cập toàn cầu của các chương trình được tổ chức bởi các nhà cung cấp dịch vụ cho người dùng qua một mạng hoặc web chuyên dụng. Kỹ thuật này cho phép hoạt động hiệu quả nhất của các ứng dụng phần mềm, quản lý mượt mà, giá cả thấp, và loại bỏ nhu cầu về giấy phép phần mềm, cài đặt vật lý, bảo trì và mua các tài nguyên phần cứng cần thiết cho các chương trình hoạt động một cách hiệu quả. Sự linh hoạt được đạt được thông qua việc phân chia công việc qua một nhóm máy chủ là một trong những lợi ích quan trọng nhất của SaaS so với các ứng dụng truyền thống.
4. Cloud Runtime - Đây đề cập đến việc cung cấp môi trường thực thi và chạy cho các máy ảo.
5. Cơ sở hạ tầng - Bao gồm phần cứng như các thiết bị mạng, máy chủ, hệ thống lưu trữ, v.v.
6. Bảo mật - Bảo mật thực hiện các cơ chế bảo mật để bảo vệ dữ liệu được lưu trữ trong đám mây, hệ thống và kiến trúc của người dùng đến đám mây.
7. Quản lý - Đảm bảo tích hợp và hoạt động mượt mà của tất cả các thành phần backend.

IV. GIỚI THIỆU VÀ SO SÁNH CÁC CLOUD SERVICE:
A. Microsoft Azure (Azure):
	Microsoft Azure là một dịch vụ cho điện toán đám mây và một nền tảng web cho phép người dùng truy cập và quản lý các dịch vụ và tài nguyên đám mây của Microsoft. Các dịch vụ và tài nguyên này bao gồm việc lưu trữ và thay đổi dữ liệu dựa trên nhu cầu của người dùng. Để truy cập vào các tài nguyên và dịch vụ này, người dùng chỉ cần có một kết nối internet được thiết lập và khả năng đăng nhập vào cổng thông tin Azure. Nó đã được ra mắt vào năm 2010, và hiện nay nằm trong số các nhà cung cấp dịch vụ đám mây hàng đầu và là đối thủ cạnh tranh với AWS và GCP. Azure cung cấp hơn 100 dịch vụ điện toán đám mây.
	Nó tương thích với nhiều ngôn ngữ lập trình khác nhau, bao gồm Java, Node.js và C#. Azure có số lượng trung tâm dữ liệu nhiều nhất so với AWS hay GCP với hơn 42 trung tâm dữ liệu Azure được đặt tại khắp nơi trên thế giới và sẽ còn phát triển thêm.

B. Amazon Web Services (AWS):
	Amazon Web Services (AWS) là một nền tảng cung cấp các dịch vụ đám mây linh hoạt và tiết kiệm chi phí. AWS được sử dụng rộng rãi, cung cấp nhiều hoạt động theo yêu cầu như sức mạnh tính toán, cơ sở dữ liệu và quản lý, giao hàng thông tin và dữ liệu, và nhiều hơn nữa để giúp các doanh nghiệp phát triển và thịnh vượng. Các doanh nghiệp có thể sử dụng AWS để tạo ra nhiều ứng dụng phức tạp. Nó được ra mắt vào năm 2002 và hiện nay nằm trong số các nhà cung cấp dịch vụ đám mây hàng đầu và là đối thủ cạnh tranh với Azure và GCP. AWS cung cấp hơn 170 dịch vụ điện toán đám mây.
	Nhiều công ty trên khắp thế giới sử dụng AWS điển hình như Netflix, Adobe, Coinbase,...

C. Google Cloud (GCP):
	Google Cloud Platform là tập hợp các dịch vụ được trang bị kỹ thuật đám mây do Google cung cấp, hoạt động trên cùng kiến trúc với các ứng dụng chính khác của Google như YouTube, Gmail và các ứng dụng khác. Google Cloud Platform cung cấp hơn 100 dịch vụ. Nó được ra mắt vào năm 2008.
	Các công ty như PayPal, Twitter, Airbus, v.v. đang sử dụng các dịch vụ do Google Cloud Platform cung cấp.

V. SO SÁNH CHI PHÍ:
	Đối với loại phiên bản tổng quát (General Purpose), AWS có dịch vụ rẻ nhất với $0.154 mỗi giờ, tiếp theo là GCP với $0.156 mỗi giờ. Azure là đắt nhất cho loại phiên bản tổng quát trong số ba nhà cung cấp với $0.166 mỗi giờ. Đối với phiên bản tối ưu hóa điện toán (Compute Optimized), AWS lại là rẻ nhất với $0.136 mỗi giờ, tiếp theo là Azure với $0.169 mỗi giờ. GCP là đắt nhất trong số ba nhà cung cấp cho phiên bản tối ưu hóa điện toán với $0.235 mỗi giờ. Đối với loại phiên bản tối ưu hóa bộ nhớ (Memory Optimized), GCP là đắt nhất với $6.303 mỗi giờ, tiếp theo là Azure với $0.252 mỗi giờ và AWS lại là rẻ nhất với $0.202 mỗi giờ. Đối với loại phiên bản tính toán tăng tốc (Accelerated Computing), Azure cung cấp dịch vụ rẻ nhất với $0.526 mỗi giờ và GCP là đắt nhất với $3.839 mỗi giờ. 
	Phân tích và so sánh tổng quan về giá độc quyền của các nhà cung cấp dịch vụ đám mây này cho thấy AWS là rẻ nhất trong hầu hết các phiên bản và sẽ phù hợp với túi tiền của bất kỳ ai muốn sử dụng nó.

VI. SO SÁNH HIỆU SUẤT:
	Để kiểm tra hiệu suất của các phiên bản máy ảo(VM) của Ubuntu Linux Server 16.04 64 bit, đã được tạo trên AWS, Azure và GCP. 
	Phoronix Test Suite3 đã được chọn để tiến hành kiểm định vì nó cho phép đánh giá các hệ thống Linux và hiệu suất hệ thống trong các tình huống cụ thể. Việc cài đặt gói này từ kho lưu trữ Ubuntu rất đơn giản. Trên cả hai nền tảng, quá trình kiểm định các bài kiểm tra Apache, Dbench và tốc độ RAM (bao gồm trong Phoronix Test Suite3) đã được hoàn thành.
	Apache đo lường hiệu suất tổng thể của hệ thống và liên quan đến số lượng yêu cầu mà máy chủ có thể trả lời khi có 1 triệu yêu cầu và 100 trong số chúng là đồng thời. Qua bảng và biểu đồ, chúng ta có thể thấy rằng Azure có thể xử lý nhiều yêu cầu HTTP hơn hai nền tảng khác. GCP đứng ở vị trí thứ hai trong bài kiểm tra Apache này để xử lý số lượng yêu cầu mà máy chủ có thể trả lời. GCP đang cung cấp một sự cạnh tranh khó khăn cho Azure trong trường hợp kiểm tra này. Điều này là một yếu tố quan trọng cần xem xét đối với các khách hàng dự định sử dụng VM như một máy chủ với một lượng yêu cầu mỗi giây cao. Đối với những người dùng như vậy, Azure là lựa chọn tốt hơn giữa ba nền tảng.
	Bài kiểm tra Dbench là một lựa chọn miễn phí thay thế cho tiện ích netbench được sản xuất bởi dự án Samba. Phần mềm miễn phí này kiểm tra hiệu suất đĩa bằng cách gửi yêu cầu đến hệ thống tệp. Bảng và biểu đồ cho thấy sự so sánh giữa ba nhà cung cấp dịch vụ đám mây được thu được từ bài kiểm tra Dbench. Từ bảng, chúng ta có thể thấy rằng giá trị trung bình của Google Cloud ít hơn so với Azure và AWS. Ngoài ra, sự khác biệt giữa giá trị trung bình của Azure và AWS là không đáng kể. Vì vậy, không quan trọng nếu người dùng chọn bất kỳ trong hai lựa chọn này khi xem xét hiệu suất đĩa.
	Tốc độ RAM là một bài kiểm tra đánh giá hiệu quả của RAM. Copy, Scale, Add, Triad và Average là năm cấu hình kiểm tra cho bài kiểm tra này. Tất cả năm cấu hình kiểm tra này được thử nghiệm cho số nguyên cũng như số thực.
	Như đã thấy qua biểu đồ và bảng cho bài kiểm tra Integerbenchmark tốc độ RAM, AWS và Azure đang cạnh tranh cạnh nhau, nhưng với AWS có trung bình tốt hơn. Tuy nhiên, GCP vẫn đứng sau trong bài kiểm tra này.Đối với bài kiểm tra RAM tốc độ dấu chấm động, AWS vẫn giữ vị trí đầu tiên.
	Vì vậy, người dùng đang tìm kiếm hiệu suất và tốc độ RAM tốt hơn có thể chọn sử dụng dịch vụ được cung cấp bởi AWS.

VII. Kết luận:
	Mặc dù Google Cloud đang dẫn đầu trong cuộc đua của điện toán đám mây so với nhiều nhà cung cấp dịch vụ đám mây khác, nhưng vẫn còn một quãng đường dài phải đi trước khi nắm bắt được toàn bộ thị trường giống như đã làm với công cụ tìm kiếm của mình. Sự khác biệt giữa giá trị trung bình của Azure và GCP không nhiều trong bài kiểm tra Apache, GCP không thể cạnh tranh mạnh trong bài kiểm tra Dbench và tốc độ RAM.

Azure có giao diện người dùng đơn giản và trực quan để điều khiển các tài nguyên ảo, nhưng không có tùy chọn để điều chỉnh VM. AWS, từ phía khác, cung cấp các tiện ích bổ sung cho việc điều chỉnh hệ thống và nhiều lựa chọn hơn cho việc quản lý VM Linux.

Khi đến hiệu suất của các dịch vụ đám mây này, các bài kiểm tra thực hiện và kết quả của chúng từ việc kiểm tra các VM mẫu nhỏ rất giống nhau cho cả AWS và Azure, nhưng AWS vẫn vượt trội ở cả Dbench và RAM speed benchmarks. Tuy nhiên, việc kiểm tra hiệu suất của các VM mẫu phức tạp hơn nên được tiến hành tuân thủ với biểu đồ biểu diễn phần cứng ảo được cung cấp cho người dùng đám mây. Cơ sở hạ tầng AWS phù hợp hơn cho các VM Linux vì nó cung cấp nhiều khả năng tùy chỉnh cho người dùng cuối, như được minh chứng bởi kết quả kiểm tra tốc độ bộ nhớ và RAM.






