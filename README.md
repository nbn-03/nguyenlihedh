# nguyenlihedh  
1. (chuowng1) hệ thống máy tính hoạt động như 1 interrupt driven (quá trình điều khiển ngắt là một kĩ thuật trong lĩnh vực điện tử và lập trình máy tính, cho phép một sự kiện ngoại vi hoặc yêu cầu ưu tiên (gọi là ngắt) được phát hiện và xử lí bởi máy tính trong quá trình nhiệm vụ chính đang được thực hiện thông qua vecto ngắt. khi một ngắt xảy ra, máy tính sẽ tạm dừng công việc dang làm, lưu trạng thái hiện tại và thực hiện một việc khác mà ngắt yêu cầu. sau khi việc này hoàn thành, máy tính sẽ tiếp tục công việc trước đó từ trạng thái đã lưu. quá trình điều khiển ngắt giúp máy tính xử lí một cách linh hoạt các tác vụ đa luồng và đsấp ứng nhanh chóng với các sự kiện xuất hiện ngẫu nhiên trong hệ thống. tuy nhiên nếu nhiều ngắt thì các ngắt sẽ phải chờ xử lí lần lượt). ví dụ: khi bạn đặt một báo đổ chuông trên máy tính hoặc điện thoại di động, máy tính cài đặt một đếm ngược thời gian và sử dụng một timer. Khi thời gian kết thúc, timer tạo ra một ngắt để thông báo về việc kết thúc thời gian đặt trước. Hệ thống máy tính ngắt công việc hiện tại và thực hiện hành động cần thiết, chẳng hạn như xuất hiện thông báo hoặc báo đổ chuông để thông báo rằng thời gian đã kết thúc
2. bảng vecto ngắt chứa tất cả các địa chỉ của tất cả các chương trình phục vụ ngắt; chương trình phục vụ ngắt được thực hiện bở CPU  
3. ![image](https://github.com/nbn-03/nguyenlihedh/assets/98254107/ebc41607-0198-4f36-9e6f-39d8a9539f70)
4. trong hệ thống bộ nhớ tốc độ cao nhất là register (thanh ghi) thành phần nằm trong bộ nhớ CPU còn register không phải bộ nhớ tiêp đến cache-bộ nhớ đệm nhưng tốc độ nhanh như lại có dung lượng thấp
5. caching - kỹ thuật tăng tốc xử lí của hệ thống. bằng cách lưu trữ dữ liệu hàng ngày vào bộ nhớ cache, để giảm thời gian truy cập dữ liệu từ bộ nhớ chậm hơn như ổ cứng hoặc mạng,... chú ý với dữ liệu chỉ được truy cập và sử dụng 1 lần tốc độ dùng caching sẽ chậm hơn tốc độ không dùng caching
6. hệ điều hành có chế độ kép (dual-mode) để bảo vệ tài nguyên hệ thống
7. ![image](https://github.com/nbn-03/nguyenlihedh/assets/98254107/0296cc84-172b-48f1-9c32-621edeb167d6)  
8. khái niệm hệ điều hành: là một chương trình (mã nguồn và dữ liệu - các tham số hệ thống) đã được cài đặt sẵn có chức năng thỏa mãn tối đa yêu cầu của người dùng. là chương trình trung gian giao tiếp giữa phần cứng và người sử dụng. user sẽ giao tiếp bằng 2 cách: giao tiếp dòng lệnh, giao tiếp biểu tượng.  
9. khái niệm về tiến trình là một chương trình đang xử kí (hoạt đông và thực hiện), sở hữu một con trỏ lệnh (một thanh ghi (register) trong bộ xử lý của máy tính, nhiệm vụ chính của nó là lưu trữ địa chỉ của lệnh hiện tại mà bộ xử lý đang thực hiện), tập hợp các thanh ghi và các biến
10. phân biệt tiến trình và chương trình: chương trình là một thực thể thụ động chứa lệnh và dữ liệu để tiến hành 1 tác vụ(công việc). khi thực hiện các lệnh chương trình chuyển thành tiến trình. một chương trình có thể có nhiều tiến trình; tiến trình là một thực thể hoạt động
11. phân loại hệ điều hành: đơn chương trình; đa chương trình; thời gian thực; song song và phân tán
12. hệ điều hành đơn chương trình: toàn bộ hệ thống máy tính phục vụ 1 chương trình từ lúc bắt đầu khi chương trình đưa và bộ nhớ đến khi kết thúc (nó chiếm toàn bộ tài nguyên nên không thể đưa chương trình khác vào)
13. hệ điều hành đa chương trình: tại một thời điểm có nhiều chương trình có mặt đồng thời trong bộ nhớ và đều có nhu cầu được phân phối bộ nhớ và CPU. gồm 2 loại: hđh hoạt động theo lô và hđh chia sẻ thời gian
14. hệ điều hành thời gian thực: đảm bảo giải quyết tiến trình không muộn hơn thời gian xác định được gọi là deadtime. nếu muộn hơn tiến trình không còn ý nghĩa
15. hệ điều hành song song:  phối hợp nhiều bộ xử lí để nhằm giải quyết một vấn đề cho nhanh nhất
16. hệ điều hành phân tán: mỗi bộ xử lí nói chung có chương trình làm việc riêng
17. chức năng hệ điều hành: quản lí các tiến trình; quản lí và phân phối tài nguyên; hoạt động mạng; hệ thống bảo vệ; hệ thống thông dịch lệnh
18. quản lí các tiến trình: các chương trình để hoàn thành một một việc đều phải thực hiện các tiến trình. hđh chịu trách nhiệm: tạo và xóa tiến trình; tạm ngưng và tiếp tục tiến trình; cung cấp cơ chế đồng bộ hóa và sự giao tiếp tiến trình.
19. tài nguyên gồm: bộ nhớ chính, file, hệ thống vào ra I/O; bộ nhớ thứ cấp (bộ nhớ ngoài)
20. các dịch vụ của hệ điều hành: thực hiện chương trình; thực hiện vào ra I/O; thao tác với hệ thống file; giao tiếp; phát hiện lỗi
21. system call là giao diện giao tiếp giữa ứng dụng đang chạy (tiến trình) với HĐH và có thể truyền các tham số qua các thanh ghi, bảng nhớ hoặc ngăn xếp; bản chất là lời gọi hàm của hđh
22. (chuowng2) để một tiến trình hoạt động nó cần được cung cấp đầy đủ tài nguyên cần thiết và được CPU tiếp nhận và thực hiện
23. 
