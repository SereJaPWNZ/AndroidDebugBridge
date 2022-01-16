# Android Debug Bridge
![Logo](https://github.com/SereJaPWNZ/AndroidDebugBridge/blob/master/assert/Logo.png)

## Home Work

 1. Отобразить подключённый девайс в консоли.

        adb devices   

 2. Вывести адрес приложения todolist в системе Android

        adb shell "pm list packages -f | grep todolist"

 3. Установить .apk файл приложениия todolist на телефон с компьютера через  ADB

        adb install /путь до файла/todolist.apk 

 4. Сделать скриншот запущенного приложения todolist и сразу скопировать на компьютер в одной команде.

        adb shell screencap /storage/emulated/0/DCIM/gr_24.png&&adb pull /storage/emulated/0/DCIM/gr_24.png C:/Users/oofat/Documents/

 5. Вывести в консоль логи приложения todolist

        adb logcat com.android.todolist

 6. Скопировать логи приложения todolist на компьютер.

        adb logcat com.android.todolist >log.txt

 7. Удалить приложение todolist с телефона через ADB

        adb uninstall com.android.todolist

Сценарий напишите в .txt файл.
.txt сценарий и .log файл приложения "To Do List" выгружайте на GitHub.
## 📫 How to reach me
[![Telegram](https://img.shields.io/badge/-Telegram-000000?style=for-the-badge&logo=telegram&logoColor=00ff88)](https://t.me/res1stpwnz)
[![Email](https://img.shields.io/badge/-gmail-000000?style=for-the-badge&logo=gmail&logoColor=red)](mailto:oofatherxomgoo@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-linkedin-000000?style=for-the-badge&logo=linkedin&logoColor=3955a8)](https://linkedin.com/in/morkovkinsergey)
