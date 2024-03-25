# OPRIC &ndash; ОПРИС &ndash; Мультидисциплинарное электронное учебное пособие
## Аннотация
Это мультидисциплинарное кроссплатформенное электронное учебное пособие (ЭУП).  
В приложении:
- собраны лекции, практические задания и тесты самопроверки (в настоящий момент доступны дисциплины "Программирование на языке С/С++" и "Численные методы");  
- доступны вспомогательные сервисы &ndash; С++ компилятор, редактор блок-схем, а также построитель графиков (*только в десктопной версии*);  
- есть личный кабинет, где ведется рейтинг лучших студентов и можно отслеживать свой прогресс.  
При входе в личный кабинет от имени преподавателя с десктопной платформы появляется возможность видеть статистику всех студентов, а также редактировать учебный контент;  
- есть возможность сменить тему на тёмную;  
- можно работать как с доступом к интернету, так и без него (без доступа к сети доступны *все функции, за исключением аккаунта*).

![видеодемонстрация версии 2](https://github.com/LeoKhariton/Opric/blob/main/Test/видео1.gif)

## Установка
Начиная с версии 1.0, приложение разрабатывалось с помощью кроссплатформенных фрейморков, поэтому его можно запустить на широком круге устройств:
| Версия | Поддерживаемые платформы<br/>(минимальная версия) |
| :--: | -- |
| 0 | Windows 7 |
| [1](https://github.com/LeoKhariton/Opric/releases/tag/v1.2.2) | &#9989;**Android** 6.0 (API 23)<br/>**iOS** 10<br/>&#9989;**Windows** 8.1 (необходима поддержка **UWP**)<br/>**macOS** Mojave (10.14) |
| [2](https://github.com/LeoKhariton/Opric/releases/tag/v2.0.0) | &#9989;**Android** 5.0 (API 21)<br/>**iOS** 11<br/>&#9989;**Windows** 10 (с помощью **Win UI 3**)<br/>**macOS** 10.15 |
| [3<br/>(preview only)](https://github.com/LeoKhariton/Opric/releases/tag/v3.0-preview2) | **Android** 5.0 (API 21)<br/>**iOS** 11<br/>&#9989;**Windows** 10 (с помощью **Win UI 3**)<br/>**macOS** 10.15 |
### Android
Скачайте установочный файл с расширением `.apk` и запустите его на устройстве Android.  
При необходимости, дайте приложению доступ к мобильной сети.
### Windows 11
1. Загрузить файл-установщик с расширением `.msix`.
2. Если сертификат еще не установлен, сначала необходимо его установить.
<details><summary>Установка сертификата</summary>
  
  1. Сначала откройте окно свойств установочного файла и перейдите к вкладке "Цифровые подписи". Выберите единственную подпись из списка и нажмите "Сведения":  
  ![w1](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w1.png)  
  2. В открывшемся окне "Состав цифровой подписи" выберите "Просмотр сертификата":  
  ![w2](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w2.png)  
  3. В открывшемся окне нажмите "Установить сертификат":  
  ![w3](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w3.png)  
  4. Выберите установку сертификата для всего локального компьютера и нажмите "Далее" от имени администратора:  
  ![w4](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w4.png)  
  5. Выберите "Доверенные корневые центры сертификации", нажмите "ОК":  
  ![w5](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w5.png)  
  6. А затем "Далее" и "Готово". Появится уведомление, оповещающее об успешной установке сертификата.  
  7. Закройте окно свойств и запустите установщик.
</details>

3. Запустите установщик
### Windows 10
Для Windows 10 необходимо проделать всю процедуру установки для Windows 11, а также дополнительно:

4. Установить с официального сайта Microsoft [Windows App SDK](https://learn.microsoft.com/ru-ru/windows/apps/windows-app-sdk/downloads) (если еще не установлена).
5. Первый раз необходимо открыть программу от имени администратора.

## Эксплуатация
Сразу после запуска приложения загружается "главная" &ndash; страница выбора дисциплины. На текущий момент для изучения доступны две дисциплины &ndash; "Программирование на языке С/С++" и "Численные методы".  

После открытия приложения загрузится "главная" страница &ndash; страница, на которой можно выбрать раздел.  
![](https://github.com/LeoKhariton/Opric/blob/main/Test/1.png)  
В левом верхнем углу доступно навигационное меню-гамбургер, содержащее 3 вкладки &ndash; разделы, личный кабинет и настройки.
### Вкладка "Разделы"
Кликнув по соответствующему названию раздела, открывается страница с вкладками (Android/iOS) / верхним меню (Windows/macOS), на которой располагается содержимое раздела, которое включает "Лекцию", "Тест" и "Практику". В десктопных платформах доступны две дополнительные вкладки &ndash; С/С++ компилятор и редактор блок-схем.
![](https://github.com/LeoKhariton/Opric/blob/main/Test/3.png)  
Для преподавателя доступен режим редактирования учебного контента.  
![режим редактирования](https://github.com/LeoKhariton/Opric/blob/main/Test/4.png)
### Вкладка "Личный кабинет"
После прохождения регистрации будет доступен личный кабинет с рейтингом самых активных пользователей и со статистикой прохождения тестов, а на "главной" вокруг иконок разделов будет отображаться статистика прохождения теста по соответствующей теме.  
![](https://github.com/LeoKhariton/Opric/blob/main/Test/Презентация1.jpg)  
### Вкладка "Настройки"
В разделе "Настройки" можно выбрать тему приложения, а также доступны некоторые настройки аккаунта.  
![](https://github.com/LeoKhariton/Opric/blob/main/Test/6.png)  
***
Если вы нашли ошибку, просьба сообщить о ней *максимально подробно*, воспользовавшись формой для отправки отзывов. Необходимо описать ситуацию, которая привела к ошибке, и саму ошибку, желательно приложив скриншот. **Важно сообщить об ошибке как можно подробнее, чтобы разработчики могли повторить ситуацию, приведшую к ошибке и исправить ее.**  
Другой вариант сообщения об ошибке &ndash; сформировать подробный отчет о ней [на странице данного репозитория](https://github.com/LeoKhariton/Opric/issues). Там также следует описать саму обишку, по возможности приложить скриншот и описать шаги для ее воспроизведения.  
## Публикации и работы ##
1. Международная конференция ["Новые информационные технологии и системы" (НИТиС-2022)](https://elibrary.ru/item.asp?id=50454558&pff=1), Пенза.
2. [Всеросскийская конференция Нижневартовского государственного университета](https://konference.nvsu.ru/konffiles/383/Stud_konf_CH3_Informacionnye_tehnologii.pdf).  
3. [Региональный научно-практический семинар им. Л.В. Широкова](https://elibrary.ru/item.asp?id=54087229), Арзамас.
4. Международная конференция "Инновационные процессы в науке и технике XXI века", Нижневартовск.
5. Всероссийская научно-практическая конференция им. Жореса Алфёрова, Санкт-Петербург.
6. Всероссийская научно-практическая конференция "Наука молодых", посвященная 125-летию НГТУ им. Р.Е. Алексеева, Арзамас.
7. ИИТМА
8. Конкурс работ региональный и конкурс в Брянске
## Апробация и внедрение
![](https://github.com/LeoKhariton/Opric/blob/main/Акт%20о%20внедрении.png)

## История версий \[АРХИВ]
### Версия 2

### Версия 1
![видеодемонстрация версии 1](https://github.com/LeoKhariton/Opric/blob/main/Test/видео.gif)  
#### Windows
Это приложение является универсальным приложением Windows (т.е. доступно как на десктопных платформах, так и на Windows Phone, и даже на очках смешанной реальности HoloLens, которые также функционируют на базе универсальной платформы Windows). Поэтому установочный файл имеет не привычное расширение `.exe`, `.msi` или `.msix` (как у программ, разработанных на платформах WPF или Windows Forms), а `.APPX` или `.APPXBUNDLE`.  
#### Что делать, если компьютер не распознает файл .appx или .appxbundle?
Бывают случаи, когда компьютер с ОС Windows 10 не распознает файлы `.appx` и `.appxbundle` как установочные, и предлагает открыть их с помощью какой-то программы.  
В этом случае необходимо открыть Power Shell и ввести следующую команду:
```md
add-appxpackage [путь к установочному файлу]
```
Если все необходимые пакеты установлены, то эта команда приведет к запуску установки приложения (важно, что **сертификат должен быть предварительно установлен вручную тем же способом, который описан выше в пп. 2-9**). В противном случае выведется сообщение об ошибке, возникшей в ходе устновки. Чаще всего это может быть связано с отсутствием каких-либо пакетов (например, пакета поддержки XAML необходимой версии). Их можно установить либо вручную, либо с обновлением Windows, либо с помощью Visual Studio 2019 (для этого обычно достаточно обновить VS до последней версии или подключить пакет разработки приложений для универсальной платформы Windows).  
*Примечание*  
Во избежание конфликтов стилей желательно, чтобы тема приложения соответствовала системной.  
### Версия 0
Для работы приложения необходимо загрузить весь образовательный контент отдельно и распаковать его в `C:\faust\`.  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Version%20History/v0-WinForms.png)
