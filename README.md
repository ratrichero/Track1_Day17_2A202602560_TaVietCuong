# Track1_Day17 — Lab Problem Interview (Case A)

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202602560
- **Họ tên:** Tạ Việt Cường
- **Tên nhóm:** FinTech
- **Thành viên nhóm (3 người):**
  - Tạ Việt Cường
  - Nguyễn Văn Thăng
  - Nguyễn Anh Dũng
- **Case đã chọn:** Case A — AI Tutor: Diagnostic Refresher
- **Vai trò trong buổi lab:** Người phỏng vấn

> Repo cá nhân: `Track1_Day17_2A202602560_TaVietCuong/`
> Cấu trúc: `README.md` + `interview/notes.md` + `interview/recording.m4a`

---

## 2. Problem Hypothesis Brief (Kết quả Chặng 1 của nhóm)

### 2.1. Solution directive (nguyên văn Case A)

> Thêm nút "Tôi vẫn chưa hiểu" vào bài học. Khi học viên bấm nút, AI Tutor sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để:
> 1. Đặt 2–3 câu hỏi chẩn đoán ngắn.
> 2. Chọn một khái niệm nền để học viên ôn lại.
> 3. Tạo một phần giải thích ngắn.
> 4. Đưa học viên trở về bài đang học.

### 2.2. Capability trung tính (đã gỡ tên tính năng / giao diện / AI)

Giúp học viên đang bị mắc kẹt giữa bài xác định lỗ hổng kiến thức nền và ôn lại nhanh để tiếp tục bài đang học.

### 2.3. Change kỳ vọng (Solution → … → Outcome)

Solution → Học viên nhận ra mình mắc kẹt ở đâu → Ôn đúng khái niệm nền còn thiếu → Quay lại hiểu được bài hiện tại → Outcome: giảm bỏ dở, tăng tỉ lệ hoàn thành và mức độ hiểu bài.

- Đầu ra của nhóm làm (output): phần ôn lại đúng chỗ và đưa học viên về lại bài cũ.
- Kết quả cần hướng tới (outcome): học viên phải tự ôn và quay lại làm tiếp thì kết quả mới xảy ra. Nếu người học không thay đổi hành vi, solution không tạo ra kết quả.

### 2.4. Actor

| Actor | Họ đang làm gì? | Pain / hậu quả có thể gặp | Được lợi gì? |
|---|---|---|---|
| **Người học (chọn điều tra trước)** | Học bài mới trên VLearn, làm bài trắc nghiệm / đọc slide | Bị mắc kẹt mà không biết thiếu gì, ôn lan man, tốn thời gian, bỏ bài | Hiểu tiếp được bài, không bị đứt mạch học |
| Giảng viên | Giảng bài, trả lời câu hỏi, giao bài tập | Phải giảng lại nhiều lần, không biết ai đang mắc kẹt ở đâu | Giảm số lần phải hỗ trợ lặp lại |
| Trợ giảng / cố vấn học tập (nếu có) | Hỗ trợ trực tiếp 1-1 | Không có tín hiệu sớm để can thiệp | Can thiệp đúng người, đúng chỗ |

**Lý do chọn người học trước:** Người học là người trực tiếp chịu cảm giác mắc kẹt, phải thay đổi cách học và gánh hậu quả (mất thời gian / làm sai / bỏ học). Phía giảng viên để lại vòng sau.

### 2.5. Situation & Job

> Khi đang học một bài mới mà gặp đoạn không hiểu (ví dụ: làm sai bài trắc nghiệm, đọc slide mà không vào), người học đang cố hiểu tiếp bài để làm được bài tập / qua môn bằng cách xem lại slide cũ, tìm trên Google / YouTube, hỏi bạn / hỏi ChatGPT, hoặc bỏ qua làm tiếp.

**JTBD Hypothesis:**

> Khi tôi bị mắc kẹt giữa bài học và không muốn dừng lại, tôi muốn nhanh biết mình đang thiếu cái gì, để có thể hiểu tiếp mà không bị đứt mạch học.

Nhu cầu (job) này vẫn tồn tại ngay cả khi bỏ AI và tính năng khỏi bối cảnh.

### 2.6. Pain Hypothesis (2 cách lý giải cạnh tranh)

**Pain Hypothesis A (chính — hổng kiến thức nền mà không tự nhận ra):**

> Khi đang học bài mới trên VLearn, người học gặp khó khăn trong việc hiểu tiếp bài vì không xác định được mình đang thiếu khái niệm nền nào nên ôn lan man / sai chỗ, dẫn đến tốn 30–60 phút mà vẫn không hiểu, nản và dễ bỏ dở bài.

**Pain Hypothesis B (cạnh tranh — bị đứt mạch học):**

> Khi đang học bài mới trên VLearn, người học gặp khó khăn trong việc hiểu tiếp bài vì mọi cách xử lý hiện tại đều bắt rời khỏi bài học (mở thẻ mới, chờ bạn trả lời, chờ giảng viên trả lời), dẫn đến mất tập trung, quên ngữ cảnh và quay lại khó hơn.

**Nhóm chọn điều tra trước: A.** Lý do: nếu B đúng thì chỉ cần giải thích ngay trong bài, không cần chẩn đoán lịch sử học. Cần kiểm tra A trước để xem có cần bước chẩn đoán hay không.

### 2.7. Evidence Map

| Điều cần kiểm tra | Bằng chứng làm nhóm tin hơn | Bằng chứng làm nhóm nghi ngờ / bác bỏ |
|---|---|---|
| Tình huống có thật | Kể được lần bị mắc kẹt cụ thể trong 7 ngày, nhớ rõ môn / bài / câu nào | Chỉ kể chung chung kiểu "thường thì khó" |
| Pain có ý nghĩa | Nói "không biết mình thiếu gì / không biết gõ từ khóa gì để tìm" | Nói "biết ngay thiếu gì, chỉ lười ôn lại" |
| Cách xoay xở (workaround) có tồn tại | Đã thử: xem lại slide cũ, tìm trên Google / YouTube, hỏi bạn / hỏi ChatGPT, bỏ qua làm tiếp | Không làm gì, chờ giảng viên giảng lại |
| Hậu quả có tồn tại | Mất trên 15 phút, làm sai tiếp, căng thẳng / bỏ bài | Chỉ mất 5 phút, không ảnh hưởng gì |
| Mẫu lặp lại có tồn tại | Lặp lại từ 2 lần / tháng trở lên | Hiếm gặp, một kỳ một lần |

**Problem Hypothesis mang sang Chặng 2:**

> Khi người học bị mắc kẹt giữa bài trên VLearn, họ không xác định được khái niệm nền còn thiếu nên ôn sai / lan man, dẫn đến tốn thời gian mà vẫn không theo được bài và dễ bỏ dở.

- Điều phải đúng để giả thuyết đứng vững: (1) Tình huống trong 7 ngày có thật, (2) Có cách xoay xở tốn công sức, (3) Có hậu quả nhìn thấy được (mất thời gian / làm sai tiếp / bỏ bài).
- Điều khiến nhóm sửa / bác bỏ giả thuyết: người học biết ngay thiếu gì, hoặc chỉ mất dưới 5 phút mà không có hậu quả, hoặc không bao giờ tự tìm cách xử lý.

### 2.8. Solution Parking Lot (từ 5 hướng trở lên, có ít nhất 1 hướng không dùng AI)

| Hướng giải quyết có thể có | AI / Không dùng AI |
|---|---|
| 1. Nút ôn lại theo chẩn đoán như trong chỉ thị | AI |
| 2. Sơ đồ "bài này cần nền tảng gì" hiện sẵn ở đầu bài | Không dùng AI |
| 3. Bảng thuật ngữ và ví dụ ngắn ngay trong bài học | Không dùng AI |
| 4. Nhờ bạn cùng lớp đã học qua giảng lại | Không dùng AI |
| 5. Diễn đàn hỏi nhanh / giờ gặp giảng viên | Không dùng AI |
| 6. Bài trắc nghiệm chẩn đoán ngắn 2–3 câu do giảng viên soạn sẵn | Không dùng AI |

---

## 3. Conversation Guide

### Tiêu chí chọn người phỏng vấn

> Chúng tôi cần nói chuyện với người đã **có lúc không hiểu một phần bài học và phải tìm cách xử lý trong 7 ngày gần đây.**

**Câu kiểm tra đầu vào (Recruitment check, chỉ để chọn đúng người, không tính là bằng chứng):**

> "Trong 7 ngày qua có lúc nào bạn học mà phải dừng lại vì không hiểu không? Đó là môn / bài gì?"

### Lời mở đầu (đọc nguyên văn, không nhắc solution)

> "Bọn mình đang tìm hiểu cách mọi người xử lý khi học mà bị mắc kẹt. Không có đúng / sai, chỉ muốn nghe chuyện thật bạn đã trải qua. Bạn cho mình ghi âm để xem lại được không? Bản ghi chỉ dùng cho bài học này, không chia sẻ ra ngoài."

- Chỉ ghi khi người được phỏng vấn đồng ý.
- Tuyệt đối không nhắc: "Tôi vẫn chưa hiểu", "AI Tutor", "chẩn đoán", "khái niệm nền".

### Câu mở chuyện (Story opener)

> "Kể mình nghe về lần gần nhất bạn học mà không hiểu một đoạn và phải xử lý?"

### Big 3 Questions (3 câu hỏi chính, bám theo 3 điều cần học)

| Điều cần học | Câu hỏi sẽ dùng |
|---|---|
| 1. Cách xoay xở và công sức thực tế | "Lúc đó chuyện gì xảy ra tiếp theo? Bạn đã làm gì đầu tiên, rồi làm gì nữa?" |
| 2. Pain A có thật không? (câu hỏi khó — có thể bác bỏ giả thuyết) | "Phần nào khó nhất? Có lúc nào bạn không biết mình đang thiếu cái gì / không biết gõ từ khóa gì để tìm không?" |
| 3. Hậu quả và tần suất có đáng giải quyết không? | "Việc đó kéo theo gì? Bạn mất bao lâu? Lần gần trước đó là khi nào?" |

### Kho câu hỏi đào sâu (Probe bank, chỉ dùng khi cần moi thêm chuyện)

- "Lúc đó bạn ở đâu, đang học môn gì?"
- "Vì sao bạn chọn cách đó?"
- "Bạn đã thử cách nào khác chưa?"
- "Điều gì làm bạn mất thời gian nhất?"
- "Sau đó bạn có hiểu để làm tiếp không, hay bỏ qua / bỏ bài?"
- "Lần gần trước đó là khi nào?"

### Ba phản xạ khi câu chuyện lệch hướng

| Người học đưa ra | Phản xạ | Cách kéo về bằng chứng |
|---|---|---|
| Lời khen ("tính năng hay đó") | Lảng sang chuyện khác (Deflect) | "Cảm ơn bạn, quay lại chuyện của bạn — lúc đó bạn đang làm gì?" |
| Câu chung chung / hứa hẹn tương lai ("thường thì / mình sẽ dùng") | Neo về lần gần nhất (Anchor) | "Lần gần nhất chuyện đó xảy ra là khi nào?" |
| Gợi ý tính năng ("nên có nút…") | Đào sâu nhu cầu (Dig) | "Điều đó giúp bạn làm được gì? Hiện tại bạn xử lý ra sao?" |

### Những chỗ đã SỬA sau khi luyện (để đạt Gate 4)

1. **Bỏ** câu nháp "Bạn có muốn AI giúp tìm chỗ chưa hiểu không?" vì hỏi ý kiến tương lai và làm lộ solution → **thay bằng** câu Big 3 số 2 hỏi về việc đã xảy ra ("Có lúc nào không biết gõ từ khóa gì để tìm không?").
2. **Thêm cụm "lần gần nhất"** vào câu mở chuyện và câu hỏi đào sâu, vì bản nháp người học toàn kể kiểu "thường thì…".
3. **Thêm câu hỏi về thời gian và hậu quả** ("Mất bao lâu? Rồi có làm tiếp được không?") vì bản đầu bỏ sót hậu quả, chỉ hỏi cách xoay xở.

---

## 4. Practice Reflection (tự viết sau khi nghe lại bản ghi)

**1. Câu hỏi nào đã giúp người học kể một tình huống cụ thể?**

> Câu "Bạn đã làm gì đầu tiên, rồi làm gì nữa?" là câu mở được chuyện thật. Lúc đầu bạn được phỏng vấn chỉ nói chung chung "bài RAG khó". Sau câu này, bạn kể lại tối 01/10 học bài RAG trên VLearn, làm sai 2 lần câu về chia đoạn văn bản (chunking) và chọn top-k kết quả truy xuất ở bài trắc nghiệm cuối bài, rồi xem lại slide 8–10, lên Google gõ "RAG chunk overlap bao nhiêu là đủ", xem một video YouTube 18 phút về vector hoá văn bản (embedding) rồi nhắn hỏi bạn cùng phòng. Nếu không có câu hỏi theo trình tự này, mình chỉ thu được nhận xét chung, không có hành vi cụ thể để đối chiếu với Pain A.

**2. Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?**

> Mình mắc hai lỗi khi nghe lại bản ghi. Thứ nhất, mình ngắt lời ở phút 06 khi bạn đang kể đoạn tìm trên Google về RAG, mình đoán hộ "là do không biết từ khóa đúng không?" — đây là câu dẫn, ép bạn đồng ý với Pain A. Lần thật mình sẽ đợi bạn nói hết 3 giây rồi chỉ hỏi "Rồi sao nữa?". Thứ hai, mình bỏ sót tín hiệu hậu quả ở phút 11 khi bạn nói "mất gần 1 tiếng mà vẫn sai câu top-k, thôi tắt máy đi ngủ", mình lại chuyển chủ đề thay vì hỏi "Việc tắt máy hôm đó kéo theo gì cho bài nộp hôm sau?". Lần thật mình sẽ đào ngay mỗi khi nghe thấy con số thời gian, hành vi bỏ dở hoặc làm sai tiếp.

**3. Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?**

> (1) Bỏ hẳn câu nháp "Bạn có muốn AI chỉ chỗ hổng cho bạn không?" vì đây là câu hỏi ý kiến tương lai và làm lộ solution — bản ghi cho thấy vừa hỏi câu này là bạn chuyển sang khen "nghe hay đó" thay vì kể chuyện. Đã thay bằng câu Big 3 số 2 hỏi việc đã xảy ra. (2) Thêm cụm "lần gần nhất" vào câu mở chuyện và kho câu hỏi đào sâu, vì cả hai lượt luyện đầu người học đều trả lời kiểu "thường thì em hay…". (3) Thêm câu hỏi bắt buộc về thời gian và hậu quả "Mất bao lâu? Sau đó có làm tiếp được không hay bỏ?", vì bản ghi của mình thiếu hẳn hậu quả nên không đối chiếu được với Evidence Map dòng Consequence.

---

## 5. AI Support Log (khai báo việc dùng AI)

- **AI đã giúp gì:** Gợi ý cách viết gọn JTBD / Pain Hypothesis và rà soát câu hỏi dễ dẫn dắt trong Guide (ví dụ: phát hiện câu hỏi tương lai kiểu "bạn có muốn…").
- **Điểm AI làm chưa tốt:** Lần đầu AI viết Pain còn lẫn tên tính năng ("thiếu nút Tôi vẫn chưa hiểu") và gợi ý câu hỏi làm lộ solution. Câu Big 3 do AI đề xuất còn chung chung, chưa neo vào "lần gần nhất".
- **Bạn đã tự sửa thế nào:** Tự viết lại Capability trung tính không nhắc tên tính năng, tự thay câu hỏi xin ý kiến bằng câu hỏi về việc đã xảy ra, tự đối chiếu với bản ghi buổi luyện để sửa Guide. Không dùng AI để bịa dữ liệu phỏng vấn, bịa trích dẫn hay viết hộ Reflection — phần Reflection trên là tự nghe lại bản ghi và tự viết.

---

## Danh mục kiểm tra trước khi nộp

- [x] Repo đúng tên `Track1_Day17_2A202602560_TaVietCuong`
- [x] README đủ 5 phần
- [x] `interview/notes.md` là ghi chép của lượt mình làm người phỏng vấn
- [x] Có `interview/recording.mp3`
- [x] Người được phỏng vấn đã đồng ý cho ghi lại
- [x] Guide cuối không làm lộ solution và đã khác bản nháp (có ghi rõ chỗ sửa)
