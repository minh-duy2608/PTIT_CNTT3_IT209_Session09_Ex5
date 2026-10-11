## Mục tiêu
Sử dụng Docker Compose để khởi chạy dịch vụ web Nginx.

## Cấu hình
- Image: nginx:alpine
- Port: 8082:80

## Các lệnh kiểm tra

```bash
docker compose up -d
docker compose ps
curl http://localhost:8082
docker compose down
```

## Kết quả mong đợi
- Service web chạy thành công.
- Truy cập localhost:8082 hiển thị trang chào mừng Nginx.
- Docker Compose dừng dịch vụ thành công.
