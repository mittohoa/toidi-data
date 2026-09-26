# TÔI ĐI — dữ liệu

Dữ liệu giao thông công cộng **TP. Hồ Chí Minh** và **Hà Nội** đã xử lý sẵn cho app TÔI ĐI:
bản đồ nền offline, tuyến, trạm, lộ trình, lịch chạy, giá vé, địa điểm.

Dữ liệu được phát hành dưới dạng **[Releases](../../releases)**, cập nhật định kỳ.
App đọc `manifest.json` của bản mới nhất:

```
https://github.com/mittohoa/toidi-data/releases/latest/download/manifest.json
```

## Mỗi bản phát hành gồm

| File | Nội dung |
|---|---|
| `manifest.json` | Danh sách file (sha256, dung lượng), ngày dữ liệu, tóm tắt thay đổi so với bản trước |
| `CHANGES.md` | Ghi chú thay đổi (tuyến mới/ngừng, đổi lộ trình, giờ chạy, giá vé) |
| `<city>-transit.json.gz` | Tuyến, trạm, lộ trình, lịch chạy, giá vé |
| `<city>-places.json.gz` | Tên đường + địa điểm có tên, dùng cho ô tìm kiếm |
| `<city>-map.pmtiles` | Bản đồ nền vector ([PMTiles](https://docs.protomaps.com/pmtiles/), schema Protomaps v4) |

`<city>`: `hcm`, `hanoi`.

## Nguồn và giấy phép

- **Bản đồ nền, địa điểm, tên đường, metro Hà Nội:** © [OpenStreetMap](https://www.openstreetmap.org/copyright)
  contributors, giấy phép [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Bản đồ dựng từ
  [Protomaps](https://protomaps.com) basemap. Phần dữ liệu dẫn xuất từ OSM ở đây cũng theo ODbL.
- **Tuyến buýt, trạm, lịch chạy, giá vé:** tổng hợp từ thông tin công khai của Trung tâm Quản lý Giao thông
  công cộng TP.HCM (Go!Bus) và Tổng công ty Vận tải Hà Nội — Transerco (timbus.vn). Bản quyền dữ liệu thuộc
  các đơn vị này. Repo không phải kênh chính thức của họ.

## Lưu ý

**Dữ liệu chỉ để tham khảo.** Lịch chạy là biểu đồ giờ (giờ hoạt động + tần suất), không phải vị trí xe thực tế;
tuyến, trạm, giá vé có thể đã thay đổi sau ngày dữ liệu ghi trong `manifest.json`. Hãy kiểm tra thông tin
chính thức trước những chuyến đi quan trọng.

Thấy dữ liệu sai? Mở [issue](../../issues) kèm mã tuyến / tên trạm.
