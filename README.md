<p align="center">
   <a href="https://www.uit.edu.vn/">
      <img src="https://i.imgur.com/WmMnSRt.png" border="none">
   </a>
</p>
<h1 align="center">
    DATA ANALYST
</h1>

## GIỚI THIỆU ĐỀ TÀI
+ **Dữ liệu**: Amazon Sale Report
+ ** Nội dung đề tài :
  + Dataset này chứa các thông tin chi tiết về các đơn hàng được đặt trên Amazon, bao gồm thông tin về sản phẩm, dịch vụ vận chuyển, thông tin khách hàng, và các chi tiết tài chính liên quan. Các cột này cho phép phân tích chi tiết về hiệu suất bán hàng, xu hướng mua sắm của khách hàng, và các yếu tố địa lý ảnh hưởng đến doanh số bán hàng.
  + Dataset gồm có các cột dữ liệu như sau:
  * 1. index:
Giải thích: Đây là chỉ số (index) của các hàng trong DataFrame. Chỉ số này được tự động tạo ra khi dữ liệu được nhập vào DataFrame và giúp xác định vị trí của từng hàng trong dataset.
  * 2. Order ID:
Giải thích: Mã định danh duy nhất cho mỗi đơn hàng. Mỗi đơn hàng trên Amazon đều có một Order ID duy nhất, giúp theo dõi và quản lý đơn hàng.
  * 3. Date:
Giải thích: Ngày mà đơn hàng được tạo hoặc giao dịch diễn ra. Cột này cho phép phân tích thời gian, xu hướng đặt hàng theo ngày, tháng, hoặc năm.
  * 4. Status:
Giải thích: Trạng thái hiện tại của đơn hàng. Một số trạng thái phổ biến bao gồm:
Cancelled: Đơn hàng đã bị hủy.
Shipped: Đơn hàng đã được gửi đi.
Shipped - Delivered to Buyer: Đơn hàng đã được giao cho người mua.
  * 5. Fulfilment:
Giải thích: Phương thức thực hiện đơn hàng. Có hai loại chính:
Merchant: Đơn hàng được thực hiện bởi người bán hàng.
Amazon: Đơn hàng được thực hiện bởi Amazon.
  * 6. Sales Channel:
Giải thích: Kênh bán hàng qua đó đơn hàng được đặt. Trong trường hợp này, kênh bán hàng là Amazon.in, tức là trang web Amazon tại Ấn Độ.
  * 7. ship-service-level:
Giải thích: Mức độ dịch vụ giao hàng được chọn cho đơn hàng, chẳng hạn như:
Standard: Dịch vụ giao hàng tiêu chuẩn.
Expedited: Dịch vụ giao hàng nhanh.
  * 8. Category:
Giải thích: Loại sản phẩm được đặt hàng, ví dụ: T-shirt, Shirt, Trousers, Blazzer, v.v. Đây là thông tin quan trọng để phân tích danh mục sản phẩm nào được bán nhiều nhất.
  * 9. Size:
Giải thích: Kích cỡ của sản phẩm được đặt hàng. Các kích cỡ thông thường bao gồm S, M, L, XL, 3XL, 6XL, v.v.
  * 10. Courier Status:
Giải thích: Trạng thái của dịch vụ chuyển phát, thể hiện quá trình giao hàng. Các trạng thái phổ biến bao gồm:
On the Way: Đang trong quá trình giao hàng.
Shipped: Đã được gửi đi.
Cancelled: Dịch vụ chuyển phát đã bị hủy.
  * 11. Qty:
Giải thích: Số lượng sản phẩm được đặt trong đơn hàng. Thông tin này rất hữu ích khi phân tích tổng số lượng sản phẩm bán ra.
  * 12. currency:
Giải thích: Đơn vị tiền tệ của giao dịch. Trong dataset này, đơn vị là INR (Rupee Ấn Độ).
  * 13. Amount:
Giải thích: Tổng số tiền của đơn hàng (sau khi đã tính tất cả các chi phí). Cột này có thể được sử dụng để phân tích doanh thu.
  * 14. ship-city:
Giải thích: Thành phố nơi đơn hàng được giao. Thông tin này giúp xác định vị trí địa lý của khách hàng.
  * 15. ship-state:
Giải thích: Bang nơi đơn hàng được giao. Kết hợp với ship-city, cột này cung cấp thông tin chi tiết hơn về địa điểm giao hàng.
  * 16. ship-postal-code:
Giải thích: Mã bưu chính của địa chỉ giao hàng. Đây là mã xác định khu vực cụ thể trong thành phố hoặc bang.
  * 17. ship-country:
Giải thích: Quốc gia nơi đơn hàng được giao. Trong trường hợp này, quốc gia là IN (Ấn Độ).
  * 18. B2B:
Giải thích: Biến boolean (TRUE/FALSE) cho biết đây có phải là đơn hàng kinh doanh đến kinh doanh (B2B) hay không. TRUE cho biết đây là một giao dịch giữa các doanh nghiệp.
  * 19. fulfilled-by:
Giải thích: Phương thức giao hàng, ví dụ như Easy Ship. Đây là dịch vụ giao hàng mà Amazon thực hiện để giúp người bán vận chuyển sản phẩm.
  * 20. New:
Giải thích: Đây có thể là một cột đánh dấu các đơn hàng mới hoặc có thông tin đặc biệt nào đó. Tuy nhiên, trong hình ảnh không có dữ liệu cho cột này.
  * 21. PendingS:
Giải thích: Cột này không có dữ liệu trong hình ảnh, nên không thể giải thích chính xác chức năng của nó.

## Tên
<a name="thanhvien"></a>
| STT | Họ và tên | MSSV | Email |
|:-----:|:-------:|:-------:|:-------:|
| 1 | [Nguyễn Đặng Đức Minh](https://github.com/Minh-begintolovecoding)| 21521131 | 21521131@gm.uit.edu.vn |

