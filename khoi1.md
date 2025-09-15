 Hồi quy tuyến tính đa biến
 Hồi quy tuyến tính đa biến (Multiple Linear Regression) là một mở rộng của hồi quy tuyến
 tính đơn biến, trong đó đầu vào x không chỉ là một đặc trưng (feature) mà là một vector
 chứa nhiều đặc trưng. Điều này cho phép mô hình dự đoán giá trị đầu ra y dựa trên sự kết
 hợp tuyến tính của nhiều biến đầu vào.
 Trong hồi quy tuyến tính đơn biến, hàm dự đoán có dạng:
 h(x) = w0 +w1x
 với x là một đặc trưng duy nhất, w0 là bias, và w1 là trọng số.
 Trong hồi quy tuyến tính đa biến, đầu vào x là một vector x = [x1,x2,...,xn]T, và hàm dự
 đoán được biểu diễn dưới dạng tích vô hướng:
 h(x) = wTx = w0+w1x1+w2x2+···+wnxn
 trong đó:
 • w=[w0,w1,...,wn]T: Vector trọng số (bao gồm bias w0).
 • x=[1,x1,x2,...,xn]T: Vector đặc trưng (thêm 1 để tương ứng với bias).
 Sự khác biệt chính giữa hồi quy tuyến tính đơn biến và đa biến nằm ở số lượng đặc trưng:
 • Hồi quy đơn biến chỉ sử dụng một đặc trưng, phù hợp với các bài toán đơn giản.
 • Hồi quy đa biến sử dụng nhiều đặc trưng, cho phép mô hình học được các mối quan
 hệ phức tạp hơn giữa các đặc trưng và đầu ra.

• w=[w0,w1,...,wn]T: Vector trọng số (bao gồm bias w0).
 • x=[1,x1,x2,...,xn]T: Vector đặc trưng (thêm 1 để tương ứng với bias).
 Sự khác biệt chính giữa hồi quy tuyến tính đơn biến và đa biến nằm ở số lượng đặc trưng:
 • Hồi quy đơn biến chỉ sử dụng một đặc trưng, phù hợp với các bài toán đơn giản.
 • Hồi quy đa biến sử dụng nhiều đặc trưng, cho phép mô hình học được các mối quan
 hệ phức tạp hơn giữa các đặc trưng và đầu ra.