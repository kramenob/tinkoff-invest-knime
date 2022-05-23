# Инструкция по установке и настройке

Весь процесс установки и настройки осуществлен на ОС Windows 10



## Загрузка необходимого

### GitHub репозиторий workspace

Клонировать [GitHub репозиторий workspace](https://github.com/ruisdaeless/tinkoff_invest_knime) в удобное место на ПК следующей командой:

```bash
git clone https://github.com/ruisdaeless/tinkoff_invest_knime
```

**Или** загрузить архив со [страницы релизов](https://github.com/ruisdaeless/tinkoff_invest_knime/releases).

### KNIME Analytics Platform

Загрузить установщик KNIME с официального сайта: https://www.knime.com/downloads/download-knime

- [Прямая ссылка на загрузку для Windows](https://download.knime.org/analytics-platform/win/knime-latest-installer-win32.win32.x86_64.exe) (486 MB)

- [Прямая ссылка на загрузку для Linux](https://download.knime.org/analytics-platform/linux/knime-latest-linux.gtk.x86_64.tar.gz) (601 MB)

- [Прямая ссылка на загрузку для macOS](https://download.knime.org/analytics-platform/macosx/knime-latest-app.macosx.cocoa.x86_64.dmg) (566 MB)

### Palladian for KNIME

Загрузить пакет расширения Palladian с официального сайта: https://nodepit.com/iu/ws.palladian.nodes.feature.feature.group

- [Прямая ссылка на загрузку](https://download.nodepit.com/palladian/4.5.zip) (70.5 MB, рекомендуется)

Установка Palladian for KNIME будет рассмотрена на примере пакета, а не ссылки-источника



## Установка

### KNIME Analytics Platform

1. Запустить загруженный установщик `KNIME 4.5.2 Installer (64bit)`
2. Следовать дальнейшей инструкции по установке. Рекомендуется не менять путь установки

По завершению установки KNIME будет автоматически запущен



## Настройка

### Workspace

1. По запуску KNIME Analytics Platform всплывет следующее окно:

   в котором необходимо указать путь к папке, клонированного ранее репозитория ([Скриншоте 01](https://i.ibb.co/XX67b5s/01.png)),

   нажать `Launch`

<p align="center">
  <a href="https://i.ibb.co/XX67b5s/01.png" alt="01"><img src="https://i.ibb.co/XX67b5s/01.png"/></a>
</p>

2.  Когда KNIME Analytics Platform загрузится, будет открыт MAIN workflow ([Скриншоте 02](https://i.ibb.co/GcXnLSd/02.png)):

<p align="center">
  <a href="https://i.ibb.co/GcXnLSd/02.png" alt="01"><img src="https://i.ibb.co/GcXnLSd/02.png"/></a>
</p>
На этом этапе Workspace, Tinkoff Invest KNIME, настроен

### Extension (Расширение)

1. Не закрывая KNIME Analytics Platform, открыть настройки: `File` - `Preferences` ([Скриншоте 03](https://i.ibb.co/jG1GCX0/03.png))

<p align="center">
  <a href="https://i.ibb.co/jG1GCX0/03.png" alt="01"><img src="https://i.ibb.co/jG1GCX0/03.png"/></a>
</p>

2. В боковом меню слева: `Install/Update` перейти в `Available Software Sites` ([Скриншоте 04](https://i.ibb.co/W0Ts2N7/04.png), цифра 1)
2. Убрать все галочки с чек-боксов ([Скриншоте 04](https://i.ibb.co/W0Ts2N7/04.png), цифра 2)
2. Нажать `Add...` ([Скриншоте 04](https://i.ibb.co/W0Ts2N7/04.png), цифра 3)

<p align="center">
  <a href="https://i.ibb.co/W0Ts2N7/04.png" alt="01"><img src="https://i.ibb.co/W0Ts2N7/04.png"/></a>
</p>

2. На всплывшем окне "Add Site" ([Скриншоте 05](https://i.ibb.co/dcWTYWx/05.png)):

   Указать `Name:` Palladian

   Нажать `Archive...` и выбрать загруженный архив расширения Palladian

   Нажать `Add` для добавления

<p align="center">
  <a href="https://i.ibb.co/dcWTYWx/05.png" alt="01"><img src="https://i.ibb.co/dcWTYWx/05.png"/></a>
</p>

2. Пакет расширений подключен ([Скриншоте 06](https://i.ibb.co/LphQFx0/06.png)):
   Нажать `Apply and Close`

<p align="center">
  <a href="https://i.ibb.co/LphQFx0/06.png" alt="01"><img src="https://i.ibb.co/LphQFx0/06.png"/></a>
</p>

2. Остается запустить установку расширений ([Скриншоте 07](https://i.ibb.co/ypDTCS1/07.png)):

   Перейти по `File` - `Install KNIME Extensions...`

<p align="center">
  <a href="https://i.ibb.co/ypDTCS1/07.png" alt="01"><img src="https://i.ibb.co/ypDTCS1/07.png"/></a>
</p>

2. Галочкой заполнить чек-бокс "Palladian for KNIME" ([Скриншоте 08](https://i.ibb.co/X4jmY1c/08.png)):
   Нажать `Next >`, затем снова `Next >` вплоть до `Finish`

<p align="center">
  <a href="https://i.ibb.co/X4jmY1c/08.png" alt="01"><img src="https://i.ibb.co/X4jmY1c/08.png"/></a>
</p>
В процессе установки необходимо принять пользовательское соглашение и "установить в любом случае".

После успешной установки на всплывшем окне нажать `Restart Now` для применение установленного расширения

<p align="center">
  <a href="https://i.ibb.co/jzpJ933/09.png" alt="01"><img src="https://i.ibb.co/jzpJ933/09.png"/></a>
</p>
На этом моменте рабочее окружение полностью настроенное и можно приступить к [Использованию](https://github.com/ruisdaeless/tinkoff_invest_knime/#%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
