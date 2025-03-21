---
lab:
  title: "Изучение меток конфиденциальности в Microsoft\_Purview"
  module: Describe the data security solutions of Microsoft Purview
---

# Практическое занятие: Изучение меток конфиденциальности в Microsoft Purview

Это практическое занятие выполняется на основе следующего содержимого Learn:

- Путь обучения. Описание возможностей Microsoft Priva и Microsoft Purview
- Модуль. Описание решений по обеспечению безопасности данных Microsoft Purview
- Урок. Описание меток конфиденциальности и политик в Защита информации Microsoft Purview

## Сценарий практической работы

В рамках этого практического занятия вы изучите возможности меток конфиденциальности.  Вы оцените параметры уже созданных меток конфиденциальности и соответствующую политику по публикации метки.   Затем вы рассмотрите с точки зрения пользователя, как можно будет применять метку, а также результат воздействия этой метки.

**Предполагаемое время**: 45 минут

### Задача 1

В этой задаче вы получите представление о том, какие метки конфиденциальности можно сделать, пройдя процесс создания новой метки и создания политики для публикации метки.

1. Откройте вкладку браузера на домашней странице Microsoft Purview.  Если вы ранее закрыли ее, откройте вкладку браузера и введите **`https://admin.microsoft.com`**. Войдите, используя учетные данные администратора для клиента Microsoft 365, предоставленные полномочным поставщиком услуг размещения заданий (ALH).

1. В левой области навигации центра администрирования Microsoft 365 выберите **Показать все**, а затем **Соответствие**.  Откроется новая страница браузера на странице приветствия портала Microsoft Purview.

1. На панели навигации слева выберите **"Решения"** , а затем выберите **"** Защита информации".  Вы находитесь на странице обзора. Прокрутите вниз, чтобы просмотреть доступные сведения.

1. На левой панели навигации выберите **метки** конфиденциальности.
1. Вы увидите желтый баннер, указывающий, что ваша организация не включила возможность обработки содержимого в файлах Office Online, которые применили зашифрованные метки конфиденциальности и хранятся в OneDrive и SharePoint.  Выберите **Включить сейчас**.

1. Для вашего удобства мы уже предварительно настроили некоторые метки в клиенте практического занятия Microsoft 365. Выберите метку с названием **Конфиденциально-Финансы**.  Откроется окно с информацией об этой метке.  Обратите внимание на параметры для этой метки.  Выберите **"Изменить метку** ", если этот параметр не отображается, выберите многоточие.
    1. Конфигурация начинается с предоставления базовых сведений для метки.  Ничего не изменяйте.  Выберите **Далее** в нижней части страницы.
    1. Просмотрите область для этой метки. Ничего не изменяйте.  Выберите **Далее** в нижней части страницы.
    1. На следующем экране можно выбрать параметры защиты для помеченных элементов. Эта метка настроена для поддержки маркировки содержимого. Ничего не изменяйте.  Выберите **Далее** в нижней части страницы.
        1. На странице маркировки содержимого обратите внимание на информационное поле в верхней части страницы.  Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. Теперь вы находитесь в окне «Автоматическое добавление меток для файлов и сообщений эл. почты».  Ознакомьтесь с описанием автоматической маркировки в верхней части страницы и информационным полем ниже.  Кроме того, обратите внимание, что эта метка настроена для автоматической маркировки для определенных условий. Не меняйте настройки.  Выберите **Далее** в нижней части страницы.
    1. В этом окне определяются параметры защиты для групп и сайтов, на которых применена эта метка. Эта функция не активирована, нажмите кнопку **Далее** в нижней части страницы.
    1. Это окно представляет собой функцию предварительного просмотра для автоматического применения этой метки к схематизированным ресурсам данных в карте данных Microsoft Purview (например, SQL, Synapse и т. д.), которые содержат выбранные типы конфиденциальной информации.  Эта функция не включена. Нажмите кнопку **Отменить** в нижней части страницы, чтобы выйти из мастера настройки меток и вернуться на страницу "Защита информации".

1. В области навигации слева разверните **пункт "Политики", а затем выберите **"** Политики** публикации".  С помощью политик меток можно публиковать метки конфиденциальности.  Для вашего удобства клиент Microsoft 365 уже настроен с некоторыми политиками меток.

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

1. В разделе "Защита информации" на панели навигации слева выберите "Автоматическое применение меток". Просмотреть описание. Обратите внимание, что вы создаете политики автоматической маркировки для автоматического применения меток конфиденциальности к сообщениям электронной почты или файлам OneDrive и SharePoint, содержащим конфиденциальные сведения. В клиенте не настроены политики применения автоматической метки. Чтобы создать политику автоматического присвоения метки, нажмите кнопку **Создать политику автоматического присвоения метки**.  На этой странице вы узнаете, как создать новую политику.
    1. Начните с выбора типа сведений, к которым применяется эта метка.  Обратите внимание на доступные варианты.  Выберите **Медицина и здравоохранение**, а затем выберите один из доступных шаблонов.  Выберите **Далее**.
    1. Вы можете самостоятельно придумать имя политики автоматической метки или использовать имя по умолчанию.  Выберите **Далее**.
    1. Вы можете назначить административные единицы, к которым применяется эта политика.  Оставьте значение по умолчанию для полного каталога и выберите **Далее**.
    1. Обратите внимание на доступные расположения, в которых нужно применить метку.  Оставьте значения по умолчанию, а затем выберите **Далее**.
    1. Вы можете настроить общие или расширенные правила, определяющие, к чему применяется метка содержимого.  Оставьте значение по умолчанию для общих правил и выберите **Далее**.
    1. Вы можете определить правила для содержимого во всех расположениях.  Метка будет применена к содержимому, которое соответствует правилам, определенным на этой странице.  Для выбранного шаблона должен появиться элемент строки. Разверните его, чтобы просмотреть применимые условия.  Оставьте все параметры по умолчанию и выберите **Далее**.
    1. Выберите метку для автоматического применения, нажав **Выбрать метку**.  Выберите метку и нажмите кнопку **Добавить**. Выберите **Далее**.
    1. Для электронной почты можно настроить дополнительные параметры. Оставьте значения по умолчанию, а затем выберите **Далее**.
    1. Политику можно проверить сразу или позже.  Нажмите кнопку **Не включать политику**, а затем нажмите **Далее**.
    1. Просмотрите параметры и выберите **Создать политику**, а затем выберите **Готово**.

1. На панели навигации слева выберите **"Главная"** , чтобы вернуться на портал Microsoft Purview.

1. Оставьте эту страницу открытой, так как она будет использоваться в следующей задаче.

### Задача 2

В данном задании вы узнаете, как применять метку конфиденциальности к документу Microsoft Word и просматривать маркировку содержимого (подложку), созданную меткой. ПРИМЕЧАНИЕ. При использовании онлайн версии Microsoft Word может возникнуть задержка перед появлением опции выбора меток конфиденциальности на верхней ленте.  Рекомендуется завершить все оставшиеся практические задания, а затем вернуться к этому заданию.

1. Вы по-прежнему должны находиться на домашней странице портала Microsoft Purview. 
1. На портале Microsoft Purview выберите **значок** средства запуска приложений рядом с местом, где он говорит Microsoft Purview. Щелкните значок **Word**.  

1. В разделе «Создать» выберите **Пустой документ**, а затем введите на странице любой текст.  В верхней части страницы рядом с значком Word выберите место, где он говорит **"Документ** " и переименуйте файл в **test-label** , а затем нажмите клавишу **ВВОД** на клавиатуре.

1. В правой части верхней строки меню (также называется лентой) находится стрелка вниз. Нажмите ее, а затем выберите **Классическая лента**.  Это упрощает идентификацию значка конфиденциальности. Выберите **Конфиденциальность** рядом со значком микрофона. В раскрывающемся меню выберите **Конфиденциально — финансы**.  

1. В верхней строке меню выберите **Вид**, а затем выберите режим **Чтение**.

1. Обратите внимание, каким образом в документе включена подложка - Конфиденциальные ФИНАНСОВЫЕ ДАННЫЕ.  

1. Закройте вкладки Microsoft Word, открытые в браузере, чтобы выйти из Word, но оставьте открытой вкладку браузера на домашней странице Microsoft Purview.

### Отзыв

В рамках этого практического занятия вы изучите возможности меток конфиденциальности.  Вы ознакомитесь с параметрами уже созданных меток конфиденциальности и соответствующей политикой публикации метки.   Затем вы увидите, как применить метку.
