# user_actions_contact_views
## Описание проекта
Анализ связи целевого события — просмотра контактов — и других действий пользователей. Также в проекте рассматривается, какие действия чаще совершают те пользователи, которые просматривают контакты.

## Датасеты
### mobile_sources.csv
Датасет содержит информацию о профилях пользователей мобильного приложения.

**Информация о датасете mobile_sources.csv:**
| Столбец | Описание |
|---|---|
| user_id | Уникальный идентификатор пользователя |
| source | Источник, из которого пользователь узнал о приложении |

### mobile_dataset.csv
Датасет содержит информацию о сессиях пользователей мобильного приложения.

**Информация о датасете mobile_dataset.csv:**
| Столбец | Описание |
|---|---|
| event_time | Дата и время события |
| event_name | Название события |
| user_id | Уникальный идентификатор пользователя |

## Jupyter Notebook
**user_actions_contact_views.ipynb**

## requirements.txt
Этот файл содержит список библиотек Python, необходимых для запуска проекта.

Чтобы установить библиотеки, запустите следующую команду: <pre>pip install -r requirements.txt<pre>
