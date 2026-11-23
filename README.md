# hethong-quanly.github.io

Trang gốc: chuyển hướng tới ứng dụng Kỹ năng Kiểm sát và chứa `/.well-known/assetlinks.json` (Digital Asset Links) để ứng dụng Android (TWA) `io.github.hethongquanly.kynangkiemsat` mở toàn màn hình, không hiện thanh địa chỉ.

- Vân tay SHA-256 hiện có: khoá ký APK phát hành trực tiếp (upload key).
- Nếu phát hành qua Google Play với Play App Signing: vào Play Console → Kiểm tra và phát hành → Thiết lập → Tính toàn vẹn của ứng dụng → Ký ứng dụng, chép «Vân tay chứng chỉ SHA-256» của *khoá ký ứng dụng* và thêm vào mảng `sha256_cert_fingerprints` (giữ vân tay cũ).
