# Memo Teardown — ChatGPT

**Họ tên:** Hoàng Anh Tài

**Vì sao chọn sản phẩm này:** AI đóng vai trò đủ lớn trong trải nghiệm, có timeline 6 bước và có usecase, JTBD rõ ràng

**§1. Timeline các cập nhật lớn**

| Thời điểm | Cập nhật | Context lúc đó | Nguyên lý |
| :--- | :--- | :--- | :--- |
| **30/11/2022** | [**ChatGPT ra mắt**](https://openai.com/index/chatgpt/) | OpenAI giới thiệu ChatGPT bản *research preview*, chứng minh sức mạnh của mô hình đàm thoại nhiều lượt (multi-turn), follow-up và phản hồi theo ngữ cảnh. | **Conversation-first:** Chuyển đổi tương tác AI từ dạng prompt/code kỹ thuật sang giao diện hội thoại tự nhiên với người dùng đại chúng. |
| **14/03/2023** | [**GPT-4**](https://openai.com/index/gpt-4/) | GPT-3.5 bùng nổ nhu cầu nhưng hay "ảo giác" và yếu reasoning; GPT-4 ra mắt độc quyền trên Plus, giải quyết bài toán suy luận phức tạp và độ chính xác cao. | **Capability expansion:** Nâng trần năng lực của mô hình nền tảng để giải quyết các bài toán tri thức chuyên sâu. |
| **23/03/2023** | [**Plugins & Tool Use**](https://openai.com/index/chatgpt-plugins/) | ChatGPT bị giới hạn bởi tri thức đóng (cutoff date); OpenAI mở hệ sinh thái Plugin kết nối API bên ngoài để đọc web, tính toán và truy xuất data theo thời gian thực. | **Tool augmentation:** AI không chỉ dừng ở việc "nhớ và sinh từ" mà biết sử dụng công cụ bên ngoài để hoàn thành tác vụ. |
| **06/11/2023** | [**Custom GPTs**](https://openai.com/index/introducing-gpts/) | Nhu cầu cá nhân hóa chuyên sâu theo từng vai trò tăng vọt; cho phép người dùng tự đóng gói prompt, tệp tri thức (RAG) và action mà không cần viết code. | **Personalization & Ecosystem:** Chuyển dịch từ "một AI phục vụ tất cả" sang nền tảng cho phép tự build trợ lý chuyên biệt cho từng Job-to-be-Done. |
| **13/05/2024** | [**GPT-4o (Multimodal)**](https://openai.com/index/hello-gpt-4o/) | Giao tiếp thuần text chưa đủ nhanh và trực quan; 4o xử lý native đồng thời text, audio, image/video với độ trễ thấp và mở rộng miễn phí tính năng cho toàn bộ user. | **Multimodal-first:** Tương tác đa giác quan thời gian thực, đưa AI tiệm cận phản xạ tự nhiên của con người. |
| **31/10/2024** | [**ChatGPT Search**](https://openai.com/index/introducing-chatgpt-search/) | User có thói quen tra cứu tin tức nhưng Google trả về danh sách link rác/quảng cáo; Search tích hợp trực tiếp khả năng tra cứu web có trích dẫn nguồn uy tín. | **Grounding & Retrieval:** Kết hợp tư duy tổng hợp hội thoại với dữ liệu web thời gian thực, trực tiếp cạnh tranh Search engine truyền thống. |
| **01/2025 – 02/2025** | [**Operator**](https://openai.com/index/introducing-operator/) & [**Deep Research**](https://openai.com/index/introducing-deep-research/) | User không chỉ muốn câu trả lời tóm tắt mà cần AI tự nghiên cứu sâu đa nguồn hoặc trực tiếp thao tác click/form trên trình duyệt để ra kết quả cuối. | **Agentic execution:** Chuyển từ AI "trả lời câu hỏi" sang AI "thực thi công việc" (tự lập kế hoạch, dùng tool và hành động nhiều bước). |

**Vì sao chọn những mốc này:** Tôi chọn 7 cột mốc này vì chúng đại diện cho các bước nhảy vọt về **khả năng cốt lõi** và **mô hình sử dụng** của ChatGPT, từ giao diện hội thoại (30/11/2022), năng lực reasoning (GPT-4), kết nối thế giới thực (Plugins), cá nhân hóa (GPTs), giao tiếp đa phương thức (GPT-4o), truy xuất thông tin (Search) cho đến khả năng tự hành động (Operator/Deep Research).

**§2. Tệp user & JTBD**

| | Early adopters | Tệp hiện tại |
|---|---|---|
| **Đặc điểm** | AI researchers, developers, tech enthusiasts và những người muốn khám phá công nghệ AI mới. | Tệp đại chúng và đa dạng: sinh viên, người đi làm, developer, marketer, researcher, IT và doanh nghiệp. |
| **JTBD chính** | Khám phá khả năng của một AI có thể hiểu và phản hồi bằng hội thoại; hỗ trợ hỏi đáp, viết, giải thích và giải quyết vấn đề. | Hoàn thành công việc hoặc đạt mục tiêu nhanh hơn với ít effort hơn: học, viết, nghiên cứu, coding, phân tích, sáng tạo và thực hiện tác vụ. |
| **Trước đó họ làm bằng cách nào** | Search engine, diễn đàn, tài liệu, Stack Overflow, tự viết và tự giải quyết vấn đề. | Kết hợp search engine, phần mềm chuyên dụng, tài liệu và workflow thủ công; thường phải tự tìm → đọc → tổng hợp → thực hiện. |

**Dịch chuyển tệp:** Cột mốc **GPT-4o & Multimodal (05/2024)** là một trong những bước quan trọng thúc đẩy ChatGPT từ nhóm người dùng thiên về công nghệ sang tệp người dùng đại chúng hơn. GPT-4o giúp tương tác với AI tự nhiên và dễ tiếp cận hơn thông qua text, hình ảnh và giọng nói, đồng thời OpenAI đưa nhiều năng lực GPT-4o đến người dùng miễn phí. Nhờ giảm rào cản về kỹ năng, chi phí và cách tương tác, ChatGPT trở nên hữu ích cho nhiều nhóm như sinh viên, người làm nội dung, nhân viên văn phòng và người dùng phổ thông, thay vì chủ yếu hấp dẫn những người muốn thử nghiệm công nghệ AI.

**Switching cost (map 4 forces):** 
- **High Switching Cost (Giữ user lại):**
    - **Học sâu (Deep Learning/Retention):** Nhiều user đã đầu tư thời gian để học cách viết prompt hiệu quả (prompt engineering). Sự am hiểu này tạo ra một rào cản chuyển đổi lớn vì kiến thức và kỹ năng này có thể không chuyển giao dễ dàng sang các hệ thống khác, hoặc việc bắt đầu lại từ đầu với một AI mới đòi hỏi nỗ lực học tập đáng kể.
    - **Tích hợp quy trình công việc (Workflow Integration):** ChatGPT đã được tích hợp vào nhiều quy trình làm việc hàng ngày, từ soạn thảo email, viết code đến nghiên cứu. Việc chuyển sang một nền tảng khác sẽ phá vỡ sự liền mạch của quy trình này, gây gián đoạn đáng kể cho công việc hiện tại.
- **Low Switching Cost (Đang kéo đi):**
    - **Dễ dàng thử nghiệm (Ease of Experimentation):** Với nhiều tùy chọn AI mới xuất hiện liên tục, người dùng rất dễ dàng thử nghiệm các công cụ thay thế. Nếu một công cụ mới cung cấp hiệu suất tốt hơn hoặc tính năng đột phá, người dùng có thể chuyển sang mà không tốn nhiều chi phí.
    - **Tiêu chuẩn hóa giao diện (Interface Standardization):** Giao diện chatbot đã trở thành một tiêu chuẩn. Các sản phẩm mới có thể nhanh chóng mô phỏng giao diện này, làm giảm rào cản kỹ thuật cho việc chuyển đổi.

**§3. Ba dự đoán hướng đi (6–12 tháng tới)**

**Dự đoán 1** 
- **Dự đoán:** ChatGPT sẽ mở rộng sang lĩnh vực giáo dục chuyên sâu, cung cấp các khóa học được cá nhân hóa hoàn toàn dựa trên khả năng và mục tiêu của từng người học.
- **Lập luận:** ChatGPT đã cho thấy khả năng hiểu và phản hồi thông minh trong các bối cảnh đa dạng. Bằng cách kết hợp khả năng này với dữ liệu học tập của người dùng, ChatGPT có thể tạo ra các lộ trình học tập riêng biệt, điều chỉnh nội dung và phương pháp giảng dạy theo từng cá nhân. Điều này sẽ tạo ra một phân khúc thị trường mới cho ChatGPT, thu hút người dùng tìm kiếm giải pháp giáo dục cá nhân hóa.

**Dự đoán 2** 
- **Dự đoán:** ChatGPT sẽ phát triển các tính năng chuyên sâu hơn cho người dùng doanh nghiệp, cho phép tùy chỉnh và tích hợp dễ dàng vào quy trình làm việc hiện tại của công ty.
- **Lập luận:** Nhiều doanh nghiệp đã tích hợp ChatGPT vào quy trình làm việc của họ. Việc mở rộng các tính năng chuyên sâu và tùy chỉnh sẽ giúp doanh nghiệp tối ưu hóa hiệu suất làm việc, giảm chi phí vận hành và tăng cường khả năng cạnh tranh.

**Dự đoán 3** 
- **Dự đoán:** ChatGPT sẽ tiếp tục cải thiện khả năng đa phương thức, cho phép người dùng tương tác với AI thông qua giọng nói, hình ảnh và video một cách tự nhiên và liền mạch hơn.
- **Lập luận:** Người dùng ngày càng mong muốn tương tác với AI một cách tự nhiên và trực quan. Việc cải thiện khả năng đa phương thức sẽ giúp ChatGPT đáp ứng nhu cầu này, tạo ra trải nghiệm người dùng tốt hơn và thu hút thêm người dùng mới.

**§4. AI Log**

| Việc | AI làm hay bạn làm? | Bạn kiểm chứng/phán đoán lại thế nào? |
|---|---|---|
| Tìm kiếm thông tin về các mốc cập nhật của ChatGPT | Bạn tự tìm kiếm thông tin trên Google | Kết quả tìm kiếm bao gồm nhiều nguồn tin cậy, bao gồm trang web chính thức của OpenAI và các trang tin tức công nghệ uy tín |
| Phân tích và tóm tắt các mốc cập nhật của ChatGPT | ChatGPT | Kết quả tóm tắt đầy đủ và chính xác |
| Tìm kiếm thông tin về user của ChatGPT | Bạn tự tìm kiếm thông tin trên Google | Kết quả tìm kiếm bao gồm nhiều nguồn tin cậy, bao gồm trang web chính thức của OpenAI và các trang tin tức công nghệ uy tín |
| Phân tích và tóm tắt thông tin về user của ChatGPT | ChatGPT | Kết quả tóm tắt đầy đủ và chính xác |
| Tìm kiếm thông tin về các dự đoán hướng đi của ChatGPT | Bạn tự tìm kiếm thông tin trên Google | Kết quả tìm kiếm bao gồm nhiều nguồn tin cậy, bao gồm trang web chính thức của OpenAI và các trang tin tức công nghệ uy tín |
| Phân tích và tóm tắt thông tin về các dự đoán hướng đi của ChatGPT | ChatGPT | Kết quả tóm tắt đầy đủ và chính xác |
| Phân tích 4 forces switching cost | Bạn tự phân tích | Kết quả phân tích logic và chính xác |
| Tạo cấu trúc và nội dung cho bài memo | ChatGPT | Kết quả đáp ứng đúng yêu cầu và format |
| | | |
