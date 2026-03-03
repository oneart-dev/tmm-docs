# Подключения <a target="_blank" href="https://tradermake.money/app2/settings/?tab=connections" class="btn btn-header">Перейти в подключения</a>

Раздел «Подключения» — это ваш центральный узел для интеграции Trader Make Money с внешними сервисами, такими как Telegram и Discord. Это позволяет получать уведомления, отчеты и алерты в реальном времени прямо там, где вы общаетесь.

## Обзор

На панели управления подключениями вы можете управлять всеми активными интеграциями, видеть, какие уведомления включены для каждой из них, и быстро добавлять новые.

<picture>
  <source srcset="_media/connections/overview_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/overview.png">
</picture>

---

## Настройка нового подключения

Выполните следующие шаги, чтобы связать новый сервис с вашим торговым журналом.

<!-- panels:start -->
<!-- div:left-panel -->

### Шаг 1: Выберите сервис
В данный момент вы можете подключить свой торговый журнал к:
- **Telegram**: Получайте обновления в личные сообщения, закрытые группы или публичные каналы.
- **Discord**: Свяжите с вашим личным или публичным сервером Discord.

<!-- div:right-panel -->

<picture>
  <source srcset="_media/connections/step1_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/step1.png" class="medium-img">
</picture>
<em>Выбор типа сервиса</em>

<!-- panels:end -->

<!-- panels:start -->
<!-- div:left-panel -->

### Шаг 2: Базовая конфигурация
Дайте вашему подключению узнаваемое имя (например, «Личный Telegram» или «Торговая группа Discord»).

Выберите типы уведомлений, которые вы хотите получать:
- **Новая сделка**: Мгновенное оповещение при открытии позиции.
- **Результаты сделки**: Сводка прибыли/убытка при закрытии сделки.
- **Исполнение ордера**: Подробный лог каждого ордера на покупку или продажу.
- **Нарушение правил риска**: Оповещения в реальном времени при достижении границ [Управления рисками](risk-management.md).

<!-- div:right-panel -->

<picture>
  <source srcset="_media/connections/step2_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/step2.png" class="medium-img">
</picture>
<em>Имя подключения и типы уведомлений</em>

<!-- panels:end -->

<!-- panels:start -->
<!-- div:left-panel -->

### Шаг 3: Детальные настройки
Настройте, какие именно данные и как будут отправляться для этого подключения:

- **API-ключи**: Выберите, по каким аккаунтам должны приходить уведомления.
- **Язык**: Выберите язык сообщений.
- **Приватный режим**: Если включен, то точные числовые значения (например, прибыль в $) будут скрыты — идеально для публичных каналов.

<!-- div:right-panel -->

<picture>
  <source srcset="_media/connections/step3_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/step3.png" class="medium-img">
</picture>
<em>Выбор языка и API-ключей</em>

<!-- panels:end -->

---

## Завершение подключения

После нажатия кнопки **Создать** вы получите конкретные инструкции для завершения связи между нашей платформой и выбранным сервисом.

### Подключения Telegram

<!-- panels:start -->
<!-- div:left-panel -->

#### Личный чат
1. Нажмите кнопку **Создать подключение**.
2. Вы будете перенаправлены в приложение Telegram.
3. Нажмите кнопку **Start**, чтобы связать свой аккаунт.

<!-- div:right-panel -->

<picture>
  <source srcset="_media/connections/telegram_connect_personal_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/telegram_connect_personal.png" class="small-img">
</picture>
<em>Личное подключение Telegram</em>

<!-- panels:end -->

<!-- panels:start -->
<!-- div:left-panel -->

#### Группы и каналы
1. Добавьте бота `@TraderMakeMoneyBot` в свою группу или канал в качестве **Администратора**.
2. Скопируйте уникальную команду `/start`, указанную в инструкции.
3. Отправьте эту команду в вашу группу или канал.

> **Важный нюанс**: Вы **должны** отправить сообщение о подключении от имени своего **личного аккаунта**. Если вы отправите его, используя функцию Telegram «Анонимный администратор» или «Отправить от имени канала», подключение не будет установлено.

<!-- div:right-panel -->

<picture>
  <source srcset="_media/connections/telegram_connect_group_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/telegram_connect_group.png" class="small-img">
</picture>
<em>Подключение группы в Telegram</em>

<!-- panels:end -->

### Подключения Discord

<!-- panels:start -->
<!-- div:left-panel -->

1. Нажмите кнопку **Создать подключение** (вы должны быть создателем сервера).
2. Разрешите боту присоединиться к вашему серверу.
3. Скопируйте уникальную команду `/tmm-start`, указанную в инструкции.
4. Отправьте ее в конкретный **канал**, в котором вы хотите получать уведомления.

> **Заметка о приватности**: Бот ответит скрытым сообщением с подтверждением, которое будете видеть только вы. Другие участники сервера не увидят, что вы отправили команду или что подключение было установлено.

<!-- div:right-panel -->

<picture>
  <source srcset="_media/connections/discord_connect_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/discord_connect.png" class="small-img">
</picture>
<em>Инструкция по подключению Discord</em>

<!-- panels:end -->

---

## Продвинутые функции уведомлений

Настройка позволяет сделать ваши уведомления настолько подробными или минималистичными, насколько вы захотите.

<!-- panels:start -->
<!-- div:left-panel -->

### Визуализация и шаблоны
Для каждого типа уведомлений вы можете включить дополнительные функции:

- **Предпросмотр графика**: Добавьте скриншот графика сделки и точек исполнения прямо в сообщение.
- **Шаблон уведомления**: Используйте стандартный вид или создайте полностью индивидуальное сообщение с помощью нашего движка шаблонов.

<!-- div:right-panel -->

<picture>
  <source srcset="_media/connections/step4_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/step4.png" class="medium-img">
</picture>
<em>Настройки шаблона и изображений</em>

<!-- panels:end -->

### Пользовательские шаблоны уведомлений

«Сделайте уведомления своими». Наш движок шаблонов использует **токены**, которые автоматически заменяются реальными данными о сделке.

- **Гибкий макет**: Меняйте порядок информации так, как удобно вам.
- **Поддержка Emoji**: Добавляйте иконки для быстрой идентификации типа сделки (Long/Short) или результата (Профит/Лосс).
- **Доступные токены**: Используйте токены, такие как `{{apikey}}`, `{{side}}`, `{{ticker}}`, `{{profit}}` и многие другие, чтобы собрать идеальное оповещение.

<picture>
  <source srcset="_media/connections/new-custom-template_dark.png" media="(prefers-color-scheme: dark)">
  <img src="_media/connections/new-custom-template.png">
</picture>
<em>Редактор пользовательского шаблона</em>
