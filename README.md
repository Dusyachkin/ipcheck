# IPcheck service

Проверяет внешний IP, если отличается от заданного закрывает браузер и отправляет уведомление
1. Закинуть папку на диск C 

> C:\\IPCheck

 *(можно в любое место, главное поменять путь лога в .ps1 и в Create/Delete.bat)*

2. В .ps1 файле вставить нужный IP, заменить имя площадки, добавить данные для ящика.

3. Запустить CreateService от админа

4. Если удалить, DeleteService от админа

Каждые 3 минуты проверяет IP и закрывает браузер, если IP отличается от того, который в скрипте. Так же отправляет письмо на почту.

Можно добавить любую нужную функцию вместо блокировки браузера, если нужно.
![image](https://github.com/user-attachments/assets/64648049-fca6-4204-ab2d-76bb3dfc5c4d)


