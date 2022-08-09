# Sound-Cloud-project
Trang Soundcloud là một trang web cho phép người dùng upload và chia sẻ các bài hát. Chúng ta sẽ thu thập thông tin về các nghệ sĩ, ban nhạc, podcast và người sáng tác âm nhạc trên trang Soundcloud 

# Thu thập dữ liệu
Thu nhập các thông tin từ trang https://soundcloud.com/ bằng cách parse HTML và thông qua API. Với mỗi cách, dữ liệu thu thập gồm 3 file: user, playlist, track đặt trong 2 thư mục Api_data & Crawl_data

# Phân tích dữ liệu
## Tiền xử lý dữ liệu
• Dữ liệu có bao nhiêu dòng và bao nhiêu cột?
• Dữ liệu có các dòng bị lặp không?
• Mỗi cột có ý nghĩa gì?
• Mỗi cột hiện đang có kiểu dữ liệu gì? Có cột nào có kiểu dữ liệu chưa phù hợp để có thể xử lý tiếp không?
• Với mỗi cột có kiểu dữ liệu dạng số (numerical), các giá trị được phân bố như thế nào?
• Số-lượng/tỉ-lệ các giá trị thiếu?
• Min? max? → Có gì bất thường không?
• Với mỗi cột có kiểu dữ liệu dạng phân loại (categorical), các giá trị được phân bố như thế nào?
• Số-lượng/tỉ-lệ các giá trị thiếu?
• Số lượng các giá trị khác nhau? Show một vài giá trị → Có gì bất thường không?
## Khám phá dữ liệu
1. Thể loại phổ biến/được yêu thích/được nghe nhiều/được tương tác nhiều nhất trong năm 2020
2. Thể loại phổ biến nhất tại khu vực châu Âu
3. Xét 1 playlist, có mối tương quan nào giữa số lượt thích và số lượt chia sẻ ? 
4. Có tồn tại mối quan hệ nào giữa số lượng track mà 1 người dùng xác thực (verified user) đăng lên SoundCloud và số lượng người theo dõi của user ấy? 
5. Mối tương quan giữa likes_count, playback_count, download_count, reposts_count, comment_count
6. Mùa nào trong 4 mùa là mùa có nhiều bài hát được sáng tác và đăng tải nhất?
