# Brackets-Mudim
Trên Linux, khi bạn gõ Tiếng Việt thông qua các bộ gõ như IBus, nó sẽ không trực tiếp nhúng ký tự ngay khi đang gõ. Chính vì thế, chức năng autocomplete trong Brackets sẽ không đưa ra gợi ý trong lúc bạn gõ qua nguyên âm và các ký tự đặt dấu.
Extension Bộ gõ Tiếng Việt Mudim sẽ giúp khắc phục vấn đề đó.

## Cài đặt

###Cách 1
1. Tải **Brackets-Mudim** về máy https://github.com/baivong/brackets-mudim/archive/master.zip
2. Giải nén và chép vào thư mục **extensions / user** của Brackets (**Help > Show Extensions Folder**).
3. Khởi chạy lại Brackets (**F5**).

###Cách 2
1. Mở trình quản lý Extension (**File > Extension Manager...**).
2. Tìm Extension *Bộ gõ Tiếng Việt Mudim* với từ khoá ```Mudim```
3. **Install** và khởi chạy lại Brackets (**F5**).

## Hướng dẫn
Bật / tắt bằng cách chọn trên menu **Edit > Bộ gõ Mudim**.

Chọn kiểu gõ **Debug > Open Preferences File** tìm thông số ```baivong.mudim.method``` và thay giá trị tương ứng với kiểu gõ bạn cần:

1. VNI
2. Telex
3. Viqr
4. Tổng hợp
5. Tự động

Ví dụ, chọn kiểu gõ **VNI** thì dùng ```"baivong.mudim.method": 1```

Lưu lại.
