# Chính sách quyền riêng tư: Bộ gõ Hán (Android)

Tác giả: Hue Hung and Claude.

Bộ gõ Hán là dự án phi lợi nhuận, miễn phí, không quảng cáo và **không thu thập dữ liệu**.

- **Những gì bạn gõ** chỉ được xử lý ngay trên máy. App không gửi chữ gõ, lịch sử hay bất kỳ thông tin nào đi đâu.
- **Lịch sử chọn chữ** (để đưa chữ hay dùng lên trước) và các tùy chọn chỉ lưu trong bộ nhớ riêng của app trên máy bạn. Ô mật khẩu và ô ở chế độ ẩn danh không được ghi nhớ. Gỡ app là xóa hết.
- **Chữ bạn gõ không bao giờ được gửi đi.** Quyền mạng (INTERNET) chỉ dùng để cập nhật app, và chỉ khi bạn cho phép (câu hỏi "Báo khi có bản mới?" hiện một lần trên bàn phím; đổi lại được trong app). Khi đó, lúc có Wi-Fi, app hỏi trang phát hành trên GitHub vài giờ một lần và tải sẵn tệp cài đặt nếu có bản mới. Không gửi đi dữ liệu nào của bạn.
- **Quyền thông báo** (POST_NOTIFICATIONS) chỉ để báo "có bản mới" ở thanh trạng thái.
- **Quyền cài ứng dụng** (REQUEST_INSTALL_PACKAGES) chỉ dùng để cài bản cập nhật của chính app, và chỉ khi bạn chạm vào thông báo hoặc nút "Cài"; Android luôn hỏi lại bạn trước khi cài. Android chỉ chấp nhận bản ký cùng khóa với bản đang cài.
- **Quyền chạy sau khi khởi động máy** (RECEIVE_BOOT_COMPLETED) chỉ để giữ lịch kiểm tra bản mới.
- **Báo lỗi** chỉ gửi khi bạn tự bấm "Báo lỗi" rồi "Gửi qua email": app mở app thư của bạn với mô tả, ảnh bạn tự chọn, thông tin máy ẩn danh (đời máy, phiên bản Android, phiên bản app, cỡ màn hình, ngôn ngữ, tùy chọn bàn phím) và lỗi văng app gần nhất nếu có. Bạn xem lại và bỏ bớt được trước khi gửi. Người nhận sẽ thấy địa chỉ email bạn dùng để gửi.
- **Lỗi văng app** được ghi vào một tệp trên máy (loại lỗi và vị trí trong mã, không có chữ bạn gõ); tệp không tự gửi đi đâu.
- App không dùng thư viện phân tích, theo dõi hay quảng cáo nào.

Khi kiểm tra bản mới, máy chủ GitHub nhận được yêu cầu từ máy bạn như mọi lần truy cập web thông thường (địa chỉ IP); xem chính sách của GitHub tại https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement.
