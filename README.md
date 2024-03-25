# XayDungWebsiteKinhDoanhDoGiaDung_PHPLaravel-HTML-CSS-Bootstrap
# XÂY DỰNG WEBSITE KINH DOANH ĐỒ GIA DỤNG

------------------------------------------------------------------------------------------

## MỤC LỤC

MỤC TIÊU ĐỀ TÀI	

Chương 1.	Tổng quan về Website	

	1.1	Giới thiệu Website kinh doanh bán hàng đồ gia dụng	
		1.1.1.	Khái niệm	
		1.1.2.	Phân loại	
		1.1.3.	Ưu điểm	
		1.1.4.	Nhược điểm	
	1.2	Quy trình xây dựng Website	
		1.2.1.	Các bước xây dựng Website bán hàng đồ gia dụng	
	1.3	Các ngôn ngữ phát triển Website	
		1.3.1.	PHP	
		1.3.2.	JAVA	
		1.3.3.	C#	
Chương 2.	Tổng quan về ASP.NET	

	2.1	Giới thiệu về ASP.NET	
		2.1.1.	Khái niệm	
		2.1.2.	Lịch sử phát triển	
		2.1.3.	Ưu điểm	
		2.1.4.	Nhược điểm	
	2.2	Tổng quan mô hình MVC	
		2.2.1.	Khái niệm	
		2.2.2.	Mô tả	
		2.2.3.	Các phiên bản của MVC
		2.2.4.	Cơ chế hoạt động của MVC	
		2.2.5.	Ưu điểm	
		2.2.6.	Nhược điểm	
	2.3	Các Framework dùng trong Website	
		2.3.1.	Entity Framework	
Chương 3.	Phân tích – Thiết kế cơ sở dữ liệu

	3.1	Quy trình xây dựng	
		3.1.1.	Các thông tin đầu ra đầu vào của hệ thống	
		3.1.2.	Tác nhân	
		3.1.3.	Danh sách các Actor của hệ thống	
		3.1.4.	Danh sách các Use – Case chính của hệ thống	
		3.1.5.	Biểu đồ Use – Case mức tổng quát	
		3.1.6.	Use – Case quản lý hệ thống	
		3.1.7.	Use – Case người dùng	
		3.1.8.	Use – Case giỏ hàng Online	
		3.1.9.	Use – Case đặt hàng Online	
		3.1.10.	Use – Case tìm kiếm sản phẩm	
		3.1.11.	Use – Case thêm một sản phẩm vào giỏ hàng	
		3.1.12.	Use – Case quản lý thông tin sản phẩm	
		3.1.13.	Use – Case quản lý thông tin bài viết	
		3.1.14.	Use – Case cập nhật Banner	
	3.2	Danh sách các thực thể	
	3.3	Xây dựng các bảng cơ sở dữ liệu	
		3.3.1.	Bảng Category
		3.3.2.	Bảng Product	
		3.3.3.	Bảng Topic	
		3.3.4.	Bảng Post	
		3.3.5.	Bảng Slider	
		3.3.6.	Bảng Order	
		3.3.7.	Bảng OrderDetail	
		3.3.8.	Bảng User	
		3.3.9.	Bảng Menu	
		3.3.10.	Bảng Contact	
		3.3.11.	Bảng Link	
Chương 4.	Trình bày sản phẩm	

	4.1	Giao diện quản lý (ADMIN)	
	4.2	Giao diện trang người dùng (USER)	

-----------------------------------------------------------------------------------------------



MỤC TIÊU ĐỀ TÀI

Giới thiệu, quảng bá về cửa hàng bán đồ gia dụng. Cách liên hệ, địa chỉ, những điều khoản khi khách hàng có nhu cầu mua hàng tại cửa hàng.

Giúp khách hàng có thể tìm các sản phẩm gia dụng mà mình yêu thích, hay phù hợp với mục đích của mình, …

Tiếp nhận phản ánh của khách hàng về sản phẩm cũng như phương pháp làm việc của cửa hàng thông qua website.

Mục tiêu chính là có thể thành thạo lập trình:
	
   -	Lập trình hướng đối tượng.
	
   -	Lập trình Web
	
   -	Lập trình cơ sở dữ liệu (SQL server)
	
   -	Hoàn thành được một website bán đồ gia dụng cơ bản
	
   -	Nâng cao khả năng làm và kỹ năng mềm

Chương 1.	Tổng quan về Website

1.1	Giới thiệu Website kinh doanh bán hàng đồ gia dụng

Mô hình kinh doanh bán hàng trực tuyến trên mạng đang trở nên rất phát triển. Sự tiện lợi và hiệu quả trong việc tìm kiếm một sản phẩm, một mặt hàng sẽ là điểm mạnh nếu ta khai thác được chúng.

Việc xây dựng trang web bán hàng trực tuyến là điều tất yếu cho những cửa hàng, các tổ chức kinh doanh muốn bán các mặt hàng qua hình thức trực tiếp (hay còn gọi là online), tới cộng đồng cư dân mạng.

Để xây dựng được một trang web trên các công cụ tìm kiếm thì SEO là một điều rất quan trọng để tồn tại và phát triển một trang web..

Trong giới hạn của đề tài em sẽ không tìm hiểu về SEO mà sẽ chuyên sâu vào việc làm sao để thiết kế được một trang web phải đẹp, đầy đủ chức năng và thực hiện tốt những chức năng cơ bản nhất.

Đó cũng là lý do chọn đề tài: Xây dựng trang web bán hàng đồ gia dụng.
 
1.1.1.	Khái niệm

•	Web bán đồ gia dùng giống như một "siêu thị trực tuyến" - Nơi trưng bày & giới thiệu các sản phẩm gia dụng. Điều này đồng nghĩa với việc, phạm vi & số lượng sản phẩm là không hề nhỏ và nó cần phải được phân loại cẩn thận theo nhiều tiêu chí khác nhau để đảm bảo người dùng có thể tìm thấy sản phẩm mong muốn một cách dễ dàng.

•	Website bán đồ gia dụng là một trang được thiết kế ra nhằm mục đích cho các khách hàng có nhu cầu mua sắm các vật dụng gia đình đặc biệt là các người cha các người mẹ muốn mua các vật dụng để đầy đủ tiện nghi hơn     Vd: Nồi cơm, bình đun sôi,…...

•	Chính vì thế mà Website bán đồ gia dụng ra đời.

1.1.2.	Phân loại

•	Theo dữ liệu

o	Web tĩnh: Được hiểu theo nghĩ là dữ liệu không thay đổi thường xuyên. Với dạng web này người để thay đổi nội dung trên trang web người sở hữu phải truy cập trực tiếp vào các mã lệnh để thay đổi thông tin. Không có cơ sở dữ liệu bên dưới hệ thống, không có công cụ để điều khiển nội dung gián tiếp. Dạng file của trang web tĩnh thường là html.

o	Web động: Với web động khi xây dựng sẽ bao gồm 2 phần. Một phần hiển thị trên trình duyệt mà khi truy cập internet ta thường thấy và một phần ngầm bên dưới dùng để điều khiển nội dung của trang web, phần nội dung ngầm này thường thì chỉ những người quản trị

-	Theo đối tượng sở hữu

o	Web cá nhân: Các đối tượng như diễn viên, ca sĩ, ngừơi nổi tiếng, người thiết kế đồ hoạ, hoặc bất kỳ cá nhân nào thích giới thiệu bản thân mình đều có thể tạo ra một website cho cá nhân mình.

o	Web thương mại điện tử: là các dạng web cho phép bán hàng trực tuyến, việc thanh toán có nhiều hình thức như: tiền mặt, chuyển khoản, thanh toán bằng thẻ, hoặc thông qua cổng thanh toán của các dịch vụ hỗ trợ. Dạng web này thường tập hợp rất nhiều loại hàng hoá và chủ sở hữu trực tiếp quản lý việc bán buôn đây giống như dạng siêu thị bán hàng trong quầy tự chọn. Ngoài ra cũng có thể là loại web mà chủ sở hữu chỉ xây dựng hệ thống web và tạo những gian hàng riêng để cho thuê

1.1.3.	Ưu điểm

-	Quản lý toàn bộ sản phẩm trên web thương mại điện tử một cách đơn giản và nhanh chóng.

-	Thực hiện hàng loạt cập nhật để không ngừng cải tiến quản lý website.

-	Cung cấp đầy đủ những thông tin chi tiết về sản phẩm giúp khách hàng dễ dàng lựa chọn được sản phẩm phù hợp.

-	Cung cấp phương thức thanh toán đa dạng, linh hoạt một cách gián tiếp hoặc trực tiếp bằng chức năng thanh toán trực tuyến với những đối tác uy tín.

-	Hoạt động ổn định, tính bảo mật cao. Dễ dàng nâng cấp theo yêu cầu.

1.1.4.	Nhược điểm

-	Sản phẩm dễ bị so sánh với các sản phẩm cùng loại ở trang khác dẫn đến việc cạnh tranh giá cả.

-	Việc xây dựng thương hiệu cũng khá khó khăn.

-	Có mức độ rủi ro cao về chất lượng sản phẩm so với các mô hình kinh doanh khác.

1.2	 Quy trình xây dựng Website

1.2.1.	Các bước xây dựng Website bán hàng đồ gia dụng

Bước 1.	Xác lập dạng website

-	Xây dựng website theo đúng với mục đích: 

-	Website bán hàng trực tuyến

Bước 2.	Đăng ký tên miền

-	Nghiên cứu, lựa chọn tên miền phụ hợp với nhu cầu của website bán hàng đồ gia dụng

Bước 3.	Xác lập mục tiêu

-	Thống kê những chi tiết nhỏ để phát triển website theo đúng với yêu cầu:

-	Xây dựng website kinh doanh đồ gia dụng

Bước 4.	Ghi chú những yêu cầu về website

-	Cần xây dựng bao nhiêu website trực tuyến? – 1

-	Lưu lượng lưu trữ cần thiết cho các website là bao nhiêu? – Trước mắt : 4G

-	Các tiện ích cần thiết như: đánh giá của khách hàng, bản đồ chỉ dẫn, chat trực tuyến,…

-	Website có cần các video hay file âm thanh hay không? – Cần

-	Website có cần liên kết với các mạng xã hội: facebook, linkedln, G+,… hay không? – Cần

-	Giỏ hàng có nên có trong website bao gồm những gì? 

-	Tên món hàng

-	Số lượng

-	Số tiền

-	Chức năng: thêm ,sửa,xóa đơn hàng

-	Mã khuyến mãi cho đơn hàng

-	Thiết kế web cho mobile hay cho cả các thiết bị di động khác?

-	Trên Desktop

-	Mobile (dành cho cả hệ điều hành Android và IOS)

-	Và cả trên Tablet

-	Quản trị cần có những công cụ như thế nào để hiệu quả hơn?

-	Thêm, sửa, xóa các tiêu đề, các danh mục, các bài viết và các chính sách

-	Cập nhật, thống kê các đơn hàng, các thành viên đăng ký

-	Update các Plugin mới cho Website

Bước 5.	Quyết định người thực hiện

Bước 6.	Nghiên cứu và lựa chọn nhà thiết kế

Vì là website bán hàng Online nên cần phải đạt chuẩn SEO cho web

Bước 7.	Mua hosting

Sau khi đã lựa chọn lưu trữ website trên hosting, hay chuyển hướng tên miền về nơi lưu trữ website

Bước 8.	Trỏ tên miền

Sau khi đã lựa chọn lưu trữ website trên hosting, chuyển hướng tên miền về nơi lưu trữ website.

Bước 9.	Xây dựng nội dung cơ bản

-	Thông tin liên hệ

-	Địa chỉ

-	Email

-	Số điện thoại

-	Lĩnh vực kinh doanh

Bước 10.	Quảng bá Website

Chạy quảng cáo về các chiến dịch khi mua tại website kinh doanh đồ gia dụng

Bước 11.	Phát triển Website

Liên kết với các doanh nghiệp bán hàng gia dụng khác để đưa Website tiến xa hơn trong thị trường bán hàng mặt hàng đồ gia dụng

1.3	Các ngôn ngữ phát triển Website

1.3.1.	PHP

1.3.3.1	Tổng quan

PHP là ngôn ngữ lập trình mã nguồn mở phía server được thiết kế để xây dựng ứng dụng web động. Code PHP thực thi trên server để sinh ra code HTML và trả về cho trình duyệt web render theo yêu cầu của nhà phát triển. PHP cho phép xây dựng ứng dụng web tương tác với mọi cơ sở dữ liệu như: MySQL, Oracle, ... 

1.3.3.2	Lịch sử phát triển

PHP được phát triển từ một sản phẩm có tên là PHP/FI. PHP/FI do Rasmus Lerdorf tạo ra năm 1995 được viết bằng C và được sửa lại năm 1997.

PHP 3.0: Được Andi Gutmans và Zeev Suraski tạo ra năm 1997 sau khi viết lại hoàn toàn bộ mã nguồn trước đó. Lý do chính mà họ đã tạo ra phiên bản này là do họ nhận thấy PHP/FI 2.0 không mở rộng được trong việc phát triển các ứng dụng thương mại điện tử. PHP 3.0 như là phiên bản thế hệ kế tiếp của PHP/FI 2.0, và chấm dứt phát triển PHP/FI 2.0. PHP 3.0 cung cấp cho người dùng cuối một cơ sở hạ tầng dùng cho nhiều cơ sở dữ liệu, giao thức và API khác nhau. Cho phép người dùng có thể mở rộng theo module. Chính điều này làm cho PHP3 thành công so với PHP2. Lúc này chính thức đặt tên ngắn gọn là PHP (Hypertext Preprocessor).

PHP4: Được công bố năm 2000 tốc độ xử lý được cải thiện, PHP 4.0 đem đến các tính năng chủ yếu khác gồm có hỗ trợ nhiều máy chủ web, hỗ trợ session HTTP, tạo output buffering, nhiều cách xử lý dữ liệu input bảo mật hơn và cung cấp một vài các cấu trúc ngôn ngữ mới. Với PHP 4, số nhà phát triển dùng PHP lên đến hàng trăm nghìn và hàng triệu trang web dùng PHP, chiếm 20% số tên miền trên mạng Internet. Team phát triển PHP lên tới con số hàng nghìn người và nhiều người khác tham gia vào các dự án có liên quan đến PHP như PEAR, PECL và tài liệu cho PHP.

PHP5: Bản chính thức ra mắt ngày 13 tháng 7 năm 2004 sau một chuỗi các bản kiểm thử bao gồm Beta 4, RC 1, RC2, RC3. Mặc dù đây là phiên bản sản xuất đầu tiên nhưng PHP 5.0 vẫn còn một số lỗi, đáng kể là lỗi xác thực HTTP.

Một số tính chất của file php

-	Các file PHP trả về cho trình duyệt là một trang thuần HTML.

-	Các file PHP có thể chứa văn bản (Text), các thẻ HTML (HTML tags) và code kịch bản (Script).

-	Các file PHP có phần mở rộng là: .php, .php3, .phpml.

-	Từ phiên bản 4.0 trở về sau mới hỗ trợ session.

1.3.3.3	Làm thế nào chạy được code php

Để chạy được code PHP cần phải có môi trường server vì PHP là ngôn ngữ phía server (server-side). Tạo ra môi trường server thì có thể dùng XAMPP. XAMPP là gói cài đặt tích hợp sẵn Apache, MySQL và PHP. XAMPP cũng bao gồm phpMyAdmin - 1 công cụ dạng web giúp cho nhà phát triển quản trị cơ sở dữ liệu và rất nhiều thư viện hỗ trợ khác như: OpenSSL, pdf class, ...

1.3.2.	JAVA

1.3.3.1	Tổng quan

Java (phiên âm Tiếng Việt: "Gia-va") là một ngôn ngữ lập trình hướng đối tượng (OOP) và dựa trên các lớp (class)[9]. Khác với phần lớn ngôn ngữ lập trình thông thường, thay vì biên dịch mã nguồn thành mã máy hoặc thông dịch mã nguồn khi chạy, Java được thiết kế để biên dịch mã nguồn thành bytecode, bytecode sau đó sẽ được môi trường thực thi (runtime environment) chạy. Trước đây, Java chạy chậm hơn những ngôn ngữ dịch thẳng ra mã máy như C và C++, nhưng sau này nhờ công nghệ "biên dịch tại chỗ" - Just in time compilation, khoảng cách này đã được thu hẹp, và trong một số trường hợp đặc biệt Java có thể chạy nhanh hơn. 
Java chạy nhanh hơn những ngôn ngữ thông dịch như Python, Perl, PHP gấp nhiều lần. Java chạy tương đương so với C#, một ngôn ngữ khá tương đồng về mặt cú pháp và quá trình dịch/chạy

1.3.3.2	Lịch sử phát triển

Java được khởi đầu bởi James Gosling và bạn đồng nghiệp ở Sun Microsystems năm 1991. Ban đầu ngôn ngữ này được gọi là Oak (có nghĩa là cây sồi; do bên ngoài cơ quan của ông Gosling có trồng nhiều loại cây này), 
họ dự định ngôn ngữ đó thay cho C++, nhưng các tính năng giống Objective C. Không nên lẫn lộn Java với JavaScript, hai ngôn ngữ đó chỉ giống tên và loại cú pháp như C. Công ty Sun Microsystems đang giữ bản quyền và phát triển Java thường xuyên. Tháng 04/2011, công ty Sun Microsystems tiếp tục cho ra bản JDK 1.6.24.

1.3.3.3	Một số tính chất của Java

-	Đơn giản, hướng đối tượng và quen thuộc
  

-	Dễ sử dụng cho người dùng Java

-	Kiến trúc trung lập và di động

1.3.3.4	Các phiên bản của Java

•	JDK 1.0 (23 tháng 01, 1996)

•	JDK 1.1 (19 tháng 2 năm 1997)

o	JDK 1.1.5 (Pumpkin) 03 tháng 12 năm 1997

o	JDK 1.1.6 (Abigail) 24 tháng 4 năm 1998

o	JDK 1.1.7 (Brutus) 28 tháng 9 năm 1998

o	JDK 1.1.8 (Chelsea) 08 tháng 4 năm 1999

•	J2SE 1.2 (Playground) 08 tháng 12 năm 1998

o	J2SE 1.2.1 (không có) 30 tháng 3 năm 1999

o	J2SE 1.2.2 (Cricket) 08 tháng 7 năm 1999

•	J2SE 1.3 (Kestrel) 08 tháng 5 năm 2000

o	J2SE 1.3.1 (Ladybird) 17 tháng 5 năm 2001

•	J2SE 1.4.0 (Merlin) 06 tháng 02, 2002

o	J2SE 1.4.1 (Hopper) 16 tháng 9 năm 2002

o	J2SE 1.4.2 (Mantis) 26 tháng 6 năm 2003

•	J2SE 5 (1.5.0) (Tiger) 30 tháng 9 năm 2004

•	Java SE 6 (còn gọi là Mustang), được công bố 11 tháng 12 năm 2006

•	JDK 6.18, 2010

•	Java SE 7 (còn gọi là Dolphin), được bắt đầu từ tháng 8 năm 2006 và công bố ngày 28 tháng 7 năm 2011.

•	JDK 8, 18 tháng 3 năm 2014

•	JDK 9, 21 tháng 9 năm 2017

•	JDK 10, 20 tháng 3 năm 2018

1.3.3.	C#

1.3.3.1	Tổng quan

C# (hay C sharp) là một ngôn ngữ lập trình đơn giản, được phát triển bởi đội ngũ kỹ sư của Microsoft vào năm 2000, trong đó người dẫn đầu là Anders Hejlsberg và Scott Wiltamuth. C# là ngôn ngữ lập trình hiện đại, hướng đối tượng và nó được xây dựng trên nền tảng của hai ngôn ngữ mạnh nhất là C++ và Java. C# được thiết kế cho Common Language Infrastructure (CLI), mà gồm Executable Code và Runtime Environment, cho phép chúng ta sử dụng các ngôn ngữ high-level đa dạng trên các nền tảng và cấu trúc máy tính khác nhau. C# với sự hỗ trợ mạnh mẽ của .NET Framework giúp cho việc tạo một ứng dụng Windows Forms hay WPF (Windows Presentation Foundation), . . . trở nên rất dễ dàng.

1.3.3.2	Lịch sử phát triển

1.3.3.3	Đặc trưng

-	Là ngôn ngữ đơn giản

o	Như ta đã biết thì ngôn ngữ C# dựng trên nền tảng C++ và Java nên ngôn ngữ C# khá đơn giản. Nếu chúng ta thân thiện với C và C++ hoậc thậm chí là Java, chúng ta sẽ thấy C# khá giống về diện mạo, cú pháp, biểu thức, toán tử và những chức năng khác được lấy trực tiếp từ ngôn ngữ C và C++, nhưng nó đã được cải tiến để làm cho ngôn ngữ đơn giản hơn. Một vài trong các sự cải tiến là loại bỏ các dư thừa, hay là thêm vào những cú pháp thay đổi.

-	Là ngôn ngữ hiệu đại

o	Một vài khái niệm khá mới mẻ khá mơ hồ với các bạn vừa mới học lập trình, như xử lý ngoại lệ, những kiểu dữ liệu mở rộng, bảo mật mã nguồn..v..v... Đây là những đặc tính được cho là của một ngôn ngữ hiện đại cần có.

-	Là một ngôn ngữ lập trình thuần hướng đối tượng

o	Lập trình hướng đối tượng(tiếng Anh: Object-oriented programming, viết tắt: OOP) là một phương pháp lập trình có 4 tính chất. Đó là tính trừu tượng (abstraction), tính đóng gói (encapsulation), tính đa hình (polymorphism) và tính kế thừa (inheritance). C# hỗ trợ cho chúng ta tất cả những đặc tính trên.

-	Là một ngôn ngữ có ít từ khóa

o	là ngôn ngữ sử dụng giới hạn những từ khóa (gồm khoảng 80 từ khóa và mười mấy kiểu dữ liệu xây dựng sẵn)

Chương 2.	Tổng quan về ASP.NET

2.1	Giới thiệu về ASP.NET

2.1.1.	Khái niệm

ASP.NET là một nền tảng ứng dụng web (web application framework) được phát triển và cung cấp bởi Microsoft, cho phép những người lập trình tạo ra những trang web động, những ứng dụng web và những dịch vụ web. Lần đầu tiên được đưa ra thị trường vào tháng 2 năm 2002 cùng với phiên bản 1.0 của .NET framework, là công nghệ nối tiếp của Microsoft's Active Server Pages(ASP). ASP.NET được biên dịch dưới dạng Common Language Runtime (CLR), cho phép những người lập trình viết mã ASP.NET với bất kỳ ngôn ngữ nào được hỗ trợ bởi .NET language.

2.1.2.	Lịch sử phát triển

Sau khi phát hành phiên bản Internet Information Service 4.0 vào năm 1997, hãng Microsoft bắt đầu nghiên cứu một mô hình ứng dụng web để giải quyết những bất tiện của ASP, đặc biệt là việc tách riêng biệt phần thể hiện và phần nội dung cũng như cách viết mã rõ ràng hơn. Mark Anders, quản lý của nhóm IIS và Scott Guthrie, gia nhập Microsoft vào năm 1997 sau khi tốt nghiệp Đại học Duke, được giao nhiệm vụ định hình mô hình cần phát triển. Những thiết kế ban đầu được thực hiện trong vòng 2 tháng bởi Anders và Guthrie, Guthrie đã viết mã prototype đầu tiên trong khoảng thời gian nghỉ lễ Giáng sinh năm 1997.

2.1.3.	Ưu điểm

-	Code chạy bằng ngôn ngữ asp.net rất ổn định tiêu biểu là trang vnexpress.net trang web tin tức online số 1 việt nam hiện nay, thời đầu vnexpress được xây dựng bằng ASP sau đó khi ASP.net ra đời được cập nhật lên, bên cạnh đó dân trí cũng chạy bằng asp.net cũng rất ổn định.

-	Bảo mật tốt được thiết kế bằng ngôn ngữ lập trình hướng đối tượng và thừa hưởng các điểm mạnh của JS giúp bảo mật cao hơn.

-	Có khả năng tùy biến cao.

-	Có độ truy xuất dữ liệu nhanh nhờ sử dụng các đối tượng để truy xuất không những giúp bảo mật của ASP.net được đánh giá cao mà tốc độ xử lý, truy xuất dữ liệu của nó cũng được cải thiện một cách rõ rệt.

2.1.4.	Nhược điểm

-	Không hỗ trợ cho các thiết bị sử dụng hệ điều hành Linux.

-	Không hỗ trợ Visual studio trong quá trình viết code.

-	ASP.NET có phí sử dụng khá cao, không phù hợp sử dụng cho các doanh nghiệp nhỏ hay các cá nhân.

2.2	Tổng quan mô hình MVC

2.2.1.	Khái niệm

MVC (Model – View - Controller) là một design partern đã tồn tại rất lâu trong ngành công nghệ phần mềm. Một ứng dụng viết theo mô hình MVC sẽ bao gồm 3 thành phần tách biệt nhau đó là Model, View, Controller. 

Giống như trong cấu trúc Three – Tier, mô hình MVC giúp tách biệt 3 tầng trong mô hình lập trình web, vì vậy giúp tối ưu ứng dụng, dễ dàng thêm mới và chỉnh sửa code hoặc giao diện

2.2.2.	Mô tả

•	Model: ở phần trước mình đã nhắc lại cho các bạn về 3 tầng trong mô hình

•	Three – Tier thì trong đó gồm có 2 tầng Data Access Layer và tầng Business Logic Layer. Hai tầng này là hai tầng tương đương với tầng model trong mô hình MVC.

•	View: là tầng giao diện, hiển thị dữ liệu được truy xuất từ tầng model. Tầng này tương đương với tầng Presentation Layer trong cấu trúc Three – Tier.

•	Controller: đây là tầng giúp kết nối giữa tầng model và tầng view trong mô hình MVC, có nghĩa là nếu phía client yêu cầu hiển thị dữ liệu thì controller gọi giữ liệu từ model và trả về cho view vì view tương tác trực tiếp với client

2.2.3.	Các phiên bản của MVC

<img src="https://private-user-images.githubusercontent.com/134685355/315059775-578ab4fc-599f-4588-8a11-e3d7a11c3271.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY2NzksIm5iZiI6MTcxMTM5NjM3OSwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5Nzc1LTU3OGFiNGZjLTU5OWYtNDU4OC04YTExLWUzZDdhMTFjMzI3MS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTUyNTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mNTYyYmNjZjY0MDY3MzFhNDJhMzVhMjdiM2MxYTZkMzk4MTE4ZmYzMzBjNmFiZDUzNjhiNWMxN2JmNTk5ZGY5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.GzjZmCZ9ANcS9jDAqLzJ8GXoR4TQLdbcHhj959-UJ2A">
 
Hình 1: Các phiên bản của MVC

2.2.4.	Cơ chế hoạt động của MVC

-	User gửi 1 yêu cầu tới server bằng cách truyền vào 1 URL trong browser 

-	Yêu cầu đó được gửi tới controller đầu tiên, controller sẽ xử lý yêu cầu, nếu yêu cầu cần truy xuất dữ liệu thì controller sẽ chuyển qua tầng model 

-	Tại tầng model, dữ liệu được truy xuất từ database và sau đó truyền qua view thông qua controller 

-	Controller sẽ giúp dữ liệu được chuyển từ model qua view 

-	View là tầng cuối cùng giao tiếp với User, mọi dữ liệu sẽ được hiển thị cho User thông qua tầng View

2.2.5.	Ưu điểm

-	Thể hiện tính chuyên nghiệp trong lập trình, phân tích thiết kế

-	Do được chia thành các thành phần độc lập nên giúp chúng phát triển ứng dụng nhanh, đơn giản, dễ nâng cấp, bảo trì, …

2.2.6.	Nhược điểm

-	Đối với dự án nhỏ việc áp dụng mô hình MVC gây cồng kềnh

-	Tốn thời gian trong quá trình phát triển. 

-	Tốn thời gian trung chuyển dữ liệu của các thành phần.

2.3	Các Framework dùng trong Website

2.3.1.	Entity Framework

1.3.3.1	Khái niệm

Entity Framework là một khung ORM mã nguồn mở cho các ứng dụng .NET được Microsoft hỗ trợ. Nó cho phép các nhà phát triển làm việc với dữ liệu bằng cách sử dụng các đối tượng của các lớp cụ thể của miền mà không cần tập trung vào các bảng và cột cơ sở dữ liệu cơ bản nơi dữ liệu này được lưu trữ. Với Entity Framework, các nhà phát triển có thể làm việc ở mức độ trừu tượng cao hơn khi họ xử lý dữ liệu và có thể tạo và duy trì các ứng dụng hướng dữ liệu với ít mã hơn so với các ứng dụng truyền thống.

1.3.3.2	Các tính năng

-	Đa nền tảng: EF Core là một khung đa nền tảng có thể chạy trên Windows, Linux và Mac

-	Mô hình hóa: EF (Entity Framework) tạo EDM (Mô hình dữ liệu thực thể) dựa trên các thực thể POCO (Plain Old CLR Object) với các thuộc tính get / set của các loại dữ liệu khác nhau. Nó sử dụng mô hình này khi truy vấn hoặc lưu dữ liệu thực thể vào cơ sở dữ liệu cơ bản

-	Truy vấn: EF cho phép chúng tôi sử dụng các truy vấn LINQ (C # / VB.NET) để truy xuất dữ liệu từ cơ sở dữ liệu cơ bản. Nhà cung cấp cơ sở dữ liệu sẽ dịch các truy vấn LINQ này sang ngôn ngữ truy vấn dành riêng cho cơ sở dữ liệu (ví dụ: SQL cho cơ sở dữ liệu quan hệ). EF cũng cho phép chúng tôi thực hiện các truy vấn SQL thô trực tiếp đến cơ sở dữ liệu.

-	Theo dõi thay đổi: EF theo dõi các thay đổi xảy ra đối với các phiên bản của các thực thể của bạn (Giá trị thuộc tính) cần được gửi đến cơ sở dữ liệu.

-	Lưu: EF thực thi các lệnh INSERT, UPDATE và DELETE vào cơ sở dữ liệu dựa trên những thay đổi xảy ra với các thực thể của bạn khi bạn gọi phương thức SaveChanges (). EF cũng cung cấp phương thức SaveChangesAsync () không đồng bộ. Đồng thời: EF sử dụng Đồng thời lạc quan theo mặc định để bảo vệ các thay đổi ghi đè do người dùng khác thực hiện do dữ liệu được lấy từ cơ sở dữ liệu.

-	Giao dịch: EF thực hiện quản lý giao dịch tự động trong khi truy vấn hoặc lưu dữ liệu. Nó cũng cung cấp các tùy chọn để tùy chỉnh quản lý giao dịch.

-	Bộ nhớ đệm: EF bao gồm cấp bộ nhớ đệm đầu tiên ra khỏi hộp. Vì vậy, truy vấn lặp đi lặp lại sẽ trả về dữ liệu từ bộ đệm thay vì nhấn cơ sở dữ liệu.

-	Các quy ước tích hợp: EF tuân theo các quy ước về mẫu lập trình cấu hình và bao gồm một bộ quy tắc mặc định tự động định cấu hình mô hình EF.

-	Cấu hình: EF cho phép chúng tôi định cấu hình mô hình EF bằng cách sử dụng các thuộc tính chú thích dữ liệu hoặc API Fluent để ghi đè các quy ước mặc định.

-	Di chuyển: EF cung cấp một tập hợp các lệnh di chuyển có thể được thực thi trên Bảng điều khiển Trình quản lý gói NuGet hoặc Giao diện dòng lệnh để tạo hoặc quản lý Lược đồ cơ sở dữ liệu cơ bản.

Chương 3.	Phân tích – Thiết kế cơ sở dữ liệu

3.1	Quy trình xây dựng

3.1.1.	Các thông tin đầu ra đầu vào của hệ thống

Thông tin đầu vào:

•	Thông tin khách hàng

•	Thông tin sản phẩm

•	Thông tin về công ty và các bài viết liên quan

•	Thông tin quảng cáo

•	Các phản hồi

•	Đơn đặt hàng

Thông tin đầu ra:

•	Chi tiết về sản phẩm

•	Hóa đơn

•	Các phản hồi

3.1.2.	Tác nhân

•	Khách hàng:

o	User

o	Guest (Khách viếng thăm)

o	Admin

<img src="https://private-user-images.githubusercontent.com/134685355/315059792-6aa9fec8-4eda-4cef-91c4-75c94c02bf39.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY2NzksIm5iZiI6MTcxMTM5NjM3OSwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5NzkyLTZhYTlmZWM4LTRlZGEtNGNlZi05MWM0LTc1Yzk0YzAyYmYzOS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTUyNTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03M2RiNGE4NDJjMjM1MjBiMzU2MTM1NjdhOTcxMDA5MjM2ZTMxMTNiZTU0YzAwZTZmM2FiY2IzZDJhYjg2MDUzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.deEkF5QA42u94SG-KrhbOSwm4RjAxa7jX9wVU-0dFo4">

3.1.3.	Danh sách các Actor của hệ thống

<img src="https://private-user-images.githubusercontent.com/134685355/315059783-26b0bc81-6c7d-45bd-b32d-84a0779e0db8.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY2NzksIm5iZiI6MTcxMTM5NjM3OSwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5NzgzLTI2YjBiYzgxLTZjN2QtNDViZC1iMzJkLTg0YTA3NzllMGRiOC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTUyNTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZDYyOWM3MzAxYjAwMzY1YzI3ZGMxMDlmNDc4M2QzNWFmMjU0YzczOTVhYWIwYzFhMTcxYmFhYjQ5OWE1NzRhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.HbmF2jAem49vtzrjz49GqAle2-Ak0sBFnkLTfIZJSjo">

Hình 2: Danh sách các Actor của hệ thống

3.1.4.	Danh sách các Use – Case chính của hệ thống

<img src="https://private-user-images.githubusercontent.com/134685355/315059788-9b79b4e5-1203-4945-b946-c5df8fbcbd90.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY2NzksIm5iZiI6MTcxMTM5NjM3OSwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5Nzg4LTliNzliNGU1LTEyMDMtNDk0NS1iOTQ2LWM1ZGY4ZmJjYmQ5MC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTUyNTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04NDZhMDNhMzE0ZDE4MWMwMzkxMmRkMGQ5YjhiNjQ4ZWJhYjU5NDYyNjUyNmU3NzNkYzQ0ZjZmYzU3ZDk0NGYxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.VcD-0FS5Bcj2iZRce9538ctr4NXryZq-BOknc2m73Zg">

Hình 3: Danh sách các Use – Case chính của hệ thống

3.1.5.	Biểu đồ Use – Case mức tổng quát

<img src="https://private-user-images.githubusercontent.com/134685355/315059798-fa7e9c04-17cc-49a1-9bb3-340cb842b6b4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5Nzk4LWZhN2U5YzA0LTE3Y2MtNDlhMS05YmIzLTM0MGNiODQyYjZiNC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01N2U3NWEwZmJlOTM4NTMzNGY1OGJiMDA5ZjJmNDExODRmMzAwNzgxZDFlYzU2OWFhYzI4NzM1MWQ4OGFjMTZlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.tTGTv53oreUx5VCrtyQy9eNsYjPxDvXl3U4neNfx6BE">

Hình 4: Biểu đồ Use – Case mức tổng quát

3.1.6.	Use – Case quản lý hệ thống

<img src="https://private-user-images.githubusercontent.com/134685355/315059801-bef6249d-e69f-4747-859e-3a5ee06f8258.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODAxLWJlZjYyNDlkLWU2OWYtNDc0Ny04NTllLTNhNWVlMDZmODI1OC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yZDdhYTM1MjQ0Y2FiOTcxNmQwOTA0MTU1MTI2YjQ4NWVkN2FkMTYwNTNiYWQyYTQ4YjkyM2RmZDc0Y2QzODNhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.MwEJ98OX6FF6PT_cAF-Lb6NTvzECl3kC1OLN8YKz6Io">

Hình 5 : Biểu đồ Use – Case quản lý hệ thống

3.1.7.	Use – Case người dùng

<img src="https://private-user-images.githubusercontent.com/134685355/315059808-f7ec4fea-cf9c-4d6f-a9ea-29a964db7fbd.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODA4LWY3ZWM0ZmVhLWNmOWMtNGQ2Zi1hOWVhLTI5YTk2NGRiN2ZiZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jMGRiNTkzNTFjNDA5N2RiZGIwYmRlNDkzZGQ4ZTgyNGQ0ZjdhODllMDRjNDYyNzI1NTI3ZDk1MmYxODYwYmNkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.DiEl6K5xFnCI74HSswJTfDjjV6RprCWi8HwvI8xrwOg">

Hình 6 : Biểu đồ Use – Case người dùng

Mô tả tóm tắt:

-	Tên Case sử dụng:Người dùng

-	Mục đích: Người dùng muốn trở thành thành viên của hệ thống thì phải đăng ký ài khoản. Tài khoản của người dùng là miễn phí họ không phải đóng bất cứ khoản chi phí nào khi sử dụng các dich vụ.

-	Tác nhân: Người dùng

-	Tóm lược: Người dùng khi muốn muốn làm thành viên của trang web cần phải đăng kí làm thành viên của hệ thống. Các bước đăng kí đơn giản và dễ dàng, mọi thông tin đăng kí phải chính xác.

Mô tả kịch bản:

 Thông tin đầu vào: Các thông tin đăng kí của người dùng.

-	Tài khoản

-	Mật khẩu

-	Nhập lại mật khẩu

-	Email

-	Tra cứu thông tin

-	Xem sản phẩm

3.1.8.	Use – Case giỏ hàng Online

Chức năng

•	Mục đích: 

Giúp người dùng thêm sản phẩm vào giỏ hàng và có thể tiến hành đặt hàng

•	Tác nhân liên quan:

Tác nhân ở đây là người dùng khách hàng của hệ thống

<img src="https://private-user-images.githubusercontent.com/134685355/315059812-2cd57860-8ee9-4f2b-bd84-8ff2f8a318fe.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODEyLTJjZDU3ODYwLThlZTktNGYyYi1iZDg0LThmZjJmOGEzMThmZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hMGFhMGZiNmM0ODQ3MmNhM2JiNDhjMWY2MDg1NzI5YmNhMmM4MmQ4ZDg3ZTViOTY1Yzg0MGI0NTZlMzZjYThiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.19MqUFiO01eWX2xUw83CbQXZJwzilcWrjWZAfcPRV5Y">

Hình  7: Biểu đồ Use – Case giỏ hàng

3.1.9.	Use – Case đặt hàng Online

-	Khi khách hàng mua hàng thì khách hàng tiến hành chọn hàng, sau đó đặt hàng, khách hàng có thể tiếp tục mua hàng hay lựa chọn huỷ bỏ và cập nhật giỏ hàng.

-	Hệ thống sẽ lưu những thông tin về quá trình mua hàng của khách hàng vào giỏ hàng. Sau khi khách hàng hoàn tất đơn hàng thì hệ thống sẽ in hoá đơn.

<img src="https://private-user-images.githubusercontent.com/134685355/315059814-dd0898ae-5212-471d-90e1-d53ab2099978.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODE0LWRkMDg5OGFlLTUyMTItNDcxZC05MGUxLWQ1M2FiMjA5OTk3OC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01MGQ0MGFkODgzYTAzNzU5YTdjMTZlMWNjNDFmNmI0MjhiMDY5Y2ZlNmViNGExNDY3YWNjNWNhY2MzNDVmNGYxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.GSCSNn40t1u1K5wawRwfg_LKI9QFzc-V6H3V56cyht8">

Hình 8: Biểu đồ Use – Case cho chức năng đặt hàng Online

3.1.10.	Use – Case tìm kiếm sản phẩm

Tác nhân: khách hàng

•	Chức năng: Cho phép khách hàng tìm kiếm sản phẩm theo nhiều tiêu chí khác nhau: theo hãng sản xuất, theo khoảng giá, theo kiểu dáng.

•	Mô tả: Khách hàng thấy được sản phẩm theo yêu cầu.

<img src="https://private-user-images.githubusercontent.com/134685355/315059817-49e94aab-31a6-43d3-ba9f-9bb0e30031fd.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODE3LTQ5ZTk0YWFiLTMxYTYtNDNkMy1iYTlmLTliYjBlMzAwMzFmZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jZTcxNzhhZmJiNWE2ZDdmZmFiNjY0Nzc1ZDlmNjAwMjZlZTVlYjI5NWNiZGQ3YmE0YjQwZWVmM2Y2ZWY0ODk4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.zM7XE4ndsXezvzNkxfkF-7h7ZIl-EFhw6pdPIGPtToo">

Hình 9: Biểu đồ Use - Case tìm kiếm sản phẩm

3.1.11.	Use – Case thêm một sản phẩm vào giỏ hàng

Tác nhân: quản trị hệ thống

•	Chức năng: Cho phép người quản trị thêm sách vào cửa hàng, làm cho cửa hàng thêm đa dạng sản phẩm.

•	Mô tả: Khi sản phẩm được nhập vào cửa hàng người quản lý cần điền đầy đủ thông tin vào phiếu nhập để người quản trị dễ dàng quản lý sản phẩm mà khách hàng đã chọn mua.

3.1.12.	Use – Case quản lý thông tin sản phẩm

<img src="https://private-user-images.githubusercontent.com/134685355/315059823-f4bcfc2e-77e9-40a3-b2e8-b401895af28b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODIzLWY0YmNmYzJlLTc3ZTktNDBhMy1iMmU4LWI0MDE4OTVhZjI4Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NzZkNGM5NWZhN2E1Mzk1NDJiZjc3ODZlMWIxMTcwNDcxNjRhM2UzNzRiYTVhYTE5NjJmNTQ1YzAyOGVmZjRmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Fs8v8tGs2XeQdJFw1ePPI4GGaYI9VR1suzsuv8xt0TM">
 
Hình 10: Biểu đồ Use – Case quản lý thông tin sản phẩm

3.1.13.	Use – Case quản lý thông tin bài viết

<img src="https://private-user-images.githubusercontent.com/134685355/315059826-bc398add-a9c4-4000-b8f4-0aa6c2de2a1c.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODI2LWJjMzk4YWRkLWE5YzQtNDAwMC1iOGY0LTBhYTZjMmRlMmExYy5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yMGYwZTgyMGJjZmZiYTkzNTE0NmE3Njc3YzdkZDhlZmFlM2YzMTc0MjMwMjA2NjBmMTNmMzYyZGJhN2NhNTM2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.hD7mFaKYdu5GxVRTp-KL_XNad_0CMQDvXYycUpf28Uk">
 
Hình 11: Biểu đồ Use – Case quản lý thông tin bài viết

3.1.14.	Use – Case cập nhật Banner

<img src="https://private-user-images.githubusercontent.com/134685355/315059836-7d4ee3d8-ffa3-4ac2-b138-4dc85570d6a7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODM2LTdkNGVlM2Q4LWZmYTMtNGFjMi1iMTM4LTRkYzg1NTcwZDZhNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03N2I1NGJmYzhlZTc1NzY5ZmM2Y2UxY2RhOWUwZWQzZTRlMzI1NDQ2NmJiZTRmOTI2ZDZlMTI5OTEzNmExMGQxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.CRpdolzqy2Panbq5dF3O7hDRz_uJtEC37OVrwuFV6T8">
 
Hình 12: Biểu đồ Use – Case cập nhật Banner

3.2	Danh sách các thực thể

<img src="https://private-user-images.githubusercontent.com/134685355/315059832-331185c9-162f-4b28-b28a-e8715ab6282a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODMyLTMzMTE4NWM5LTE2MmYtNGIyOC1iMjhhLWU4NzE1YWI2MjgyYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jODM2MWVjYjg0YTdmYTk5OTBmNmYzMmZlOGU5OTRiZTRiZTZlZmRkNmYxZDk1ZGQzNzlhMjA2OWRjODQzNjI5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.eT4Af-WLrSiJez1Qj5RDu9lX_kbCRnivfXYRqcNzNtg">

3.3	Xây dựng các bảng cơ sở dữ liệu

3.3.1.	Bảng Category

<img src="https://private-user-images.githubusercontent.com/134685355/315059837-da29987d-3812-4d94-803a-30c4f2b24116.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODM3LWRhMjk5ODdkLTM4MTItNGQ5NC04MDNhLTMwYzRmMmIyNDExNi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yNWIwMmQxZGQ3YzI3NmJlOWI1NmVkOGFlZjZjN2I4ZWJlOGE0MTg0NjQwZWVlN2ViMzMwYjNiMWYzNTcxYWM4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.gxEnjg9h2oaUKSO-WNF2eDdNPAo8N6LavpPj3zoQ4YM">

Hình 13: Bảng Category
 
3.3.2.	Bảng Product

 <img src="https://private-user-images.githubusercontent.com/134685355/315059844-72ea20f0-e7b1-4254-86d4-c404a79ef63b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODQ0LTcyZWEyMGYwLWU3YjEtNDI1NC04NmQ0LWM0MDRhNzllZjYzYi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wY2RjZGQxMGRhYmI5MmEzNWFhOTNhMWIyYTk4YzE1NzdhM2Y5YjFjOGU0NmJmMmRjNjYxMTA1N2UyZDA5MDJlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.in9Ny8cR2R1FU9eCXmDeYyrQK-kECny3xNeHuBOcaq4">
 
Hình 14: Bảng Product

3.3.3.	Bảng Topic

 <img src="https://private-user-images.githubusercontent.com/134685355/315059847-e2a72386-ddb7-43a8-8b2b-713b834d6c07.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODQ3LWUyYTcyMzg2LWRkYjctNDNhOC04YjJiLTcxM2I4MzRkNmMwNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00OTU3OGNjNDUyNTllNTk4MTkxOTI3ZDk2ODBmMWNjZTczNWUwZDBmMDgwMmVlZDkxYTQ5OGUyOTViZTgwNDQ2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.-Kcb78NIvOkyqKoKyfXuwA0ZuERczo0lYKC-tUehx_U">
 
Hình 15: Bảng Topic

3.3.4.	Bảng Post

 <img src="https://private-user-images.githubusercontent.com/134685355/315059850-3c2c6afa-b465-4f3e-807f-964de4aa9588.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODUwLTNjMmM2YWZhLWI0NjUtNGYzZS04MDdmLTk2NGRlNGFhOTU4OC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01MGY3MzM5OTZjNDZkZTdjNTJhNzE1YTU4OGFkNTljYjcwYjRlYjE4YTc3NGFhZDc5MGU2NjYzN2ViNmE3ZGMyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.9qw56Gi_bABlBHpaJJm7myHE0YelHimyOTqVBf8e0yU">
 
Hình 16: Bảng Post

3.3.5.	Bảng Slider

 <img src="https://private-user-images.githubusercontent.com/134685355/315059851-beafb9c9-9c2f-4d84-aa47-bb657d4cde7a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODUxLWJlYWZiOWM5LTljMmYtNGQ4NC1hYTQ3LWJiNjU3ZDRjZGU3YS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02YWUwYzNhMjY0MDk0MWU2MGNmN2FmYWYzNDk5ZjNkODRhOGMzNmUwYmUxYzg1MmQ5MmVmMTI3NGRmMWI4Mzk4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.KHDLCRRN0HA0xCHTFlAOlwPeSQBN86zJ5306JCed7Eg">
 
Hình17: Bảng Slider 

3.3.6.	Bảng Order

 <img src="https://private-user-images.githubusercontent.com/134685355/315059855-b155d76f-2abd-4fde-a0ab-901bae429730.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODU1LWIxNTVkNzZmLTJhYmQtNGZkZS1hMGFiLTkwMWJhZTQyOTczMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wOThmY2EyMTg1NWY3MDM2YjczOWYxMGRiNGYxNTEwYTE3ODRkMjY1ZDIzMTg3ZGU2ZjBmZmEyNWRlYzFlMWYyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.47Ga4ax-AC2AoI0-HQVY3IDAqKHX6lks-D-WDXYU0M0">
 
Hình 18: Bảng Order

3.3.7.	Bảng OrderDetail

 <img src="https://private-user-images.githubusercontent.com/134685355/315059856-cf6e7cd1-8c24-4e5e-a382-a2642abc3c43.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODU2LWNmNmU3Y2QxLThjMjQtNGU1ZS1hMzgyLWEyNjQyYWJjM2M0My5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kMGI1ZTg0OTU2MTg4ZjRhN2U5MTI5ZDRjNGVmNjlhYmJlYzA1MDE4ZDg5YzE1Y2VkZjFlYTAzZjVmNDRhYTA5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.DzvvJpX5DOOWa0zn5xez9HwQTwEAtw4rgRLxCQvAZF4">
 
Hình 18: Bảng OrderDetail

3.3.8.	Bảng User

 <img src="https://private-user-images.githubusercontent.com/134685355/315059859-251206ea-53f0-4ac8-bafd-df4a1d560b5c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODU5LTI1MTIwNmVhLTUzZjAtNGFjOC1iYWZkLWRmNGExZDU2MGI1Yy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NWNiMTdlZjM4NDRkZmJkMTgzNTg0Y2M0ZjlkN2VhYTJlZTJhM2Q0MGZmMzBiMzMyNjBkYmY5NWU2MDU4YjYwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ZbWk-pbM5w8cl2emlQWmXuz_zjFeH84POSlXQg9Sh5s">
 
Hình 19: Bảng User

3.3.9.	Bảng Menu

 <img src="https://private-user-images.githubusercontent.com/134685355/315059862-7a3aa03a-8cab-4052-95f9-4367c0079557.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODYyLTdhM2FhMDNhLThjYWItNDA1Mi05NWY5LTQzNjdjMDA3OTU1Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jMDU0ZjhkM2ZkYjkwYTRkODg5OWNlMDAxODFiNmNlNzQwOWZkNWJmNzgwMjBkZTBhNmRjN2U5MmNkZWYxNjVjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.v74Q538YRx5H7fOpdWt-lcwNqxznj0LsJqT4d7xBA8c">
 
Hình 20: Bảng Menu

3.3.10.	 Bảng Contact

 <img src="https://private-user-images.githubusercontent.com/134685355/315059866-0c0a0965-4081-412d-8a3b-6cf2c432900b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODY2LTBjMGEwOTY1LTQwODEtNDEyZC04YTNiLTZjZjJjNDMyOTAwYi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kYjE3MDNlNDg2YTMzNTBhMDRkZGQ4M2RhZTdlOThjZjFhMDY5MDQ1YzZkYTcwNWQxNjQ2OWJlMzJiZGJmYTNhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.JLtShG2HlHTpQ5PLtyhw0N1iIA6HbXsPQg8UfURCa6g">
 
Hình 21: Bảng Contact

3.3.11.	Bảng Link

 <img src="https://private-user-images.githubusercontent.com/134685355/315059869-0e6479bf-4a9f-42a5-a593-a8fb2f12099a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODY5LTBlNjQ3OWJmLTRhOWYtNDJhNS1hNTkzLWE4ZmIyZjEyMDk5YS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mYTViMDFjYmFjMzBlMzhiZDVjYjJkM2Y4OGNmM2I0ZDcyMmFkMjViZmUyZTMyMTA5N2VjZDU0OGI0MTg5YmVlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.yS6ih6IdMZELEHLvp_JRNLGOY2Vf11lnd-wmQn6aTDE">
 
Hình 21: Bảng Link

Chương 4.	Trình bày sản phẩm

4.1	Giao diện quản lý (ADMIN)

 <img src="https://private-user-images.githubusercontent.com/134685355/315059872-1610b5d7-e5a6-4d02-963b-6d4aa3864a4f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODcyLTE2MTBiNWQ3LWU1YTYtNGQwMi05NjNiLTZkNGFhMzg2NGE0Zi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xY2EzMTlhMGM3OTZhOWJlMGJlNDY4MzdiODdhMzdjNDE3MzMwOGQ1M2NiY2UxYTMyNzRhOWIxMzllNDU3YjY4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.T_94N1WVn5D98Jn76LK21kaQVrTC7wFeCRuvb5eLEd0">
 
Hình 22: Giao diện quản lý

4.2	Giao diện trang người dung (USER)

 <img src="https://private-user-images.githubusercontent.com/134685355/315059874-72beea91-db34-4224-a7e4-f1ecaaa77de6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEzOTY5OTgsIm5iZiI6MTcxMTM5NjY5OCwicGF0aCI6Ii8xMzQ2ODUzNTUvMzE1MDU5ODc0LTcyYmVlYTkxLWRiMzQtNDIyNC1hN2U0LWYxZWNhYWE3N2RlNi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyNVQxOTU4MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01MDRkNWM0NDU4ZGI0MmJlZDVlNTAzODZiYjQ2M2U2NDc5MTlhNjRlYTdlNDI3NTExOTI3ZGRkZTE3MDY1NTZmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.LL4R0KtPUIAqb8rDwrl3Z4D-GVHHelcr6K0D-vkO1y8">
 
Hình 23: Giao diện người dùng
