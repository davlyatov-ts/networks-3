1.Подключитесь к публичному маршрутизатору в интернет. Найдите маршрут к вашему публичному IP<br>
```
telnet route-views.routeviews.org
Username: rviews
show ip route x.x.x.x/32
show bgp x.x.x.x/32
```
-	Ответ
![show ip route](https://github.com/davlyatov-ts/networks-3/blob/master/bgp-internal.png)<br>
[show ip bgp](https://github.com/davlyatov-ts/networks-3/blob/master/sho%20ip%20bgp)<br>
___
2.Создайте dummy0 интерфейс в Ubuntu. Добавьте несколько статических маршрутов. Проверьте таблицу маршрутизации.<br>

-	Ответ
![dummy interface](https://github.com/davlyatov-ts/networks-3/blob/master/dummy.png)<br>
![routel](https://github.com/davlyatov-ts/networks-3/blob/master/routerl.png)<br>
___
3. Проверьте открытые TCP порты в Ubuntu, какие протоколы и приложения используют эти порты? Приведите несколько примеров.<br>

-	Ответ

![TCP](https://github.com/davlyatov-ts/networks-3/blob/master/tcp1.png)<br>
___
4. Проверьте используемые UDP сокеты в Ubuntu, какие протоколы и приложения используют эти порты?<br>

-	Ответ

![UDP](https://github.com/davlyatov-ts/networks-3/blob/master/udp.png)
___
5. Используя diagrams.net, создайте L3 диаграмму вашей домашней сети или любой другой сети, с которой вы работали.

-	ответ

![Scheme](https://github.com/davlyatov-ts/networks-3/blob/master/cv.png)
__
