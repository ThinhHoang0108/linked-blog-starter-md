![[Diagram.svg]]

*Note*:
- Vì để tránh trùng lặp trong bảng role ta phải lấy khóa ngoại roleId ở bảng User.
- Bảng rating phải chia ra thành nhiều bảng tương ứng với mỗi model được user rating
- Bảng nào chứa khóa ngoại thì @ManyToOne + @JoinColumn
