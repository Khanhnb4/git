# git
### Setting up git
git config --global user.name "Nguyen Bao Khanh"
git config --global user.email "khanh.nguyenbao@ivnd.com.vn"
git config --list
nano ~/.gitconfig

### Dưới đây là một số câu lệnh Git thường được sử dụng:

1. Clone một repository từ remote về máy cục bộ:
   ```
   git clone <URL_repository>
   ```

2. Xem trạng thái của repository:
   ```
   git status
   ```

3. Xem lịch sử commit:
   ```
   git log
   ```

4. Tạo một nhánh mới:
   ```
   git branch <branch_name>
   ```

5. Chuyển sang một nhánh khác:
   ```
   git checkout <branch_name>
   ```

6. Tạo và chuyển sang một nhánh mới:
   ```
   git checkout -b <branch_name>
   ```

7. Thêm tệp hoặc thư mục vào staged area:
   ```
   git add <file_name>            # Thêm một tệp cụ thể
   git add .                      # Thêm tất cả các tệp thay đổi
   git add <directory_name>       # Thêm một thư mục cụ thể
   ```

8. Commit các thay đổi đã staged:
   ```
   git commit -m "Commit message"
   ```

9. Push các thay đổi lên remote repository:
   ```
   git push origin <branch_name>
   ```

10. Lấy các thay đổi mới nhất từ remote repository:
    ```
    git pull origin <branch_name>
    ```

11. Xem các nhánh hiện có và vị trí HEAD:
    ```
    git branch -a
    ```

12. Xóa một nhánh:
    ```
    git branch -d <branch_name>
    ```

13. Hủy bỏ các thay đổi chưa staged:
    ```
    git checkout -- <file_name>
    ```

14. Hủy bỏ các thay đổi đã staged:
    ```
    git reset HEAD <file_name>
    ```

15. Xem sự khác biệt giữa các thay đổi:
    ```
    git diff <file_name>
    ```

 `git --help` 
