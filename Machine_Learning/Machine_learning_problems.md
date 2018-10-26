# Phân loại các bài toán học máy
Các bài toán học máy có thể chia ra thành ba nhóm chính:
* Học có giám sát (supervised learning)
* Học không giám sát (unsupervised learning)
* Học bán giám sát (semi-supervised learning)

Ngoài ra ta cũng có thể coi học củng cố (reinforcement learning) cũng thuộc các bài toán học máy

## Học có giám sát
Dữ liệu để học đã được gán nhãn và dữ liệu đầu ra cần được gán một số nhãn cố định đã biết. Tức là với mỗi dữ liệu, ta đều có một hoặc một vài nhãn. Nhãn này nói cách khác chính là đầu ra cần tìm của bài toán.
Xét trên mặt toán học, giả sử ta có một x, ta cần tìm đi một hàm f sao cho f(x) = y, thì y chính là output của x. 
Ta dựa vào các dữ liệu đã được gán nhãn này để giám sát việc học, sao cho sai lệch khi dữ đoán với dữ liệu mới là ít nhất.

Input: x1, x2,..xn

Output: y1, y2,... yn

Hai bài toán cơ bản nhất của học không giám sát là phân lớp (classification) và hồi quy (regression).
## Học không giám sát
Dữ liệu để học không có nhãn và mục tiêu trong bài toán này cũng không phải đi gán nhãn cho dữ liệu.

Input: x1, x2,..xn

Output: mối liên quan giữa các điểm dữ liệu (association), phân nhóm các cụm dữ liệu có đặc điểm giống nhau (clustering)
## Học bán giám sát
Bạn đọc có thể ngầm đoán được dạng bài toán này, nó là kiểu 'lai' giữa hai bài toán trên. Tức dữ liệu đầu vào có nhãn và cả không có nhãn. 
Nhiệm vụ của ta trong bài toán này cũng đa dạng hơn, có thể phân lớp, phân cụm, hồi quy,... 
Đây là bài toán khá phổ biến trong thực tế, thường thì dữ liệu không có nhãn chiếm tỉ trọng cao hơn rất nhiều so với dữ liệu đã được gán nhãn.
Việc làm dữ liệu và gán nhãn đòi hỏi chi phí cao (trong vài trường hợp cần có bàn tay của chuyên gia), trong khi dữ liệu trong có nhãn thì có rất nhiều (như ta có thể claw từ internet về) với chi phí thấp
## Học củng cố
Bài toán này khá đặc biệt và khác với các bài toán khác, đôi khi chúng ta xếp nó vào một loại riêng.

Học củng cố (hay học tăng cường) là bài toán học dựa trên lý thuyết xác suất và lí thuyết trò chơi. Máy sẽ tự động đưa ra các phép thử đúng/sai để đạt được một mục tiêu nào đó, từ đó nhận được phần thường hoặc bị phạt.
Dần dần, máy có thể học được cách đi để càng đạt được nhiều phần thưởng và tránh ít bị phạt nhất, do đó, máy sẽ có các hành vi 'thông minh' hơn.
Học củng cố ứng dụng rất nhiều vào thực tế như robotic, các ứng dụng nổi tiếng của nó có thể kể ra như DeepBlue, AlphaGo, AlphaZero, Dota2OpenAI,...
