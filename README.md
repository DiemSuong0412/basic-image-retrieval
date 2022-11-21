# Basic-Image-Retrieval
Xây dựng một chương trình cho phép truy vấn hình ảnh sử dụng các phép đo độ tương đồng giữa các hình ảnh (Similarity Measure).

- **Input**: Hình ảnh truy vấn q và bộ dữ liệu C.
- **Output**: Danh sách các hình ảnh c (c ∈ C) có sự tương quan đến hình ảnh truy vấn.

<img width="459" alt="image" src="https://user-images.githubusercontent.com/88385496/198692020-95495c2c-725f-4fd6-b850-7d1bc13238f0.png">
<img width="475" alt="image" src="https://user-images.githubusercontent.com/88385496/198692288-83307a4c-32cc-4fcd-8321-e323eab72ac4.png">

## Download dataset
> Data đã được xử lý, tải [tại đây](https://drive.google.com/file/d/1TtQukE5VE4r7DNZcSJaTpRxH1yaFph1A/view?usp=sharing). Chuyển sang step 4 

## Faiss
Facebook AI Similarity Search (Faiss) là một thư viện sử dụng similiarity search cùng với clustering các vector. Faiss được nghiên cứu và phát triển bởi đội ngũ Facebook AI Research; được viết trong C++ và đóng gói trên môi trường Python. Bộ thư viện bao gồm các thuật toán tìm kiếm vector đa chiều trong similarity search

### Similarity search
Bắt đầu với một tập các vector $$\x_i$$ có **d** chiều, Faiss sẽ tự tạo một cấu trúc dữ liệu từ RAM. Sau đó, vector x mới sẽ được tính toán: 

## Yêu cầu
- python==3.8.10
- `pip install -r requirements.txt`

## Test web + chức năng: 
- Run web: [](http://localhost:6868/)
`python app.py`

# Demo website
- Giao diện của web
<img width="1080" alt="image" src="https://user-images.githubusercontent.com/88385496/198829340-565d3b87-8ce5-4536-8f9c-f9b80c11b434.png">

- Upload ảnh
<img width="1080" alt="image" src="https://user-images.githubusercontent.com/88385496/198829382-bb520312-9433-4545-9dee-93a922bc5fdb.png">

- Kết quả 
<img width="1063" alt="image" src="https://user-images.githubusercontent.com/88385496/198829405-6812e96f-a5b3-48f2-90f8-1d895dae033d.png">

