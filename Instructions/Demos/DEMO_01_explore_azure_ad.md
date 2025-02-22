<!---
---
Ролик: Название: "Изучите настройки пользователя Microsoft Entra ID" Схема обучения/Модуль/Урок: "Схема обучения. Описание возможностей Microsoft Entra; Модуль 1. Описание функции и типов удостоверений Microsoft Entra ID; Урок 3. Описание типов удостоверений Microsoft Entra"
---
--->

# Ролик: Настройки пользователя Microsoft Entra ID

Эта демонстрация выполняется на основе следующего содержимого Learn:

- Схема обучения: Описание возможностей Microsoft Entra.
- Модуль: Описание функции и типов удостоверений Microsoft Entra ID.
- Урок: Описание типов удостоверений.

## Демонстрационный сценарий

В этом ролике вы получите доступ к Microsoft Entra ID и изучите различные параметры для существующего пользователя.

1. Откройте Microsoft Edge.

1. В адресной строке введите **admin.microsoft.com**, чтобы получить доступ к Центру администрирования Microsoft 365.

1. Выполните вход с использованием учетных данных администратора.
    1. В окне входа введите **admin@WWLxZZZZZZ.onmicrosoft.com** (где ZZZZZZ — уникальный идентификатор клиента, предоставленный поставщиком размещения практических занятий), затем нажмите кнопку **Далее**.
    1. Введите пароль администратора, который должен быть предоставлен поставщиком услуг размещения практических занятий. Выберите **Вход.**
    1. При появлении предложения не выходить из системы выберите **Да**.

1. В левой области навигации центра администрирования Microsoft 365 выберите пункт **Показать все**.

1. В Центрах администрирования выберите **Удостоверение** (может потребоваться прокрутить вниз).  Откроется новая страница браузера, ведущая на страницу обзора центра администрирования Microsoft Entra. Здесь вы увидите основные сведения о клиенте Contoso. Если прокрутите главное окно, вы также увидите сведения о оповещениях, моем канале, выделении функций и т. д.  
    1. Примечание для докладчика/инструктора: вы также можете получить доступ к Центру администрирования Microsoft Entra напрямую, перейдя на сайт **[entra.microsoft.com](https://entra.microsoft.com)**.

1. На панели навигации слева разверните раздел **Пользователи ** и выберите **Все пользователи**.  На странице пользователей можно просмотреть дополнительные параметры навигации и список пользователей. Ваш клиент уже настроен для пользователей.

1. В списке пользователей выберите **Adele Vance**.

1. Обратите внимание, что на левой панели навигации **Обзор** выделен светло-серым цветом.  Покажите/проговорите информацию, показанную на странице обзора.  Выберите вкладку **Мониторинг** в верхней части страницы, в которой отображаются входы пользователей (вход в систему не будет отображаться, если вы ранее не вошли в систему как Adele Vance).  Затем выберите **Свойства**, чтобы просмотреть все свойства для пользовательского объекта Adele Vance.

1. На панели навигации слева выберите **Назначенные роли**.  У этого пользователя нет назначенных административных ролей.  В верхней части страницы выберите **+Добавить назначения**, а затем на странице добавления назначений разверните поле "Поиск роли" в разделе "Выбор роли", чтобы просмотреть список доступных типов административных ролей.  Не добавляйте ничего, просто закройте страницу, нажав **X** в правом верхнем углу страницы.

1. На панели навигации слева выберите **Группы**.  Обсудите тот факт, что этот пользователь является членом нескольких групп.  Здесь можно обратиться к типам групп.  Чтобы добавить этого пользователя в другие группы, следует выбрать **+ Добавить членства**.  Не добавляйте новые группы. Просто обсудите тему простоты добавления пользователя в существующие группы. Закройте окно "Выбор групп", нажав **X** в правом верхнем углу страницы.

1. На панели навигации слева выберите **Лицензии**. Обратите внимание, что этому пользователю назначены лицензии Microsoft 365 E5 и лицензия EMS.  Чтобы добавить лицензию, выберите **+ Назначения** в верхней части главного окна.  Показать лицензии для этого пользователя. Ничего НЕ изменяйте.  Закройте это окно, щелкнув значок **X** в правом верхнем углу страницы.

1. На панели навигации слева выберите элемент **Устройства**.  Ничего не отображается, но можно сказать, что если бы этому пользователю были назначены устройства, они бы отображались именно здесь.

1. На панели навигации слева выберите **Назначения ролей Azure**.  Укажите:
    1. Это отличается от вкладки "Назначенные роли", показанной ранее, тем, что предыдущая вкладка предназначена для управления доступом на основе ролей в Microsoft Entra.
    1. Хотя здесь ничего не указано, на этой вкладке вы сможете просмотреть назначения ролей, назначенных Adele, для ресурсов Azure. Например, если вы создадите группу ресурсов Azure и назначите Adele определенную роль, например владельца или участника группы ресурсов, вы увидите, что эта роль указана здесь. Это часть управления доступом на основе ролей Azure (Azure RBAC). Это назначение роли добавляется и управляется в рамках этого конкретного ресурса.

1. Нажмите **X** в правом верхнем углу страницы. Вы вернетесь в список пользователей.

1. Нажмите **X** в правом верхнем углу страницы. Вы вернетесь на главную страницу центра администрирования Microsoft Entra.

1. Не закрывайте эту вкладку браузера, поскольку вы будете использовать ее для следующей демонстрации.

### Отзыв

В рамках этой демонстрации вы показали параметры существующего пользователя, включая группы, которым он может быть назначен, доступность ролей и назначение пользовательских лицензий.
