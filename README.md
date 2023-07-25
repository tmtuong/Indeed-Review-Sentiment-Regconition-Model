# Sentiment-Recognition-and-Modeling-
1. Để thực hiện bài toán phân loại cảm xúc thông qua các đánh giá (comments) của công ty trên các trang mạng xã hội, trước hết cần thu nhập dữ liệu trên trang indeed, cụ thể như bài này tôi thu thập dữ liệu Công ty Tesla.
2. Sau khi đã thu thập dữ liệu xong, để thuận tiện tôi lưu data lên google sheets
3. Sau khi đã có dữ liệu thì thực hiện các phương pháp EDA để khám phá dữ liệu. Thực hiện các bước xử lý để làm sạch văn bản như:
- Sửa đổi các ký tự rút gọn
- In thường đoạn văn bản
- Trích xuất từ loại (chỉ giữ các từ dạng danh từ, động từ và tính từ)
- Steaming: kỹ thuật dùng để biến đổi 1 từ về dạng gốc bằng cách cực kỳ đơn giản là loại bỏ 1 số ký tự nằm ở cuối từ mà nó nghĩ rằng là biến thể của từ (VD: running -> run)
- Tokenize: tách đoạn văn bản thành các list
4. Sau khi đã tiền xử lý xong, tôi sẽ tiến hành xây dựng mô hình phân loại cảm xúc bằng mô hình Varder
