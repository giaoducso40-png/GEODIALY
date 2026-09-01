GEODÀNẴNG 2026 — BẢN WEB ONLINE V5.3 TOÀN CẢNH VÀ HẢI ĐỒ

1. Giải nén toàn bộ tệp ZIP vào một thư mục.
2. Bấm đúp tệp index.html để mở bằng trình duyệt.
3. Cần kết nối Internet để xem các lớp nền OpenStreetMap, ảnh vệ tinh Esri và OpenTopoMap.
4. Ranh giới hành chính, quả địa cầu và ảnh minh họa đã được đóng gói sẵn; không cần máy chủ riêng.

ĐƯA LÊN GITHUB PAGES
- Tải toàn bộ nội dung bên trong thư mục này lên nhánh dùng cho GitHub Pages; index.html phải nằm ở thư mục gốc được xuất bản.
- Không đổi tên hoặc tách riêng các thư mục assets, data và vendor.
- Bật HTTPS để chức năng “Vị trí tôi” hoạt động ổn định trên trình duyệt hiện đại.

CHẾ ĐỘ GIÁO VIÊN VÀ NHẬT KÍ
- Mật khẩu mở chế độ giáo viên: admin@
- Nhật kí, bài làm, ghi chú, điểm và tiến độ được lưu trong trình duyệt của từng thiết bị.
- Học sinh chọn “Tải hồ sơ JSON”; giáo viên vào “Mở chế độ giáo viên” rồi chọn “Nhập hồ sơ HS” để tổng hợp nhiều hồ sơ trên máy giáo viên.
- Có thể xuất toàn bộ nhật kí đang xem thành CSV.
- GitHub Pages là dịch vụ web tĩnh nên không thể tự đồng bộ dữ liệu từ nhiều thiết bị. Muốn theo dõi trực tiếp toàn lớp theo thời gian thực cần kết nối thêm cơ sở dữ liệu hoặc máy chủ có xác thực; bản này không gửi âm thầm dữ liệu học sinh ra ngoài.

GHIM VỊ TRÍ
- Sau khi chọn “Ghim”, chạm bản đồ để hiện tọa độ và địa chỉ. Kim có thể kéo để hiệu chỉnh.
- Địa chỉ chi tiết được tra cứu trực tuyến; nếu dịch vụ tra cứu tạm thời không phản hồi, hệ thống dùng tên xã/phường từ dữ liệu địa giới đóng gói sẵn.
- Tọa độ trong vùng Hoàng Sa luôn trả về “Đặc khu Hoàng Sa, thành phố Đà Nẵng, Việt Nam”; tọa độ trong vùng Trường Sa luôn trả về “Đặc khu Trường Sa, tỉnh Khánh Hòa, Việt Nam”, không dùng kết quả địa chỉ bên ngoài cho hai vùng này.

TOÀN CẢNH VÀ HẢI ĐỒ BIỂN ĐẢO
- Ở mức toàn cảnh và thu nhỏ, lớp nền đang chọn luôn được giữ nguyên để quan sát rõ đường phố, ảnh vệ tinh hoặc địa hình; Hoàng Sa và Trường Sa có nhãn cờ Việt Nam gọn phía trên.
- Khi chọn trực tiếp Hoàng Sa/Trường Sa hoặc đưa tâm bản đồ vào vùng đảo từ mức thu phóng 6, hệ thống chuyển sang hải đồ vector cục bộ và tắt lớp nền bên ngoài.
- Cơ chế này áp dụng thống nhất cho bốn nền: Đường phố, Ảnh vệ tinh, Địa hình và Địa hình tổng hợp.
- Khi trở về đất liền hoặc thu nhỏ về toàn cảnh, lớp nền đã chọn và bảng thông tin đất liền được tự động khôi phục.
- Hải đồ vector hiển thị nền biển liền mạch, lưới tọa độ, ký hiệu đảo san hô, cờ Việt Nam và tên hành chính tiếng Việt; các ký hiệu dùng cho học tập, không dùng cho hàng hải hoặc xác lập ranh giới pháp lý.

ẢNH TƯ LIỆU
- Phố cổ Hội An: David McKelvey, CC BY 2.0, Wikimedia Commons.
- Khu đền tháp Mỹ Sơn: Philip Nalangan, CC BY 4.0, Wikimedia Commons.
- Cù Lao Chàm: Lê Uy Lân, CC BY-SA 4.0, Wikimedia Commons.
- Đèo Hải Vân: Tuabiht Rellahcs, CC BY 2.0, Wikimedia Commons.

DỮ LIỆU BẢN ĐỒ
- Đường biên và 94 đơn vị cấp xã được đóng gói trong data/danang-boundaries.js.
- Hệ tọa độ WGS 84. Nền bản đồ trực tuyến giữ nguyên thông tin ghi công trên bản đồ.
