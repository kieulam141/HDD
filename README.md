# Cơ bản về Ổ đĩa cứng (HDD)

### 1. Khái niệm

`Ổ đĩa cứng (Hard disk driver)` là một kiểu thiết bị lưu trữ dữ liệu (storage device).

### 2. Cấu trúc

#### a. Sector

- Vùng vật lý chứa dữ liệu nhỏ nhất trong ổ cứng kể cả khi đọc và ghi.
- Các sector được chứ trong 1 track.
- Thông thường 1 sector chứa được 512 byte dữ liệu.
- Dung lượng track càng nhỏ, dung lượng mà 1 sector có thể chứa càng ít.

<img src="http://i.imgur.com/jT9swOg.png" />

#### b. Track

- Mỗi vòng trong đồng tâm trên đĩa gọi là track.
- Mỗi đĩa có từ 312 đến 2048 track.
- Các track càng gần trục thì có dung lượng càng nhỏ.

<img src="http://i.imgur.com/Z8OFFSf.png" />


#### c.Cylinder

- Cylinder bao gồm những track có cùng bán kính.

<img src="http://i.imgur.com/KMCueQG.png" />

### 3. Câu lệnh làm việc với ổ đĩa
- fdisk: Phân vùng đĩa.
- sfdisk: Show ra các thông tin về phân vùng trên đĩa, và rất nguy hiểm hơn là có thẻ tái phân vùng.
- parted: tạo, xóa, thay đổi kích cỡ, kiểm tra, và sao chép các phân vùng.
- resize2fs: resize các định dạng file ext2, ext3, ext4.

### 4.Tham Khảo
- 1.http://www.langson.gov.vn/ubnd/node/117
