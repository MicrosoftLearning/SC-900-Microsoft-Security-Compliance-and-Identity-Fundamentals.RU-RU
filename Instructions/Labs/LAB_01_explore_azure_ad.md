---
lab:
  title: Изучение Azure Active Directory
  module: 'Module 2 Lesson 1: Describe the capabilities of Microsoft Identity and access management solutions: Explore the services and identity types of Azure AD'
ms.openlocfilehash: ca6ea1f2fc67ad1c09a108079eada6c8a9ebd89c
ms.sourcegitcommit: 25998048c2e354ea23d6f497205e8a062d34ac80
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/04/2022
ms.locfileid: "144557294"
---
# <a name="lab-explore-azure-active-directory"></a>Практическое занятие. Изучение Azure Active Directory

## <a name="lab-scenario"></a>Сценарий практического занятия

На этом практическом занятии вы откроете Azure Active Directory.  Кроме того, вы создадите пользователя и настроите различные параметры, включая добавление лицензий.  

**Примерное время**: 10–15 мин

### <a name="task-1"></a>Задача 1

Как подписчик Microsoft 365 вы уже используете Azure AD.  В рамках этой задачи вы выполните пошаговые инструкции, чтобы получить доступ к Azure AD через портал администрирования Microsoft 365 и портал Azure.

1. Откройте Microsoft Edge.

2. В адресной строке введите **admin.microsoft.com**, чтобы получить доступ к Центру администрирования Microsoft 365.

3. Войдите под своими учетными данными администратора.
    1. В окне входа введите **admin@WWLxZZZZZZ.onmicrosoft.com** (где ZZZZZZ — уникальный идентификатор клиента, предоставленный поставщиком размещения практических занятий), затем нажмите кнопку **Далее**.
    1. Введите пароль администратора, который должен быть предоставлен поставщиком размещения практических занятий. Выберите **Войти**.
    1. При появлении предложения не выходить из системы выберите **Да**.

4. В левой области навигации Центра администрирования Microsoft 365 выберите пункт **Показать все**.

5. В центрах администрирования выберите **Azure Active Directory** (возможно, понадобится прокрутить вниз).  Открывается новая страница браузера «Моя панель мониторинга» Центра администрирования Azure Active Directory. В главном окне панели мониторинга содержатся несколько плиток, включая плитку «Удостоверение организации» (Contoso, клиент и выпуск Azure AD), плитка пользователей и групп и многое другое.

6. В разделе «Избранное» на панели навигации слева выберите **Azure Active Directory**.  В главном окне будет расположена другая панель навигации, на которой приведены все службы, доступные в Azure AD. Справа содержатся сведения о клиенте Contoso и ссылки на типы удостоверений, доступных для создания, и предоставляемые службы.  

7. Теперь откройте новое окно браузера и в адресной строке введите **portal.azure.com**.  Поскольку вы уже выполнили вход как admin@WWLxZZZZZZ.onmicrosoft.com и изначально использовали эти учетные данные для активации Azure pass, то должны выполнить вход на портал Azure в качестве администратора.  Это можно проверить, посмотрев на адрес эл. почты в правом верхнем углу страницу и наведя указатель мыши на значок пользователя.

8. На целевой странице портала Azure приведены службы Azure, включая Azure Active Directory, ВМ, учетные записи хранения, базы данных и многое другое.  Выберите **Azure Active Directory**.  

9. Теперь можно увидеть Azure Active Directory для вашего клиента Microsoft 365 Contoso.    Независимо от используемого вами подхода для получения доступа к службам Azure Active Directory (портал администрирования Microsoft 365 или портал Azure), вы окажетесь в одном и том же месте: Azure Active Directory компании Contoso, где можно управлять службами Azure AD.

10. Не закрывайте эту страницу, поскольку она понадобится в следующей задаче.

### <a name="task-2"></a>Задача 2

В рамках этой задачи вы узнаете, как создать нового пользователя в Azure Active Directory, и изучите некоторые службы, которыми можно управлять на уровне пользователя.

1. Перейдите на вкладку «Contoso — Microsoft Azure» в вашем браузере. Если ранее вы закрыли эту вкладку, откройте страницу браузера и в адресной строке введите portal.azure.com, затем выберите Azure Active Directory.  Вы должны выполнить вход на портал Azure в качестве администратора. Если это не так, выполните вход повторно.

2. На панели навигации слева выберите **Пользователи**.  Обратите внимание, что в вашем клиенте уже настроены пользователи.

3. В верхней части страницы выберите **+ Новый пользователь**.

4. Пункт **Создать пользователя** уже должен быть выбран. В противном случае выберите его.

5. Заполните поля **Удостоверение** следующим образом.

    1. Имя пользователя: **sara**.

    2. Поле имени: **Sara Perez**.

    3. Имя: **Sara**.

    4. Фамилия: **Perez**.

6. Заполните поля **Пароль** следующим образом:

    1. Выберите **Разрешить мне создать пароль**.

    1. Исходный пароль: **Naja8996**. Когда Sara в первый раз выполняет вход в систему, появляется запрос на изменение пароля.

7. Настройте **Группы и роли**.

    1. Рядом с пунктом «Группы» выберите **Выбрано 0 групп**.  Отображаются доступные группы.  Просмотрите список доступных групп.

    2. Выберите **Операции**. Возможно, понадобится прокрутить вниз и нажать **Выбрать**. Обратите внимание, как текст рядом с группами был обновлен, чтобы отразить, что выбрана 1 группа.  

    3. Рядом с пунктом «Роли» выберите **Пользователь**. Отображается список «Роли каталога».  Прокрутите вниз для просмотра различных встроенных ролей, но не меняйте пользовательской роли.  Закройте это окно, выбрав **X** в правом верхнем углу страницы.

8. Настройте **параметры**.

    1. Блокировать вход:  **Нет** (оставьте значение по умолчанию).

    1. Расположение использования: **США** (выберите раскрывающийся список, затем прокрутите вниз, чтобы найти этот параметр).  Настройка расположения использования необходима для назначения лицензий.

9. В нижней части страницы нажмите кнопку **Создать**.

10. Убедитесь, что пользователь отображается в списке пользователей (имена приведены в алфавитном порядке).

11. В списке пользователей выберите только что созданного пользователя **Sara Perez**.  Открывается страница профиля.

12. На панели навигации слева показаны различные параметры, которые могут быть настроены для пользователя.  Выберите **Группы**.  Здесь можно просмотреть дополнительные сведения о группе.  Убедитесь, что в списке содержится группа «Операции» (может уйти несколько минут на отображение назначения группы).  Примечание. Здесь также будет отображаться группа Contoso, хотя мы назначили только одну группу при создании пользователя.  Это результат предварительно настроенной в клиенте политики, которая автоматически назначает новых пользователей в группу Contoso.

13. На панели навигации слева выберите **Лицензии**.  Обратите внимание, что для этого пользователя не найдены назначения лицензий.  

14. Чтобы добавить лицензию выберите **+ Назначения** в верхней части главного окна.

15. В разделе «Выберите лицензии» выберите **Office 365 E3** и **Windows 10 Enterprise E3**, затем нажмите кнопку **Сохранить** в нижней части экрана. В правом верхнем углу экрана появляется уведомление об успешных назначениях лицензий.

16. Выберите **X** в правом верхнем углу экрана, чтобы закрыть окно назначения лицензий.

17. Выберите значок **Обновить** в верхней части страницы, чтобы подтвердить назначения лицензий.

18. Вернитесь на страницу обзора Azure Active directory Contoso, выбрав **Contoso** в левом верхнем углу экрана (строка навигации) над надписью "Sara Perez | Лицензии".

19. Вы успешно создали и настроили пользователя в Azure Active Directory.

20. Выполните выход на всех вкладках браузера, щелкнув значок пользователя рядом с адресом эл. почты в правом верхнем углу экрана. Затем закройте все окна браузера.

### <a name="task-3"></a>Задача 3

В рамках этой задачи вы выполните первый вход в качестве пользователя Sara Perez.

1. Откройте Microsoft Edge.

2. В адресной строке введите **login.microsoft.com**.

3. Войдите как **sara@WWLxZZZZZ.onmicrosoft.com** (где ZZZZZZ — уникальный идентификатор клиента, предоставленный поставщиком услуг размещения в лаборатории).

4. Введите временный пароль **Naja8996**.

5. Появится запрос на обновление пароля. В поле «Текущий пароль» введите **Naja8996**.

6. В поле «Новый пароль» введите **SC900-Lab**.  В поле подтверждения пароля введите SC900-Lab, затем выполните вход.  Примечание. Рекомендуется использовать более надежный пароль. Этот пароль выбран для скорости набора и исключительно в целях выполнения этого практического занятия.

7. Вы должны успешно войти в Microsoft 365.

8. **Выполните выход** на всех вкладках браузера, щелкнув значок пользователя рядом с адресом эл. почты в правом верхнем углу экрана. Затем закройте все окна браузера.

### <a name="review"></a>Просмотр

В рамках этого практического занятия вы начали изучать Azure AD. Поскольку подписчики Microsoft 365 автоматически используют Azure AD, вы узнали, что доступ к функциям и службам Azure AD можно получить через портал администрирования Microsoft 365 или через портал Azure.  Вы можете использовать тот или иной способ, чтобы попасть в одно и то же место.  Кроме того, вы изучили процедуру создания нового пользователя и рассмотрели различные настройки, включая группы, которым может быть назначен пользователь, доступность ролей и назначение пользовательских лицензий.
