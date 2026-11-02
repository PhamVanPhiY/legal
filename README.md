# DoubleP Tech - Legal Documentation (GitHub Pages)

Tập tài liệu chính sách bảo mật (Privacy Policy) và điều khoản sử dụng (Terms of Use) chuẩn cho ứng dụng **Color Page ASMR: Art Coloring** (`com.doubleptech.draw.color.page.asmr`).

---

## 📁 Các file bao gồm:
1. `index.html`: Cổng trang chủ điều hướng chung (Legal Center).
2. `privacy-policy.html`: Chính sách bảo mật chuẩn Google Play (tuân thủ AdMob, Qonversion, COPPA trẻ em, GDPR).
3. `terms-of-use.html`: Điều khoản sử dụng chuẩn về gói VIP Subscription, gia hạn tự động qua Google Play.

---

## 🚀 Hướng dẫn đưa lên GitHub Pages trong 2 phút (Hoàn toàn Miễn phí & Vĩnh viễn):

### Cách 1: Tải lên trực tiếp trên web GitHub (Không cần dòng lệnh)
1. Truy cập [GitHub](https://github.com/) $\rightarrow$ Đăng nhập $\rightarrow$ Bấm nút xanh **New** để tạo Repository mới.
2. Đặt tên Repo: ví dụ `legal` (hoặc `policy`, `doublep-tech-policy`).
3. Chọn chế độ: **Public** $\rightarrow$ Bấm **Create repository**.
4. Trên trang vừa tạo, bấm vào dòng chữ: **uploading an existing file**.
5. Kéo thả cả 3 file (`index.html`, `privacy-policy.html`, `terms-of-use.html`) từ thư mục này vào $\rightarrow$ Bấm **Commit changes**.
6. Vào tab **Settings** của Repo $\rightarrow$ Ở menu bên trái chọn **Pages**:
   - Ở mục **Build and deployment**:
     - **Source**: Chọn `Deploy from a branch`.
     - **Branch**: Chọn `main` (thư mục `/root`) $\rightarrow$ Bấm **Save**.
7. Đợi khoảng 1 phút, GitHub sẽ cấp cho bạn một đường link HTTPS chính thức:
   - **Privacy Policy**: `https://<tên-github-của-bạn>.github.io/<tên-repo>/privacy-policy.html`
   - **Terms of Use**: `https://<tên-github-của-bạn>.github.io/<tên-repo>/terms-of-use.html`

---

### Cách 2: Dùng Git dòng lệnh
```bash
cd "C:\Users\ECER\Desktop\doublep-tech-legal"
git init
git add .
git commit -m "Add legal documents for Color Page ASMR"
git branch -M main
git remote add origin https://github.com/<tên-github-của-bạn>/<tên-repo>.git
git push -u origin main
```
Sau đó vào **Settings** $\rightarrow$ **Pages** bật branch `main` là xong!

