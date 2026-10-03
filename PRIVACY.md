# Chính sách quyền riêng tư

*Hiệu lực từ ngày 2/10/2026. Văn bản này do người bán (một cá nhân) tự soạn theo pháp luật Việt Nam về bảo vệ dữ liệu cá nhân (Luật Bảo vệ dữ liệu cá nhân số 91/2025/QH15 và các văn bản hướng dẫn) và có thể được cập nhật (xem mục 13).*

Tóm tắt:

- App **không có tài khoản**: không hỏi tên, email hay số điện thoại.
- Riêng khi bạn **tự chọn đăng ký làm gia sư**, app gửi lên máy chủ thông tin hồ sơ (họ tên, cách liên hệ…) và **ảnh giấy tờ** (CCCD mặt trước **đã che trên máy**, chỉ còn ảnh chân dung, họ tên, ngày sinh, 4 số cuối số CCCD; ảnh chân dung; chứng chỉ HSK) — xử lý như **dữ liệu cá nhân nhạy cảm**, chỉ khi bạn đồng ý riêng. Mọi thông tin hồ sơ được **mã hóa ngay trên máy** bạn, máy chủ (có thể ở nước ngoài) chỉ giữ bản mã hóa không đọc được; chỉ người bán giải mã trên máy của mình để duyệt; ảnh tự xóa 3 ngày sau khi có quyết định (mục 3, Hồ sơ gia sư). Người không đăng ký làm gia sư không bị hỏi những thông tin này.
- **Dữ liệu học nằm trên máy của bạn**, không gửi lên máy chủ.
- **Trước lượt AI đầu tiên, app hỏi bạn có đồng ý** gửi câu hỏi tới AI qua máy chủ trung gian. Chưa đồng ý thì app không gửi câu hỏi hay dữ liệu học nào.
- Riêng khi bạn **mở mục Gói của bạn, nhập mã hoặc mua gói**, app hỏi máy chủ thông tin gói: gửi mã cài đặt, mã gói (nếu có) và phiên bản app; máy chủ nhận được địa chỉ IP của bạn (mục 5).
- Máy chủ chỉ lưu những gì cần để tính lượt AI và bật gói: mã cài đặt ngẫu nhiên, bộ đếm lượt dùng, và khi có gói trả phí thì mã băm của mã gói cùng thông tin đơn hàng (mã đơn, số tiền, thời điểm, bản điều khoản bạn đã đồng ý khi mua).
- Câu hỏi gửi AI đi qua máy chủ (Cloudflare) tới **nhà cung cấp dịch vụ AI bên thứ ba** (máy chủ có thể ở **nước ngoài**) để được trả lời; máy chủ **không lưu** nội dung câu hỏi. Với gói Miễn phí, có nhà cung cấp có thể lưu nội dung để cải thiện dịch vụ.
- **Luyện nói** (gói Pro+): khi bạn dùng micro, **âm thanh bạn nói** được gửi tới máy chủ của app (Cloudflare Workers AI) để chuyển thành chữ rồi bỏ, **không lưu lại** (mục 4). App hỏi đồng ý một lần trước khi gửi; không đồng ý thì gõ chữ.
- Không bán dữ liệu, không quảng cáo, không theo dõi hành vi để tiếp thị.
- Bạn có quyền xem, sửa, xóa, rút lại đồng ý và phản đối việc xử lý dữ liệu (mục 11).

## 1. Ai chịu trách nhiệm về dữ liệu

**Ngô Văn Tiến Dũng**, một cá nhân tại Việt Nam (gọi là "người bán"), là bên kiểm soát và xử lý dữ liệu nêu trong chính sách này. Cách liên hệ: mục 14.

Căn cứ xử lý:

- **Sự đồng ý của bạn**: gửi câu hỏi tới AI (hộp thoại trước lượt AI đầu tiên, mục 4), gửi báo lỗi, góp ý (mục 6), và hồ sơ gia sư khi bạn tự đăng ký làm gia sư (ba sự đồng ý riêng, mục 3, Hồ sơ gia sư).
- **Thực hiện thỏa thuận với bạn**: tính hạn mức lượt AI, bật gói và giữ gói hoạt động trên các máy của bạn (Điều khoản sử dụng).
- **Nghĩa vụ pháp luật**: giữ chứng từ giao dịch theo pháp luật kế toán, thuế (mục 8).
- **Bảo vệ dịch vụ**: đếm theo địa chỉ IP trong ngày để chống lạm dụng gói miễn phí và dò mã (mục 3).

## 2. Dữ liệu nằm trên máy của bạn

- Sổ từ, lịch sử ôn, lịch sử hỏi đáp, bài đọc, tiến độ giáo trình, cài đặt, lựa chọn đồng ý dùng AI, nhật ký lỗi của app.
- Trên Windows: thư mục `%USERPROFILE%\.spchina`. Trên điện thoại: bộ nhớ riêng của app.
- Mã gói (kể cả Key Pro+, tức mã gói Pro+): trên Windows nằm trong kho mật khẩu của hệ điều hành (máy không có kho mật khẩu thì nằm trong thư mục dữ liệu ở trên); trên điện thoại nằm trong bộ nhớ riêng của app.
- **Mã hồ sơ gia sư** (chỉ khi bạn đăng ký làm gia sư): mã bí mật app tạo ra để chỉ máy của bạn xem, sửa, rút được hồ sơ; nằm trong kho mật khẩu của Windows hoặc bộ nhớ bảo mật của Android, không nằm trong bản sao lưu. Mất mã (gỡ app, đổi máy) thì liên hệ người bán để xóa hồ sơ cũ rồi đăng ký lại.
- **Mã cài đặt**: một chuỗi ngẫu nhiên app tạo ra khi lần đầu cần gọi máy chủ trung gian (dùng AI, mở mục Gói của bạn hoặc gửi góp ý), không chứa thông tin về bạn hay về thiết bị. Trên Windows nó nằm trong file `install_id` ở thư mục dữ liệu trên.
- **Bản sao lưu dữ liệu học** (Cài đặt → Sao lưu dữ liệu học) là file bạn tự tải về và tự giữ; app không gửi file này đi đâu. File chứa sổ từ, lịch sử ôn, tiến độ giáo trình (không có lịch sử hỏi đáp, mã gói, mã cài đặt hay mã hồ sơ gia sư): cất nơi riêng tư như mọi tài liệu cá nhân.
- Người bán không đọc được các dữ liệu này. Chúng không được gửi lên máy chủ, trừ những phần nêu ở mục 4 và mục 6.

## 3. Máy chủ trung gian lưu gì

Máy chủ trung gian của người bán chạy trên Cloudflare và lưu:

| Dữ liệu | Để làm gì | Lưu bao lâu |
|---|---|---|
| Mã cài đặt và ngày đầu tiên AI trả lời thành công trên máy đó | Tính 14 ngày dùng thử | Trong thời gian dịch vụ còn hoạt động |
| Bộ đếm lượt dùng AI trong ngày (theo máy hoặc theo gói) | Tính hạn mức ngày | Xóa khi sang ngày mới (7 giờ sáng) |
| Địa chỉ IP, chỉ nằm trong bộ đếm | Chống lạm dụng gói miễn phí, chặn dò mã | Xóa khi sang ngày mới |
| Mức dùng trong tháng và tổng số lượt AI của gói trả phí | Tính hạn mức tháng; đối soát khi có sự cố về gói hoặc thanh toán | Cùng thông tin gói |
| Mã băm (hash) của mã gói, gói, ngày hết hạn, danh sách mã cài đặt đang dùng mã kèm ngày dùng gần nhất của từng máy | Bật gói, giới hạn 3 máy, tự gỡ máy không dùng quá 30 ngày | Như chứng từ giao dịch (mục 8) |
| Đơn hàng: mã đơn `DH…`, gói, số tiền, thời điểm lập đơn và thanh toán, mã cài đặt của máy lập đơn, **ngày hiệu lực của bản Điều khoản sử dụng và Chính sách hoàn tiền bạn đã tick đồng ý** khi lập đơn | Bật gói, đối soát thanh toán, xử lý sự cố thanh toán; chứng từ rằng bạn đã đồng ý điều khoản (gồm chính sách không hoàn tiền) khi mua | Đơn chưa thanh toán: 180 ngày; đơn đã thanh toán: mục 8 |
| Giao dịch tiền về: mã giao dịch của SePay, số tiền, thời điểm, mã đơn tìm thấy trong nội dung chuyển khoản (khoản tiền không có mã đơn và không đúng giá gói nào thì bị bỏ qua, không lưu) | Khớp tiền với đơn, tránh xử lý trùng, xử lý chuyển nhầm, thừa, trùng | Mục 8; khoản không có mã đơn mà chưa được đối soát: 90 ngày |
| Sổ doanh thu: ngày, kênh, gói, số tiền, mã đơn (kể cả khoản trả lại tiền thừa, tiền chuyển nhầm, nếu có) | Nghĩa vụ kế toán, thuế | Mục 8 |
| Thống kê tổng theo ngày (số lượt, số lần bị chặn, doanh thu theo gói), không gắn với máy nào | Theo dõi chi phí | 400 ngày |
| Báo lỗi, góp ý (mục 6) | Sửa lỗi, cải thiện app | Mục 6 |
| **Mời bạn** (chỉ khi bạn lấy link mời hoặc nhập mã mời): mã mời của máy, mã cài đặt của máy đã nhập mã mời, số lượt AI máy đó đã dùng sau khi nhập (tối đa 3), số lượt thưởng còn lại và hạn dùng | Xác minh lời mời thành công, cộng lượt AI thưởng, giới hạn 10 lần thưởng mỗi tháng | Trong thời gian dịch vụ còn hoạt động; lượt thưởng hết hạn sau 30 ngày |
| Mã băm của địa chỉ IP (không lưu IP gốc) khi bấm link mời, lấy hoặc nhập mã mời | Xác minh link mời được bấm thật trên cùng mạng với máy nhập mã, chặn tự mời mình | Lượt bấm link: 7 ngày; dấu thưởng theo mạng: 2 ngày |
| **Đếm người học hôm nay**: mã cài đặt và ngày, gửi một lần mỗi ngày khi bạn làm bài tập (máy có kết nối) | Hiện "Hôm nay N người đã học" (chỉ con số tổng, không gắn với ai) | 2 ngày |
| **Đua top** (chỉ khi bạn bật "Tham gia" và đặt biệt danh): biệt danh, XP theo ngày, theo tuần và tổng XP, danh hiệu, số tuần đứng đầu, lượt AI thưởng | Hiện bảng xếp hạng: **người dùng khác nhìn thấy biệt danh và XP tuần của bạn** (không thấy mã cài đặt hay thông tin nào khác) | Biệt danh: tới khi bạn rời bảng; XP: tuần này và tuần trước; XP theo ngày: 2 ngày |
| **Hồ sơ gia sư** (chỉ khi bạn tự đăng ký làm gia sư): kết quả bài kiểm tra (điểm, số lần làm, thời điểm), mã cài đặt của máy nộp hồ sơ, dấu nhận mã hồ sơ gia sư | Xác nhận trình độ trước khi nộp, giới hạn 2 lần kiểm tra trong 30 ngày | Khi hồ sơ còn hiệu lực; xóa trong vòng 24 giờ khi bạn rút hồ sơ |
| **Hồ sơ gia sư — thông tin khai**: họ tên (như trên CCCD), cấp dạy, số và cấp chứng chỉ HSK, ghi chú bằng cấp, giá tham khảo, cách liên hệ (Zalo, email hoặc điện thoại), link video dạy thử, lời giới thiệu | Xét duyệt hồ sơ (**mã hóa đầu-cuối**, máy chủ không đọc được); khi app có phần giới thiệu gia sư, hiển thị hồ sơ đã duyệt cho người học (báo trước, không gồm giấy tờ) | Khi hồ sơ còn hiệu lực; xóa trong vòng 24 giờ khi bạn rút hồ sơ |
| **Hồ sơ gia sư — ảnh giấy tờ** (xử lý như **dữ liệu cá nhân nhạy cảm**): ảnh CCCD mặt trước **đã che vĩnh viễn trên máy** (chỉ còn ảnh chân dung, họ tên, ngày sinh, 4 số cuối số CCCD; ảnh gốc không rời máy), **ảnh chân dung** (chỉ khuôn mặt), chứng chỉ HSK, bằng cấp (nếu gửi; bạn tự che thông tin không cần); **mã hóa đầu-cuối** trên máy bạn, máy chủ không đọc được | Chỉ để xác minh danh tính, tuổi (đủ 18) và trình độ khi duyệt, chống giả mạo | **3 ngày sau khi người bán ra quyết định**; chờ quá **14 ngày** chưa duyệt thì xóa (bạn gửi lại); **trong vòng 24 giờ** khi bạn rút hồ sơ |
| **Hồ sơ gia sư — thông tin tối thiểu**: họ tên, năm sinh, **4 số cuối** số CCCD, cấp HSK đã xác minh, các quyết định và lý do, trạng thái (kể cả Tạm khóa) kèm mã băm của máy, **bằng chứng đồng ý** (phiên bản văn bản, thời điểm); họ tên, năm sinh, 4 số cuối chỉ lưu dạng mã hóa đầu-cuối. **Không bao giờ thu thập** số CCCD đầy đủ, địa chỉ, giới tính | Giải quyết khiếu nại, ngăn đăng ký lại sau khi bị khóa, chứng minh việc đồng ý | Khi hồ sơ còn hiệu lực **và 12 tháng sau đó** |

Máy chủ **không lưu**: tên, số điện thoại, email (trừ hồ sơ gia sư bạn tự nộp, xem dưới), số tài khoản và tên người chuyển tiền, nội dung chuyển khoản gốc, thông tin thẻ, nội dung câu hỏi và câu trả lời AI (trừ phần bạn tự gửi kèm báo lỗi, mục 6), dữ liệu học của bạn. Mã gói chỉ được lưu dưới dạng mã băm, người khác không dựng lại được mã gốc từ đó.

Người bán không dùng các dữ liệu trên để lập hồ sơ về bạn và không ra quyết định tự động gây ảnh hưởng pháp lý với bạn; việc chặn khi vượt hạn mức hay có dấu hiệu lạm dụng chỉ dựa trên bộ đếm nêu trên và bạn có thể yêu cầu người bán xem lại (mục 14).

### Hồ sơ gia sư và giấy tờ tùy thân

Phần này **chỉ áp dụng cho người tự chọn đăng ký làm gia sư** (mục Đăng ký làm gia sư, chi tiết trong Tài liệu → Điều khoản gia sư). Người chỉ học không bị hỏi những thông tin này.

- **Dữ liệu cá nhân nhạy cảm**: trước khi gửi, app **cắt và che vĩnh viễn ngay trên máy** ảnh CCCD mặt trước, chỉ để lộ ảnh chân dung, họ tên, ngày sinh và 4 số cuối số CCCD (mã QR, các số còn lại, giới tính, quốc tịch, quê quán, nơi thường trú, ngày hết hạn bị che; **ảnh gốc không bao giờ rời khỏi máy**). Ảnh chân dung chỉ có khuôn mặt. Với chứng chỉ HSK, bằng cấp, bạn tự che thông tin không cần ở bước xem trước. Dù đã thu gọn, ảnh khuôn mặt, họ tên, ngày sinh vẫn là dữ liệu cá nhân và ảnh khuôn mặt dùng để so danh tính, nên **toàn bộ bộ giấy tờ được xử lý như dữ liệu cá nhân nhạy cảm**, với mức bảo vệ cao nhất trong app. App không nhận ảnh mặt sau CCCD (có vân tay) và không đọc mã QR.
- **Căn cứ: sự đồng ý** theo Luật Bảo vệ dữ liệu cá nhân (số 91/2025/QH15). Trước khi nộp, bạn tick **ba ô đồng ý riêng**: (1) Điều khoản gia sư; (2) xử lý dữ liệu cá nhân nhạy cảm; (3) lưu bản mã hóa của hồ sơ trên Cloudflare (máy chủ có thể ở nước ngoài). Thiếu ô nào thì không nộp được và app không gửi giấy tờ nào đi. Máy chủ ghi **phiên bản văn bản và thời điểm** của từng sự đồng ý làm bằng chứng. Im lặng hay không phản hồi không được coi là đồng ý.
- **Mục đích duy nhất**: xác minh bạn là ai, đủ 18 tuổi và có trình độ như khai, để duyệt hồ sơ gia sư và chống giả mạo. Không dùng cho việc khác, không chuyển cho người học hay bên thứ ba (trừ cơ quan nhà nước có thẩm quyền khi pháp luật yêu cầu). **Số CCCD đầy đủ, địa chỉ, giới tính không bao giờ được thu thập.**
- **Chỉ ảnh JPG/PNG, xử lý lại trên máy**: ngoài việc che ở trên, app mã hóa lại ảnh ngay trên máy của bạn, bỏ siêu dữ liệu EXIF (vị trí chụp, loại máy, thời điểm chụp…) và thu nhỏ về tối đa 2000 px mỗi chiều.
- **Mã hóa đầu-cuối**: mọi thông tin cá nhân của hồ sơ gia sư (ảnh giấy tờ và cả phần chữ: họ tên, năm sinh, cách liên hệ, số chứng chỉ, bằng cấp, giới thiệu, link video, giá, 4 số cuối CCCD) được **mã hóa ngay trên máy của bạn trước khi gửi**, bằng khóa công khai của người bán gắn sẵn trong app (ECDH P-256 + AES-256-GCM). Máy chủ trung gian và Cloudflare **chỉ lưu bản mã hóa và không đọc được**; không có khóa giải mã nào nằm trên máy chủ. Chỉ công cụ duyệt chạy trên máy tính của người bán **tại Việt Nam** giải mã được, bằng khóa riêng có mật khẩu bảo vệ và cất ngoại tuyến. Kết nối dùng thêm **HTTPS**; máy chủ không ghi nhật ký nội dung hồ sơ.
- **Nơi lưu, chuyển ra nước ngoài**: bản mã hóa của hồ sơ nằm trên hạ tầng của **Cloudflare** (công ty Hoa Kỳ, **bên lưu trữ** cho người bán); máy chủ **có thể ở ngoài Việt Nam**. Thứ được chuyển ra nước ngoài **chỉ là bản mã hóa mà bên lưu trữ không đọc được**; việc lưu này chỉ làm khi bạn đã tick ô đồng ý (3). Dữ liệu chỉ được giải mã trên máy của người bán tại Việt Nam.
- **Chỉ người bán truy cập**: chỉ người bán giữ khóa giải mã và tự tay xem hồ sơ bằng công cụ duyệt chạy trên máy của mình. Ảnh chân dung được so với ảnh trên CCCD **bằng mắt**, không dùng công nghệ nhận diện khuôn mặt hay dữ liệu sinh trắc học; không có quyết định tự động.
- **Thời gian lưu**: ảnh giấy tờ **tự xóa 3 ngày sau khi người bán ra quyết định** (Đã duyệt, Cần bổ sung hoặc Từ chối); hồ sơ **chưa được duyệt sau 14 ngày** thì ảnh bị xóa và bạn được mời gửi lại; rút hồ sơ thì ảnh và thông tin khai bị xóa **trong vòng 24 giờ** (việc xóa khỏi kho lưu trữ không tức thời; bản sao sót lại, nếu có, vẫn chỉ là bản mã hóa). **Thông tin tối thiểu** (bảng trên) giữ khi hồ sơ còn hiệu lực và 12 tháng sau đó; các trường cá nhân trong đó (họ tên, năm sinh, 4 số cuối CCCD) cũng chỉ lưu ở dạng mã hóa đầu-cuối.
- **Quyền của bạn**: **xem / tải** dữ liệu bằng nút **Xem / tải dữ liệu của tôi** trong mục Đăng ký làm gia sư (các trường cá nhân đã mã hóa đầu-cuối nên máy chủ không trả lại được nội dung; muốn **bản sao đầy đủ**, gửi email (mục 14), người bán giải mã và gửi cho bạn trong **72 giờ**); **sửa** trong app khi hồ sơ chưa nộp hoặc ở trạng thái Cần bổ sung, hoặc qua email (mục 14); **xóa** và **rút lại đồng ý** bằng nút **Rút hồ sơ**; mất mã hồ sơ gia sư (gỡ app, đổi máy) thì liên hệ kèm họ tên đã khai và 4 số cuối CCCD. Người bán trả lời trong **72 giờ**. Việc rút lại không ảnh hưởng tới việc xử lý đã làm trước đó. Khiếu nại: với người bán, hoặc Bộ Công an (Cục An ninh mạng và phòng, chống tội phạm sử dụng công nghệ cao, A05).
- **Sự cố**: nếu xảy ra sự cố lộ dữ liệu hồ sơ gia sư, người bán thông báo cho cơ quan có thẩm quyền trong **72 giờ** (như mục 10) và cho người bị ảnh hưởng qua liên hệ trong hồ sơ, kèm những gì đã xảy ra và việc bạn nên làm.
- **Người phụ trách bảo vệ dữ liệu** của hồ sơ gia sư: Ngô Văn Tiến Dũng (liên hệ: mục 14).
- Hồ sơ gia sư **không bao giờ** được gửi tới nhà cung cấp dịch vụ AI.

## 4. Câu hỏi gửi AI

- **Đồng ý trước**: lần đầu bạn dùng một tính năng AI (Hỏi đáp, tra từ, Đào câu, Bài đọc, Luyện nói, dịch nghĩa, trợ lý hỏi AI), app hiện hộp thoại hỏi bạn có đồng ý gửi câu hỏi tới AI qua máy chủ trung gian hay không. Lựa chọn được lưu trên máy bạn. Chưa đồng ý thì app **không gửi câu hỏi nào** lên máy chủ AI (riêng thông tin gói khi bạn mở mục Gói của bạn: mục 5); các phần học không dùng AI vẫn chạy bình thường.
- Khi bạn dùng AI (ở mọi gói, kể cả Pro+), app gửi tới máy chủ trung gian: nội dung cần xử lý (câu hỏi, câu dán vào Đào câu, từ cần tra hoặc dịch), các lượt trước trong cùng phiên hỏi đáp, trình độ bạn chọn, và khi tạo bài đọc thì một số từ trong sổ từ của bạn. Kèm theo là mã cài đặt, mã gói (nếu có) và phiên bản app để tính hạn mức.
- Máy chủ chuyển nội dung đó tới **nhà cung cấp dịch vụ AI bên thứ ba** (máy chủ có thể ở nước ngoài) để tạo câu trả lời, rồi trả về app. Gói **Miễn phí** có thể dùng một nhà cung cấp khác với các gói còn lại; gói **Pro+** chạy luồng riêng của máy chủ trung gian (hiện dùng cùng mô hình AI với Pro; nếu luồng này chuyển sang mô hình hoặc nhà cung cấp khác, người bán cập nhật chính sách này và báo trong app trước khi áp dụng); khi nhà cung cấp đó quá tải hoặc lỗi, máy chủ tự chuyển sang nhà cung cấp dự phòng. Mã cài đặt và mã gói **không** được gửi tới nhà cung cấp AI.
- Máy chủ trung gian **không lưu** nội dung câu hỏi và câu trả lời (trừ phần bạn tự gửi kèm báo lỗi, mục 6); chỉ đếm số lượt và độ dài để tính hạn mức.
- **Giọng nói (Luyện nói, gói Pro+)**: lần đầu bấm nút micro, app hỏi bạn có đồng ý gửi âm thanh đi chuyển thành chữ hay không (lựa chọn lưu trên máy bạn; không đồng ý thì gõ chữ, lần sau bấm micro app hỏi lại). Đồng ý thì mỗi lần bạn giữ nút micro, đoạn ghi âm (tối đa 30 giây) được gửi tới máy chủ trung gian, chuyển thành chữ bằng **Cloudflare Workers AI** (dịch vụ nhận dạng giọng nói chạy trong hạ tầng Cloudflare) rồi trả chữ về app. Âm thanh và chữ nhận dạng được **không được lưu** trên máy chủ hay trên máy bạn, không ghi vào nhật ký, không dùng để huấn luyện AI; máy chủ chỉ đếm số lần để tính hạn mức. App không phát lại hay giữ bản ghi. Chữ bạn bấm Gửi được xử lý như câu hỏi gửi AI ở trên (lịch sử phiên luyện nói nằm trên máy bạn).
- Nhà cung cấp AI xử lý nội dung theo chính sách riêng của họ, người bán không kiểm soát việc đó. **Với gói Miễn phí**, có nhà cung cấp có thể lưu và dùng nội dung câu hỏi để cải thiện dịch vụ; muốn tránh, dùng gói Dùng thử/Pro/Pro+. Vì vậy **đừng nhập thông tin cá nhân** (tên thật, số điện thoại, địa chỉ, số giấy tờ, thông tin sức khỏe…) vào câu hỏi hay bài viết nhờ chữa.

## 5. Chuyển dữ liệu ra nước ngoài

Dịch vụ AI cần chuyển một phần dữ liệu ra khỏi Việt Nam:

| Bên nhận | Ở đâu | Dữ liệu | Để làm gì |
|---|---|---|---|
| **Cloudflare** (máy chủ trung gian) | Mạng máy chủ toàn cầu của Cloudflare (công ty Hoa Kỳ) | Mọi dữ liệu ở mục 3 và nội dung câu hỏi khi đang chuyển tiếp; địa chỉ IP | Chạy máy chủ trung gian, tính hạn mức, bật gói |
| **Cloudflare** (lưu hồ sơ gia sư, chỉ khi bạn đăng ký làm gia sư) | Như trên | **Chỉ bản mã hóa** đầu-cuối của hồ sơ gia sư (ảnh giấy tờ và thông tin cá nhân), mà Cloudflare không đọc được; trạng thái hồ sơ, điểm kiểm tra (mục 3, Hồ sơ gia sư) | Lưu hồ sơ để người bán tải về duyệt trên máy tại Việt Nam |
| **Cloudflare Workers AI** (chỉ khi bạn dùng micro ở Luyện nói) | Mạng máy chủ của Cloudflare | Đoạn ghi âm giọng nói (tối đa 30 giây) | Chuyển giọng nói thành chữ; không lưu |
| **Nhà cung cấp dịch vụ AI bên thứ ba** | Máy chủ của nhà cung cấp, có thể ở nước ngoài | Nội dung cần AI xử lý (mục 4) | Tạo câu trả lời; với gói Miễn phí, có nhà cung cấp có thể lưu để cải thiện dịch vụ |

- Bạn đồng ý với việc chuyển này trong hộp thoại trước lượt AI đầu tiên (mục 4); riêng hồ sơ gia sư, trong ô đồng ý riêng về lưu và chuyển dữ liệu ra nước ngoài khi nộp hồ sơ (mục 3, Hồ sơ gia sư).
- Ngoại lệ: khi bạn tự mở mục **Gói của bạn**, nhập mã hoặc mua gói, app gửi tới Cloudflare mã cài đặt, mã gói (nếu có) và phiên bản app (kèm địa chỉ IP của kết nối) để lấy thông tin gói, thông báo của người bán và bật gói bạn yêu cầu. Việc này không kèm câu hỏi hay dữ liệu học. Đã đồng ý dùng AI thì app cũng hỏi thông tin này khi mở app để hiện thông báo mới.
- Người bán chỉ chuyển phần dữ liệu cần cho từng mục đích trên, không chuyển tên hay thông tin liên lạc của bạn (máy chủ không có các thông tin này), trừ hồ sơ gia sư bạn tự nộp, lưu trên Cloudflare như bảng trên. Người bán thực hiện các thủ tục về chuyển dữ liệu ra nước ngoài theo pháp luật Việt Nam khi thuộc diện phải thực hiện.

## 6. Báo lỗi, góp ý

- Khi bạn gửi từ Trợ lý → Báo lỗi, góp ý, máy chủ lưu: loại phản hồi, nội dung bạn gõ (app và máy chủ tự che những chuỗi giống key và mã gói `SPC-…`), thời điểm, phiên bản app, tab đang mở, trình độ và mã cài đặt.
- Khi bạn bấm **Báo câu trả lời này** dưới một câu trả lời AI, đoạn đầu câu trả lời đó (tối đa 600 ký tự) được điền sẵn vào nội dung phản hồi; bạn xem, sửa hoặc xóa trước khi gửi. Nếu gửi, đoạn này được lưu cùng phản hồi như nội dung bạn gõ.
- Không lưu địa chỉ IP vào phản hồi (IP chỉ dùng để đếm số phản hồi trong ngày, xóa khi sang ngày mới).
- Máy chủ giữ tối đa 5.000 phản hồi mới nhất; người bán xóa phản hồi sau khi xử lý xong.
- Đừng ghi thông tin cá nhân vào phản hồi.

## 7. Thanh toán và thư hỗ trợ

- Khi bạn tick đồng ý điều khoản trong hộp thoại mua và bấm Tạo đơn, app gửi lên máy chủ ngày hiệu lực của bản điều khoản đó; máy chủ lưu vào đơn hàng (mục 3) làm chứng từ, giữ cùng thời hạn với đơn hàng (mục 8). Lựa chọn này không được lưu riêng trên máy của bạn.
- Bạn chuyển khoản từ ngân hàng của bạn vào tài khoản ngân hàng của người bán. Như mọi giao dịch chuyển khoản, **sao kê ngân hàng của người bán** có tên và số tài khoản người chuyển, số tiền và nội dung chuyển khoản. **SePay** (dịch vụ báo tiền về mà người bán dùng) đọc các giao dịch vào tài khoản của người bán theo chính sách của SePay.
- Máy chủ trung gian nhận thông báo tiền về từ SePay nhưng **chỉ lưu** mã giao dịch, số tiền, thời điểm và mã đơn tìm thấy trong nội dung chuyển khoản. Nội dung chuyển khoản gốc và mọi thông tin khác về người chuyển bị bỏ đi, không lưu lại.
- Khi bạn gửi email hỗ trợ (gói không bật được, chuyển nhầm, thừa hoặc trùng, đối soát thanh toán…): địa chỉ email, nội dung thư và ảnh biên lai bạn gửi nằm trong hộp thư của người bán. Khoản tiền thừa hoặc chuyển nhầm (nếu bạn yêu cầu trả lại theo Chính sách hoàn tiền) được trả về đúng tài khoản đã chuyển theo sao kê, nên bạn không cần gửi số tài khoản.
- Người bán chỉ dùng các thông tin này để đối soát, bật gói, xử lý sự cố thanh toán, hỗ trợ bạn và làm chứng từ kế toán, thuế.

## 8. Thời gian lưu

- Bộ đếm lượt trong ngày và địa chỉ IP: tới hết ngày (7 giờ sáng hôm sau).
- Đơn chưa thanh toán: 180 ngày.
- Thống kê tổng theo ngày: 400 ngày.
- Báo lỗi, góp ý: tới khi xử lý xong, tối đa 5.000 phản hồi mới nhất.
- **Chứng từ giao dịch** (đơn đã thanh toán, giao dịch tiền về, sổ doanh thu, thông tin gói, và thư hỗ trợ liên quan tới thanh toán): **ít nhất 5 năm** kể từ giao dịch, để phục vụ nghĩa vụ kế toán, thuế (lâu hơn nếu pháp luật yêu cầu); sau đó xóa.
- Mã cài đặt và ngày bắt đầu dùng thử: trong thời gian dịch vụ còn hoạt động.
- Mời bạn: mã mời và trạng thái lời mời trong thời gian dịch vụ còn hoạt động; lượt bấm link (mã băm IP) 7 ngày; lượt thưởng 30 ngày.
- Đua top: biệt danh, tổng XP, danh hiệu tới khi bạn bấm "Rời bảng xếp hạng" hoặc yêu cầu xóa; XP tuần này và tuần trước, sau đó tự xóa.
- Đếm người học hôm nay: 2 ngày.
- Hồ sơ gia sư: ảnh giấy tờ 3 ngày sau khi có quyết định, tối đa 14 ngày nếu chưa được duyệt; rút hồ sơ thì ảnh và thông tin khai xóa trong vòng 24 giờ; thông tin tối thiểu (họ tên, năm sinh, 4 số cuối CCCD, cấp HSK đã xác minh, quyết định và lý do, bằng chứng đồng ý) khi hồ sơ còn hiệu lực và 12 tháng sau đó.
- Thư hỗ trợ không liên quan tới thanh toán: xóa sau khi xử lý xong, chậm nhất 12 tháng.
- Khi dịch vụ ngừng hoạt động, người bán xóa dữ liệu trên máy chủ, trừ chứng từ giao dịch còn trong thời hạn phải giữ.

## 9. Chia sẻ dữ liệu

Người bán không bán, không cho thuê dữ liệu và không dùng dữ liệu để quảng cáo. Dữ liệu chỉ được chuyển tới:

- **Nhà cung cấp dịch vụ AI bên thứ ba** (máy chủ có thể ở nước ngoài; với gói Miễn phí, có nhà cung cấp có thể lưu nội dung để cải thiện dịch vụ): nội dung cần AI xử lý (mục 4, mục 5).
- **Cloudflare**: nơi chạy máy chủ trung gian; có thể ghi nhận thông tin kỹ thuật như địa chỉ IP theo chính sách của Cloudflare.
- **SePay và ngân hàng**: thông tin giao dịch chuyển khoản (mục 7).
- **GitHub** (bản Windows): app kiểm tra và tải bản cập nhật từ GitHub; GitHub nhận địa chỉ IP theo chính sách của GitHub.
- **Cơ quan nhà nước có thẩm quyền**: khi pháp luật yêu cầu.

## 10. Bảo mật

- Mọi kết nối tới máy chủ dùng HTTPS. Mã gói chỉ lưu dạng mã băm; máy chủ không ghi nhật ký nội dung câu hỏi.
- Hồ sơ gia sư (ảnh giấy tờ và thông tin cá nhân) được mã hóa đầu-cuối trên máy của bạn trước khi gửi; máy chủ chỉ giữ bản mã hóa, chỉ người bán giải mã được trên máy của mình (mục 3, Hồ sơ gia sư).
- Chỉ người bán truy cập được dữ liệu quản trị, bằng mật khẩu riêng.
- Không hệ thống nào an toàn tuyệt đối. Nếu xảy ra sự cố lộ dữ liệu, người bán sẽ thông báo cho cơ quan có thẩm quyền về bảo vệ dữ liệu cá nhân trong thời hạn pháp luật quy định (hiện là 72 giờ kể từ khi phát hiện) và thông báo cho bạn bằng thông báo trong mục **Gói của bạn** và khi mở app.

## 11. Quyền của bạn

Theo pháp luật Việt Nam về bảo vệ dữ liệu cá nhân, bạn có quyền: **được biết** việc xử lý (chính sách này); **đồng ý hoặc không đồng ý**; **rút lại sự đồng ý**; **xem** (truy cập) và **yêu cầu cung cấp** dữ liệu về bạn; **chỉnh sửa**; **yêu cầu xóa**; **hạn chế** hoặc **phản đối** việc xử lý; **khiếu nại, tố cáo, khởi kiện** và **yêu cầu bồi thường** theo quy định. Cách thực hiện:

- **Dữ liệu trên máy của bạn**: bạn tự xem, sửa và xóa. Trên Windows: tắt app rồi xóa thư mục `%USERPROFILE%\.spchina`; bấm Gói của bạn → Gỡ máy này để xóa mã gói (kể cả Key Pro+) khỏi máy. Trên điện thoại: bấm Gỡ máy này, rồi xóa dữ liệu app trong cài đặt của điện thoại hoặc gỡ app.
- **Hồ sơ gia sư**: xem / tải bằng nút **Xem / tải dữ liệu của tôi** (bản sao đầy đủ phần đã mã hóa: gửi email, người bán gửi lại trong 72 giờ); sửa khi hồ sơ chưa nộp hoặc ở trạng thái Cần bổ sung (hoặc qua email); **rút hồ sơ** bất kỳ lúc nào trong mục Đăng ký làm gia sư để xóa ảnh giấy tờ và thông tin khai trong vòng 24 giờ (đồng thời rút lại sự đồng ý; thông tin tối thiểu giữ 12 tháng, mục 3). Mất mã hồ sơ gia sư (gỡ app, đổi máy): liên hệ người bán (mục 14) kèm họ tên đã khai và 4 số cuối CCCD.
- **Rút lại đồng ý cho việc gửi câu hỏi tới AI**: ngừng dùng các tính năng AI, hoặc xóa dữ liệu app để app hỏi lại từ đầu. Việc rút lại không ảnh hưởng tới những lượt đã xử lý trước đó. Các phần học không dùng AI không gửi nội dung học của bạn lên máy chủ.
- **Phản đối hoặc hạn chế xử lý**: người bán không dùng dữ liệu để tiếp thị hay lập hồ sơ, nên ngoài những gì cần cho dịch vụ không có việc xử lý nào khác. Không muốn máy chủ đếm lượt hay giữ gói cho máy của bạn nữa: bấm Gỡ máy này và ngừng dùng AI; muốn xóa cả dữ liệu đã lưu thì gửi yêu cầu như dưới đây.
- **Dữ liệu trên máy chủ**: máy chủ không biết bạn là ai, nên cần thông tin để tìm đúng dữ liệu. Gửi email tới **gausgear.nd@gmail.com** kèm **mã đơn `DH…`** (có trong nội dung chuyển khoản) hoặc, nếu chưa mua gói, mã cài đặt của máy (file `install_id` trong thư mục dữ liệu, mục 2) để yêu cầu xem, sửa hoặc xóa. Người bán xóa những gì không bắt buộc phải giữ (ví dụ danh sách máy đang dùng mã, mức dùng, ngày bắt đầu dùng thử); chứng từ giao dịch được giữ tới hết thời hạn ở mục 8. Sau khi xóa, gói còn hạn vẫn giữ nguyên nhưng mọi máy phải nhập lại mã gói.
- **Thư hỗ trợ**: muốn xóa thư và thông tin bạn đã gửi, ghi rõ trong email; thư liên quan tới thanh toán được giữ tới hết thời hạn ở mục 8.
- Người bán trả lời trong **72 giờ** kể từ khi nhận đủ thông tin để tìm đúng dữ liệu (hoặc theo thời hạn khác nếu pháp luật quy định), miễn phí. Yêu cầu không tìm được dữ liệu tương ứng (không có mã đơn, mã cài đặt) thì người bán trả lời là không có dữ liệu để xử lý.
- Bạn có thể khiếu nại với người bán (mục 14), hoặc với cơ quan nhà nước có thẩm quyền về bảo vệ dữ liệu cá nhân (Bộ Công an).

## 12. Trẻ em

- App không dành cho trẻ em dưới 16 tuổi tự mình dùng tính năng AI hay mua gói. Nếu bạn dưới 16 tuổi, chỉ dùng tính năng AI và gói trả phí khi **cha mẹ hoặc người giám hộ đã đồng ý** và giám sát; người mua gói cho trẻ em phải là cha mẹ hoặc người giám hộ.
- App không yêu cầu thông tin định danh nên người bán không xác minh được tuổi. Nếu bạn là cha mẹ hoặc người giám hộ và biết trẻ dưới 16 tuổi đã dùng AI hoặc mua gói mà chưa được bạn đồng ý, hãy liên hệ người bán (mục 14): người bán xóa dữ liệu liên quan trên máy chủ theo mục 11 (chứng từ giao dịch giữ theo mục 8).
- Chỉ người **đủ 18 tuổi** được đăng ký làm gia sư; hồ sơ của người chưa đủ 18 tuổi bị từ chối và ảnh giấy tờ bị xóa theo mục 3 (Hồ sơ gia sư).
- Các phần học không dùng AI (giáo trình, ôn thẻ, quiz, tập viết, tài liệu) không gửi dữ liệu lên máy chủ nên trẻ em dùng được mà không phát sinh dữ liệu cá nhân nào ở phía người bán.

## 13. Thay đổi chính sách

Người bán có thể cập nhật chính sách này. Ngày hiệu lực luôn ghi ở đầu văn bản; thay đổi quan trọng (ví dụ đổi nhà cung cấp AI, lưu thêm loại dữ liệu mới, đổi mục đích xử lý) được báo **trước khi áp dụng** bằng thông báo trong mục **Gói của bạn** và khi mở app. Việc xử lý theo mục đích mới chỉ bắt đầu sau khi bạn đồng ý (với phần cần đồng ý) hoặc sau ngày hiệu lực của bản mới.

## 14. Liên hệ

- Người bán: Ngô Văn Tiến Dũng
- Email hỗ trợ: gausgear.nd@gmail.com (tiêu đề gợi ý: "Dữ liệu cá nhân DH…", thay bằng mã đơn của bạn)
- Thông tin người bán đầy đủ: Điều khoản sử dụng, mục 1.
