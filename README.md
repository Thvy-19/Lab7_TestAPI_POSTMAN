#Tên đề tài: Xây dựng bộ kiểm thử API tự động
#Mục tiêu: 
Tìm hiểu khái niệm REST API, HTTP method, status code và JSON. 
Tạo Postman Collection có cấu trúc rõ ràng cho các thao tác CRUD. 
Viết test script để tự động xác minh response. 

#Kịch bản 1: Kiểm thử GET - lấy danh sách
URL: https://jsonplaceholder.typicode.com/posts
Kết quả mong đợi: Status: 200 OK
Hình ảnh minh họa kết quả: 01.GET
 
#Kịch bản 2: Kiểm thử GET - lấy theo ID
URL: https://jsonplaceholder.typicode.com/posts/1
Kết quả mong đợi: Status: 200 OK
Hình ảnh kết quả minh họa: 02.GET - ID


#Kịch bản 3: Kiểm thử POST
URL: https://jsonplaceholder.typicode.com/posts 
Kết quả mong đợi: 201 Created
Hình ảnh minh họa kết quả: 03.POST

#Kịch bản 4: Kiểm thử PUT
URL: https://jsonplaceholder.typicode.com/posts/1 
Kết quả mong đợi: Status: 200 OK
Hình ảnh minh họa kết quả: 04.PUT

#Kịch bản 5: Kiểm thử PATCH
URL: https://jsonplaceholder.typicode.com/posts/1
Kết quả mong đợi: Status 200 OK
Hình ảnh minh họa: 05. PATCH

#Kịch bản 6: Kiểm thử DELETE
URL: https://jsonplaceholder.typicode.com/posts/1 
Kết quả mong đợi: Status: 200 OK
Hình ảnh minh họa: 06. DELETE

#Kết luận
Đề tài đã xây dựng quy trình kiểm thử REST API bằng Postman, bao gồm tạo Collection, gửi các HTTP request, viết assertion bằng JavaScript và chạy bộ kiểm thử tập trung. Các nội dung này giúp người học hiểu cách xác minh response ở tầng API và tổ chức test case có thể tái sử dụng. Kết quả cuối cùng cần được hoàn thiện bằng số liệu thực tế và ảnh chụp màn hình từ môi trường thực hành.  
