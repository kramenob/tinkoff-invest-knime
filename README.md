<h1 align="center" color="#FFDD2D">TINKOFF INVEST KNIME</h1>
<p align="center">
  <img src="https://i.ibb.co/HGHtHSv/logo.png"/>
</p>
<p align="center">
  <a href="https://www.tinkoff.ru/invest/portfolio/">Tinkoff</a> |
  <a href="https://www.knime.com/">KNIME</a> |
  <a href="https://nodepit.com/product/palladian">Palladian</a>
</p>



<p align="center">
<a href="https://opensource.org/licenses/Apache-2.0"><img alt="apache" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"></a>
<a href="https://www.knime.com/downloads/download-knime"><img alt="knime" src="https://img.shields.io/badge/KNIME-v.4.5-yellow"></a>
<a href="https://nodepit.com/product/palladian"><img alt="palladian" src="https://img.shields.io/badge/Palladian-v.4.5-lightgrey"></a>
<a href="https://www.knime.com/downloads/download-knime"><img alt="platform" src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-orange"></a>
</p>
<h1></h1>


## Работа с API Тинькофф Инвестиций без навыков программирования

Tinkoff Invest [KNIME](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#knime-analitics-platform) — это [Workspace](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#workspace) KNIME с примером простейшего функционала взаимодействия [Tinkoff Invest API](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#tinkoff-invest-api), а именно: авторизация через токен доступа; просмотр информации по инвестиционным счетам; выбор счёта; просмотр информации выбранного брокерского счёта; задание бюджета инвестирования; просмотр доступных инструментов с учётом заданного бюджета; осуществление покупки выбранных инструментов; просмотр информации по осуществленным покупкам; и другое.

В связке KNIME + [Palladian](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#palladian) можно работать с Tinkoff Invest API без навыков программирования, путём интерактивной работы с интерфейсом KNIME: добавление [node'ов](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#workspace) в [workflow](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#workflow), их настройка и исполнение, а также просмотр полученных данных (таблиц, графиков, и др.) с дальнейшим выводом в [Interactive View](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#interactive-view), посредством [component'ов](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#component).

Также есть возможность публикации в общий доступ конфигурированного Workspace посредством [KNIME Server](https://github.com/ruisdaeless/tinkoff_invest_knime/blob/main/docs/glossary.md#knime-server), где любой пользователь сможет работать с Tinkoff Invest API самостоятельно, аналогично веб-сервису.

[Глоссарий терминов](./docs/glossary.md)

## Подготовка

Для успешной работы Tinkoff Invest API в KNIME необходимо:

1. Наличие Брокерского счёта в Тинькофф Инвестициях;
2. Установленный на ПК KNIME Analytics Platform;
3. Установленное расширение KNIME: Palladian for KNIME 

[Инструкция по установке и настройке](./docs/installation.md)

## Использование

После успешной установки и настроки необходимого, workspace доступен к использованию.

### Авторизация

Для совершения каких либо операций необходимо авторизоваться посредством токена доступа, который необходимо выпустить в Инвестиционных настройках Тинькофф аккаунта, на [странице Управление токенами Invest API](https://www.tinkoff.ru/invest/settings/api/).


<p align="center">
  <a href="https://i.ibb.co/JcN9nzh/token.png" alt="token"><img src="https://i.ibb.co/JcN9nzh/token.png"/></a>
</p>


Как токен выпущен - сохраните его в укромное место, к копированию в настройках он более не будет доступен. Но можно будет выпустить новый.

!ВАЖНО! - не делитесь ни с кем токеном. Это запрещено, да и опасно!

Теперь необходимо вставить токен в синий компонент - `Авторизация`, дважды кликнув по которому всплывет диалоговое окно, где в единственное поле необходимо вставить токен и нажать `OK`

<p align="center">
  <a href="https://i.ibb.co/m69qxcB/token-paste.png" alt="token_paste"><img src="https://i.ibb.co/m69qxcB/token-paste.png"/></a>
</p>

Теперь необходимо выполнить компонент на `F7`, после чего будет доступен просмотр `F10`.

### Портфель

Когда таблица всех счетов сформирована можно получить портфель по любому счёту (уровень доступа которого позволяет).

Для этого дважды кликаем по жёлтому компоненту и в выпадающем списке выбираем интересующий счёт и жмём `OK`. На выбранный счёт будет осуществленна пробная покупка инструмента.

<p align="center">
  <a href="https://i.ibb.co/CJyyj2x/account.png" alt="account"><img src="https://i.ibb.co/CJyyj2x/account.png"/></a>
</p>
Теперь необходимо выполнить компонент на `F7`, после чего будет доступен просмотр `F10`.



*на доработка*





















