# Crawl Data shopee
## Hướng dẫn chạy
- Có 3 file chính cần quan tâm: 
  - shopee_product_id: file này để nhập các đường link shopee cần crawl
  - crawl_data_shopee_nhieu_input: File này để crawl comment về, với file này thì mình có thể để shopee_product_id có nhiều link sản phẩm, mỗi link nằm trên 1 dòng
  - crawl_data_shopee_1input: Cũng có chức năng crawl nhưng file input shopee_product_id chỉ được có 1 đường link 
- Sau khi chạy thì output sẽ được lưu trong file shopee_comments_data
## Lưu ý : Mỗi lần chạy thì comment mới sẽ được ghi đè lên comment cũ nên nếu muốn giữ data cũ thì phải copy ra 1 file mới
