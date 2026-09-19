# SportHub-frontend
# Quy tắc chia nhánh 

* Nhánh main: chứa code final lúc báo cáo. Ko push code trực tiếp lên nhánh này
* Nhánh dev: tất cả tính năng mới code xong pull request lên nhánh này. Tester kéo nhánh này về để kiểm thử.
* feature/[tên-tính-năng]: Nhánh làm việc hàng ngày của Dev. 
  * Ví dụ:* `feature/cart-ui`, `feature/login-api`. 
  * *Cách làm:* kéo từ nhánh `dev` ra, code xong thì tạo pull request gộp ngược lại vào `dev`.
