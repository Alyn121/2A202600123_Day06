# Individual reflection — Lý Quốc An (2A202600123)

## 1. Role
AI design + prompt engineer. Phụ trách thiết kế chunking và system prompt.

## 2. Đóng góp cụ thể
- Thiết kế prompt để model có thể trả lời câu hỏi của tài xế , nếu câu trả lời chưa rõ ràng thì hỏi lại
- Viết và test 3 phiên bản system prompt
- chunking dữ liệu và chuyển về vector database cho RAG

## 3. SPEC mạnh/yếu
- Mạnh nhất: xác định được vấn đề của tài xế , Hiểu pain point user,Thiết kế prompt phù hợp,Tối ưu RAG retrieval
- Yếu nhất: Xác định bài toán chưa đúng scope ban đầu  
## 4. Đóng góp khác
- crawl dữu liệu để dùng cho bài toán 
- xây dụng chat bot phân loại dành cho người dùng để phát triển sau này

## 5. Điều học được
Học đucowj cách làm việc nhóm , phân chia công việc hợp lý, biết cách xác định pain point của người dùng và đưa ra giải pháp phù hợp, tối ưu truy vấn cho RAG.

## 6. Nếu làm lại
Sẽ xác định pain point rõ ràng hơn , đào sâu hơn vào vấn đề của người dùng, chungking bao quát hơn

## 7. AI giúp gì / AI sai gì
- **Giúp:** dùng GEMINI để làm api
    debug cho chunking và prompt
- **Sai/mislead:** Claude gợi ý thêm feature "đặt lịch khám" vào chatbot —
  nghe hay nhưng scope quá lớn cho hackathon. Suýt bị scope creep nếu không dừng lại.
  Bài học: AI brainstorm tốt nhưng không biết giới hạn scope.
