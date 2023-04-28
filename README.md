SafeInsure Core integration/staging repository
=====================================

 EUR/TJS: AskAndBid(ask=12.47605, bid=12.26265)
EUR/RUB: AskAndBid(ask=88.748, bid=87.23)
RUB/KZT: AskAndBid(ask=5.607267, bid=5.506002)
CNY/RUB: AskAndBid(ask=11.59775, bid=11.39938)
USD/AMD: AskAndBid(ask=400.07568, bid=395.69892)
KGS/RUB: AskAndBid(ask=0.93057, bid=0.91443)
RUB/CNY: AskAndBid(ask=0.087503, bid=0.086416)
RUB/KGS: AskAndBid(ask=1.093853, bid=1.074345)
RUB/TJS: AskAndBid(ask=0.136628, bid=0.134123)
USD/KZT: AskAndBid(ask=465.94576, bid=457.97594)
USD/CNY: AskAndBid(ask=7.29125, bid=7.16835)
TJS/RUB: AskAndBid(ask=7.45214, bid=7.32471)
AMD/RUB: AskAndBid(ask=0.2099, bid=0.20755)
EUR/USD: AskAndBid(ask=1.12865, bid=1.11603)
RUB/AMD: AskAndBid(ask=4.820439, bid=4.761905)
USD/EUR: AskAndBid(ask=0.8992, bid=0.88294)
RUB/USD: AskAndBid(ask=0.012617, bid=0.012385)
EUR/AMD: AskAndBid(ask=441.35928, bid=433.81001)
EUR/CNY: AskAndBid(ask=8.02168, bid=7.88451)
RUB/EUR: AskAndBid(ask=0.01147, bid=0.011259)
USD/TJS: AskAndBid(ask=11.34566, bid=11.15165)
EUR/KGS: AskAndBid(ask=99.84785, bid=98.16475)
EUR/KZT: AskAndBid(ask=512.6235, bid=503.7304)
USD/KGS: AskAndBid(ask=90.50827, bid=89.51813)
USD/RUB: AskAndBid(ask=80.44, bid=79.54)
KZT/RUB: AskAndBid(ask=0.18158, bid=0.17842)
 -----
Maven:
1. IDEA
File | Settings | Build, Execution, Deployment | Build Tools | Maven | Archetype Catalogs

Add catalogs:
Type: Remote
https://nexus.ahml.ru/repository
https://nexus.ahml.ru
https://nexus.ahml.ru/repository/maven-public/

copy from project: potfolio/.m2/setting.xml  to ~/.m2/

Описание к задаче:
Добавить проверку пропуска значений rpt_seq.
При правильной работе Gate этот счетчик должен идти autoincrement.
Если возникает пропуск, должны писаться логи с уровнем Warn.
Логика для Moex и  СПб бирж отличается (необходимо проверить):
1) У Moex rpt_seq отдельный для каждого инструмента
2) СПб используется общий rpt_seq для всех инструментов

На сколько я понял в Gate не реализована обработка ошибок.
Источники данных FAST-протокола:
1) Там идут 2 стрима UDP, 
2) Похоже тоже не реализовано. Есь snapshot данных за сессию
3) Не реализовано. TCP протокол, позволяющий запросить любой диапазон пропущенных данных.

Со слов Ильи все и так ок работает. Но на самом деле, корее всего, никто и не следил за этими пропаданиями данных.

Гэп может быть вызван простым сбоем сети. Даже не сбоем, а коллизией. Не говоря о том, что сервис может быть коратковременно сотановлен.
---

Книги, которые могут вам помочь
"Как привести дела в порядок. Искусство продуктивности без стресса", Дэвид Аллен.
"Жесткий тайм-менеджмент. Возьмите свою жизнь под контроль", Дэн Кеннеди.
"Максимальная концентрация. Как сохранить эффективность в эпоху клипового мышления", Люси Джо Палладино.
"18 минут. Как повысить концентрацию, перестать отвлекаться и сделать действительно важные дела", Питер Брегман.
"Работай меньше, успевай больше", Керри Глинсон.
--

{
На телефон Cisco any connct
	https://wiki.domrf.ru/pages/viewpage.action?pageId=130700890
	Илье Васердаму. мне нужно подклчюится через vpn. оформи  мне заявку
	устновить на тел cisco any connect
	apk install
	В чачте *alone
	in TB
	use ruben12 user
}

Instal telegram

Мои задачи:
{
По задачам на завтра
По возможно тоже писать код
С++, что с ним делать?
	Переписывать на Java
Паша девопс. Забрать архитектуру
}

Встречи:
	С++
	Backend

Try to make software applications
Read Wiki
Try Citrix

Insatall APK:
	Front:
	подключение Илья Васердам.
Clone GitLab
Add TG chats

Созвониться:
	backend C++
	Java
	TL

Есть ли созвоны у Back-end?

Установка софта на ноут:
	список софта

Other TG chat

Front show

HD:
По заявкам можно звонить
50001

Dom_invets тестовые сборки


Safeinsure is a decentralized insurance marketplace bringing equitable price discovery and global access to insurance policy shoppers worldwide. SafeInsure puts consumer power back in your hands with an honest, accountable, and democratic insurance marketplace on the blockchain.
- Decentralized blockchain voting providing for consensus based advancement of the current Masternode technology used to secure the network and provide the above features, each Masternode is secured with collateral of 1000 SINS
- Anonymized transactions using coin mixing technology, we call it _Privatesend_.
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _InstantSend_.

More information at [safeinsure.io](https://www.safeinsure.io)

### Coin Specs
<table>
<tr><td>Type</td><td>POS + Masternode</td></tr>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Maturity</td><td>100 Confirmations</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Masternode Collateral</td><td>1,000 SINS</td></tr>
<tr><td>P2P port</td><td>39105</td></tr>
<tr><td>RPC port</td><td>39106</td></tr>
<tr><td>Max Coin Supply</td><td>21,000,000 SINS</td></tr>
<tr><td>Premine</td><td>5% *</td></tr>
</table>

*View Coin Distribution on [safeinsure.io](https://www.safeinsure.io)

### Reward Distribution


<table>
<thead>
<tr>
<th scope="col">BLock no</th>
<th scope="col">Reward / block</th>
<th scope="col">Staking</th>
<th scope="col">Masternodes</th> 
</tr>
</thead>
<tbody>
<tr>
<th scope="row">1-21600</th>
<th scope="row">0.5 SINS</th>
<td>0.10 SINS (20%)</td>
<td>0.40 SINS (80%)</td> 
</tr>
<tr>
<th scope="row">21601-43200</th>
<th scope="row">1 SINS</th>
<td>0.20 SINS (20%)</td>
<td>0.80 SINS (80%)</td>
</tr>
<tr>
<th scope="row">43201-64800</th>
<th scope="row">1.5 SINS</th>
<td>0.30 SINS (20%)</td>
<td>1.20 SINS (80%)</td>
</tr>
<tr>
<th scope="row">64801-87840</th>
<th scope="row">2 SINS</th>
<td>0.40 SINS (20%)</td>
<td>1.60 SINS (80%)</td>
</tr>
<tr>
<th scope="row">87841-106560</th>
<th scope="row">2.5 SINS</th>
<td>0.37 SINS (15%)</td>
<td>2.12 SINS (85%)</td>
</tr>
<tr>
<th scope="row">106561-129600</th>
<th scope="row">3 SINS</th>
<td>0.45 SINS (15%)</td>
<td>2.55 SINS (85%)</td>
</tr>
<tr>
<th scope="row">129601-151200</th>
<th scope="row">3.5 SINS</th>
<td>0.52 SINS (15%)</td>
<td>2.97 SINS (85%)</td>
</tr>
<tr>
<th scope="row">151201-172800</th>
<th scope="row">4 SINS</th>
<td>0.60 SINS (15%)</td>
<td>3.40 SINS (85%)</td>
</tr>
<tr>
<th scope="row">172801-194400</th>
<th scope="row">4.5 SINS</th>
<td>0.45 SINS (10%)</td>
<td>4.05 SINS (90%)</td>
</tr>
<tr>
<th scope="row">194401-216000</th>
<th scope="row">5 SINS</th>
<td>0.50 SINS (10%)</td>
<td>4.50 SINS (90%)</td>
</tr>
<tr>
<th scope="row">216001-237600</th>
<th scope="row">5.5 SINS</th>
<td>0.55 SINS (10%)</td>
<td>4.95 SINS (90%)</td>
</tr>
<tr>
<th scope="row">237601-259200</th>
<th scope="row">6 SINS</th>
<td>0.60 SINS (10%)</td>
<td>5.40 SINS (90%)</td>
</tr>
<tr>
<th scope="row">259201-280800</th>
<th scope="row">6.5 SINS</th>
<td>0.65 SINS (10%)</td>
<td>5.85 SINS (90%)</td>
</tr>
<tr>
<th scope="row">280801-302400</th>
<th scope="row">7 SINS</th>
<td>0.70 SINS (10%)</td>
<td>6.30 SINS (90%)</td>
</tr>
<tr>
<th scope="row">302401-324000</th>
<th scope="row">7.5 SINS</th>
<td>0.75 SINS (10%)</td>
<td>6.75 SINS (90%)</td>
</tr>
<tr>
<th scope="row">324001-345600</th>
<th scope="row">8 SINS</th>
<td>0.8 0SINS (10%)</td>
<td>7.20 SINS (90%)</td>
</tr>
<tr>
<th scope="row">345601-367200</th>
<th scope="row">8.5 SINS</th>
<td>0.85 SINS (10%)</td>
<td>7.65 SINS (90%)</td>
</tr>
<tr>
<th scope="row">367201-388800</th>
<th scope="row">9 SINS</th>
<td>0.90 SINS (10%)</td>
<td>8.10 SINS (90%)</td>
</tr>
<tr>
<th scope="row">388801-525600</th>
<th scope="row">5 SINS</th>
<td>1 SINS (20%)</td>
<td>4 SINS (80%)</td>
</tr>
<tr>
<tr>
<th scope="row">525601-1,051,200</th>
<th scope="row">4 SINS</th>
<td>0.8 SINS (20%)</td>
<td>3.2 SINS (80%)</td>
</tr>
<tr>						
<th scope="row" colspan=4>After 2 years, each year, the reward will be reduced with 10%</th>
</tr>
</tbody>
</table>
