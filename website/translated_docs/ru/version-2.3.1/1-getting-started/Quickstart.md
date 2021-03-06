---
id: version-2.3.1-Quickstart
title: Быстрый старт
sidebar_label: Быстрый старт
original_id: Quickstart
---

Эта страница предоставляет руководство для пользователей с различными целями, чтобы помочь определиться какие именно части в документации стоит просматривать.

## Если вы хотите знать базовые концепции IOST

Вначале будет полезно ознакомиться с базовыми понятиями IOST и иметь полное представление об IOST перед тем как углубиться в технические детали IOST или разработку смарт-контрактов на IOST. Вы можете изучить некоторые основные понятия о [системе аккаунтов](2-intro-of-iost/Account.md), [экономической модели](2-intro-of-iost/Economic-model.md), [процессе голосования](2-intro-of-iost/Vote.md) IOST.



## Если вы хотите использовать IOST

Вы можете присоединиться к комьюнити IOST и участвовать в ежедневной работе IOST даже если вы и *НЕ* являетесь разработчиком.  
Вы можете [подать заявку на аккаунт IOST](https://explorer.iost.io/applyIOST) и [просмотреть наш браузер](http://47.244.109.92:8006/).

## Если вы разработчик

Для разработчиков есть много материалов, которые вам могут помочь.

### Запустите и попробуйте IOST

Вы можете выбрать [запуск локальной одноузловой сети](4-running-iost-node/LocalServer.md) или [присоединиться к сети IOST](4-running-iost-node/Deployment.md).   
Вы можете использовать [инструмент командной строки](4-running-iost-node/iWallet.md) для взаимодействия с блокчейном IOST.

### Разработка смарт-контрактов

Будучи разработчиком смарт-контрактов, вы можете обратиться к [разделам разработки смарт-контрактов](3-smart-contract/ContractStart.md) для получения подробной информации.   

Также предоставлены некоторые примеры для разработчиков смарт-контрактов, в которых описывается как писать/развертывать/запускать контракты.

#### Пример Bet
Этот пример включает контракт bet написанный на javascript и скрипт, демонстрирующий развертывание/вызов контракта с помощью командной строки.

* [документация](5-lucky-bet/LuckyBet.md)
* [код](https://github.com/iost-official/luckybet_sample)

#### Пример Go Game
Это веб-страница go game с использованием в бэкенде блокчейна IOST .   

* [код контракта](https://github.com/iost-official/contracts/tree/master/demos)
* [код фронтенда](https://github.com/iost-official/gobang)
* [веб-страница игры](http://47.244.109.92:8001)

Также вы можете использовать некоторые контракты предоставленные IOST, включая [экономические контракты](6-reference/EconContract.md) и [системные контракты](6-reference/SystemContract.md). Вы также можете обратиться к [таблице расходов gas](6-reference/GasChargeTable.md) для просчета расходов связанных с контрактом.

### SDK и API

Для разработчиков предусмотрены также SDK и API:

* Javascript SDK
	* [код](https://github.com/iost-official/iost.js)
	* Документация по [классу IOST](7-iost-js/IOST-class.md), [классу blockchain](7-iost-js/Blockchain-class.md), [классу keypair](7-iost-js/KeyPair-class.md) и [классу transaction](7-iost-js/Transaction-class.md)
* Java SDK
	* [код](https://github.com/iost-official/java-sdk)
* Python SDK
	* [код](https://github.com/iost-official/pyost)
* JSON RPC API
	* [Документация](6-reference/API.md)

## Если вас интересуют технические детали

Те из вас, которые интересуются техническими деталями, могут изучить [инфраструктуру баз данных](2-intro-of-iost/Database.md), [уровень сети](2-intro-of-iost/Network-layer.md) и [виртуальную машину](2-intro-of-iost/VM.md). Вы сможете понять внутреннюю логику IOST с помощью этой документации.

## Помощь
Не стесняйтесь спрашивать на [Slack](https://iost-community.slack.com) или [форуме IOST](https://forum.iost.io), если у вас есть какие-либо вопросы.
