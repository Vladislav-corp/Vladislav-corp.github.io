---
permalink: /glow/privacy/
title: "Glow — Privacy Policy"
---

# Glow — Privacy Policy

**Last updated:** 2026-05-12

## Overview / Обзор

Glow — iOS приложение, превращающее iPhone в StandBy-режиме в кастомизируемые прикроватные часы с каталогом тем. Всё хранение и вычисления происходят локально на устройстве.

Glow is an iOS app that turns your iPhone in StandBy mode into a customizable bedside clock with a catalog of themes. All storage and computation happen locally on your device.

## No data collection / Сбор данных не ведётся

Glow не собирает, не хранит, не обрабатывает и не передаёт никакие персональные данные. Нет пользовательских аккаунтов, нет аналитики, нет отслеживания, нет third-party SDK, нет передачи данных на внешние серверы.

Glow does not collect, store, process, or share any personal data. No user accounts, no analytics, no tracking, no third-party SDKs, no transmission to external servers.

Пользовательские настройки (выбранная тема, формат времени, ночной режим) хранятся в локальном `UserDefaults` и shared App Group container — для синхронизации между приложением, виджетом StandBy и Live Activity. Эти данные **не покидают устройство**.

User preferences (selected theme, time format, night mode) are stored in local `UserDefaults` and a shared App Group container — to sync between the app, the StandBy widget, and Live Activity. This data **never leaves the device**.

## Location / Геолокация

Некоторые темы (Tide, Sunrise) могут запросить доступ к приблизительной геолокации для отображения зависимого от места содержимого: следующий прилив, время восхода и т. п. Координаты используются **только на устройстве** для расчёта отображения и не сохраняются и не передаются на серверы.

Some themes (Tide, Sunrise) may request access to your approximate location to display location-dependent content: next tide event, sunrise time, etc. Location data is used **only on-device** for display computation and is not stored or transmitted to any server.

Вы можете отозвать разрешение в любой момент: Settings → Privacy & Security → Location Services → Glow. Темы, зависящие от локации, переключатся в статический режим.

You can revoke access any time: Settings → Privacy & Security → Location Services → Glow. Location-dependent themes will fall back to a static state.

## Calendar / Календарь

Тема Calendar Next читает ближайшие события из iOS-календаря через EventKit для отображения следующего события и обратного отсчёта. Данные календаря читаются **только на устройстве** и не сохраняются вне приложения.

The Calendar Next theme reads upcoming events from your iOS calendar via EventKit to display the next event and a countdown. Calendar data is read **only on-device** and is not stored off-device.

Отозвать доступ: Settings → Privacy & Security → Calendars → Glow.

Revoke any time: Settings → Privacy & Security → Calendars → Glow.

## In-App Purchases / Покупки

Покупки обрабатываются Apple через App Store. Политика Apple регулирует обработку платёжных данных. Glow получает от StoreKit только статус entitlement (разблокирован ли пак тем) и хранит его в локальном App Group container.

In-app purchases are processed by Apple via the App Store. Apple's privacy policy governs payment data handling. Glow receives only entitlement status (whether a theme pack is unlocked) from StoreKit and stores it in the local App Group container.

## Widgets and Live Activities / Виджеты и Live Activity

Виджеты StandBy и Live Activity Glow работают на устройстве через WidgetKit и ActivityKit. Они читают те же локальные настройки и ассеты тем, что и основное приложение. Данные не передаются вовне устройства.

Glow widgets and Live Activities run on-device via WidgetKit and ActivityKit. They read the same local preferences and theme assets as the main app. No data is transmitted off-device.

## Children / Дети

Glow не предназначен для детей младше 13 лет.

Glow is not intended for children under 13.

## Changes / Изменения

При существенных изменениях этой политики мы обновим дату вверху файла и уведомим в App Store update notes.

For material changes to this policy, we will update the date at the top and notify via App Store update notes.

## Contact / Контакты

Email: vrnrelax@gmail.com
Developer: Individual Entrepreneur Vladislav Kolupaev
