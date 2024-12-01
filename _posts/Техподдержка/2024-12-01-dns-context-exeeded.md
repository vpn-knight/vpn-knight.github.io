---
title: |
    app/dns: failed to retrieve response for *** > Post "https://8.8.8.8/dns-query": context deadline exeeded
categories: [Техподдержка, NekoRay]
tags: [техподдержка, техническое, nekoray]     # TAG names should always be lowercase
description: Много сообщений о неудачных попытках разрешить доменное имя в IP адрес.
---

## Быстрый ответ

> __Нужно сделать:__ Поменять настройки DNS сервера в приложении на `tls://1.1.1.1`.
{: .prompt-info }

для NekoRay это

`Preferences -> Routing Settings -> DNS -> Remote DNS`

или

`Настройки -> Настройки маршрутов -> DNS -> Удаленный (remote) DNS`

ЗДЕСЬ ДОЛЖНО БЫТЬ ИЗОБРАЖЕНИЕ ПРИЛОЖЕНИЯ ДЛЯ ДЕМОНСТРАЦИИ

## Почему так?

[https://github.com/MatsuriDayo/nekoray/issues/487](https://github.com/MatsuriDayo/nekoray/issues/487)

И это помогло нескольким пользователям. В чем причина - без понятия.