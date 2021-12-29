#Đồ án AI phần 2 Machine learning

Intents.json: Tệp dữ liệu có các mẫu và phản hồi được xác định trước.
train_chatbot.py: Tệp python chứa tập lệnh để xây dựng mô hình và đào tạo chatbot.
Words.pkl: Tệp lưu trữ các từ đối tượng Python có chứa danh sách từ vựng.
Classes.pkl: Tệp chọn lớp chứa danh sách các danh mục.
Chatbot_model.h5: Đây là mô hình được đào tạo có chứa thông tin về mô hình và có trọng lượng của các tế bào thần kinh.
Chatgui.py: Tệp python để triển khai GUI cho chatbot. Người dùng có thể dễ dàng tương tác với bot.

Đảm bảo đã cài đặt các thư viện:
    pip install tensorflow, keras, pickle, nltk

Tạo model bằng lệnh:
    python train_chatbot.py

Để chạy ứng dụng:
    python chatgui.py
