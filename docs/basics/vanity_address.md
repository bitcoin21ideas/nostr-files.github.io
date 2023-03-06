---
layout: default
title: Генераторы запоминающихся ключей
parent: Основы Nostr
nav_order: 7
---

[← Инструменты](https://nostr.21ideas.org/docs/basics/tools.html) | [Верификация NIP-05 →](https://nostr.21ideas.org/docs/basics/stats.html)

![vanity](https://cdn.discordapp.com/attachments/1082203170979205172/1082243258345857134/Tony_HODLer_Blueprint_of_a_bulky_computer_from_the_1980-s_Leona_800b54d1-2556-4201-8492-dfd6c94cc0f8.png)

# Генераторы запоминающихся ключей
Генераторы запоминающихся ключей, известных в биткоин-кругах как [Vanity-адреса](https://en.bitcoin.it/wiki/Vanitygen#Difficulty_of_finding_a_vanity_address), позволяют создать публичный ключ Nostr, который будет начинаться c выбранных вами символов (или заканчиваться ими). Такая утилита позволяет добавить немного персонализации вашему адресу. Учтите, что чем больше символов вы хотите указать, тем больше времени займет Proof-of-Work генерация такого адреса (зависит от мощности вашего компьютера).

{: .info }
> Например, поиск одного символа может занять до 0.1 секунды
> 
> Двух - до 1 секунды
> 
> Трех - до 30 секунд
> 
> Четырех - до 10 минут
> 
> Пяти - до часа
> 
> Хотите подобрать шесть символов? Несите огнетушитель и да поможет вам бог!

* [hitony.com](https://hitony.com/nostrogen/) — bech32 генератор (npub1)
* [nostr.rest](https://www.nostr.rest/) — генератор адресов через хеширование

{: .highlight}
> Генерация Vanity-адресов не является обязательной, но если вы все же решили завладеть "красивым" адресом, делайте это в оффлайн-среде (на устройстве, отключенном от интернета).

[← Инструменты](https://nostr.21ideas.org/docs/basics/tools.html) | [Верификация NIP-05 →](https://nostr.21ideas.org/docs/basics/stats.html)
