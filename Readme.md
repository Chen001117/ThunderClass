# ThunderClass

This repository implements ThunderClass, a Video conference software written in C++. It supports multiple functions, including chat, quiz, sharing screen, user management and calling the roll. 

## Usage

Click `./app/ThunderClassDemo.exe` to open software.

#### login

First, Log in as one of the three identity

```
administrator: 
	account : Admin
	password: Admin
teacher:
	account : test_teacher
	password: test_teacher
student:
	account : test_student
	password: test_student
```



#### Teacher

Click `上课` to start the class. Once you starting the class, students can access your class by entering your ip address. You can click `下课` to dismiss the class. 

Click `共享屏幕` to share the screen with students.

Click `发送语音` to share your voice with students.

Click `随机提问` to ask a question to a random student.

Click `出题` to make a quiz. You can Click `显示结果` to check the students' answer once you releasing the quiz.



#### Student

Entering teacher's ip address and click `进入课堂` to enter a specific class. If the teacher is sharing his screen or voice, you can receive it once entering the class.

You can interact with teacher in chatbox.

Click `退出课堂` to leave the class. Your performance (like score of the exams, time you focus on the app and the walltime you enter and leave the class) will be reported to teacher once you leave the class or the class is dismissed.



#### administrator

You can add/remove/edit account in this page.



## Code

All codes are accompanied by detailed comments. Check `./code` for more details.