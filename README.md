# Play Together Giftcode Redeemer

Trang web đơn giản để tự động nhập giftcode cho nhiều tài khoản Play Together.

## Tính năng

- ✅ Tự động redeem giftcode cho nhiều tài khoản
- ✅ Hiển thị progress bar theo thời gian thực
- ✅ Hiển thị kết quả chi tiết cho từng tài khoản
- ✅ Giao diện đẹp, responsive
- ✅ Tổng kết cuối cùng với số liệu thành công/thất bại

## Cách sử dụng

1. Truy cập website
2. Nhập giftcode vào ô input
3. Nhấn nút "Redeem Giftcode"
4. Đợi hệ thống xử lý và xem kết quả

## Cấu hình

Để thêm hoặc chỉnh sửa danh sách tài khoản, mở file `index.html` và tìm phần `ACCOUNTS`:

```javascript
const ACCOUNTS = [
    { roleId: "YOUR-ROLE-ID", name: "Tên người dùng" },
    // Thêm tài khoản mới vào đây
];
```

## Demo

[Live Demo](https://your-username.github.io/play-together-redeemer/)

## License

MIT
