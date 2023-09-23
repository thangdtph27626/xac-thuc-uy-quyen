# Phân biệt authenticator và authorization


Authentication and authorization là hai quy trình bảo mật thông tin quan trọng mà quản trị viên sử dụng để bảo vệ hệ thống và thông tin. Authentication xác minh danh tính của người dùng hoặc dịch vụ và Authorization  xác định quyền truy cập của họ. Mặc dù hai thuật ngữ này nghe có vẻ giống nhau nhưng chúng đóng vai trò riêng biệt nhưng không kém phần quan trọng trong việc bảo mật ứng dụng và dữ liệu. Hiểu được sự khác biệt là rất quan trọng. Kết hợp lại, chúng xác định tính bảo mật của một hệ thống. Bạn không thể có giải pháp an toàn trừ khi bạn đã định cấu hình chính xác cả Authentication and authorization

## Authentication  là gì?
Authentication  là một quá trình xác minh rằng ai đó hoặc điều gì đó đúng như họ nói. Các hệ thống công nghệ thường sử dụng một số hình thức xác thực để bảo mật quyền truy cập vào ứng dụng hoặc dữ liệu của ứng dụng đó. Ví dụ: khi bạn cần truy cập một trang web hoặc dịch vụ trực tuyến, bạn thường phải nhập tên người dùng và mật khẩu của mình. Sau đó, nó sẽ so sánh tên người dùng và mật khẩu bạn đã nhập với bản ghi có trên cơ sở dữ liệu của nó. Nếu thông tin bạn gửi trùng khớp, hệ thống sẽ coi bạn là người dùng hợp lệ và cấp cho bạn quyền truy cập. Xác thực hệ thống trong ví dụ này giả định rằng chỉ bạn mới biết tên người dùng và mật khẩu chính xác. Do đó, nó xác thực bạn bằng cách sử dụng nguyên tắc của điều gì đó mà chỉ bạn mới biết.

## Mục đích của Authentication là gì?
Mục đích của việc Authentication  là để xác minh rằng ai đó hoặc cái gì đó là ai hoặc cái gì mà họ tuyên bố là. Có nhiều hình thức xác thực. Ví dụ, thế giới nghệ thuật có các quy trình và thể chế xác nhận một bức tranh hoặc tác phẩm điêu khắc là tác phẩm của một nghệ sĩ cụ thể. Tương tự như vậy, các chính phủ sử dụng các kỹ thuật xác thực khác nhau để bảo vệ tiền tệ của họ khỏi bị làm giả. Thông thường, Authentication bảo vệ các mục có giá trị và trong thời đại thông tin, nó bảo vệ hệ thống và dữ liệu.

## Authorization   là gì?
Authorization  là quy trình bảo mật xác định cấp độ truy cập của người dùng hoặc dịch vụ. Trong công nghệ, chúng tôi sử dụng Authorization  để cấp cho người dùng hoặc dịch vụ quyền truy cập vào một số dữ liệu hoặc thực hiện một hành động cụ thể. Nếu chúng ta xem lại ví dụ về quán cà phê, Rahul và Lucia có những vai trò khác nhau trong quán cà phê. Vì Rahul là nhân viên pha chế nên anh ấy chỉ có thể đặt và xem đơn hàng. Mặt khác, Lucia, với vai trò là người quản lý, cũng có thể có quyền truy cập vào tổng doanh số bán hàng hàng ngày. Vì Rahul và Lucia có công việc khác nhau trong quán cà phê nên hệ thống sẽ sử dụng danh tính đã được xác minh của họ để cấp cho mỗi người dùng các quyền riêng lẻ. Điều quan trọng cần lưu ý ở đây là sự khác biệt giữa xác thực và Authorization . Xác thực xác minh người dùng (Lucia) trước khi cho phép họ truy cập,

## Các loại Authorization  phổ biến
Hệ thống Authorization  tồn tại dưới nhiều hình thức trong một môi trường công nghệ điển hình. Ví dụ: Danh sách kiểm soát truy cập (ACL) xác định người dùng hoặc dịch vụ nào có thể truy cập vào một môi trường kỹ thuật số cụ thể. Họ thực hiện việc kiểm soát truy cập này bằng cách thực thi các quy tắc cho phép hoặc từ chối dựa trên cấp độ Authorization  của người dùng. Chẳng hạn, trên bất kỳ hệ thống nào, thường có người dùng phổ thông và người dùng cấp cao hoặc quản trị viên. Nếu người dùng chuẩn muốn thực hiện các thay đổi ảnh hưởng đến bảo mật của họ, ACL có thể từ chối quyền truy cập. Mặt khác, quản trị viên có quyền thực hiện các thay đổi về bảo mật nên ACL sẽ cho phép họ làm như vậy.

Một loại Authorization  phổ biến khác là quyền truy cập vào dữ liệu. Trong bất kỳ môi trường doanh nghiệp nào, bạn thường có dữ liệu với các mức độ nhạy cảm khác nhau. Ví dụ: bạn có thể có dữ liệu công khai mà bạn tìm thấy trên trang web của công ty, dữ liệu nội bộ chỉ nhân viên mới có thể truy cập và dữ liệu bí mật mà chỉ một số ít cá nhân mới có thể truy cập. Trong ví dụ này, Authorization  xác định người dùng nào có thể truy cập các loại thông tin khác nhau.


## Sự khác nhau authenticator và authorization

<table>
    <thead>
        <tr>
            <th>Authentication</th>
            <th>Authorization</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Authentication xác nhận danh tính của bạn để cấp quyền truy cập vào hệ thống.</td>
            <td>Authorization xác định xem bạn có được phép truy cập tài nguyên không.</td>
        </tr>
        <tr>
            <td>Đây là quá trình xác nhận thông tin đăng nhập để có quyền truy cập của người dùng.</td>
            <td>Đó là quá trình xác minh xem có cho phép truy cập hay không.</td>
        </tr>
        <tr>
            <td>Nó quyết định liệu người dùng có phải là những gì anh ta tuyên bố hay không.</td>
            <td>Nó xác định những gì người dùng có thể và không thể truy cập.</td>
        </tr>
        <tr>
            <td>Authentication thường yêu cầu tên người dùng và mật khẩu.</td>
            <td>Các yếu tố xác thực cần thiết để authorization có thể khác nhau, tùy thuộc vào mức độ bảo mật.</td>
        </tr>
        <tr>
            <td>Authentication là bước đầu tiên của authorization vì vậy luôn luôn đến trước.</td>
            <td>Authorization được thực hiện sau khi authentication thành công.</td>
        </tr>
        <tr>
            <td>Ví dụ, sinh viên của một trường đại học cụ thể được yêu cầu tự xác thực trước khi truy cập vào liên kết
                sinh viên của trang web chính thức của trường đại học. Điều này được gọi là authentication.</td>
            <td>Ví dụ, authorization xác định chính xác thông tin nào sinh viên được phép truy cập trên trang web của
                trường đại học sau khi authentication thành công.</td>
        </tr>
    </tbody>
</table>
