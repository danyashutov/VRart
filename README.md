# VR art

## Цель проекта

Создание VR приложения представляющего собой виртуальный музей картин, при взаимодействии с которыми проигрываются уникальные визуальные и звуковые эффекты.

## Описание проекта

Приложение виртуальной реальности, позволяющее наслаждаться шедеврами изобразительного искусства, преображёнными визуальными эффектами. Также к каждой картине будет доступно уникальное музыкальное сопровождение, которое позволит погрузиться в нужную атмосферу. Общая цель приложения – релаксация для пользователя.

## Задачи по реализации

- реализовать движение с помощью контроллеров (перемещение + поворот)
- проработать помещение (музейный зал)
- подобрать картины
- придумать и проработать визуальные и звуковые эффекты
- реализовать эффекты
- настроить автоматическое включение эффектов при подходе к картине

## Описание технологий
Платформа для разработки проекта: Unity  
Веб-сервис для совместной работы: Unity Collab  
Архитектурный паттерн: Game Loop  
Язык программирования: C#  
Фреймворки: .NET (Mono), OpenXR  
Для реализации анимаций и картин понадобилось работать с инструментами .NET (синхронизация потоков, волатильные поля и interlocked конструкции), инструментом для анимации Unity и корутинами (которые так же предоставляет движок Unity). С помощью данных инструментов были анимированы: руки игрока, двери и все анимации картин.
Для реализации VR части проекта мы использовали OpenXR плагин. Данный плагин является основным фреймворком для работы с VR для Unity. С помощью фреймворка было реализовано передвижение, повороты (через контроллеры), анимацию рук игрока, отслеживание игрока в реальном пространстве (для передвижения и поворотов без контроллеров).


| Ассеты | |
|-----|-----|
| Двери | https://assetstore.unity.com/packages/3d/props/interi.. |
| Музей | https://assetstore.unity.com/packages/3d/environments.. |
| Водопад | https://assetstore.unity.com/packages/vfx/particles/s.. |
| Салют | https://assetstore.unity.com/packages/vfx/particles/s.. |
| Вулкан | https://assetstore.unity.com/packages/vfx/particles/s.. |
| Окно | https://assetstore.unity.com/packages/tools/particles.. |
| Корабль| https://assetstore.unity.com/packages/3d/environments.. |
| Огонь | https://assetstore.unity.com/packages/vfx/particles/f.. |


## Команда проекта

| ФИО |
|-----|
| Шутов Даниил |
| Демин Глеб |
| Ковалеров Ярослав |
| Хорошкеева Ксения |

## Контакты
Телеграмм: @danyaa_s

## Оборудование для проекта

| Наименование | Стоимость |
|-----|-----|
| VR шлем Oculus Quest 2 | - |

## Видео проекта
https://drive.google.com/file/d/1WzrrH8szBsPotCrmfPCE4SkTgomWq0Vv/view 

## Аудитория для работы

Нужна
