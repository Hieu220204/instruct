# instruct
Cài đặt Git

- Bước 1: Tải xuống và cài đặt Git từ https://git-scm.com/downloads.

- Bước 2: Mở terminal (cmd) và nhập lệnh git --version để kiểm tra phiên bản Git đã được cài đặt.

Khởi tạo kho lưu trữ Git

- Bước 1: Tạo thư mục mới cho dự án của bạn.
    mkdir <tên_thư_mục>
- Bước 2: Mở terminal và di chuyển đến thư mục dự án.
    cd <tên_thư_mục>
- Bước 3: Khởi tạo kho lưu trữ Git bằng lệnh git init.
    git init

Thêm và lưu trữ thay đổi

- Bước 1: Thêm các file bạn muốn quản lý vào kho lưu trữ bằng lệnh git add. Ví dụ: git add README.md.
    git add README.md
- Bước 2: Lưu trữ thay đổi bằng lệnh git commit. Nhập mô tả ngắn gọn về thay đổi của bạn.
    git commit -m "Thêm file README.md"

Xem lịch sử thay đổi

- Bước 1: Xem danh sách các commit bằng lệnh git log.
    git log
- Bước 2: Xem chi tiết một commit cụ thể bằng lệnh git show. Ví dụ: git show HEAD.
    git show HEAD

Hợp nhất nhánh

- Bước 1: Tạo nhánh mới bằng lệnh git checkout -b <tên_nhánh>. Ví dụ: git checkout -b dev.
    git checkout -b dev
- Bước 2: Thực hiện thay đổi trên nhánh mới.
- Bước 3: Hợp nhất nhánh mới vào nhánh chính bằng lệnh git merge. Ví dụ: git merge dev.
    git checkout master
    git merge dev

Chia sẻ dự án

- Bước 1: Tạo tài khoản trên https://github.com/.

- Bước 2: Khởi tạo kho lưu trữ mới trên Github.

- Bước 3: Liên kết kho lưu trữ cục bộ với kho lưu trữ Github bằng lệnh git remote add origin <url_kho_lưu_trữ_Github>. Ví dụ: git remote add origin https://github.com/user/project.git.
    git remote add origin https://github.com/user/project.git
- Bước 4: Gửi thay đổi lên Github bằng lệnh git push. Ví dụ: git push origin master.
    git push origin master

