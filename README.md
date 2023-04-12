# Chatbot-for-English
## Dataset
Đây là bộ dữ liệu những câu hỏi đáp giữa bệnh nhân và bác sĩ thu thập trên các trang web  
Dữ liệu có 2 cột:  
- question là câu hỏi của bệnh nhân
- answer là câu trả lời của bác sĩ
## Code
Trong phần này, mình sử dụng các kiến trúc mô hình khác nhau cho bài toán Chatbot:  
- LSTM
- LSTM + Attention
- BERT
- GPT
## Evaluation
- Biểu đồ Loss với 100 epochs
<img src='img/loss 100.PNG'>
- Biểu đồ Loss cho tất cả các model
<img src='img/loss all.PNG'>
- Bảng đánh giá các model
<img src='img/time_train, time_test, blue_score.PNG'>
