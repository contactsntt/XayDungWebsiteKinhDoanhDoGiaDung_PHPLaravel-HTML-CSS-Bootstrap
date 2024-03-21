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


