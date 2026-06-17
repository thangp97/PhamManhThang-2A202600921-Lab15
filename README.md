# TRACK DECISION MEMO – Day 15

**Họ tên:** Phạm Mạnh Thắng   
**Pathway:** A *(Tìm / chuyển việc - Phù hợp vì bạn là sinh viên năm cuối đang muốn vào một role AI cụ thể trong thời gian tới).*

---

## 1. ĐỊNH HƯỚNG 
*(vài job/role mình hướng tới + kỹ năng mỗi job đòi hỏi từ JD thật + report)*

* **Job 1: AI Engineer / Generative AI Engineer**
  * **Kỹ năng cần:** Xây dựng hệ thống LLM ở mức production-grade, Advanced RAG, thiết kế kiến trúc Agent nâng cao.
* **Job 2: Backend Engineer (AI Integration)**
  * **Kỹ năng cần:** Python/FastAPI, tích hợp API LLM, quản trị Vector Database, tối ưu hóa độ trễ hệ thống.
* **Job 3: LLM Application Developer**
  * **Kỹ năng cần:** Prompt Engineering, Tool-calling, Multi-agent orchestration, thiết lập luồng CI/CD cho AI.

---

## 2. ĐỐI CHIẾU BẢN THÂN 
*(từ Phase 1)*

* **Những việc mình đã làm được (liệt kê tự do, không giới hạn):**
  * Có nền tảng thiết kế kiến trúc phần mềm, viết API, và quản trị cơ sở dữ liệu. 
  * Đã hoàn thành các lab liên quan đến ReAct, tool calling (D3-4) và RAG, supervisor-worker (D8-9) và nhận thấy đây mới là phần mình thực sự thích.
* **Loại công việc cho mình năng lượng, muốn làm tiếp:**
  * Chịu được khối kỹ thuật nặng.
  * Thích cảm giác đọc paper gốc để tìm giải pháp, debug khi code bị lỗi (scaffold xfail/skip).
  * Hứng thú với việc xây dựng logic suy luận cho máy (Agent).

---

## 3. KỸ NĂNG MÌNH ĐỊNH PHÁT TRIỂN TỚI

* **Kỹ năng mục tiêu:** Advanced RAG (GraphRAG), Kiến trúc Multi-agent, AI Eval & Guardrails (Reliability).
* **Gap lớn nhất + thứ mình sẽ build để cho thấy tiến bộ:**
  * **Gap lớn nhất:** Kinh nghiệm thực tế để đưa hệ thống LLM từ dạng "chạy được" lên mức production-grade.
  * **Sẽ build:** Một Capstone Project chuyên sâu (ví dụ: một AI Agent tự động phân tích code hoặc một hệ thống RAG xử lý tài liệu kỹ thuật phức tạp cho doanh nghiệp).

---

## 4. QUYẾT ĐỊNH TRACK

* **Track chọn:** **T3 AI Engineering**
  * **Vì:** Đây là track chuyên sâu kỹ thuật, tập trung vào việc xây dựng agent / LLM systems ở mức production-grade. Nó khớp hoàn hảo với nền tảng Software Engineering hiện có và mong muốn đi sâu vào RAG/Agent của bản thân.
* **Track cân nhắc nhưng KHÔNG chọn + lý lẽ mạnh nhất cho nó:** **T2 Data & Infrastructure**
  * **Lý lẽ:** Mặc dù T2 rất quan trọng (đào tạo kỹ sư hạ tầng tự dựng và vận hành backend AI production), nhưng nó thiên về cloud, DevOps và quản trị tài nguyên (GPU/FinOps). Tôi muốn dành thời gian để tập trung phát triển lớp Application và Logic (Agent/RAG) hơn là làm hạ tầng.
* **Dấu hiệu sẽ khiến mình xem lại lựa chọn:**
  * Cảm thấy quá tải với nội dung nặng và đi rất nhanh.
  * Đuối sức khi phải liên tục đọc paper vì nhiều thứ chưa có "best practice".
  * Thấy việc tự thử nghiệm và benchmark/eval tốn quá nhiều công sức mà không đem lại kết quả thực tế.

---

## 5. ĐỊNH HƯỚNG & CHUẨN BỊ 
*(ghi mở – có gì ghi nấy)*

* **Định hướng tiếp theo:** Đi sâu vào việc tối ưu hóa khả năng truy xuất dữ liệu (RAG) kết hợp với luồng suy luận của AI (ReAct/LangGraph).
* **Những thứ cần chuẩn bị:** Củng cố kỹ năng Python nâng cao, chuẩn bị tâm lý sẵn sàng đọc nhiều tài liệu tiếng Anh và paper gốc. Tìm kiếm vài JD thực tế về AI Engineer để làm mốc phấn đấu.
* **Plan nếu có:** Dành 1-2 tuần tới để review lại toàn bộ code lab Phase 1 về RAG/Agent nhằm đảm bảo hiểu sâu gốc rễ trước khi bước vào Phase 2.
* **Câu hỏi còn mở:** Các framework/tool nào đang là tiêu chuẩn thực tế (industry standard) để đánh giá (eval) và benchmark hệ thống Agentic RAG một cách tự động hóa?