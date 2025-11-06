---
type: Page
title: 'note taking + journal apps '
description: null
icon: 👁️
createdAt: '2024-02-29T08:26:39.650Z'
creationDate: 2024-02-29 15:26
modificationDate: 2024-04-06 18:51
tags: [NoteTaking, applications, computer]
coverImage: null
---


[https://pandao.github.io/editor.md/en.html](https://pandao.github.io/editor.md/en.html)



```text
# h1
## h2
### h3
- bullet
`quote`
**bold**
```



---

Các PKM hiện tại như mình thấy đều có ưu/nhược điểm riêng, chưa có cái nào one-size-fits-all cả. Vậy nên tuỳ vào nhu cầu cụ thể của từng người và mức độ ưu tiên để chọn một cái thích hợp.

**Lấy ví dụ với nhu cầu cá nhân của mình:**

- Định dạng văn bản phải đơn giản và phổ biến, đọc/ghi dạng plaintext file. Markdown và Org[1] là hai định dạng đáp ứng được nhu cầu này.

    - Mình dùng các loại phần mềm ghi chú hơn 20 năm nay rồi, từ plaintext (.txt), cho đến mind map (.mm), và giờ là Markdown (.md). Note là thứ để lưu và đọc lại khi cần (đỡ công nghiên cứu tìm hiểu lại từ đầu) chứ không phải thứ mất đi cũng chẳng sao. Mình thấm thía nỗi khổ của việc convert dữ liệu từ định dạng này sang dạng khác.

    - Mình có thể mở Markdown/Org file bằng bất cứ plaintext editor nào để ghi chú **(Notepad++, Sublime Text, EmEditor, v.v.),** không nhất thiết phải phụ thuộc vào phần mềm PKM.

    - Thế nên, các phần mềm PKM chỉ cho dùng online và các phần mềm PKM lưu note trong database không (hoặc khó) đáp ứng được yêu cầu trên. Nếu bạn có vài chục nghìn trang note quan trọng, và bạn bế tắc trong việc export/import sang một phần mềm khác thì bạn sẽ hiểu.

- Cũng vì yêu cầu kể trên, phần mềm PKM cũng phải hỗ trợ một Markdown và/hoặc Org.

    - Nếu phần mềm PKM mình dùng người ta dừng không phát triển nữa, ít ra mình vẫn còn có cơ hội batch convert những file plaintext kia để phù hợp một phần mềm PKM khác.

- **Mình quan tâm đến privacy, thế nên phần mềm PKM phải lưu dữ liệu local. Thích sync cách nào thì tuỳ mình.**



---


Ok , hôm nay rảnh rỗi nên preview thử Visual Studio Code với extension [Foam](https://voz.vn/[Foam]https://foambubble.github.io/foam/).

Theo như lời trên Github của tác giả:

> **Foam** is a personal knowledge management and sharing system inspired by [Roam Research](https://roamresearch.com/), built on [Visual Studio Code](https://code.visualstudio.com/) and [GitHub](https://github.com/).

Docs: [Foam Features (https://foambubble.github.io/foam/user/recipes/recipes)](https://foambubble.github.io/foam/#whats-in-a-foam)

Hỗ trợ :

- Markdown

- Tags cho từng note để tiện việc sắp xếp các note và tìm kiếm

- Template cho từng kiểu note (report, daily...)

- Wikilinks như trong hình dưới đây.

- Hỗ trợ cả Data Graph

Nhìn chung, nếu ai từng có kinh nghiệm sử dụng Obisdian thì có thể làm quen được với thanh niên này ngay

---


Vâng, nhu cầu của em nó cũng đơn giản. Ko phải là viết văn chương hay tài liệu nghiên cứu 1000 trang đâu.

Nhưng nhu cầu học của em cao cũng như công việc hiện tại đòi hỏi bảng biểu, liên kết nhiều mà **Excel**/ **Google sheet** nó ko đáp ứng được/ hoặc bất tiện (thời điểm này e ko rõ) + **chart graph** thì em dùng **Google Looker Studio** (mấy cái này làm việc data nhỏ/ doanh nghiệp nhỏ chắc ko cần nhiều, chứ em làm việc dữ liệu lớn thì nó ngon vl và tiện hơn M$ Power BI).

Như vậy công việc của em gồm 2 phần:

- Data thô được xử lý rồi đưa lên **Google Looker Studio**/ **M$ Power BI** phục vụ report, xem số liệu còn đưa ra quyết định nhanh.

- Note data để phục vụ nghiên cứu truy xuất nhanh, theo dạng PKM, dùng cá nhân, ko có nhu cầu chia sẻ, collaborate

Em ko nghiêng về code/ hay viết văn nên các tính năng khác có cũng được, ko có ko sao miễn là có dạng database, có relation này nọ (mà phải tiện nữa, chứ **CherryTree** vất vả quá).

1 thằng bao được cả 2 nhu cầu trên của em là **LarkSuite** thì nó lại làm chưa tới, hơi nửa mùa nên cũng để ở chế độ tham khảo thêm. Các bác có thể tìm hiểu thêm xem dạo này có j hay ho ko.



---

Vâng, em đã kịp lướt qua xong

Lần gần nhất ngắm con này là tầm tháng 10 11 năm ngoái

Đến giờ cũng có nhiều cải thiện

Vì ngài Shenzero chuyên nghiên cứu privacy sexcu-ri-tito ti bé nên không bàn thêm nhiều, công nhận là login kiểu phrase tiện nhanh gọn, file thì đúng vô nghĩa luôn, mà dek biết đổi chỗ lưu file kiểu j, cứ nằm trong Roaming data

Phần chính là chức năng dành cho end user ngoo/mù công nghệ hoặc chỉ quan tâm tiện lợi thì:

- **Bảng biểu** kiểu set/ collection na ná Capacities nhưng tag thì **thua Capacities** (Cap rất mạnh ở object linking với hệ thống tag thích đặt đâu thì đặt, tuy lộn xộn nhưng quan trọng là tiện)

- Vẫn là bảng biểu đó có **inline table** (như vậy hơn Capacities) thì lại **chưa ăn được Notion**

- Để làm **note, viết lách** thì cần tổ chức quản lý sub-level thì ông này lại **thua CherryTree và SiYuan**

- Làm **daily note** thì **thua Capacities** (thg này làm daily note quá mạnh, đi họp thì m gần như Sublime rồi đưa vào Capacities cả)

- Nếu Offline thì cần thêm tính năng **view ảnh từ link** thì ông này đến get ảnh từ link về local còn lỗi hiển thị (test với Imgur thôi, bãi rác ảnh thế giới) trong khi **SiYuan** làm rất tốt phần này, insert image link cái là lên hình luôn, làm gallery cũng được ý chứ. Còn thôi, khỏi so với Capacities và Notion với khả năng lưu vô cmn hạn ảnh, ảnh idol jav từ SL t lưu trên Capacities cũng hàng đống luôn

- Làm **codeSnippet** thì cần an toàn tránh bấm nhầm -> cần read-only/ lock block đó thì cũng chưa thấy (-> **thua SiYuan, Capacities** )

- Lại thêm vấn đề là **không có portable** thì **thua CherryTree** ở góc độ làm công cụ note

- Do chỉ lướt, không đổ data vào nên không đánh giá **tốc độ** (vẫn như năm ngoái, chưa có gì hay để lưu luyến cả) nhưng chắc đổ nhiều lại **thua AppFlowy** thôi

**-> Như vậy những feature ông này có thì ae họ đều có cả**

- Điểm cộng là UI đẹp, login dễ, bảo mật cao

Từ những phân tích trên, có thể thấy AnyType này vẫn dở dở ương ương lắm, bảo mật cao không phải yếu tố quyết định nhất với PKM khi mà mục đích để note. Hẹn 3 tháng sau lại quay lại xem có tiến bộ gì không

---


P/S: Ngta note bằng giấy được (thì lấy đâu ra bảo mật), bằng word được (cũng không có bảo mật) -> ngta mong chờ có nhiều tính năng hay hỗ trợ note hơn là lo mất tài sản là cái đống rác toàn chữ. T nghĩ như vậy nên là dùng note vẫn với combo như sau:

---


**Online**

- **Notion Plus** lưu unlimited file, dung lượng 1 file cũng unlimited - chuyên lưu app nặng kiểu PTS, bộ cài Win... trước có lưu văn hoá phẩm cơ mà thấy OneDrive cũng được vì mất thì thôi, down lại [:D](https://data.voz.vn/styles/next/xenforo/smilies/popo/biggrin.png?v=01)

- **Capacities** - daily note, linking object kèm graph view thì cũng bá đạo rồi

---


**Offline**:

- **Sublime** cho note hàng ngày (bởi nó đóng/mở quá nhanh, ý tưởng xuất hiện là phải note ngay không thể chờ mấy thg app kia khởi động được, còn mở sẵn các thứ thì không phù hợp với hội di chuyển nhiều như e)

- **CherryTree/ SiYuan** cho các nghiên cứu cần đọc nhiều tài liệu vì có tổ chức kiểu folder (sau cũng ném lên Capacities để có kiểu linking note, truy xuất dễ dàng / Notion dùng kiểu synced block cũng hay nên tuỳ casestudy để ứng dụng, khai thác). 2 ông này vẫn đang trong phạm vi vừa dùng vừa test, chứ chưa chọn được ông nào làm chính, 8 lạng nửa cân quá do CherryTree có portable còn SiYuan phải cài, mà cài là đã cấn cấn rồi (nhưng vẫn hơn AnyType ở điểm config được vị trí lưu Data, AnyType là chịu dek biết chỗ nào để sửa). CherryTree lại có thêm 1 lợi điểm là gắn Folder path vào note luôn, bấm cái là Directory Opus thiên thần xuất hiện trong chớp mắt, quá ổn cho việc note offline.

Trên đây là tất cả những gì e có thể viết về AnyType sau 15p test mấy tính năng cơ bản. Cũng chẳng biết nói j thêm nữa [😔](https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f614.png) mời các danh thủ vào cho ý kiến để e mở mang thêm kiến thức dùng Note

====================

> [HIL said:](https://voz.vn/goto/post?id=31141690)

Mình thấy ngược lại. LibreTube thua xa Grayjay về tính năng (chỉ tính chức năng cho YouTube).

Đấy là chưa kể đến Grayjay còn stream được từ Twitch, SoundCloud, nhưng lạc đề nên mình không muốn đề cập.

À chắc em nhầm bị nói ngược bởi down về lướt qua rồi chọn Grayjay dùng luôn, xoá LibreTube do không có cast và không có nhiều nguồn input như Grayjay. Grayjay được quả load đủ thứ, hay thật.

Ngoài ra, có 1 điểm nữa là Grayjay cho tạo Subscribed Group (như tạo Workspace, Group Tab... trên Browser, Directory Opus) -> bấm cái là chỉ load video từ những Channel m đã subscribe theo chủ đề. Khá là tiện vì Youtube chỉ có lưu theo playlist, hơi hẻo. Với hệ thích note, thích tag như em thì những thứ như Capacities hay browser là hội Firefox là ăn điểm (Firefox có tag, có keyword khi bookmark)

Cứ nói hết đi bác, cái thớt này là thớt Gâu bờ rồ công nghệ mới đúng ^^

> [shenzero999 said:](https://voz.vn/goto/post?id=31142004)

Ngài có biết tên dev maintainer của sponsorblock là ai ko? Đúng vậy, ajay. Nhưng ajay hơi gei nên mới tạo ra gayjay đó ngài

[FJsFo6m.png](https://voz.vn/proxy.php?image=https%3A%2F%2Fi.imgur.com%2FFJsFo6m.png&hash=b937a05c5ce4adda6cc7bf0c14f411a4)

Hoá ra vậy, kể mà làm cái Grayjay ngon thêm tí nữa thì tốt, bê nguyên features của Revanced sang cũng được.

====================

> [toi la gay :sosad: said:](https://voz.vn/goto/post?id=31142311)

Mát máy là ok rồi ngài, hè năm nay phải 40 độ C mà để máy nóng là rất nguy hiểm, hiện tại dùng Linux thì máy mát hơn Win 10, 11 tầm 4-5độ, quá cần thiết máy toàn hàng tầm cỡ bí mật quốc gia mà hỏng phát méo mồm 

[😔](https://voz.vn/proxy.php?image=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Ftwitter%2Ftwemoji%4014.0.2%2Fassets%2F72x72%2F1f614.png&hash=d4e2536b7d647646c0eb17056b7c0591)

Giờ e lúc nào cũng ở tư thế sẵn sàng ý. Máy hỏng cũng được.

Luôn backup mọi thứ không đến mức mỗi ngày nhưng cũng 2 3 lần 1 tuần.

Từ cuối năm ngoái đến giờ là chuyển hết app về dạng portable cả rồi, data hay dùng hàng ngày gần như đã nằm trong con USB cả. vài ngày lại loay hoay zip + pass mấy data quan trọng, 1 tháng backup nguyên cái USB rồi ném lên OneDrive + Notion (đặt pass cả r) -> thôi thì mày đi lúc nào thì đi, bố lấy con khác [:D](https://data.voz.vn/styles/next/xenforo/smilies/popo/biggrin.png?v=01)

---


Cùng quan điểm với bác Hiu

Bởi có những loại kiến thức, nghiên cứu đặc thù cần có tổ chức rõ ràng mà ví dụ đơn giản nhất chính là **Bộ máy tổ chức**. Việc làm phẳng bộ máy này rồi lại sắp xếp thành mục để hiển thị thì tóm cái váy lại nó vẫn có **output là dạng folder/tree/path**.

Do đó có những cái em lại **dùng CherryTree, SiYuan chứ không phải cứ cố gò nó vào Capacities**.

Nhưng đương nhiên, về kiến thức nói chung thì bởi não người sẽ dễ dàng hơn với dạng network và cũng chỉ cần vậy cho mục đích tìm lại thông tin nên có thể import dữ liệu vào những app như Capacities hay AnyType để làm dày kho kiến thức cá nhân, tránh search không ra.

-> Em đã chia sẻ khá khá nhiều để ae thảo luận kinh nghiệm dùng:

- **Capacities + Notion** cho mục đích lưu trữ PKM

- **CherryTree/ SiYuan** cho mục đích nghiên cứu, làm tài liệu

====================

> [toi la gay :sosad: said:](https://voz.vn/goto/post?id=31148538)

[@shenzero999](https://voz.vn/u/1721891/) [@hpa557](https://voz.vn/u/1942372/) Các chuyên gia về Pokemon thấy ghi chú dạng MindMap kiểu này ổn không ? Nhu cầu là để ghi chú một khối lượng dự án lớn (>100) để sửa lỗi, cải thiện.

[View attachment 2425501](https://voz.vn/attachments/2425501/)

Đến đoạn **MindMap** rồi

Xin chia sẻ xâu chuỗi tí trước khi đi vào vấn đề chính ạ:

1 - Em vốn là người dùng **Macbook** lâu năm,

2 - **Họp hành** về kiến trúc hệ thống với mấy thằng **System Architect** Ấn thì bọn nó vẽ lên bảng sau đó tối về cũng hì hục gửi m cái **MindMap** UML này nọ vẽ ra giấy rồi chụp lại

3 - Em thấy dân công nghệ mang tiếng System Architect của tập đoàn lớn, đang xây cái **hệ thống ERP** rõ đồ sộ làm nông dân vãi cái khâu này => Em bắt đầu nghiên cứu MindMap để vẽ lại và khi họp thì còn tiện vừa họp trao đổi vừa chỉnh sửa trực tiếp

4 - Từ đó với cái tính tò mò vốn có, cứ vừa làm vừa tìm MindMap app phù hợp để còn tiện note này nọ, mà chẳng có thằng nào ưng ý luôn [:(](https://data.voz.vn/styles/next/xenforo/smilies/popo/frown.png?v=02)

5 - Trong quá trình nghiên cứu thì tự dung bị lạc vào PKM (lúc này vẫn còn trung thành với **Microsoft OneNote + Evernote**)... rồi thg đầu tiên mà em dùng là **ClickUp** với khả năng ghi chép như OneNote + **có dạng bảng, có timeline, có MINDMAP, có các thứ mà Trello có** (em thì cũng dùng Trello luôn, chủ yếu collaboration). Và đã **xuống tiền mua ClickUp** vừa để lưu trữ dữ liệu cá nhân vừa làm cái MindMap

6 - Bất cập là nó **chậm, đơ lag khi có nhiều data** -> lại tiếp tục tìm và lúc này có **3 yêu cầu**: 01 - **nhanh mượt**, 02 - **online** để dễ chia sẻ, 03 - **free** hoặc crack vì không có tư tưởng mua.

7 - Trên Mac, nhớ là rất thích **xMind** và ngày xưa còn 1 con nào nữa ý, không nhớ (app có dạng **bubble linking note** - giống graph view của các PKM app hiện tại, rất đẹp, dễ dàng Brainstorm) nhưng app crack hoạt động dẩm l, chán vl nên đành từ bỏ con app đó (lúc đó vẫn nói không với Windows)

8 - Vì không thể dùng được con app MindMap rõ ngon đó -> bỏ phương án Crack, tập trung tìm theo hướng **Online & Free** -> có mấy con như LucidChart, Mindomo, Mindmeister và MindMup. Sau quá trình thử từng con thì đã chọn 2 con là LucidChart và MindMup:

- **LucidChart** - vẽ UML ngon nhưng mất thời gian

- **MindMup** - đơn giản nhưng bố của nhanh, ông nội của tốc độ

9 - cả 2 (LucidChart và MindMup) đều online, free, và đặc biệt là có **tương thích với Google Drive** rất dễ chia sẻ (tạo trực tiếp file khi đang ở Google Drive luôn)

...

Sau quá trình lần mò app ủng PKM note abcxyz thế nào rồi e xuất hiện ở đây, trước đó cực ít online chat chit cũng chẳng fb ig này nọ đâu.

===

Sau 9 ý trên thì em đã tiến vào thế giới PKM với ClickUp và sau dự án cũng dần xa rời MindMap vì cũng mải mê nhiều thứ quá.

Em **rất thích MindMap** bởi với người **thích vẽ** như em (ngày xưa vẽ bán tranh luôn), **tư duy não phải** và **ghi nhớ kiểu dạng lướt phát là nhớ** (như **siêu trí tuệ siêu trí nhớ mả mẻ j đó** hiện nay ý, gọi là chụp ảnh, lấy con mắt làm cái camera rồi chụp lại trang sách rồi nó hiện lên trong đầu hình ảnh cái trang đó luôn), thì MindMap là hướng tiếp cận phù hợp cho bất kỳ ai (đương nhiên muốn đọc nhanh, nhớ nhanh, nhớ nhiều, nhớ lâu lại là 1 quá trình rèn luyện)

===

Dài dòng quá, giờ quay lại vấn đề chính của thầy gầy

Em xin phép phân tích trước:

- Với **MindMap** thì nó **na ná Note** nhưng thiên hướng nghiêng về **Brainstorming** hoặc có **tính chất tổ chức/ rẽ nhánh/ phân tầng** chứ không phẳng lỳ network như Capacities (đương nhiên cái này giờ nó chỉ còn **mang tính tương đối**, tương tự bóng đá ngày nay, không còn kiểu giữ nguyên 1 khối đội hình cả trận mà thay đổi liên xoành xoạch formation từ 4-2-3-1 sang phòng thủ 4-4-2 hoặc tấn công 2-4-4)

- MindMap khi tạo mới, ở thời điểm mà ngta gọi là **Start from the Scratch** thì sẽ là **Brainstorming** rồi, vậy **cần yếu tố nhanh tốc độ tiện dễ dùng** (bác tham khảo **MindMup** - lâu lắm e chả động vào nên không biết giờ ra sao rồi). Và nên bắt đầu với **MindMap** thay vì text vì khả năng **lên ý tưởng tốt hơn**, **xâu chuỗi tốt hơn**, **giảm** thiểu rủi ro **sót ý** hơn bởi nó **trực quan**. Em toàn chơi MindMup rồi **in A0 ra họp**, khi họp thì bôi vẽ đến mức sau đó dek nhận ra cái tờ A0 đẹp đẽ của m ban đầu nữa.

- Ngoài ra, có thể **ghi chú**, hiển thị **properties**, có thể **view media link** nữa thì **đúng ngon** (vì hầu hết các app đều có note nhưng vẫn làm hời hợt chưa ưng ý, và đấy là lý do em không còn dùng MindMap nhiều nữa, chuyển sang PKM rồi đâm ra viết text nhiều hơn là vẽ hình)

- Nếu muốn ghi nhớ nhanh thì nên **màu sắc long lanh** và **làm đẹp mắt** (các app trả phí đều làm khá đẹp)

Từ những phân tích trên thì em thấy rất ổn và rất nên dùng dạng này rồi sau đó mới ghi chú gì thì ghi, cái khó là nếu đưa vào thương mại thì chưa chắc vì người hiểu được tầm quan trọng của MindMap lại không quá nhiều, so với số đông thích viết chữ.

P/S: Cái sát nhất với cái này là **Capacities** rồi vì cứ bấm bấm tí là có cả 1 network to đùng với graph view chằng chịt. Cơ mà cũng chưa từng động vào xem việc sửa trực tiếp trên graphview có ổn không [:(](https://data.voz.vn/styles/next/xenforo/smilies/popo/frown.png?v=02)

Sau đây là danh sách các MindMap app e đã kinh qua, chỉ list tên thôi vì lâu rồi chả dùng:

1 **MindMup** (dùng nhiều nhất, nghiêng về **brainstorming**, **listing**)

2 **LucidChart** (dùng nhiều thứ 2, nghiêng về vẽ **UML**, **workflow**, guide)

3 Mindomo (dùng thoáng qua)

4 **ClickUp** (trước dùng nhiều vì nó là PKM, tính năng **table** mạnh mẽ chả kém Notion nhưng chậm đơ lag -> bỏ)

5 **Figma** (**custom mạnh** nhưng phù hợp **Designer** hơn vì nó lại custom thái quá)

6 Ayoa

7 Creatly

8 MindMeister

9 MindNote

10 Miro

Còn vài cái tên nữa mà không nhớ nên thôi, chắc e kinh qua cỡ này là cũng đủ để bác Gầy tham khảo.

Khi nào bác xây xong cái app thì cho ae làm tester nhé ^^

