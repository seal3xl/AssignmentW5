# AssignmentW5
***
## 要求三：基本的 SQL 指令

### insert into user (name,username,passward) values('Seal','ply','ply');
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-1.jpg)
***
### select * from user;
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-2.jpg)
***
### select count(*) from user;
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-3.jpg)
***
### select * from user order by time desc;
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-4.jpg)
***
### ~~<font color="red">select * from user where id between 2 and 4 order by time desc;</font>~~
### select * from user order by time desc limit 1,3;
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-5.jpg)
***
### select * from user where username='ply';
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-6.jpg)
***
### select * from user where username='ply' and passward='ply';
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-7.jpg)
***
### update user set name='丁滿' where username='ply';
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-8.jpg)
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-8-2.jpg)
***
### delete from user;
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/3-9.jpg)
***
## 要求四：結合資料表 SQL JOIN 的操作 (Optional)

### select user.name,message.content from user right join message on user.id=message.user_id;
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/4-1.jpg)
***
### select user.name,message.content from user right join message on user.id=message.user_id where user.username='ply';
![image](https://raw.githubusercontent.com/seal3xl/AssignmentW5/main/img/4-2.jpg)
***
