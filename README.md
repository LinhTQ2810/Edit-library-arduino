# Edit-library-arduino
Chỉnh sửa vài thư viện arduino để phù hợp cá nhân hóa thiết bị
- Chỉnh lại tên hostname của thư viện ethernet : Lưu ý khi thay đổi chỉ chứa tối đa 12 kí tự
  Chỉnh ở file DHCP.h tại dòng 45 : #define HOST_NAME "*LinhTQ-BKAV". Sau đó lưu lại và update lại thư viện
