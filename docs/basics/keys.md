---
layout: default
title: Ключи
parent: Основы Nostr
nav_order: 2
---

[← Что такое Nostr?](https://nostr.21ideas.org/docs/basics/what-is-nostr.html) | [Управление ключами →](https://nostr.21ideas.org/docs/basics/keys_management.html)

![keys](https://cdn.discordapp.com/attachments/1082203170979205172/1082236494363770900/Tony_HODLer_Blueprint_of_numerous_keys_Leonardo_Da_Vinci_white__8e05ce5f-ab2e-4e50-8197-b114961c127c.png)

# Ключи
Ваши ключи – это ваша личность. Вы можете считать свой открытый ключ (`npub...`) своим именем пользователя, а свой закрытый ключ (`nsec...`) – своим паролем.

{: .highlight }
> Не вставляйте свой закрытый ключ в поля на веб-сайтах
> 
> Храните ключи [надежным образом](https://nostr.21ideas.org/docs/guides/Alby.html) и ни с кем не делитесь своим закрытым ключом.
> 
> В отличие от пароля, ваш приватный **ключ нельзя восстановить** в случае утери.
> 
> Если вы потеряете приватный ключ, вы **потеряете аккаунт** Nostr. Если кто-то получит доступ к вашему приватному ключу, он **получит контроль** над вашим аккаунтом.

Ключи существуют в двух форматах – шестнадцатеричном `hex` и вышеупомянутом `npub`/`nsec`. 

{: .info }
> Ключи в формате `hex` выглядят следующим образом: `7f5c2b4e48a0e9feca63a46b13cdb82489f4020398d60a2070a968caa818d75d`

Для преобразования между этими двумя форматами можно использовать [инструмент конвертации ключей](https://damus.io/key/).

[← Что такое Nostr?](https://nostr.21ideas.org/docs/basics/what-is-nostr.html) | [Управление ключами →](https://nostr.21ideas.org/docs/basics/keys_management.html)
