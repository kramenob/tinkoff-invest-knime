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

*в написании*





























