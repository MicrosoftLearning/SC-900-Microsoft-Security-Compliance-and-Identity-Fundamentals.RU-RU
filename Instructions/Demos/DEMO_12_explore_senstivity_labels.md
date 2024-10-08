<!---
---
Демонстрация: название: "Метки конфиденциальности в Microsoft Purview" Путь обучения/модуль/модуль: "Путь обучения: описание возможностей Microsoft Priva и Microsoft Purview; Модуль 2.Описание решений по обеспечению безопасности данных Microsoft Purview; Урок 4. Описание меток конфиденциальности и политик в Защита информации Microsoft Purview
---
--->

# Ролик. Метки конфиденциальности в Microsoft Purview

Эта демонстрация выполняется на основе следующего содержимого Learn:

- Путь обучения. Описание возможностей Microsoft Priva и Microsoft Purview
- Модуль. Описание решений по обеспечению безопасности данных Microsoft Purview
- Урок. Описание меток конфиденциальности и политик в Защита информации Microsoft Purview

## Демонстрационный сценарий

В рамках этой демонстрации вы покажете возможности меток конфиденциальности.  Вы оцените параметры уже созданных меток конфиденциальности и соответствующую политику по публикации метки.   Затем вы рассмотрите с точки зрения пользователя, как можно будет применять метку, а также результат воздействия этой метки.  **ПРИМЕЧАНИЕ.** При первом использовании Word Online в клиенте Microsoft 365 для отображения параметра "Конфиденциальность" на ленте может потребоваться до 15 минут.  Выступающие должны запустить часть 2 демонстрации перед классом заранее, чтобы для отображения параметра прошло достаточно времени.

### Демонстрация, часть 1.

В рамках этой демонстрации вы покажите параметры существующей метки конфиденциальности и соответствующую политику по публикации метки.

1. Откройте новую вкладку браузера Microsoft Edge. В адресной строке введите **https://purview.microsoft.com**. Чтобы получить доступ к новому порталу Microsoft Purview, выберите поле рядом с этим полем, **я согласен с условиями раскрытия потока данных и заявлений** о конфиденциальности, а затем нажмите кнопку **"Начать".**  

1. На целевой странице нового портала Microsoft Purview выберите плитку **"Просмотреть все решения** ", а затем щелкните плитку **Information Manager** . Кроме того, вы выбираете **решения** на левой панели навигации, а затем выберите **Information Protection**.

1. Вы перейдете на страницу обзора. На левой панели навигации выберите **метки** конфиденциальности.

1. Для вашего удобства мы уже предварительно настроили некоторые метки в клиенте практического занятия Microsoft 365. Выберите метку с названием **Конфиденциально-Финансы**.  Откроется окно с информацией об этой метке.  Обратите внимание на параметры для этой метки.  Выберите **Изменить метку** (также может отображаться в виде значка карандаша) в верхней части страницы, чтобы просмотреть некоторые базовые настройки конфигурации. Если этот параметр не отображается, выберите многоточие.
    1. Настройка начинается с указания названия и описания метки.  Ничего не изменяйте.  Выберите **Далее** в нижней части страницы.
    1. Просмотрите область для этой метки. Ничего не изменяйте.  Выберите **Далее** в нижней части страницы.
    1. На следующем экране можно выбрать параметры защиты для помеченных элементов. Эта метка настроена для поддержки маркировки содержимого. Ничего не изменяйте.  Выберите **Далее** в нижней части страницы.
        1. На странице маркировки содержимого обратите внимание на информационное поле в верхней части страницы.  Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Теперь вы находитесь в окне «Автоматическое добавление меток для файлов и сообщений эл. почты».  Ознакомьтесь с описанием автоматической маркировки в верхней части страницы и информационным полем ниже.  Кроме того, обратите внимание, что эта метка настроена для автоматической маркировки для определенных условий. Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. В этом окне определяются параметры защиты для команд, групп и сайтов, к которым применена эта метка. Эта функция не активирована, нажмите кнопку **Далее** в нижней части страницы.
    1. Это окно представляет собой функцию предварительного просмотра для автоматического применения этой метки к схематизированным ресурсам данных в карте данных Microsoft Purview (например, SQL, Synapse и т. д.), которые содержат выбранные типы конфиденциальной информации.  Эта функция не включена. Нажмите кнопку **Отменить** в нижней части страницы, чтобы выйти из мастера настройки меток и вернуться на страницу "Защита информации".

1. На панели навигации слева выберите **"Политики", а затем выберите **"** Политики** публикации".  С помощью политик меток можно публиковать метки конфиденциальности.  Для вашего удобства клиент Microsoft 365 уже настроен с некоторыми политиками меток.

1. Выберите **политику "Конфиденциально-Финансы"**.  Откроется окно с информацией о политике. Выберите **Изменить политику** в верхней части окна.  Здесь вы будете идти по параметрам, ничего не изменяя.
    1. Ознакомьтесь с описанием параметра "Выбор меток конфиденциальности для публикации".  Обратите внимание на метку, указанную в списке.  Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Ознакомьтесь с описанием параметра "Назначить административные единицы". Для административных единиц задан полный каталог — не изменяйте параметры. Выберите **Далее**.  
    1. Ознакомьтесь с описанием параметра "Опубликовать для пользователей и групп".  Обратите внимание, что эта метка доступна всем пользователям.  Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Просмотреть параметры политики. Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Просмотреть описание в разделе «Применить к документам метку по умолчанию». Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Просмотреть описание «Применить к сообщениям электронной почты метку по умолчанию» и «Наследовать метку из вложений». Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Просмотреть описание «Применить к собраниям и событиям календаря метку по умолчанию». Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Просмотреть описание «Применить к содержимому Power BI метку по умолчанию». Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Последний параметр конфигурации — присвоение имени политике.  Так как вы изменяете политику, поле имени неактивно. Нажмите кнопку **Далее** в нижней части страницы.
    1. Просмотреть параметры политики. Нажмите кнопку **Отмена**, чтобы отменить все изменения и вернуться на страницу политик меток.

1. В разделе "Защита информации" на панели навигации слева выберите "Автоматическое применение меток". Просмотреть описание. Обратите внимание, что вы создаете политики автоматической маркировки для автоматического применения меток конфиденциальности к сообщениям электронной почты или файлам OneDrive и SharePoint, содержащим конфиденциальные сведения. Если настроены политики автоматической маркировки, выберите одну из них и посмотрите информацию о политике в области сведений.  Если список пуст и вам позволяет время, можете создать политику, выполнив пошаговые инструкции.

1. На панели навигации слева выберите "Главная", чтобы вернуться на портал Microsoft Purview.

1. Оставьте данную вкладку браузера открытой.

### Демонстрация, часть 2.

На этом этапе будет продемонстрирован процесс применения метки с точки зрения пользователя (в данном случае пользователь является администратором).  Чтобы просмотреть воздействие применения метки, выберите метку «Конфиденциально — Финансы», так как эта метка применяет водяной знак.

1. На домашней странице Портал соответствия требованиям Microsoft Purview щелкните **значок** средства запуска приложений рядом с местом, где он говорит Microsoft Purview (в верхней части значка дома). Щелкните значок **Word**.  

1. Выберите **Пустой документ** и введите на странице какой-нибудь текст.  В синей строке в верхней части страницы нажмите стрелку вниз рядом с надписью «Документ – Сохранен», затем в поле «Имя файла» введите **Тестовая метка**. На клавиатуре нажмите клавишу **ВВОД**.

1. В правой части верхней строки меню (также называется лентой) находится стрелка вниз. Нажмите ее, а затем выберите **Классическая лента**.  Это упрощает идентификацию значка конфиденциальности. Выберите **Конфиденциальность** рядом со значком микрофона. В раскрывающемся меню выберите **Конфиденциально — финансы**.  

1. В верхней строке меню выберите **Вид**, а затем выберите режим **Чтение**.

1. Обратите внимание, что документ содержит водяной знак.  

1. Закройте вкладки Microsoft Word, открытые в браузере, чтобы выйти из Word.

1. Не закрывайте вкладку Microsoft Purview в браузере для следующего ролика.

### Отзыв

В этом ролике вы показали параметры, которые можно настроить для меток конфиденциальности, а также параметры политик для публикации меток конфиденциальности. Вы также показали, как применять метки.
