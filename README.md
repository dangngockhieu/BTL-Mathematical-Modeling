BTL-Mathematical-Modeling
Mô tả giải thuật
1 First Fit Decreasing
Giải thuật First Fit Decreasing (FFD) là một phương pháp heuristic phổ biến để giải quyết bài toán cắt vật liệu. Thuật toán này là một biến thể của phương pháp First Fit, trong đó sản phẩm được sắp xếp trước theo thứ tự giảm dần về diện tích, sau đó lần lượt được chèn vào kho có khả năng chứa nó đầu tiên. Giải thuật này được thực hiện theo nguyên tắc như sau:
• Sắp xếp giảm dần theo diện tích của các tấm sản phẩm cần cắt và các kho lưu trữ.
• Duyệt qua các sản phẩm và kho, tìm kho đầu tiên mà sản phẩm có thể đặt vừa cả hai chiều.
• Nếu tìm thấy một vị trí hợp lệ, thuật toán trả về thông tin chèn sản phẩm, nếu không thuật
toán trả về giá trị mặc định (kho không hợp lệ hoặc không có vị trí khả dụng).
• Lặp lại cho đến khi hết kho và sản phẩm
2 Reinforcement Learning
Q-learning là một thuật toán học tăng cường(RL) giúp tìm kiếm chính sách tối ưu trong 2D cutting stocks problem bằng cách tối thiểu hóa lãng phí vật liệu. Thuật toán này khởi tạo bảng Q cho các trạng thái và hành động, sau đó cập nhật giá trị Q dựa trên phần thưởng từ hành động thực hiện. Quá trình lặp lại cho đến khi bảng Q hội tụ, cho phép xác định cách cắt hiệu quả nhất.
