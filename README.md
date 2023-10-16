# nguyenlihedh  
1.  
2. khái niệm hệ điều hành: là một chương trình (mã nguồn và dữ liệu - các tham số hệ thống) đã được cài đặt sẵn có chức năng thỏa mãn tối đa yêu cầu của người dùng. là chương trình trung gian giao tiếp giữa phần cứng và người sử dụng. user sẽ giao tiếp bằng 2 cách: giao tiếp dòng lệnh, giao tiếp biểu tượng.  
3. khái niệm về tiến trình là một chương trình đang xử kí (hoạt đông và thực hiện), sở hữu một con trỏ lệnh (một thanh ghi (register) trong bộ xử lý của máy tính, nhiệm vụ chính của nó là lưu trữ địa chỉ của lệnh hiện tại mà bộ xử lý đang thực hiện), tập hợp các thanh ghi và các biến
4. phân biệt tiến trình và chương trình: chương trình là một thực thể thụ động chứa lệnh và dữ liệu để tiến hành 1 tác vụ(công việc). khi thực hiện các lệnh chương trình chuyển thành tiến trình. một chương trình có thể có nhiều tiến trình; tiến trình là một thực thể hoạt động
5. phân loại hệ điều hành: đơn chương trình; đa chương trình; thời gian thực; song song và phân tán
6. hệ điều hành đơn chương trình: toàn bộ hệ thống máy tính phục vụ 1 chương trình từ lúc bắt đầu khi chương trình đưa và bộ nhớ đến khi kết thúc (nó chiếm toàn bộ tài nguyên nên không thể đưa chương trình khác vào)
7. hệ điều hành đa chương trình: tại một thời điểm có nhiều chương trình có mặt đồng thời trong bộ nhớ và đều có nhu cầu được phân phối bộ nhớ và CPU. gồm 2 loại: hđh hoạt động theo lô và hđh chia sẻ thời gian
8. hệ điều hành thời gian thực: đảm bảo giải quyết tiến trình không muộn hơn thời gian xác định được gọi là deadtime. nếu muộn hơn tiến trình không còn ý nghĩa
9. hệ điều hành song song:  phối hợp nhiều bộ xử lí để nhằm giải quyết một vấn đề cho nhanh nhất
10. hệ điều hành phân tán: mỗi bộ xử lí nói chung có chương trình làm việc riêng
11. chức năng hệ điều hành: quản lí các tiến trình; quản lí và phân phối tài nguyên; hoạt động mạng; hệ thống bảo vệ; hệ thống thông dịch lệnh
12. quản lí các tiến trình: các chương trình để hoàn thành một một việc đều phải thực hiện các tiến trình. hđh chịu trách nhiệm: tạo và xóa tiến trình; tạm ngưng và tiếp tục tiến trình; cung cấp cơ chế đồng bộ hóa và sự giao tiếp tiến trình.
13. tài nguyên gồm: bộ nhớ chính, file, hệ thống vào ra I/O; bộ nhớ thứ cấp (bộ nhớ ngoài)
14. các dịch vụ của hệ điều hành: thực hiện chương trình; thực hiện vào ra I/O; thao tác với hệ thống file; giao tiếp; phát hiện lỗi
15. system call là giao diện giao tiếp giữa ứng dụng đang chạy (tiến trình) với HĐH và có thể truyền các tham số qua các thanh ghi, bảng nhớ hoặc ngăn xếp; bản chất là lời gọi hàm của hđh
16. để một tiến trình hoạt động nó cần được cung cấp đầy đủ tài nguyên cần thiết và được CPU tiếp nhận và thực hiện
17. 
