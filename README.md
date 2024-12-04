Мои редакции:

- [Yandex Tracker](#yandex-tracker)
- [Умный дом Яндекса](#smart-home)
- [Yandex Factory](#yandex-factory)

**Группа обеспечения документирования** — это удаленные технические писатели, которые помогают менеджерам службы управления знаниями в разработке документации. Все писатели группы обеспечения документирования проходят специальную подготовку, обучение и обладают набором специфичных навыков для решения конкретных задач.

**Мини-редакция** — команда исполнителей из группы обеспечения документирования, которая следит за качеством определенного направления документирования. Для каждого сервиса или группы документов выделяется одна мини-редакция.

[Руководителем мини-редакции](https://wiki.yandex-team.ru/kpb-writers-lead/ownership/) может выступать менеджер службы управления знаниями или писатель из группы обеспечения документирования, обладающий достаточным опытом в качестве лида. Руководитель занимается организационной работой.

В мини-редакциях помимо исполнителей могут работать писатели с другими ролями: лиды, координаторы, консультанты.

---

## Yandex Tracker {#yandex-tracker}

Моя основная редакция. К ней также относятся сервисы **Yandex Wiki** и **Yandex Forms**. У этих документаций есть версии для внешних пользователей и для сотрудников Яндекса.

Сейчас я в роли помощника лида:

- Отправляю документацию на перевод, проверяю и загружаю результат.

- Настраиваю конфиги для автоматических действий.

- Делаю другую организационную работу, если меня об этом попросят. Например, разбираю бэклог, пишу внутреннюю инструкцию или готовлю кое-какие документы))

### Что по текстам

* Как писатель я приложила руку к большинству страниц. Дам ссылки на те, которые писала полностью сама:

  [Интерактивное руководство по Tracker](https://yandex.ru/support/tracker/ru/user/quick-guide)

  [Удалить задачу](https://yandex.ru/support/tracker/ru/user/ticket-cancel)

* Несколько раз редактировала интерфейсные тексты: например, всплывающие уведомления в Forms и онбординг в Tracker. К моему сожалению, этих блоков больше нет в интерфейсе, а пока были — я их не заскринила. Нашла только скриншоты «до», а «после» нарисовала  для вас на коленке:

  {% cut "Виджет «Время цикла»" %}
  
  {% list tabs %}
  
  - Было
  
    ![3-3.jpg](/homepage/portfolio/.files/3-3.jpg =x600)

  - Стало
  
    ![3.jpg](/homepage/portfolio/.files/3.jpg =x600)

  {% endlist %}

  {% endcut %}

  {% cut "Копирование дашбордов" %}
  
  {% list tabs %}
  
  - Было
  
    ![2-2.jpg](/homepage/portfolio/.files/2-2.jpg =x600)

  - Стало
  
    ![2.jpg](/homepage/portfolio/.files/2.jpg =x600)

  {% endlist %}

  {% endcut %}

  {% cut "Диаграмма «Жизненный цикл задачи»" %}
  
  {% list tabs %}
  
  - Было
  
    ![1-1.jpg](/homepage/portfolio/.files/1-1-2.jpg =x500)

  - Стало
  
    ![1.jpg](/homepage/portfolio/.files/1-3.jpg =x500)

  {% endlist %}

  {% endcut %}

* Еще я изменяла структуру разделов. Оценить изменения предлагаю в сравнении с [документацией на домене cloud](https://yandex.cloud/ru/docs/tracker/), которая нами больше не поддерживается:

  {% cut "Раздел «Автоматизации и шаблоны»" %}
  
  {% list tabs %}
  
  - Было
  
    Что здесь не так?

    1. Сложная навигация: не сразу понятно, что относится к автоматизациям, что к шаблонам, какая между ними связь, причем тут вообще макросы и переменные.

    2. Две страницы с тематикой «Шаблоны» отделены от ката «Шаблоны». Тут тоже может возникнуть путаница.

    3. Нет последовательности: между страницами про шаблоны затесалась страница «Переменные».

    ![templates-cloud.gif](/homepage/portfolio/.files/templates-cloud.gif =x600)

  - Стало
  
    1. Я четко разделила разные сущности: шаблоны и автоматизации.

    2. В разделе описаны шаблоны для создания комментариев и задач внутри очереди, а страница [Шаблоны рабочих процессов](https://yandex.ru/support/tracker/ru/manager/work-process) несет в себе совсем другую концепцию. Поэтому она отправилась в более подходящий раздел «Настроить очередь».

    ![templates-docs.gif](/homepage/portfolio/.files/templates-docs.gif =x600)

  {% endlist %}

  {% endcut %}

  {% cut "Раздел «Статистика и дашборды»" %}
  
  {% list tabs %}
  
  - Было
  
    Что здесь не так?

    1. Под катом «Дашборды» откуда-то появляется еще одна сущность  — Виджеты. Сходу непонятно, есть ли между ними связь.

       Пояснение: виджеты — это доп. элементы, которые можно добавить на дашборд.

    2. Вместо виджетов в заголовке зачем-то заявлена статистика. Страниц с ее упоминанием всего две: «Статистика по задачам» (которая является виджетом) и «Статистика очереди» — совсем другой параметр, который ни к дашбордам, ни к виджетам не относится.

    ![dashboard-cloud.gif](/homepage/portfolio/.files/dashboard-cloud.gif =x600)

  - Стало
  
    1. Теперь раздел посвящен только двум связанным сущностям: дашбордам и виджетам.

    2. Страница [Статистика очереди](https://yandex.ru/support/tracker/ru/manager/statistics) к теме не относится, поэтому ушла в раздел про работу с очередями.

    ![dashboard-docs.gif](/homepage/portfolio/.files/dashboard-docs.gif =x600)

  {% endlist %}

  {% endcut %}

---

## Умный дом Яндекса {#smart-home}

Это объемная документация со сложной структурой, с которой я работаю как дополнительный писатель. 

* В этой редакции часто приходится кропотливо чинить сломанные YFM-разметку и CSS-стили для разводящих страниц (например, [Умная розетка](https://alice.yandex.ru/support/ru/socket/) и [Решение проблем](https://alice.yandex.ru/support/ru/station/troubleshooting/)), работать с инклюдами и переменными.  

* Здесь же застала технологию DITA на языке XML.

* ++Еще была интересная задача:++ с помощью ИИ я сгенерировала около сотни ссылок на адреса сервисных центров в Яндекс Картах и добавила их в таблицы как кнопку «Посмотреть на карте». Вот одна из страниц с такими таблицами:

  [Замена и ремонт](https://alice.yandex.ru/support/ru/services)

### Что по текстам

[Алиса сообщает о проблеме со Станцией или молчит](https://alice.yandex.ru/support/ru/station/troubleshooting/assistant-reports#tape)

[Сценарии с группами устройств](https://alice.yandex.ru/support/ru/smart-home/scenarios/device-group)

[Проблемы с устройствами Matter™](https://alice.yandex.ru/support/ru/smart-home/third-party/troubleshooting/matter)

[ Почему на Станции горит зеленая подсветка](https://alice.yandex.ru/support/ru/station/troubleshooting/green-light)

---

## Yandex Factory {#yandex-factory}

Придумыванием и согласованием структуры этого кластера занимаются продюсеры, но как исполнитель я работаю над ним полностью сама. Работа с текстом здесь минимальная, скорее техническая часть:

* Создала документацию на Diplodoc с нуля, в том числе настроила конфиги.

* Создавала кнопки и карточки в Figma, делала CSS-оформление таблиц.

* Предлагала структуру и защищала свои идеи.

++Как только ссылка появится в продакшене, я обязательно ее добавлю)++
