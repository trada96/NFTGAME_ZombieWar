# NFT-Game ZombieWar

Nội dung: Người chơi được quyền tạo ra các zombie với tên bất kì.
Thuộc tính zombie:
 - Tên
 - DNA
 - Level
 - ReadyTime
 - WinCount
 - LossCount

Chức năng:
- Zombie có thể đổi tên ( nếu qua level 2), đổi dna (nếu qua level 20)
- Tấn công zombie khác: Chạy 1 hàm random, nếu kết quả trả về lớn hơn 70/100. Thông số winCount tăng thêm 1 , level cộng thêm 1 ngược lại LossCount cộng thêm 1.
- Zombie ăn kitties để tạo ra 1 zombie mới, thời gian ăn cách nhau 1 ngày
- Zombie có thể tăng level bằng cách mua với 0.001 ether.
- Có thể chuyển zombie sang các địa chỉ khác.



IDEA [ZombieFactory](https://cryptozombies.io/) 