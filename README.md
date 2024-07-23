# لتحويل الصوت الى نص مكتوب 

#  نقوم بأستخدام برنامج Visual studio code لكتابة كود html وJavascript لتصميم الواجهه وphp لربطة بقاعدة البيانات 

![image](https://github.com/user-attachments/assets/78c31880-ef31-4c72-87e1-50776ac3a143)
![image](https://github.com/user-attachments/assets/01f28091-fa26-493c-976b-40572d9e0b89)
![image](https://github.com/user-attachments/assets/5e5cdabe-60c6-49a2-8593-6a2b3c2bf866)


## هذا الجزء من الكود يتضمن الواجهة الأمامية للصفحة. يوجد زر "Start" يتم النقر عليه لبدء الاستماع إلى الميكروفون. عندما يتم التعرف على الكلام، يتم عرضه في عنصر div. كما يتم إرسال النص المتعرف عليه إلى صفحة PHP (Speak.php) باستخدام XMLHttpRequest .


![image](https://github.com/user-attachments/assets/9f4f9d61-ed3c-4e6e-8672-6c0f6c5c8d64)


## كود php  يعمل على استقبال النص المرسل من صفحة HTML السابقة بأستخدام ($_GET["x"]) ويقوم بحفظه في قاعدة بيانات MySQL. كما يوجد جزء لاستقبال البيانات في حالة الإرسال باستخدام طريقة POST، ولكنه غير مستخدم في الكود الحالي.  



## نقوم بأنشاء قاعدة بيانات بأسم Speak ثم نقوم بأنشاء جدول بأسم s_p لاستقبال النص المكتوب يوجد فيه عمودين Num,Text

![image](https://github.com/user-attachments/assets/1a144b64-cac3-4cea-afcc-c770ad0d3f19)

## اخيراً تم انشاء واجهه لكتابة النص الذي يتحدث به المستخدم وتسجيله في قاعدة البيانات


https://github.com/user-attachments/assets/9ea5ed83-9321-432c-8dc8-32de3acec1fb




