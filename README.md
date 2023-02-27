# OPRIC - ОПРИС - Электронное учебное пособие (ЭУП) по основам программирования на С++ #
## Кроссплатформенность ##
Проект выполнен с помощью платформы Xamarin.Forms, поэтому его можно запустить на различных платформах:
| Платформа | Минимальная версия системы | Доступная версия приложения
| -- | -- | -- |
| Android | 6.0 (API 23) | 1.1 |
| iOS | 10 | Preview |
| Windows | 10 (Universal Windows Platform)* | 1.1 |
| macOS | Mojave (10.14) | Preview |
***
**Возможна установка и на более ранние версии, поддерживающие UWP, например, Windows 8.1.*
## Установка и запуск ##
Установочный файл для своей целевой платформы можно найти во вкладке "Релизы" (***Releases***), которая расположена [по ссылке](https://github.com/LeoKhariton/Mobile-Cpp-Tutorial/releases).
### Android ###
Скачайте установочный файл .apk из раздела "Релизы" и запустите его на устройстве Android.  
Возможно, при установке приложение потребует дополнительное разрешение - доступ в интернет.  
Предпочтительно, чтобы системная тема Andriod была *светлая*.  
После открытия приложения загрузится главная страница - страница выбора раздела:  
![a1](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a1.jpg)  
В верхнем левом углу находится значок "гамбургер", нажатие по которому открывает всплывающее меню:
![a2](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a2.jpg)  
Вкладки меню "Студентам" и "Преподавателям" пока находятся на стадии разработки.  
В нижней части всплывающей панели расположены элементы для отправки отзывов и связи с разработчиком.  
***
Если вы нашли ошибку, просьба сообщить о ней *максимально подробно*, воспользовавшись формой для отправки отзывов. Необходимо описать ситуацию, которая привела к ошибке, и саму ошибку, желательно приложив скриншот. **Важно сообщить об ошибке как можно подробнее, чтобы разработчики могли повторить ситуацию, приведшую к ошибке и исправить ее.**  
Другой вариант сообщения об ошибке - сформировать подробный отчет о ней в виде вопроса на вкладке "Issues" **на странице данного репозитория**. Там также следует описать саму обишку, по возможности приложить скриншот и описать шаги для ее воспроизведения.  
***
Кликнув по соответствующему названию раздела, открывается страница с вкладками, на которой располагается содержимое раздела. На нижних вкладках можно выбрать "Лекцию", "Тест" или "Практическое занятие". На верхних вкладках можно выбрать конкретный подраздел лекции:  
![a3](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a3.jpg)  
или практической/лабораторной работы:  
![a4](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a4.jpg)  
После открытия вкладки "Тест" появится начальное уведомление, оповещающее пользователя о начале тестирования. При положительном ответе начнется тестирование, при отрицательном - совершится переход к началу раздела.  
![a5](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a5.jpg)  
Следующее уведомление напоминает пользователю количество времени, отведенного под тестирование:  
![a6](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a6.jpg)  
Вопросы в тесте загружаются в случайном порядке.  
Отвечать можно, нажимая на кнопки с соответствующими вариантами ответов. При верном ответе кнопка загорится зеленым цветом:  
![a7](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a7.jpg)  
При неверном ответе кнопка загорится красным цветом:  
![a8](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a8.jpg)  
После нажатия на кнопку "Завершить сейчас!", ответа на последний вопрос теста либо по окончании времени, отведенного для тестирования, подводятся его итоги: появляется соответствующее уведомление:  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a9.jpg)
### Universal Windows ###
Это приложение является универсальным приложением Windows (т.е. доступно как на десктопных платформах, так и на Windows Phone, и даже на очках смешанной реальности HoloLens, которые также функционируют на базе универсальной платформы Windows). Поэтому установочный файл имеет не привычное расширение .exe (как у программ, разработанных на платформах WPF или Windows Forms), а *.APPX* или *.APPXBUNDLE*.  
1. Скачайте файл .appxbundle из раздела "Релизы"  
2. Для того, чтобы установить приложение, необходимо сначала установить сертификат. Для этого откройте окно свойств установочного файла и перейдите к вкладке "Цифровые подписи". Выберите единственную подпись из списка и нажмите "Сведения":  
![w1](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w1.png)  
3. В открывшемся окне "Состав цифровой подписи" выберите "Просмотр сертификата":  
![w2](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w2.png)  
4. В открывшемся окне нажмите "Установить сертификат":  
![w3](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w3.png)  
5. Выберите установку сертификата для всего локального компьютера и нажмите "Далее" от имени администратора:  
![w4](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w4.png)  
6. Выберите "Доверенные корневые центры сертификации", нажмите "ОК":  
![w5](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w5.png)  
7. А затем "Далее":  
![w6](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w6.png)  
8. Нажмите "Готово":  
![w7](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w7.png)  
9. Появится следующее уведомление, оповещающее об успешной установке сертификата:  
![w8](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w8.png)  
10. Закройте окно свойств и запустите скачанный установщик:  
![w9](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w9.png)  
11. После завершения установки приложение автоматически запустится и откроется главная страница - страница выбора раздела:  
![w10](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w10.jpg)  
12. Дизайн и навигация в приложении во многом такие же, как и на Android. Основное отличие заключается в том, что если запуск производится с компьютера (но не с Windows Phone), то становятся доступны две дополнительные вкладки - онлайн-компилятор и редактор блок-схем, которые могут помочь при решении задач.  
![w11](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w11.jpg)  
![w12](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w12.jpg)  
### Что делать, если компьютер не распознает файл .appx или .appxbundle? ###
Бывают случаи, когда компьютер с ОС Windows 10 не распознает файлы .appx и .appxbundle как установочные, и предлагает открыть их с помощью какой-то программы.  
В этом случае необходимо открыть Power Shell и ввести следующую команду:
```md
add-appxpackage [путь к установочному файлу]
```
Если все необходимые пакеты установлены, то эта команда приведет к запуску установки приложения (важно, что **сертификат должен быть предварительно установлен вручную тем же способом, который описан выше в пп. 2-9**). В противном случае выведется сообщение об ошибке, возникшей в ходе устновки. Чаще всего это может быть связано с отсутствием каких-либо пакетов (например, пакета поддержки XAML необходимой версии). Их можно установить либо вручную, либо с обновлением Windows, либо с помощью Visual Studio 2019 (для этого обычно достаточно обновить VS до последней версии или подключить пакет разработки приложений для универсальной платформы Windows).  
*****
## Публикации ##
1. Международная конференция "Новые информационные технологии и системы" (НИТиС-2022), Пенза.
2. Всеросскийская конференция Нижневартовского государственного университета.
