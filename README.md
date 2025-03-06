- # سطر أوامر لينكس (Linux Command Line)

- ### إدارة الملفات والمجلدات (File & Directory Management)
```bash
naggix@naggix-studio:~$ ls          # عرض محتويات المجلد الحالي للعمل
naggix@naggix-studio:~$ ls -l       # عرض محتويات المجلد الحالي بشكل قائمة مفصلة
naggix@naggix-studio:~$ ls -a       # عرض جميع محتويات الملفات حتى المخفية منها
```
![](./images/file_and_dir_management/0001.png)

```bash
naggix@naggix-studio:~$ cd          # تغيير المجلد الحالي إلى مجلد المستخدم
naggix@naggix-studio:~$ cd /        # تغيير المجلد الحالي إلى مجلد Root
naggix@naggix-studio:~$ cd /etc     # تغيير المجلد الحالي إلى المجلد المضمن بعد الأمر
```
![](./images/file_and_dir_management/0002.png)

```bash
naggix@naggix-studio:~$ pwd          # طباعة مجلد العمل الحالي
```
![](./images/file_and_dir_management/0003.png)

```bash
naggix@naggix-studio:~$ mkdir dir_name              # إنشاء مجلد جديد في مجلد العمل الحالي
naggix@naggix-studio:~$ mkdir dir_name -m=mode      # تحديد صلاحيات المجلد أثناء إنشائه
```
![](./images/file_and_dir_management/0004.png)

```bash
naggix@naggix-studio:~$ touch file_name          # إنشاء ملف جديد في مجلد العمل الحالي
```
![](./images/file_and_dir_management/0005.png)

```bash
naggix@naggix-studio:~$ rm file_name         # حذف ملف من مجلد العمل الحالي
naggix@naggix-studio:~$ rm -r dir_name       # حذف مجلد بما يحتويه تباعا للمجلدات التي داخله
naggix@naggix-studio:~$ rm -f file_name      # حذف ملف بالقوة دون إظهار أي تنبيهات
naggix@naggix-studio:~$ rm -i file_name      # إظهار تنبيه عند كل عملية حذف
```
![](./images/file_and_dir_management/0006.png)

```bash
naggix@naggix-studio:~$ cp old_dir/file new_dir/file    # نسخ مجلد من مكان لآخر
naggix@naggix-studio:~$ cp old_name new_name            # إعادة تسمية الملف
```
![](./images/file_and_dir_management/0007.png)