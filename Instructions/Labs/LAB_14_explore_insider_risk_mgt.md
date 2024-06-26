---
lab:
  title: "Изучение управления внутренними рисками в Microsoft\_Purview"
  module: Describe the insider risk capabilities in Microsoft Purview
---

# Практическое занятие. Изучение управления внутренними рисками в Microsoft Purview

Это практическое занятие выполняется на основе следующего содержимого Learn:

- Схема обучения. Описание возможностей соответствия требованиям Майкрософт
- Модуль. Описание возможностей управления внутренними рисками в Microsoft Purview
- Урок. Описание управления внутренними рисками

## Сценарий практической работы

В рамках этого практического занятия вы изучите процесс настройки политики в отношении внутренних рисков вместе с базовыми предварительными требованиями для настройки и использования политик управления внутренними рисками.  Примечание. В рамках этого практического занятия вы только познакомитесь с тем, что необходимо для настройки управления внутренними рисками, а также с различными параметрами, связанными с созданием политики.  В этом практическом занятии нет задачи по инициированию политики, так как количество событий, которое должно произойти для инициирования политики, и необходимое время не рассматриваются в настоящем упражнении.

**Предполагаемое время:** 45-60 мин.

### Задача 1

В данном задании вам, как глобальному администратору, необходимо включить разрешения для управления внутренними рисками.  В частности, вы добавите пользователей в группу ролей управления внутренними рисками, чтобы эти назначенные пользователи могли получать доступ к функциям управления внутренними рисками и управлять ими.  Для применения разрешений группы ролей к пользователям организации может потребоваться до 30 минут.

1. Откройте вкладку браузера на домашней странице Microsoft Purview.  Если вы ранее закрыли ее, откройте вкладку браузера и введите **https://admin.microsoft.com**. Войдите, используя учетные данные администратора для клиента Microsoft 365, предоставленные полномочным поставщиком услуг размещения заданий (ALH). В левой области навигации центра администрирования Microsoft 365 выберите **Показать все**, а затем **Соответствие**.  Откроется новая страница браузера с приветствием портала соответствия требованиям Microsoft Purview.  

1. На панели навигации слева разверните раздел **Роли и области** и выберите **Разрешения**.

1. Выберите **Роли** в разделе решений Microsoft Purview.

1. В поле поиска введите **Внутренние риски**, а затем нажмите клавишу ввода на клавиатуре.  Обратите внимание на многочисленные отображаемые роли.  Каждый из них имеет разные уровни доступа.  Выберите **Управление внутренними рисками** и просмотрите описание.  Прокрутите вниз до того места, где отображаются участники, и обратите внимание, что в списке указаны администратор MOD и Megan Bowen. Закройте окно, щелкнув значок **X** в правом верхнем углу экрана.

1. На панели навигации слева выберите **Главная**, чтобы вернуться на страницу портала соответствия требованиям Microsoft Purview.

1. Не закрывайте эту вкладку браузера, так как она будет использоваться в последующей задаче.

### Задача 2 (ПРИМЕЧАНИЕ: ПРОПУСТИТЕ Задачу 2, если вы выполнили задачу по включению журнала аудита в практическом занятии по настройке).

При управлении внутренними рисками используются журналы аудита Microsoft 365 для аналитики пользователей и различных действий, обозначенных в политиках и рекомендациях по аналитике. В рамках этой задачи вы включите возможность поиска в журналах аудита. Примечание: после включения поиска в журнале аудита может пройти несколько часов, прежде чем вы сможете получить результаты при поиске в журнале аудита.  Хотя выполнение поиска в журнале аудита может быть недоступным в течение нескольких часов, это не повлияет на возможность выполнения других задач в этом практическом занятии.

1. Перейдите на вкладку браузера **Главная — Соответствие требованиям Microsoft 365**.  Если вы ранее закрыли эту вкладку браузера, откройте Microsoft Edge и в адресной строке введите **compliance.microsoft.com**, а затем выполните вход с использованием учетных данных администратора.

1. В разделе разрешений на панели навигации слева выберите **Аудит**.

1. Убедитесь, что выбрана (подчеркнута) вкладка **Поиск**.

1. После перехода на страницу аудита подождите 2-3 минуты.  Если аудит НЕ включен, вы увидите синюю панель в верхней части страницы с рекомендацией начать регистрировать действия пользователей и администраторов.  Нажмите кнопку **Начать запись действий пользователя и администратора**.  После включения аудита синяя панель исчезнет.  Если синяя панель отсутствует, аудит уже включен и дальнейших действий не требуется.

1. Вернитесь на главную страницу портала соответствия требованиям Microsoft Purview, выбрав пункт **Главная** на панели навигации слева.

1. Не закрывайте эту вкладку браузера, так как она будет использоваться в следующей задаче.

### Задача 3

В рамках этой задачи вы изучите параметры, связанные с решением по управлению внутренними рисками.  Параметры управления внутренними рисками применяются ко всем политикам управления внутренними рисками независимо от шаблона, выбранного при создании политики.

1. Вы должны находиться на главной странице портала соответствия требованиям Microsoft Purview. В противном случае откройте вкладку браузера **Главная — Соответствие требованиям Microsoft 365**.

1. На панели навигации слева в разделе «Решения» выберите **Управление внутренними рисками**.

1. Прежде чем приступить к настройке политики, администратор должен ознакомиться с некоторыми параметрами и настроить их в соответствии с требованиями своей организации. На странице «Управление внутренними рисками» в правом верхнем углу окна управления внутренними рисками выберите значок шестеренки **Параметры**, чтобы открыть параметры внутреннего риска.  
    1. Убедитесь, что вы на вкладке **Конфиденциальность**: для пользователей, которые выполняют действия, на которые распространяются ваши политики управления внутренними рисками, этот параметр определит, следует ли отображать фактические имена этих пользователей или использовать анонимные версии для маскировки фактических имен.  Для целей этой пошаговой процедуры можно оставить значение по умолчанию.
    1. Перейдите на вкладку **Индикаторы политики**. После возникновения события активации политики действия, сопоставленные с выбранными индикаторами, используются при определении оценки риска для пользователя. Выбранные здесь индикаторы политики включают шаблоны политик внутренних рисков.  Прокрутите страницу, чтобы просмотреть все доступные индикаторы и соответствующие сведения. В разделе **Индикаторы Office** выберите **Выбрать все**, а затем нажмите кнопку **Сохранить** в нижней части страницы (прокрутите вниз).
    1. Перейдите на вкладку **Сроки действия политики**. Сроки, которые вы выбираете здесь, вступают в силу для пользователя, когда он активирует совпадение для политики внутреннего риска.   Окно активации определяет продолжительность активного определения политиками действий пользователей, которые активируются при выполнении первого действия, соответствующего политике. Благодаря функции определения предыдущих действий можно узнать, насколько далеко следует вернуть политику для обнаружения действий пользователей, и она активируется при выполнении пользователем первого действия, соответствующего политике.  Не изменяйте значения по умолчанию.
    1. Перейдите на вкладку **Интеллектуальное обнаружение **. Просмотрите параметры здесь.  Обратите внимание на параметры доменов и их связь с индикаторами.
    1. Изучите другие элементы в параметрах и обратите внимание, что многие из них находятся на стадии предварительной версии.

1. Чтобы вернуться к странице управления внутренними рисками, выберите **Управление внутренними рисками** в левом верхнем углу страницы в разделе «Параметры».

1. Не закрывайте эту вкладку браузера, так как она будет использоваться в следующей задаче.

### Задача 4

В этой задаче вы изучите параметры для создания политики.  Цель в том, чтобы просто получить представление о различных параметрах и гибкости, связанных с созданием политики.

1. Вы должны находиться на странице управления внутренними рисками.  В противном случае откройте вкладку браузера с надписью **Управление внутренними рисками — соответствие требованиям Microsoft 365**.

1. На странице обзора управления внутренними рисками перейдите на вкладку **Политики** и выберите **+ Создать политику**.  Настройте каждую из нижеприведенных вкладок политики.

    1. Шаблон политики: в категории «Утечки данных» выберите **Утечки данных**.  Изучите сведения, связанные с этим шаблоном. В разделе «Предварительные требования» политика защиты от потери данных отображается с галочкой в зеленом круге. Это означает, что предварительные требования выполнены.  Для этого клиента практического занятия предварительно настроена политика защиты от потери данных. Выберите **Далее**. 
    1. Имя и описание: введите имя **SC900-InsiderRiskPolicy**, затем нажмите кнопку **Далее**.
    1. Пользователи и группы: просмотрите поле сведений.  Не меняйте параметр по умолчанию, **включите всех пользователей и группы**.  Выберите **Далее**.
    1. Содержимое для назначения приоритетов: согласно описанию, оценки риска увеличиваются для любого действия, содержащего приоритетное содержимое, что, в свою очередь, повышает вероятность создания оповещения с высоким уровнем серьезности. Для простоты выберите **Я не хочу назначать приоритеты содержимому прямо сейчас**, а затем нажмите кнопку **Далее**.
    1. Триггеры: событие активации определяет, когда политика начнет назначать оценки риска действиям пользователя.  Можно выбрать существующую политику защиты от потери данных или выполняет ли пользователь действие по краже данных. Выберите **Пользователь соответствует политике защиты от потери данных (DLP),** а затем в раскрывающемся списке выберите **Финансовые данные США**. Выберите **Далее**.
    1. Индикаторы: обратите внимание, что выбраны все индикаторы Office, выбранные в предыдущей задаче (это можно увидеть, нажав клавишу со стрелкой вниз рядом с индикаторами Office), а затем нажмите кнопку **Далее**.
    1. На странице «Параметры обнаружения» оставьте все параметры по умолчанию, но прочитайте описание, связанное с различными параметрами, и наводите указатель мыши на значок сведений, чтобы получить более подробную информацию о конкретном параметре.  Выберите **Далее**.
    1. На странице, где нужно решить, использовать ли пороговые значения индикаторов по умолчанию или для клиентов, оставьте настройку по умолчанию **Применить пороговые значения, предоставленные Microsoft**, затем нажмите **Далее**.
    1. Завершение: просмотрите параметры, выберите **Отправить**.
    1. Просмотрите описание следующего действия, а затем нажмите кнопку **Готово**.

1. Вы вернетесь на вкладку «Политики» страницы «Управление внутренними рисками».  В списке будет указана созданная политика.  Если ее нет, щелкните значок **Обновить**.

1. Администратор может сразу же приступить к назначению оценок риска пользователям на основе действий, обнаруженных выбранными политиками. Это позволяет обойти требование того, чтобы сначала обнаруживалось событие активации (например, совпадение политики защиты от потери данных).  Для этого администратору следует выбрать пустой квадрат рядом с именем политики, чтобы выбрать политику, затем выбрать пункт **Начать действие по оценке для пользователей**, который отображается над таблицей политик.  Откроется новое окно, в котором администратор должен заполнить доступные поля. Оставьте поля пустыми, так как вы не будете настраивать этот параметр, но для получения дополнительных сведений о том, почему администратор должен это сделать, выберите **Зачем это делать?**.  Закройте окно, выбрав **X** в правом верхнем углу экрана.

1. На панели навигации слева выберите **Главная**, чтобы вернуться на главную страницу портала соответствия требованиям Microsoft Purview.

1. Оставьте данную вкладку браузера открытой.

### Отзыв

В рамках этого практического занятия вы изучили процесс настройки политики в отношении внутренних рисков вместе с базовыми предварительными требованиями для настройки и использования политик управления внутренними рисками.
