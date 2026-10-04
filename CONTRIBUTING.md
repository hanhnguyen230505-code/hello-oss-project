# Hướng dẫn đóng góp

Cảm ơn bạn đã quan tâm đến dự án hello-oss-project!

## Cách báo lỗi (Issue)

1. Kiểm tra tab Issues xem lỗi đã được báo cáo chưa.

2. Nếu chưa, chọn **New issue** và cung cấp:

   - Tiêu đề ngắn gọn, rõ nghĩa

   - Các bước tái hiện lỗi

   - Kết quả mong đợi và kết quả thực tế

   - Môi trường (hệ điều hành, phiên bản GCC)

## Cách gửi Pull Request

1. Fork repository về tài khoản của bạn.

2. Tạo nhánh mới từ `main`, ví dụ `fix/ten-loi` hoặc `feature/ten-tinh-nang`.

3. Thực hiện thay đổi, đảm bảo chương trình vẫn build và chạy đúng.

4. Commit theo quy tắc bên dưới, push lên fork của bạn.

5. Mở Pull Request về nhánh `main`, mô tả rõ thay đổi và liên kết

   Issue liên quan (ví dụ: `Closes #3`).

6. Phản hồi các góp ý của người review.

## Quy tắc đặt tên commit

Định dạng: `<loại>: <mô tả ngắn>`

| Loại | Ý nghĩa |

|---|---|

| `feat` | Thêm tính năng mới |

| `fix` | Sửa lỗi |

| `docs` | Thay đổi tài liệu |

| `refactor` | Tái cấu trúc code, không đổi hành vi |

| `test` | Thêm hoặc sửa test |

Ví dụ: `docs: add build instructions to README`

Viết ở thì mệnh lệnh, không quá 72 ký tự, không kết thúc bằng dấu chấm.