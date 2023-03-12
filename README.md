# Windows2019RDP-AP
Windows Server 2019 Github with RDP Access (ngrok AP)
Repo link: https://github.com/baokhanh2206/VPSauto

Tạo VPS miễn phí cấu hình 2cpu-7gb Ram FREE với Github:

- Click Fork góc phải màn hình để lưu vào Github của bạn.
- Truy cập https://dashboard.ngrok.com để lấy NGROK_AUTH_TOKEN
- Ở Github vào Settings > Secrets > New repository secret
 + Phần Name: điền NGROK_AUTH_TOKEN
 + Phần Value: truy cập https://dashboard.ngrok.com/auth/your-authtoken Copy và Paste Your Authtoken vào
- Ấn Add secret
- Chuyển qua Action > CI > Run workflow
- Reload lại trang và ấn CI > build 
- Ấn mũi tên xuống ở Connect To Your RPD để lấy IP, User, Password. 


