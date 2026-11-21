# Chính sách quyền riêng tư: Bộ gõ Hán Việt

Tác giả: Hue Hung, Claude & Gemini.

Bộ gõ Hán Việt (trên **Android**, **Windows** và **Linux**) là dự án phi lợi nhuận, miễn phí, không quảng cáo và **không thu thập dữ liệu**.

- **Những gì bạn gõ** chỉ được xử lý ngay trên máy. Ứng dụng không gửi chữ gõ, lịch sử hay bất kỳ thông tin nào đi đâu.
- **Lịch sử chọn chữ** (để đưa chữ hay dùng lên trước) và các tùy chọn chỉ lưu cục bộ trên máy bạn (bộ nhớ riêng của app trên Android; `%APPDATA%\HanIME` trên Windows; `~/.config/HanIME` trên Linux). Ô mật khẩu và ô ở chế độ ẩn danh không được ghi nhớ.
- **Chữ bạn gõ không bao giờ được gửi đi.** Quyền mạng chỉ dùng để kiểm tra hoặc tải bản cập nhật từ trang phát hành GitHub:
  - Trên **Android**: chỉ khi bạn cho phép công tắc "Báo khi có bản mới" trong app (hỏi GitHub Releases vài giờ một lần lúc có Wi-Fi và tải sẵn tệp APK; không bao giờ tự cài).
  - Trên **Windows**: chỉ khi bạn chủ động bấm nút "Kiểm tra cập nhật" trong mục Thông tin.
- **Các quyền hệ thống trên Android:**
  - **Quyền thông báo** (`POST_NOTIFICATIONS`): chỉ để báo "có bản mới" ở thanh trạng thái.
  - **Quyền cài ứng dụng** (`REQUEST_INSTALL_PACKAGES`): chỉ dùng để cài bản cập nhật của chính app khi bạn chạm xác nhận; Android chỉ chấp nhận bản ký cùng khóa với bản đang cài.
  - **Quyền chạy sau khi khởi động máy** (`RECEIVE_BOOT_COMPLETED`): chỉ để giữ lịch kiểm tra bản mới.
- **Báo lỗi** chỉ hoạt động khi bạn tự mở mục **Báo lỗi** rồi bấm soạn qua email: ứng dụng mở trình thư trên máy bạn với mô tả và thông số kỹ thuật cơ bản (phiên bản hệ điều hành, phiên bản bộ gõ, thiết lập tùy chọn; không có chữ bạn gõ). Bạn xem lại và sửa đổi toàn bộ trước khi gửi.
- **Lỗi văng app trên Android** được ghi vào một tệp cục bộ trên máy (loại lỗi và vị trí trong mã, không có chữ bạn gõ); tệp không bao giờ tự gửi đi đâu.
- Ứng dụng không dùng bất kỳ thư viện phân tích, theo dõi hay quảng cáo nào.

Khi kiểm tra bản mới trên GitHub Releases, máy chủ GitHub nhận được yêu cầu HTTP thông thường từ máy bạn (địa chỉ IP); xem chính sách của GitHub tại https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement.
