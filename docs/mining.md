# Cài đặt Anki & Mining

Đây là một hướng dẫn tự tạo một "bộ thẻ mining" để bạn thêm từ mới bạn bắt gặp trong quá trình immersion vào Anki để bạn học và ghi nhớ những từ vựng đó.  

Nhưng trước hết thì bạn cần [cài đặt Yomitan](yomitan.md).

Đầu tiên, bạn cần phải cài đặt Anki trước đã (Hướng dẫn này mặc định bạn sẽ sử dụng máy tính, việc thực hiện mining trên điện thoại thì bạn sẽ cần làm thủ công vì việc setup mining như trên máy tính thì chỉ làm được trên Android, và nó rất phức tạp).

[Nếu bạn đã cài Anki rồi thì bấm vào đây để bỏ qua.](#mining-setup)

## Thiết lập Anki

### Cài đặt

[Bấm vào đây để tải Anki](https://apps.ankiweb.net/). Chọn hệ điều hành mà bạn đang sử dụng (Hướng dẫn chọn cho người mù công nghệ: Nếu bạn đang dùng máy tính hay laptop mà không phải là Macbook thì chọn Windows, còn nếu dùng Macbook thì chọn MacOS).
 
Sau khi bạn bấm vào tệp `.exe` và bấm Next Next Next Next liên tục thì nó sẽ hiển thị ra cái cửa sổ đen sì này:

![Image](img/mining/shouianki1.png)

Bấm ++enter++, và chờ nó tải.  

Khi nào tải xong thì bạn sẽ thấy dòng này hiện ở cuối cái cửa sổ đen sì ấy: "Anki will start shortly. You can now close this window." Đóng cửa sổ đen sì đó lại
 
Rồi sau đó một cửa sổ khác hiện lên yêu cầu bạn chọn ngôn ngữ:

![Image](img/mining/shouianki2.png)  

Phần mềm yêu cầu bạn chọn ngôn ngữ để **hiển thị** trong ứng dụng. Khuyến khích bạn chọn Tiếng Anh (Dù vậy nhưng thao tác trong phần mềm khá đơn giản, xem qua vài cái Tutorial là bạn dùng được).  

Sau đó bạn sẽ thấy màn hình chính của Anki hiện lên. Trước tiên, chúng ta cần cài đặt một số tiện ích bên ngoài (add-on) để giúp *nâng cao trải nghiệm* học tập. Thực hiện các bước sau:

- Bấm vào "Tools" sẽ hiện ra một danh sách.  
- Bấm vào "Add-ons", sau đó cửa sổ Add-ons sẽ hiện ra.
- Bấm vào "Get Add-ons.." (Bạn nhìn ở góc trên cùng bên phải của cửa sổ là sẽ thấy)
- Dán (Paste) cái *add-on code* (mình sẽ để ở bên dưới), rồi bấm OK. 

Đây là các add-on bạn cần có

- AnkiConnect: `2055492159`
- PassFail2: `876946123`

![Image](img/mining/shouianki3.png)  
![Image](img/mining/shouianki4.png) 
![Image](img/mining/shouianki5.png) 

Sau khi cài xong add-on thì bạn đóng ứng dụng Anki và mở lại lên. Vậy là xong

### Thêm bộ thẻ vào Anki (Importing a deck)

Tải giúp mình bộ thẻ [Mẫu thẻ mining cơ bản](). Tệp có đuôi `.apkg` (Bạn nhìn ở cuối tên tệp).  

Thêm bộ thẻ vào Anki bằng cách nhấp đúp chuột (bấm 2 lần liên tiếp) vào tệp `.apkg`. Hoặc bạn có thể thêm bằng cách sử dụng "Import File" trong Anki và chọn tệp cần thêm.  

Khi cửa sổ này hiện lên, hãy import bộ thẻ bằng cách nhấn vào **Import**:

![Image](img/mining/shouianki6.png)

Sau đó, bạn có thể đóng cửa sổ import. Bây giờ bạn cần điều chỉnh *deck settings* bằng cách nhấn vào biểu tượng bánh răng (Bên phải của tên bộ thẻ), rồi chọn **Options** 

![Image](img/mining/shouianki7.png) 

Chỉnh sửa cài đặt ở phần:

- Maximum reviews/day: `9999`

![Image](img/mining/shouianki8.png) 

Bấm "Save" ở góc trên bên phải.  

## Mining setup

(Thiết lập quá trình mining của bạn)

Cần có:

- Yomitan. Nếu chưa cài thì bạn [cài giúp mình](yomitan.md)  
- AnkiConnect (Một addon trong Anki, nếu bạn chưa cài thì hãy quay lại hướng dẫn cài đặt Anki để đọc thêm nhé. Mã add-on AnkiConnect: `2055492159`).  

Then:

1. Tải [Mẫu thẻ mining cơ bản](). Chính là tệp `.apkg`.
2. Import (*thêm*) vào Anki, sau khi import xong thì xóa bộ thẻ tên là **thẻ mining** mà bạn vừa import vào Anki đó đi, chúng mình chỉ cần có note type thôi (note type về cơ bản là *kiểu thẻ từ vựng*, mặt trước (Front) trông như thế nào, mặt sau (Back) trông như thế nào).  
3. Trong Anki, bấm vào "Create Deck" ở bên dưới cửa sổ. Đặt tên cho bộ thẻ, ví dụ như là `Mining` rồi bấm OK.
3. Mở phần cài đặt Yomitan bằng cách bấm vào icon của Yomitan ![yomitan-icon](img/yomitan-icon.png) trên thanh toolbar của trình duyệt, rồi bấm vào icon hình bánh răng ![cog](img/yomitan-cog.png).  
4. Nhìn vào cái sidebar rồi bấm vào "**Anki**", rồi bật **Enable Anki integration**.  
5. Bấm vào **Configure Anki flashcards…**
6. Chọn tên bộ thẻ mà bạn đã tạo trên Anki (Ví dụ là `Mining`) ở mục "Deck". Chọn "Mining" ở mục "Model".  

Giờ chúng ta sẽ bắt đầu sửa các trường bên dưới (fields). Yomitan tự động thêm cho bạn nhưng có thể vẫn chưa đúng, nên là bạn kiểm tra và sửa lại như bên dưới giúp mình:

| Tên các trường | Nội dung bạn cần thêm |
| :--- | :--- |
| **Word** (Từ vựng) | `{expression}` |
| **Meaning** (Nghĩa của từ) | `{glossary-brief}` |
| **Sentence** (Câu ví dụ) | `{cloze-prefix}<b>{cloze-body}</b>{cloze-suffix}` |
| **Audio** (Âm thanh, cái này là phát âm của từ) | `{audio}` |
| **Picture** (Ảnh) | *(Không điền gì, bạn tự thêm sau nhé :>)* |

## Thêm một thẻ từ vựng

Bạn giữ phím ++shift++ rồi di chuột vào từ vựng bạn cần tra, bấm vào dấu cộng (+) màu xanh lá cây để thêm thẻ từ vựng.  

![Mining a card](img/mining/mining1.png)  

Nó sẽ trông như thế này:

![Mined card](img/mining/mining2.png)  

Giờ thẻ đã được thêm vào trong bộ thẻ Anki của bạn.

Nếu thẻ đã được thêm, thì khi bạn di chuột vào từ đó, chỗ hiện dấu cộng (+) màu xanh lá cây sẽ hiện thành icon hình quyển sách đang mở. Bấm vào icon quyển sách đó sẽ mở cửa sổ mới trong Anki (Browse) và hiện thông tin của thẻ từ vựng đó.  

### Tips

- Highlight (bôi đen) phần text trong từ điển (Yomitan) trước khi thêm thẻ. Điều này giúp nội dung thẻ của bạn gọn gàng hơn. Bôi đen phần text bạn muốn thêm vào Anki bằng chuột, *sau đó* nhấn vào dấu cộng (+) màu xanh để thêm thẻ.
- **Thêm hình ảnh cho danh từ**. Nếu đó là danh từ, bạn nên tìm kiếm hình ảnh cho từ vựng đó trên Google Images, sao chép (Nhấn chuột phải rồi chọn Copy Image) sau đó dán (Paste, đơn giản là ++ctrl++ ++v++ thôi) vào field (trường) "Picture" của thẻ.

*sorry nếu chú thích hơi nhiều, tôi không biết là những bạn mới tập dùng hay là không biết tiếng anh có hiểu hướng dẫn này không. Nếu vẫn còn thắc mắc thì cứ nhắn tôi trong Discord nghen.*

## Nguồn bài viết

Hướng dẫn này là bản dịch và hiệu đính lại từ bài [Mining Guide](http://learnjapanese.moe/mining/) của TheMoeWay.