---
type: Page
title: so sánh giữa các office
description: null
icon: 🙏
createdAt: '2024-03-08T04:09:10.664Z'
creationDate: 2024-03-08 11:09
modificationDate: 2024-03-08 11:10
tags: [office, applications]
coverImage: null
---

Mình xin viết 1 post ngắn review sơ sơ phần xử lý bảng tính (tương đương excel) của 3 phần mềm Only Office, WPS và Libre Office cho các bác tham khảo.

File mẫu dùng trong phần test: [6.19 MB file on MEGA (https://mega.nz/file/ORI3GIjL#KKycrd4iMYS3NZ7bUaRhPaRfgKYoWa3yDFdyEkghl_8)](https://mega.nz/file/ORI3GIjL#KKycrd4iMYS3NZ7bUaRhPaRfgKYoWa3yDFdyEkghl_8)

Cấu hình máy hiện tại:

[1707037220842.png](https://voz.vn/attachments/1707037220842-png.2323826/)

--------------------------------**Only Office**---------------------------------

**Giao Diện**: Giao diện của Only Office tương đồng với giao diện của M$ Office phiên bản từ 2013-2019, đây cũng là phiên bản office đang phổ biến ở VN, do đó, trong trường hợp phải chuyển đổi từ M$ Office sang thì người dùng sẽ ít gặp vấn đề hơn. Only Office có hỗ trợ Tab, mỗi file là 1 tab, thuận tiện cho người mở nhiều file cùng lúc. Only Office có chế độ tối.

[1707037314409.png](https://voz.vn/attachments/1707037314409-png.2323827/)

**Hàm**: Bộ hàm của Only Office có các hàm mới gần đây, bao gồm xlookup, filter, sequence, maxifs, theo mình đánh giá là tương đương với Excel 2021. Tuy nhiên Only Office không có Dynamic Array (là tính năng tự điền kết quả sang các ô bên cạnh nếu kết quả là 1 mảng có nhiều dòng, cột), do đó, nếu có nhu cầu cần dùng các công thức trên mà muốn các kết quả trả về nhiều dòng, bạn phải chọn vùng trước, nhập công thức rồi nhấn Ctrl + Shift + Enter tương tự như phiên bản cũ của Excel. Tuy nhiên mình không rõ hàm hoặc thao tác để nhập hàm trên Only Office có vấn đề gì không, mình đã thử 1 công thức đơn giản để lọc số lẻ ra khỏi 1 dãy số và nó chạy sai.

[1707037407978.png](https://voz.vn/attachments/1707037407978-png.2323829/)

**Test mở file**: Mở file mẫu 3 lần, dùng mắt canh màn hình và bấm giờ, sau 3 lần mở, thời gian trung bình để mở file là 6-7 giây.

**Test 1000 công thức Vlookup**: Sau 3 lần chạy, thời gian trung bình để thực hiện công thức, tính từ lúc thả chuột sau khi kéo 1000 dòng công thức, cho đến khi kết quả hiện lên màn hình là ~30 giây. Thành thực mà nói, đây không phải là 1 con số tốt cho lắm, mặc dù Excel không phải là công cụ để xử lý dữ liệu lớn, nhưng 1000 không phải là con số lớn lắm.

**Test 5000 công thức Vlookup**: Mình không làm được bài test này, do nó đơ quá lâu.

**Kết Luận:** Là 1 phần mềm tốt nếu có nhu cầu muốn chuyển từ Excel sang 1 phần mềm khác, có bản cho Linux, giao diện sạch sẽ, không có quảng cáo, nhược điểm là cảm giác có vẻ khá chậm, không thích hợp để làm việc với số lượng dữ liệu lớn.

--------------------------------**WPS Office** --------------------------------

**Giao Diện**: Giao diện của WPS tương đồng với giao diện của Excel 2021, từ icon cho đến cách bố trí, đây là giao diện hiện đại, sạch sẽ, lúc trước có chế độ tối giờ hình như mất rồi. Tương tự Only Office, WPS cũng có tab dành cho ai thích mở nhiều file cùng 1 lúc. Giao diện sẽ có quảng cáo, có cả quảng cáo dạng pop up kể cả khi không mở phần mềm, bạn cần cần nhắc nếu thấy khó chịu. Quảng cáo chủ yếu là gói Pro, Vip của phần mềm này.

[1707037563391.png](https://voz.vn/attachments/1707037563391-png.2323830/)

**Hàm**: Tương tự như Only Office, bộ hàm của WPS cũng có các hàm mới được cập nhật gần đây (xlookup, filter, sequence, maxifs, minifs), đảm bảo bạn có thể mở được các file được tạo bởi Excel 2021 mà không gặp lỗi. WPS không hỗ trợ Dynamic Array, do đó nếu bạn muốn sử dụng các công thức liên quan tới chức năng này (vd Filter) bạn cần chọn trước vùng, sau đó mới nhập công thức và nhấn Ctrl + Shift + Enter để thực hiện. Mình thử lại công thức lọc số lẻ bên trên, WPS đã cho kết quả đúng. Không như OnlyOffice, WPS sẽ gợi ý cho bạn kể cả khi bạn sửa hàm giữa chừng trong công thức, tương tự như Excel

[1707037600857.png](https://voz.vn/attachments/1707037600857-png.2323832/)

**Test 1000 công thức Vlookup:** Sau 3 lần chạy thử, thời gian thực thi công thức từ lúc thả chuột cho tới khi hiện kết quả là dưới 1s, tốc độ xử lý rất nhanh.

**Test 5000 công thức Vlookup:** Tương tự như trên, thời gian để xử lý dưới 1s kể cả là 5000 công thức Vlookup.

**Kết Luận**: Là 1 phần mềm tốt để thay thế Excel, tốc độ xử lý nhanh, giao diện sạch, sáng và tương đồng với Office 2021. Chỉ có 2 vấn đề mà bạn cần cân nhắc khi dùng: Nó có quảng cáo (trong cả giao diện và ở ngoài) vì đây vốn không phải là 1 phần mềm miễn phí hoàn toàn và đây là 1 phần mềm của Trung Quốc.

-----------------------------Libre Office-----------------------------------

Tại thời điểm viết bài, trang chủ LibreOffice không vào được, do đó mình sẽ dùng bản Portable trên portableapp.com ([LibreOffice Portable Fresh (full-featured office suite) | PortableApps.com (https://portableapps.com/apps/office/libreoffice_portable)](https://portableapps.com/apps/office/libreoffice_portable))

**Giao Diện**: Nói thật lòng, nếu so với các phần mềm bên trên, Libre Office hoàn toàn không có ý định là sẽ chăm chút cho cái giao diện của phần mềm này, vì cái giao diện này mình thấy từ cách đây chục năm trước rồi và đến bây giờ nó vẫn không đổi. Về cơ bản, bạn nào đang dùng Linux sẽ thấy cái giao diện này quen thuộc hơn là bên Windows. Giao diện này là mình đã chỉnh lại về dạng Tab, chứ cái mặc định của nó rất rối, toàn bộ các chức năng thông dụng sẽ được bày hết ra cái thanh công cụ, khiến nó rất rối và rất áp lực cho ai mới bắt đầu dùng. Giao diện này sẽ tương đồng với Excel 2010, thật ra Excel 2010 đẹp hơn nhưng vì không có bản Excel nào có giao diện giống như vậy nữa nên mình đành lấy cái thấp nhất vẫn còn đang thông dụng hiện nay. Libre Office không hỗ trợ Tab (mở nhiều file thành các tab như trình duyệt)

[1707037719093.png](https://voz.vn/attachments/1707037719093-png.2323834/)

**Hàm**: Libre Office không có 1 số hàm mới như 2 phần mềm trên, dựa vào số lượng hàm hiện có, mình đánh giá nó tương đương với phiên bản Excel 2019, nó có hàm Textjoin giúp ghép chuỗi tốt hơn, cũng như tạo được công thức dò tìm trả về nhiều kết quả trong 1 ô. Libre Office cũng không có Dynamic Array hoặc tính năng tương tự.

**Thao tác khi nhập hàm**: Với tiêu chí tránh xa đồ M$, các thao tác khi nhập hàm trên Libre Office cũng khác. Cụ thể, bạn vẫn sẽ có gợi ý khi nhập 1 vài chữ đầu của hàm, nhưng bạn sẽ dùng tổ hợp Ctrl + Tab và Ctrl + Shift + Tab để điều hướng qua lại (Libre trình bày danh sách hàm dạng hàng ngang, không phải danh sách dọc như các phần mềm còn lại) , và Enter để chọn hàm. Việc dùng tổ hợp phím sẽ gây khó khăn cho những ai mới dùng Libre Office lần đầu vì thực sự 3 cái phím thẳng hàng này hơi khó bấm . Libre Office cũng sẽ gợi ý công thức kể cả khi bạn thay đổi giữa chừng trong công thức của bạn.

**Thời gian mở file**: Mặc dù mình đã thử mở 2, 3 lần nhưng phần mềm xuất hiện thông báo lỗi và sau đó đơ, không có phản ứng gì, mình đã thử xóa đi và tải lại lần nữa nhưng vẫn không được, do không mở được file, nên mình cũng không thực hiện được bài test hàm Vlookup.

[1707037806596.png](https://voz.vn/attachments/1707037806596-png.2323835/)

**Kết luận:** Mình không có nhận xét gì về phần mềm này, nhận xét cá nhân là nên chôn nó chung với người anh em OpenOffice cho nó đủ cặp.




Về cơ bản, cả excel online và google sheet đều có số lượng hàm tương đương với excel 365 hiện tại, thao tác của 2 thằng này tương tự excel. Nếu xét về hàm và khả năng tương thích thì đám phần mềm trên không có tuổi gì luôn.

Ưu điểm của Google Sheet:

- Hệ thống hàm đồng bộ, không có hiện tượng máy này có hàm mày, máy kia không có.

- Có 1 số hàm mà excel không có, như hàm query có thể chạy lệnh sql, ai rành sql có thể tạo các bảng tính mà hàm bình thường rất khó làm. Hoặc nhóm làm có regex ( regular expression) giúp trích xuất dữ liệu từ chuỗi, xử lý chuỗi hiệu quả hơn.

Nhược điểm của Google Sheet là nó thiếu 1 vài công cụ trên excel vd như Table ( bảng tự mở rộng, tự copy công thức xuống dưới, tham chiếu đến table là tham chiếu động, tự co dãn theo table ), go to speial ( chọn 1 loạt ô dựa trên 1 điều kiện nào đó )

2 phần mềm này có đủ nhược điểm của 1 phần mềm online, cần mạng, phụ thuộc tốc độ đường truyền, phụ thuộc sức mạnh của máy chủ xử lý và trên hết là khả năng tương tác qua lại giữa các file còn rất hạn chế.

Google Sheet giải quyết điều này bằng hàm Importrange, cho phép lấy dữ liệu từ các file google sheet khác, nhưng nó có 2 nhược điểm: 1 là chỉ hoạt động với file google sheet, nếu bạn upload 1 file mà nó là định dạng xlsx, thì phải đổi về định dạng google sheet thì nó mới chạy, 2 là tốc độ không được nhanh lắm và thi thoảng còn bị lỗi.

Excel online thì đang thử nghiệm tính năng link file mà thấy chưa hoạt động hiệu quả lắm.

