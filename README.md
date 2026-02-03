# AWS Static Website with CI/CD Pipeline
# Features
- Static website hosting trên **Amazon S3** (public read + bucket policy)
- Global CDN với **Amazon CloudFront** (HTTPS tự động, cache optimized)
- CI/CD tự động bằng **GitHub Actions**: push code → deploy trong < 60 giây
- Bảo mật: Sử dụng **Origin Access Control (OAC)** để chỉ cho phép CloudFront truy cập S3
- Chi phí: Gần 0 (AWS Free Tier)
- Tự động invalidate cache để nội dung update ngay lập tức
# Tech Stack
- **Frontend**: HTML + CSS + JavaScript (hoặc React/Vite nếu nâng cao)
- **Hosting**: Amazon S3 (Static Website)
- **CDN**: Amazon CloudFront
- **CI/CD**: GitHub Actions
- **Security**: AWS IAM, Origin Access Control
