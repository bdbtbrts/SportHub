# SportHub-frontend
# Quy tắc chia nhánh 

* Nhánh main: chứa code final lúc báo cáo. Ko push code trực tiếp lên nhánh này
* Nhánh dev: tất cả tính năng mới code xong thì push code lên nhánh này. Tester kéo nhánh này về để kiểm thử.
* feature/[tên-tính-năng]: nháp dành cho dev để code 1 tính năng cụ thể
  * Ví dụ:* `feature/cart-ui`, `feature/login-api`. 
  * *Cách làm:* kéo từ nhánh `dev` ra, code xong thì push ngược lại vào `dev`.
