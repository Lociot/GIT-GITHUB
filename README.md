## Phần 01 Git config
Set config
```cpp
git config --global user.name "Name"
git config --global user.email "Email"
```
Get config
```cpp
git config --global user.name
git config --global user.email
```
## Phần 02 Creating repo/ Cloning repo
```cpp
git init
```
```cpp
git remote add origin git_url
git remote -v
```
```cpp
git clone git_url
```
```cpp
git pull origin master
```
```cpp
git push origin master
```
## Phần 03 Staging
Check status
```cpp
git status
```
To add a file to staging area
```cpp
git add FILE_NAME
```
To remove a file from staging area
```cpp
git rm --cached FILE_NAME
```
To add all file to staging area
```cpp
git add .
```

## Phần 04 Committing
To show all the commits with detail
```cpp
git log
```
To show all(n) the commits in one line
```
git log --oneline
```
```
git log --oneline -n
```
To commit
```cpp
git commit -m "comment"
```
## Phần 05 Git stash
```cpp
#. Đang code dở file main.cpp
#. Cần chuyển sang nhánh khác để sửa bug gấp
```
Lưu vào stash
```cpp
git stash save -m "comment"
```
Lấy ra toàn bộ stash
```cpp
git stash list
```
Khôi phục stash gần nhất và xóa khỏi danh sách
```cpp
git stash pop
```
Khôi phục stash gần nhất nhưng không xóa khỏi danh sách
```cpp
git stash apply
```
Xóa một stash
```cpp
git stash drop stash@{0}
```
Xóa mọi stash
```
Xóa tất cả stash
```
## Phần 06 Git ignore
```
Ex:
.env
/Folder
*.txt
```
## Phần 07 Reverting & Reset
## Phần 08 Branch
## Phần 09 Merging branch
## Phần 10 Git rebase
