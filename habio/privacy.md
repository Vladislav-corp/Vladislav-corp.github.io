---
permalink: /habio/privacy/
title: "Habio — Privacy Policy"
---

# Habio – Privacy Policy

**Last updated:** 2026-07-28

## Overview / Обзор

Habio – iOS приложение для отслеживания привычек. Все данные хранятся локально на устройстве через SwiftData. У Habio нет серверов, аккаунтов и облачной синхронизации.

Habio is an iOS habit tracker. All data is stored locally on your device via SwiftData. Habio has no servers, accounts, or cloud sync.

## What we store / Что мы храним

Только то, что вы сами создаёте в приложении: названия привычек, расписания, отметки выполнения, заметки. Данные живут в локальной SwiftData-базе и shared App Group container для синхронизации с виджетом.

Only what you create in the app: habit names, schedules, completion marks, notes. Data lives in a local SwiftData store and a shared App Group container for widget synchronization.

## Data never leaves your device / Данные не покидают устройство

Habio не передаёт никакие данные на серверы – у Habio нет серверов. Нет аккаунтов, нет облачного бэкапа, нет third-party аналитики (Firebase, Amplitude, Mixpanel, Sentry и т.п.).

Habio does not transmit any data to servers – Habio has no servers. No accounts, no cloud backup, no third-party analytics (Firebase, Amplitude, Mixpanel, Sentry, etc.).

## Notifications / Уведомления

Habio использует local notifications (через `UNUserNotificationCenter`) для напоминаний о привычках. Push notifications через сервер НЕ используются. Разрешение запрашивается только когда вы включаете напоминание в привычке. Отозвать можно через Settings → Notifications → Habio.

Habio uses local notifications (via `UNUserNotificationCenter`) for habit reminders. No server-driven push notifications are used. Permission is requested only when you enable a reminder on a habit. You can revoke it via Settings → Notifications → Habio.

## Required Reason APIs / Декларация API

Согласно требованиям Apple, Habio декларирует использование:

- `UserDefaults` (reason `CA92.1`) – настройки приложения и состояние виджета.
- File timestamp APIs (reason `C617.1`) – стандартные операции SwiftData с локальным хранилищем.

Per Apple's Required Reason API rules, Habio declares:

- `UserDefaults` (reason `CA92.1`) – app settings and widget state.
- File timestamp APIs (reason `C617.1`) – standard SwiftData operations on local storage.

## Tracking / Трекинг

Habio не отслеживает вас между приложениями и сайтами. `NSPrivacyTracking = false`, `NSPrivacyTrackingDomains` пустой.

Habio does not track you across apps and websites. `NSPrivacyTracking = false`, `NSPrivacyTrackingDomains` empty.

## Subscriptions and purchases / Подписки и покупки

Habio предлагает платный уровень Habio Premium: автопродлеваемые подписки (месячная и годовая) и разовую покупку lifetime. Все платежи обрабатывает Apple через StoreKit. Habio не получает и не хранит платёжные данные: ни номера карт, ни адреса, ни имя владельца. Приложение видит только факт наличия активной покупки, и этот признак остаётся на устройстве.

Habio offers a paid tier, Habio Premium: auto-renewable subscriptions (monthly and yearly) and a one-time lifetime purchase. All payments are processed by Apple via StoreKit. Habio neither receives nor stores payment data: no card numbers, no addresses, no cardholder name. The app only sees whether an active purchase exists, and that flag stays on the device.

## Children / Дети

Habio не предназначен для детей младше 13 лет.

Habio is not intended for children under 13.

## Changes / Изменения

При существенных изменениях этой политики мы обновим дату вверху файла и сообщим в App Store update notes.

For material changes to this policy, we will update the date at the top and announce it in App Store update notes.

## Contact / Контакты

Email: vrnrelax@gmail.com
Developer: Individual Entrepreneur Vladislav Kolupaev
