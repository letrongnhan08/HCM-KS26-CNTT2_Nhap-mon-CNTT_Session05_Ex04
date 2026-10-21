Phần 1: Bảng so sánh Absolute Path và Relative Path 



|Tiêu chí |Absolute Path (Đường dẫn tuyệt đối) |Relative Path (Đường dẫn tương đối) |
|-|-|-|
|độ dài|Dài, ghi đầy đủ đường dẫn |Ngắn gọn hơn |
|tính di động|Thấp, phụ thuộc vào ổ đĩa và tên máy |Cao hơn, dễ chia sẻ project cho người khác |
|Độ an toàn|Thấp vì chứa tên người dùng,lộ cấu trúc máy chủ|Cao vì không lộ tên User, dấu vết phần cứng,hệ thống|



Phần 2: Lựa chọn giải pháp tối ưu và Giải thích 

\-chọn Relative Path (../data/logs.csv) vì ngắn gọn, thuận tiện khi chia sẻ project cho người khác mà không bị hư đường truyền,không phụ thuộc vào tên tài khoản User trên máy tính. 

\-Ý nghĩa ký hiệu: “..” Đại diện cho thư mục cấp cha (lùi ra 1 cấp thư mục so với thư mục hiện tại). Khi chương trình thực thi, “..” có tác dụng chỉ thị hệ thống lùi lại src → Đến thư mục D:\\FarmProject\\ (Thư mục gốc dự án)  trước khi trỏ tiếp vào thư mục (/data/logs.csv). 

