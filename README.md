# Bài 2 - Interactive Rebase

## 1. Các commit ban đầu

Ban đầu có 4 commit:

- feat: khoi tao module auth
- fix typo
- adds utility functions
- add temp file for debug

## 2. Interactive Rebase

Sử dụng lệnh:

git rebase -i --root

Cấu hình:

pick commit-1 feat: khoi tao module auth
squash commit-2 fix typo
squash commit-3 adds utility functions
drop commit-4 add temp file for debug

## 3. Commit sau khi Rebase

Thông điệp commit sau khi gộp:

feat: hoan thien module authentication

## 4. Kiểm tra

Sử dụng:

git log --oneline

Kết quả chỉ còn commit:

feat: hoan thien module authentication

File temp.txt cũng đã được loại bỏ hoàn toàn.
