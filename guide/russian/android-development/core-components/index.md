---
title: Android core components
localeTitle: Основные компоненты Android
---
# Основные компоненты Android

Основными компонентами являются основные элементы, из которых состоит приложение для Android. Каждый из них имеет свою собственную цель и жизненный цикл, но не все из них независимы. Они бывают следующих видов:

- Активности (Activities)
- Сервисы (Services)
- Приемники широковещательных сообщений (Broadcast Receivers)
- Поставщики контента (Content Providers)

## [Активности](https://developer.android.com/guide/components/activities/)

_Активность_ - это компонент, который имеет пользовательский интерфейс и представляет собой один экран. Приложение может иметь несколько активностей, каждая из которых может быть точкой входа для самого приложения для пользователя или системы (активность приложения, которое хочет открыть другую активность, принадлежащую одному и тому же приложению или другому).

## [Сервисы](https://developer.android.com/guide/components/services)

_Служба_ представляет собой компонент без пользовательского интерфейса для выполнения длительных операций в фоновом режиме. Существует два вида служб:

- _службы переднего плана_: они строго связаны с взаимодействием пользователя (например, с воспроизведением музыки), поэтому системе сложнее их завершить.
- _фоновые службы_: они напрямую не связаны с деятельностью пользователя, поэтому система может их завершить, если требуется больше ОЗУ.

## [Приемники широковещательных сообщений](https://developer.android.com/guide/components/broadcasts)

_Широковещательный приемник_ - это еще один компонент без пользовательского интерфейса (кроме уведомления в статусной строке), который позволяет системе отправлять события из/в приложение, даже если последнее не было ранее запущено.

## [Поставщики контента](https://developer.android.com/guide/topics/providers/content-providers)

_Поставщик контента_ - это компонент, используемый для управления набором данных приложения для совместного использования с другими приложениями. Каждый элемент, сохраненный в поставщике контента, идентифицируется схемой URI.

Подробную информацию об этой теме см. в [официальной документации по основам Android](https://developer.android.com/guide/components/fundamentals).