# Báo cáo Bài 1: Khởi tạo Local Repository và Cấu hình danh tính

## Các lệnh đã thực hiện:

1. Khởi tạo Git: 
   ```bash
   git init
   ```
2. Cấu hình danh tính cục bộ:
   ```bash
   git config --local user.name "TranHoangThanh"
   git config --local user.email "tranthanh02012006@gmail.com"
   ```
3. Thêm tệp vào Staging Area: 
   ```bash
   git add README.md
   ```
4. Commit: 
   ```bash
   git commit -m "Initial commit: khoi tao du an va cau hinh danh tinh"
   ```

## Kết quả kiểm tra:

**Kiểm tra cấu hình:**
```bash
tranhoangthanh@MacBook-Air-2 bai1 % git config --local --list
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
user.name=TranHoangThanh
user.email=tranthanh02012006@gmail.com
```

**Kiểm tra lịch sử commit:**
```bash
tranhoangthanh@MacBook-Air-2 bai1 % git log --oneline
5551fd8 (HEAD -> main) Initial commit: khoi tao du an va cau hinh danh tinh
```
