# Thư viện, phông chữ của bên thứ ba

Toàn văn giấy phép ở thư mục [`giay-phep-ben-thu-ba/`](giay-phep-ben-thu-ba/).

## Đóng kèm trong phần mềm
| Thành phần | Dùng để | Giấy phép | Bản quyền |
|---|---|---|---|
| TipTap 3.32.0, ProseMirror, Floating UI | Soạn thảo văn bản, mẫu | MIT | Tiptap GmbH; Marijn Haverbeke và cộng sự; Floating UI contributors – `TipTap-ProseMirror-FloatingUI-MIT.txt` |
| fflate | Nén, giải nén zip (sao lưu, đọc Excel) | MIT | Arjun Barrett – `fflate-MIT.txt` |
| jsQR 1.4.0 | Đọc mã QR trên CCCD | Apache-2.0 | Cosmo Wolfe – `Apache-2.0.txt` |
| QR Code Generator for JavaScript | Tạo mã QR chấm công (bản đầy đủ) | MIT | Kazuhiko Arase (ghi trong đầu file `ban-day-du/src/qrcode.mjs`). "QR Code" là nhãn hiệu của DENSO WAVE INCORPORATED |
| SheetJS (xlsx.js) 0.18.5 | Đọc file .xls, .xlsb, .ods | Apache-2.0 | SheetJS LLC – `Apache-2.0.txt` |
| Phông Lexend | Chữ giao diện | SIL OFL 1.1 | The Lexend Project Authors – `Lexend-OFL-1.1.txt` |
| Phông IBM Plex Mono | Chữ số, mã | SIL OFL 1.1 | IBM Corp. – `IBM-Plex-Mono-OFL-1.1.txt` |
| Phông Be Vietnam Pro | Chữ app nhân viên | SIL OFL 1.1 | The Be Vietnam Pro Project Authors – `Be-Vietnam-Pro-OFL-1.1.txt` |
| Phông Patrick Hand | Chữ viết tay ở Hội nhập (app nhân viên) | SIL OFL 1.1 | Patrick Wagesreiter – `Patrick-Hand-OFL-1.1.txt` |

Phông chữ lấy từ Fontsource, chỉ gồm bộ ký tự tiếng Việt, Latin, Latin mở rộng.

## Chỉ tải khi dùng tính năng (không đóng kèm)
Hai thư viện sau được trình duyệt tải từ mạng phân phối nội dung **chỉ khi** anh/chị dùng tính năng đọc PDF hoặc đọc chữ trên ảnh (CV ứng viên, ảnh CCCD). Dữ liệu được xử lý ngay trên máy, không gửi đi; nơi cung cấp thư viện chỉ thấy địa chỉ mạng của máy tải về.
| Thành phần | Tải từ | Giấy phép |
|---|---|---|
| PDF.js (Mozilla) | cdnjs.cloudflare.com | Apache-2.0 |
| Tesseract.js (kèm dữ liệu nhận dạng chữ) | cdn.jsdelivr.net và nơi Tesseract.js mặc định lấy dữ liệu ngôn ngữ | Apache-2.0 |

Khi không tải được file `xlsx.full.min.js` đặt cạnh phần mềm, SheetJS cũng được tải từ cdnjs.cloudflare.com.
