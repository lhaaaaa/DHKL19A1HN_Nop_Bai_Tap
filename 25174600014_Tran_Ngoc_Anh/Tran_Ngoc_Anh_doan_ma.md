**Bài 1:**

\_git clone https://github.com/Ngocanh-25174600014/25174600014\_Tran\_Ngoc\_Anh\_bai\_tap\_chuong-3.git

\_cd 25174600014\_Tran\_Ngoc\_Anh\_bai\_tap\_chuong-3

**Bài 2 :**

\_# Mở file README.md và chỉnh sửa nội dung:

"""

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer efficitur, eros at

lacinia suscipit, magna turpis aliquam est, sit amet aliquam quam libero id mi. Ut vel

placerat risus. Sed tempor in ex vitae sodales. Donec et tempor orci. In pharetra

viverra sagittis. Vestibulum risus ante, molestie ac eros efficitur, bibendum tincidunt

turpis. In sit amet tortor gravida, ultricies ante vitae, varius tortor. Aliquam finibus

porta nulla sed gravida. Aliquam ultricies dapibus ante eget molestie. In hac habitasse

platea dictumst. Aliquam aliquam enim at massa pharetra, et vestibulum sapien

consequat. Donec accumsan quis metus at pellentesque. Morbi quis felis placerat,

interdum justo a, aliquam risus.

"""



\# Thực hiện commit và đẩy dữ liệu

git add .

git commit -m "Cập nhật nội dung README.md"

git push origin main

**Bài 3 :**

\_git checkout -b branch\_1

echo "Lorem ipsum dolor sit amet, consectetur adipiscing elit." > text\_branch\_1.txt

git add .

git commit -m "Thêm text\_branch\_1.txt"

git push origin branch\_1



\_git checkout -b branch\_2

echo "Praesent ullamcorper orci eu erat placerat sodales." > text\_branch\_2.txt

git add .

git commit -m "Thêm text\_branch\_2.txt"

git push origin branch\_2



\_git checkout main

git checkout -b branch\_3

echo "Integer sit amet nisi aliquam, tempor libero quis, cursus erat." > text\_branch\_3.txt

git add .

git commit -m "Thêm text\_branch\_3.txt"

git push origin branch\_3



\_git checkout -b branch\_4

echo "Học phần: Tin cơ sở cho ngành KHDL\\nGiảng viên: Lê Hằng Anh\\nCras ac mi nec nisi porta ultrices sed non ante." > text\_branch\_4.txt

git add .

git commit -m "Thêm text\_branch\_4.txt"

git push origin branch\_4

**Bài 4 :**

\_git branch --delete branch\_4

\_git branch --list

**Bài 5 :**

\_git pull

**Bài 6 :**

\_mkdir main\_folder

\_echo "Nội dung file 1" > main\_folder/main\_txt\_1.txt

\_echo "Nội dung file 2" > main\_folder/main\_txt\_2.txt

\_echo "Nội dung file 3" > main\_folder/main\_txt\_3.txt

\_git add .

\_git commit -m "Thêm thư mục main\_folder và 3 file bên trong"

\_git push origin main

\_git pull

**Bài 7 :**

\_git checkout branch\_1

\_git checkout -b branch\_5

\_echo "Etiam malesuada felis nulla, ac porta dui sollicitudin eget. Mauris hendrerit non"

**Bài 8 :**

\_git status

\_git checkout main

\_git merge branch\_1 --no-ff -m "Merge branch\_1 into main"

\_git merge branch\_2 --no-ff -m "Merge branch\_2 into main"

\_git merge branch\_3 --no-ff -m "Merge branch\_3 into main"

\_git merge branch\_4 --no-ff -m "Merge branch\_4 into main"                                                                                 \_ls                                                                                                                                    \_git push origin main               

\_git branch

\_cat text\_branch\_1.txt

\_cat text\_branch\_2.txt

\_cat text\_branch\_3.txt

\_cat text\_branch\_4.tx

**Bài 9 :**

\_git branch -d branch\_2

\_git branch -d branch\_3

\_git branch -d branch\_4

\_git push origin --delete branch\_2

\_git push origin --delete branch\_3

\_git push origin --delete branch\_4

\_git checkout branch\_1

\_git pull origin main

\_git push origin branch\_1



