# Chính sách quyền riêng tư — TÔI ĐI

*Privacy Policy — TÔI ĐI (Vietnamese public transport app). English version below.*

Cập nhật: 26/09/2026

TÔI ĐI là ứng dụng tra cứu và chỉ đường xe buýt, metro tại TP. Hồ Chí Minh và Hà Nội. TÔI ĐI là ứng dụng độc lập,
**không phải ứng dụng chính thức** và không đại diện cho Trung tâm Quản lý Giao thông công cộng TP.HCM, Tổng công ty
Vận tải Hà Nội (Transerco) hay bất kỳ cơ quan nhà nước nào.

**Tóm tắt:** không đăng nhập thì mọi dữ liệu của bạn nằm trên máy. Đăng nhập là tuỳ chọn, chỉ để đồng bộ địa điểm
đã lưu và lịch sử chuyến đi giữa các máy. Không quảng cáo, không công cụ phân tích, không bán hay chia sẻ dữ liệu.

## 1. Dữ liệu trên máy (không gửi đi đâu)

| Dữ liệu | Dùng để | Ghi chú |
|---|---|---|
| **Vị trí hiện tại** | Tìm trạm và tiện ích gần bạn, làm điểm xuất phát khi chỉ đường | Chỉ dùng khi app đang chạy, không lưu lại |
| **Vị trí khi tắt màn hình** | Chỉ sau khi bạn bấm "Bắt đầu đi": nhắc chuẩn bị xuống xe, đọc thông báo bằng giọng nói | Tự dừng khi tới nơi, khi bạn bấm Kết thúc/Dừng, hoặc khi quá thời gian dự kiến của chuyến |
| **Micro** | Chỉ khi bạn bấm nút 🎤 để tìm bằng giọng nói | App không lưu âm thanh. Việc nhận dạng do dịch vụ giọng nói của máy (thường là Google) thực hiện theo chính sách của nhà cung cấp đó |
| **Địa điểm đã lưu, tìm kiếm gần đây** | Chọn nhanh điểm đi/đến | Tìm kiếm gần đây không bao giờ rời khỏi máy |
| **Lịch nhắc chuyến đi** | Nhắc giờ đi theo lịch bạn đặt | Thông báo do máy tự hẹn giờ, không qua máy chủ |
| **Lịch sử chuyến đi** | Trang "Hành trình" (thống kê tháng), gợi ý chuyến quen để đặt nhắc | Ghi khi bạn dùng "Bắt đầu đi". Điểm đi/đến làm tròn ~100 m. Tắt được trong trang Hành trình › Ghi lại hành trình |

Thống kê "Hành trình" và gợi ý chuyến quen được **tính ngay trên máy**, không gửi đi đâu để phân tích.

## 2. Khi bạn đăng nhập (tuỳ chọn)

Đăng nhập bằng email hoặc tài khoản Google để giữ dữ liệu khi đổi máy/cài lại app. Dữ liệu được lưu trên
[Supabase](https://supabase.com/privacy) (nhà cung cấp hạ tầng, xử lý dữ liệu thay cho TÔI ĐI), truyền qua kết nối
mã hoá (HTTPS). Mỗi tài khoản chỉ đọc/ghi được dữ liệu của chính mình.

| Dữ liệu gửi lên | Dùng để |
|---|---|
| Email, mã tài khoản (và tên/ảnh đại diện nếu đăng nhập bằng Google) | Quản lý tài khoản |
| Địa điểm đã lưu (nhãn, tên, vị trí) | Đồng bộ giữa các máy |
| Lịch sử chuyến đi: điểm đi/đến (tên, vị trí làm tròn ~100 m), giờ bắt đầu/kết thúc, số hiệu tuyến, quãng đường, giá vé ước tính | Đồng bộ giữa các máy. **Tắt được riêng** trong Tài khoản › Đồng bộ lịch sử chuyến (tắt sẽ xoá bản trên máy chủ) |

Như mọi dịch vụ web, máy chủ ghi nhận địa chỉ IP của yêu cầu để vận hành và bảo mật.

Dữ liệu được giữ cho tới khi bạn xoá. **Không** gửi lên: vị trí hiện tại, đường đi thực tế lúc đang đi, tìm kiếm
gần đây, âm thanh.

## 3. Đánh giá chuyến đi (tuỳ chọn, ẩn danh)

Sau mỗi chuyến, bạn có thể bấm 👍/👎 và chọn vài nhãn (xe trễ, quá đông, sai giờ chạy…). Đánh giá lưu cùng lịch sử
chuyến trên máy (và đồng bộ nếu bạn đăng nhập). Nếu bạn để bật "Gửi ẩn danh để TÔI ĐI sửa dữ liệu", app gửi lên
máy chủ (Supabase) một báo cáo **không kèm tài khoản, tên địa điểm hay toạ độ**: thành phố, mã tuyến và mã trạm
lên/xuống, nhãn bạn chọn, ngày và giờ đi, tới trễ bao nhiêu phút. Báo cáo chỉ dùng để phát hiện dữ liệu sai; không
ai đọc được qua app. Tắt được ngay trong bảng đánh giá.

## 3b. Tải dữ liệu giao thông và bản đồ

App tải tệp dữ liệu tuyến/trạm và bản đồ offline công khai từ GitHub (repo này). Như mọi lượt truy cập web, GitHub
nhận địa chỉ IP của thiết bị ([chính sách của GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)).
App không gửi thông tin nào khác. Tìm kiếm địa điểm và tiện ích xung quanh chạy offline trên dữ liệu đã tải.

## 4. Những gì app KHÔNG làm

- Không quảng cáo, không bán hay chia sẻ dữ liệu cá nhân với bên thứ ba.
- Không dùng công cụ phân tích hành vi hay báo lỗi tự động, không theo dõi bạn giữa các ứng dụng.
- Không thu thập vị trí khi bạn không dùng app, trừ lúc đang ở chế độ "Bắt đầu đi" do bạn bật.

## 5. Xoá dữ liệu

- **Trên máy:** Hành trình › Xoá toàn bộ lịch sử; Đã lưu › Xoá; hoặc gỡ ứng dụng.
- **Tài khoản và dữ liệu trên máy chủ:** trong app vào **Tài khoản & đồng bộ › Xoá tài khoản**. Tài khoản và toàn bộ
  địa điểm đã lưu, lịch sử chuyến trên máy chủ bị xoá ngay, vĩnh viễn.
- **Không còn cài app?** Gửi yêu cầu xoá tài khoản tới email liên hệ của nhà phát triển trên trang Google Play của
  TÔI ĐI, từ chính email đã đăng ký. Yêu cầu được xử lý trong vòng 30 ngày.

## 6. Trẻ em

App không nhắm tới trẻ em dưới 13 tuổi và không cố ý thu thập dữ liệu của trẻ em.

## 7. Thay đổi và liên hệ

Chính sách thay đổi sẽ được cập nhật tại trang này, kèm ngày cập nhật ở đầu trang. Góp ý, câu hỏi:
[mở issue tại đây](https://github.com/mittohoa/toidi-data/issues) (đừng ghi thông tin cá nhân vào issue công khai),
hoặc email liên hệ trên trang Google Play.

---

# Privacy Policy — TÔI ĐI (English)

Updated: 26 September 2026

TÔI ĐI is an independent bus and metro app for Ho Chi Minh City and Hanoi. It is **not an official app** and is not
affiliated with any transit operator or government agency.

**In short:** without signing in, all your data stays on your device. Signing in is optional and only syncs saved
places and trip history across devices. No ads, no analytics, no selling or sharing of data.

**On-device only.** Location (nearby stops/amenities, trip start; with the screen off only after you tap "Start", and
it stops automatically when the trip ends, when you tap Stop, or after the expected trip time). Microphone only when you
tap the voice-search button (no audio is stored; recognition is done by your device's speech service). Saved places,
recent searches, trip reminders (scheduled locally by the device), and trip history (origin/destination rounded to
~100 m; can be turned off). Monthly stats and "usual trip" suggestions are computed on the device.

**If you sign in (optional)** with email or Google, the following is stored with [Supabase](https://supabase.com/privacy),
our infrastructure provider, over HTTPS and protected so each account can access only its own data: email and account
ID (plus Google name/avatar if you use Google sign-in); saved places; trip history (origin/destination names and
locations rounded to ~100 m, start/end times, route numbers, distance, estimated fare). Trip-history sync can be turned
off separately in Account › Sync trip history, which also deletes the server copy. Data is kept until you delete it.
Your live location, recent searches and audio are never uploaded.

**Trip ratings (optional, anonymous).** After a trip you can tap 👍/👎 and pick tags (late, crowded, wrong times…).
Ratings are stored with your trip history. If "Send anonymously to help fix the data" is on, the app sends a report
with **no account, place names or coordinates**: city, route and boarding/alighting stop codes, the tags you picked,
trip date and hour, and minutes late. It is used only to find wrong data and can be turned off in the rating sheet.

**Downloads.** Transit data and offline maps are downloaded from GitHub, which sees your IP address.

**Deletion.** On the device: Journeys (Hành trình) › Clear all history, or uninstall. Account and server data: **Account & sync ›
Delete account** in the app deletes everything immediately and permanently. If you no longer have the app, email the
developer contact address on TÔI ĐI's Google Play page from your registered email; requests are handled within 30 days.

**Children.** The app is not directed at children under 13.

**Contact:** https://github.com/mittohoa/toidi-data/issues (do not post personal information) or the developer email on
Google Play.
