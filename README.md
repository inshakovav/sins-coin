SafeInsure Core integration/staging repository
=====================================

 https://nexus.ahml.ru/

\\roscap.com\ctx\UserDrive1\vv.sukhanov.ROSCAP\Documents\tools\grpcurl.exe -plaintext cbscbsbrokerage-grpc.cbs.uat.domrfbank.ru:80 list
------
Maven:
1. IDEA
File | Settings | Build, Execution, Deployment | Build Tools | Maven | Archetype Catalogs

Add catalogs:
Type: Remote
https://nexus.ahml.ru/repository
https://nexus.ahml.ru
https://nexus.ahml.ru/repository/maven-public/

copy from project: potfolio/.m2/setting.xml  to ~/.m2/

lens:
eyJhY2Nlc3NfdG9rZW4iOiJleUpoYkdjaU9pSlNVekkxTmlJc0luUjVjQ0lnT2lBaVNsZFVJaXdpYTJsa0lpQTZJQ0pPWWtGVE1rbHBWM1p4V1RoemFIbDVWMWxxVkhJeVMxaEpkMVV5VVY5WFRsSlZUV1ZEV0RjMU9EQjNJbjAuZXlKbGVIQWlPakUyTnprME9EazJOVFFzSW1saGRDSTZNVFkzT1RRMk1EZzFOQ3dpWVhWMGFGOTBhVzFsSWpveE5qYzVORFl3T0RRNUxDSnFkR2tpT2lJeVpqQTVNRGt5TlMxak4yUXlMVFJoTVRndFltWTFZeTAzTVRnME5qVTVaalppTlRFaUxDSnBjM01pT2lKb2RIUndjem92TDJGd2NDNXJPSE5zWlc1ekxtUmxkaTloZFhSb0wzSmxZV3h0Y3k5c1pXNXpRMnh2ZFdRaUxDSmhkV1FpT2lKaFkyTnZkVzUwSWl3aWMzVmlJam9pT0RVeE56ZzJZVFV0WVRKaU5TMDBObVEyTFRnME5tSXRaV1ZsWXpRelpqWXhaV1JqSWl3aWRIbHdJam9pUW1WaGNtVnlJaXdpWVhwd0lqb2liR1Z1Y3kxbGVIUmxibk5wYjI0aUxDSnViMjVqWlNJNklqQmpOamcyTURNekxXTmlOVEl0TkRjMVppMDVOelkxTFRWaU9HUmxZVGhrTURJNE55SXNJbk5sYzNOcGIyNWZjM1JoZEdVaU9pSmpObUUxTnpSbE1pMDVOekUyTFRSbU5tSXRZVGd5T1Mxak5EQTRNRFF5WkRFMVpUY2lMQ0poWTNJaU9pSXdJaXdpWVd4c2IzZGxaQzF2Y21sbmFXNXpJanBiSW1oMGRIQTZMeTlzYjJOaGJHaHZjM1F2SWwwc0luSmxZV3h0WDJGalkyVnpjeUk2ZXlKeWIyeGxjeUk2V3lKdlptWnNhVzVsWDJGalkyVnpjeUlzSW1SbFptRjFiSFF0Y205c1pYTXRZekU1TkRKbVpUUXRNRGhqWkMwME9XWTBMVGczWVRrdFpqRmlOek5oTTJNMFl6SmpJaXdpZFcxaFgyRjFkR2h2Y21sNllYUnBiMjRpWFgwc0luSmxjMjkxY21ObFgyRmpZMlZ6Y3lJNmV5SmhZMk52ZFc1MElqcDdJbkp2YkdWeklqcGJJbTFoYm1GblpTMWhZMk52ZFc1MElpd2liV0Z1WVdkbExXRmpZMjkxYm5RdGJHbHVhM01pTENKMmFXVjNMWEJ5YjJacGJHVWlYWDE5TENKelkyOXdaU0k2SW05d1pXNXBaQ0J2Wm1ac2FXNWxYMkZqWTJWemN5QndjbTltYVd4bElHVnRZV2xzSWl3aWJHbGpaVzV6WlY5bVpXRjBkWEpsY3lJNld5Sk1aVzV6WDBSbGMydDBiM0FpTENKQmRYUnZjR2xzYjNRaVhTd2laVzFoYVd4ZmRtVnlhV1pwWldRaU9uUnlkV1VzSW14cFkyVnVjMlZmZEhsd1pTSTZJbkJsY25OdmJtRnNJaXdpWTNKbFlYUmxaRjloZENJNklqRTJOekkwTVRBeE5ESTRPVGdpTENKd2NtVm1aWEp5WldSZmRYTmxjbTVoYldVaU9pSjRlV2xwZEc5NWIzVWlMQ0puYVhabGJsOXVZVzFsSWpvaTBKTFFzTkdCMExqUXU5QzQwTGtpTENKc2FXTmxibk5sWDJWNGNDSTZNUzQzTVRBNU9UWTROVFF6TURkRk9Td2liR2xqWlc1elpWOXBZWFFpT2pFdU5qYzVORFl3T0RVME16QTNSVGtzSW01aGJXVWlPaUxRa3RDdzBZSFF1TkM3MExqUXVTRFFuOUdEMExfUXV0QzQwTDBpTENKbWRXeHNibUZ0WlNJNkl0Q1MwTERSZ2RDNDBMdlF1TkM1SU5DZjBZUFF2OUM2MExqUXZTSXNJbVpoYldsc2VWOXVZVzFsSWpvaTBKX1JnOUNfMExyUXVOQzlJaXdpWlcxaGFXd2lPaUo0ZVdscGRHOTViM1ZBWjIxaGFXd3VZMjl0SWl3aWJHbGpaVzV6WlY5MGNtbGhiQ0k2Wm1Gc2MyVjkuYlVSVmFoRzk2NmdDRVk1Rm9aeXBCOGJjamI4VlNSZ2pwajE2bnI0T25nNVpPRU1ReHR1YlprUUJmVE9VVkJCaFhnNW5fbkM0RmlJdEEtN3NqcUNhcHlfdFk5YkJxdXJQTWlLR1FPNUZpZHgxX0I5ZjJNalZGYWVuam9fQWRhSXJwRVA1NkFQTGVWam9ZTVM1VW5pV3VLTmJoYXRjOEtkRTljQVV4a2V0c1lsazRPa1VwdkhsNWVCY2hOdHllaXJyS2lnajJHUDZzRC15OGVVMGJOUGlJVEs1ajlEbWFMRHlvcEVaWTRWWlRGUkdpUERjLS1uOWJqMTRUWVRIX2I2QjYyakZQQl9XcGptZE90UnN3LWJEYWswakdYbjViMHlzNDdHeGE5aWNSZWxBNWQzdmpBQ1JBXzhiZS10YVd0cTA0RlMwYTdDQXE4TzRxeXZOckwtNnd3IiwiaWRfdG9rZW4iOiJleUpoYkdjaU9pSlNVekkxTmlJc0luUjVjQ0lnT2lBaVNsZFVJaXdpYTJsa0lpQTZJQ0pPWWtGVE1rbHBWM1p4V1RoemFIbDVWMWxxVkhJeVMxaEpkMVV5VVY5WFRsSlZUV1ZEV0RjMU9EQjNJbjAuZXlKbGVIQWlPakUyTnprME9EazJOVFFzSW1saGRDSTZNVFkzT1RRMk1EZzFOQ3dpWVhWMGFGOTBhVzFsSWpveE5qYzVORFl3T0RRNUxDSnFkR2tpT2lJMll6QmhaV1V3WVMxaU1tWmhMVFJtTlRBdE9EUXpPUzB4TVRKallURTRNMk5sTUdVaUxDSnBjM01pT2lKb2RIUndjem92TDJGd2NDNXJPSE5zWlc1ekxtUmxkaTloZFhSb0wzSmxZV3h0Y3k5c1pXNXpRMnh2ZFdRaUxDSmhkV1FpT2lKc1pXNXpMV1Y0ZEdWdWMybHZiaUlzSW5OMVlpSTZJamcxTVRjNE5tRTFMV0V5WWpVdE5EWmtOaTA0TkRaaUxXVmxaV00wTTJZMk1XVmtZeUlzSW5SNWNDSTZJa2xFSWl3aVlYcHdJam9pYkdWdWN5MWxlSFJsYm5OcGIyNGlMQ0p1YjI1alpTSTZJakJqTmpnMk1ETXpMV05pTlRJdE5EYzFaaTA1TnpZMUxUVmlPR1JsWVRoa01ESTROeUlzSW5ObGMzTnBiMjVmYzNSaGRHVWlPaUpqTm1FMU56UmxNaTA1TnpFMkxUUm1ObUl0WVRneU9TMWpOREE0TURReVpERTFaVGNpTENKaGRGOW9ZWE5vSWpvaWVreFdaVWxrYWpWS2NHdHdaMHhwYjJReWJYWjRVU0lzSW1GamNpSTZJakFpTENKbGJXRnBiRjkyWlhKcFptbGxaQ0k2ZEhKMVpTd2libUZ0WlNJNkl0Q1MwTERSZ2RDNDBMdlF1TkM1SU5DZjBZUFF2OUM2MExqUXZTSXNJbU55WldGMFpXUmZZWFFpT2lJeE5qY3lOREV3TVRReU9EazRJaXdpY0hKbFptVnljbVZrWDNWelpYSnVZVzFsSWpvaWVIbHBhWFJ2ZVc5MUlpd2laMmwyWlc1ZmJtRnRaU0k2SXRDUzBMRFJnZEM0MEx2UXVOQzVJaXdpWm1GdGFXeDVYMjVoYldVaU9pTFFuOUdEMExfUXV0QzQwTDBpTENKbGJXRnBiQ0k2SW5oNWFXbDBiM2x2ZFVCbmJXRnBiQzVqYjIwaWZRLmV1Y0hJVzlhU2N3aUtZd1lEVzZFZXBpRmYyUGVyM0tZRllfUFJ6Y1ZJQUpmNXZQcVBxRW9EUFJpeWV1RmpFMWFWemRDam5Fb1JXUXEtYThHYUN2Zzg4QXZUdExybmtiNmxQNERROXUwd1NkaExVR29PaF9FdWZhLXpMN2hCLTRMMVVPT051QVdpaDNOMlpjSlpJMndER2Rud3hpN0JYNHo2OEdIaUJ1Q29YNWRidFNzWkVMZ2l6V2c2TU91U1U2czdidFFnSlE3TnlsdEVQd0dTWjFMVEUtd3l2QzhmVWU4aUlrbzBHc1NEd1VKR3gyaU9Cbl9mejRFV2VEcGowVlF6WDRIeWhsejF1eDdzSWRPS3hEcmdrR1hkY3ZxTm9lQnpXX29QNDZXLUxfaFZJcjROLUFhLVN1Y01hWW1ma1VEcjFKNE9zQ0JHXzlfTjREQVA4UkpXdyIsInJlZnJlc2hfdG9rZW4iOiJleUpoYkdjaU9pSklVekkxTmlJc0luUjVjQ0lnT2lBaVNsZFVJaXdpYTJsa0lpQTZJQ0kwTW1FeVpUVmpPQzA0WWpsbExUUTVZelF0WW1aaU5DMDNPR1JsWWpjMlpERmlaamNpZlEuZXlKcFlYUWlPakUyTnprME5qQTROVFFzSW1wMGFTSTZJamt3TldRM1lqSTVMVFl6TVRJdE5HVTRZUzA0TjJGakxXUTVPREExWkRRMFpXVTFOaUlzSW1semN5STZJbWgwZEhCek9pOHZZWEJ3TG1zNGMyeGxibk11WkdWMkwyRjFkR2d2Y21WaGJHMXpMMnhsYm5ORGJHOTFaQ0lzSW1GMVpDSTZJbWgwZEhCek9pOHZZWEJ3TG1zNGMyeGxibk11WkdWMkwyRjFkR2d2Y21WaGJHMXpMMnhsYm5ORGJHOTFaQ0lzSW5OMVlpSTZJamcxTVRjNE5tRTFMV0V5WWpVdE5EWmtOaTA0TkRaaUxXVmxaV00wTTJZMk1XVmtZeUlzSW5SNWNDSTZJazltWm14cGJtVWlMQ0poZW5BaU9pSnNaVzV6TFdWNGRHVnVjMmx2YmlJc0ltNXZibU5sSWpvaU1HTTJPRFl3TXpNdFkySTFNaTAwTnpWbUxUazNOalV0TldJNFpHVmhPR1F3TWpnM0lpd2ljMlZ6YzJsdmJsOXpkR0YwWlNJNkltTTJZVFUzTkdVeUxUazNNVFl0TkdZMllpMWhPREk1TFdNME1EZ3dOREprTVRWbE55SXNJbk5qYjNCbElqb2liM0JsYm1sa0lHOW1abXhwYm1WZllXTmpaWE56SUhCeWIyWnBiR1VnWlcxaGFXd2lmUS4tMk03R1F2MGRhSmFZN0lXcjg4b3h1TVpxSjRIcHIwSnQ4X2VwNVBMWnJ3In0=
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
