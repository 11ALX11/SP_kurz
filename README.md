# SP_kurz

Курсовой проект по Системному Программированию

## Проект драйвера виртуального монитора

Проект в папке [IndirectDisplay](./IndirectDisplay). За основу взят [IndirectDisplay sample из репозитория microsoft/Windows-driver-samples](https://github.com/microsoft/Windows-driver-samples/tree/main/video/IndirectDisplay).

### Использование

Готовые к использованию файлы проекта можно найти в [релизе v0.1.0](https://github.com/11ALX11/SP_kurz/releases/tag/v0.1.0).

Перед использованием нужно подписать драйвер:

- С правами админа запустите .bat

С помощью *IddSampleApp.exe* можно временно добавить монитор. (запуск от имени администратора).

Альтернативно, можно установить драйвер. Зайдите в **диспетчере устройств**. Кликните по любому устройству, выберите в панели меню (сверху) **Действие -> Установить старое устройство**. Дальше нас интересует **установка вручную** (но на самом деле без разницы). Дальше ищем в списке **Видеоадаптеры**. Теперь выбираем **Установить с диска** и ищем наш **.inf** драйвер.

> [!WARNING]
> Если есть желание удалить виртуальный монитор, в **диспетчере устройств -> видеоадаптеры**  ищите **IddSampleDriver Device**. **Удалите** этот фиктивный адаптер.

## Лист задания

![Отсутствует](./doc/list.jpeg)

## Курсовой проект (документ)

[Отсутствет](./doc/kurz.docx)

## Литература

* https://habr.com/ru/articles/145926/

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/gettingstarted/what-is-a-driver-

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/gettingstarted/user-mode-and-kernel-mode

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/gettingstarted/writing-your-first-driver

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/gettingstarted/writing-a-umdf-driver-based-on-a-template

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/gettingstarted/writing-a-very-small-kmdf--driver

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/gettingstarted/writing-a-kmdf-driver-based-on-a-template

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/gettingstarted/provision-a-target-computer-wdk-8-1

* https://learn.microsoft.com/en-us/windows-hardware/drivers/display/multiple-monitor-support-in-the-display-driver

* https://learn.microsoft.com/en-us/windows-hardware/drivers/display/

* https://learn.microsoft.com/en-us/windows-hardware/drivers/display/roadmap-for-developing-drivers-for-the-windows-vista-display-driver-mo

* https://learn.microsoft.com/en-us/windows-hardware/drivers/display/initializing-display-miniport-and-user-mode-display-drivers

* https://learn.microsoft.com/en-us/windows-hardware/drivers/install/installing-test-signed-driver-packages

* https://learn.microsoft.com/ru-ru/windows-hardware/drivers/install/the-testsigning-boot-configuration-option
