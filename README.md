# FinalProject-NoiThatMUJI 

Link demo: https://trgiahuy14.github.io/FinalProject-NoiThatMUJI/
- - - - -
- Trước khi code thì xoá source cũ, git clone source mới từ github về để update code mới nhất
hoặc nếu vẫn muốn giữ source cũ ở máy thì bật terminal lên gõ:
```bash
git fetch origin + tên branch (huy, son, sang)
```

Có code mới rồi thì vào đúng branch để code:
```bash
git checkout + tên branch (huy, son, sang)
```

- Sau khi code xong:
```bash
git add + tên file vừa sửa
```
```bash
git commit -m "nội dung" (tốt nhất nên ghi ngày tháng update code là được rồi)
```
Xong đẩy lên github:
```bash
git push origin + tên branch (huy, son, sang)
```
Nhớ push đúng branch tên mình, push xong t vào review rồi mới gộp vô branch main

Cách fix lỗi git pull...:
```bash
git pull origin + tên branch (huy, son, sang, main) --no-rebase
```