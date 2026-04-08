# Axiom_Auto_daily

===========================================================================
        HƯỚNG DẪN CHẠY TOOL AXIOM AUTO (FILE CHÍNH: MAIN.JS)
===========================================================================

1. CÀI ĐẶT MÔI TRƯỜNG (LÀM LẦN ĐẦU)
---------------------------------------------------------------------------
Mở Terminal/CMD tại thư mục chứa tool và chạy lệnh sau để cài thư viện:

npm install fs-extra axios https-proxy-agent chalk@4.1.2 uuid moment-timezone node-machine-id

2. CẤU TRÚC THƯ MỤC CẦN CHUẨN BỊ
---------------------------------------------------------------------------
Đảm bảo thư mục của bạn có đầy đủ các file sau:

- main.js            : File code chính của tool.
- config.json        : File cấu hình (Mẫu bên dưới).
- wallets.txt        : Danh sách ví (mỗi dòng 1 ví).
- proxy.txt          : Danh sách proxy (mỗi dòng 1 proxy định dạng http://user:pass@ip:port).
- ref.txt            : Danh sách mã mời (mỗi dòng 1 mã).
- User_agents.txt    : Danh sách User Agent (mỗi dòng 1 chuỗi).
- license.txt        : File chứa key (Tool tự tạo sau khi bạn nhập key lần đầu).

* Mẫu file config.json:
{
  "apiKey": "69786444-245c-482d-888e-c351f8224765",
  "maxThreads": 5,
  "threadStaggerDelay": 2,
  "actionDelayMin": 5,
  "actionDelayMax": 10,
  "switchDelayMin": 30,
  "switchDelayMax": 60
}

3. CÁCH CHẠY TOOL CHI TIẾT
---------------------------------------------------------------------------
Bước 1: Nhập lệnh khởi động:
   node main.js

Bước 2: Kích hoạt License (Chỉ lần đầu)
   - Tool sẽ hỏi: "=> Vui lòng dán Key của bạn vào đây:"
   - Bạn Copy Key được cấp, chuột phải vào Terminal để dán và nhấn Enter.
   - Tool tự động lấy HWID máy bạn để khóa vào Key.

Bước 3: Chờ tool chạy tự động
   - Tool tự Check License -> Register ví -> Bind Ref -> Daily Checkin -> Làm Quest.
   - Sau khi chạy hết ví, tool tự động chờ đến 07:00 Sáng hôm sau (giờ VN) để chạy lại.

4. CÁC LƯU Ý QUAN TRỌNG
---------------------------------------------------------------------------
- HWID: Key chỉ chạy được trên 1 máy. Muốn đổi máy phải báo Admin reset HWID.
- PROXY: Tool dùng proxy ngẫu nhiên từ danh sách. Nếu proxy chết tool sẽ báo lỗi kết nối.
- FILE UREF.TXT: Sau khi chạy, mã mời của chính ví của bạn sẽ được lưu vào file này.
- LỖI LICENSE: Nếu nhập sai key hoặc dùng key máy khác, tool sẽ tự xóa nội dung file license.txt để bạn nhập lại key mới.
===========================================================================

Tham Gia NHóm tele : https://t.me/HVchannelss

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 1 Tháng 4u - 15u 6thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây







