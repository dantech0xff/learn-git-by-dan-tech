# Git Config là gì?

## Giới thiệu

- `git config` is a command line tool that is used to set or get configuration variables that control all aspects of how Git looks and operates.
- `git config` là một công cụ dòng lệnh được sử dụng để thiết lập hoặc lấy các biến cấu hình của Git. Các biến cấu hình này sẽ kiểm soát tất cả các khía cạnh của cách Git hoạt động.

## Cấu hình Global của Git

Mỗi lần commit trong Git sẽ sử dụng một danh tính được thiết lập trong cấu hình global. Điều này rất hữu ích khi bạn đang làm việc trên một dự án với nhiều người cộng tác, để mỗi lần commit có thể được xác định với tác giả đúng.

Bạn cũng có thể thiết lập danh tính của riêng mình trong một kho lưu trữ cụ thể, điều này sẽ ghi đè lên cấu hình global. Nhưng điều này không được khuyến khích, vì nó sẽ làm cho việc xác định tác giả của mỗi commit trở nên khó khăn.

- `git config --global user.name "John Doe"`: Thiết lập một tên có thể xác định được để ghi nhận khi xem lịch sử phiên bản.
- `git config --global user.email "your-git-email@email.domain"`: Thiết lập một địa chỉ email sẽ được liên kết với mỗi điểm đánh dấu lịch sử.
- Chi tiết các cấu hình global khác có thể được tìm thấy [tại đây](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration).
