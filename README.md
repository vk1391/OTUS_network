# Проектирование сети
![alt-dtp](https://github.com/vk1391/OTUS_network/blob/main/11.jpg "Схема к домашнему заданию №4")
 ## Выделенные адреса в г.Москва:
**Город** | **AS№** | **Устройство** | **Интерфейс** | **ip address** | **Маска подсети**
 --- | --- | --- | --- | --- | -- 
 Москва | 1001 | VPC1 | eth0 | 172.16.0.2 | 255.255.255.252
 Москва | 1001 | VPC2 | eth0 | 172.16.0.6 | 255.255.255.252
 Москва | 1001 | R12 | e0/0 | 172.16.0.1 | 255.255.255.252
 Москва | 1001 | R12 | e0/2 | 172.16.1.1 | 255.255.255.252
 Москва | 1001 | R12 | e0/3 | 172.16.1.5 | 255.255.255.252
 Москва | 1001 | R13 | e0/0 | 172.16.0.5 | 255.255.255.252
 Москва | 1001 | R13 | e0/2 | 172.16.1.13 | 255.255.255.252
 Москва | 1001 | R13 | e0/3 | 172.16.1.10 | 255.255.255.252
 Москва | 1001 | R14 | e0/0 | 172.16.1.2 | 255.255.255.252
 Москва | 1001 | R14 | e0/1 | 172.16.1.9 | 255.255.255.252
 Москва | 1001 | R14 | e0/2 | 10.110.111.1 | 255.255.255.252
 Москва | 1001 | R14 | e0/3 | 172.16.1.17 | 255.255.255.252
 Москва | 1001 | R15 | e0/0 | 172.16.1.14 | 255.255.255.252
 Москва | 1001 | R15 | e0/1 | 172.16.1.6 | 255.255.255.252
 Москва | 1001 | R15 | e0/2 | 10.110.111.5 | 255.255.255.252
 Москва | 1001 | R15 | e0/3 | 172.16.1.21 | 255.255.255.252
 Москва | 1001 | R19 | e0/0 | 172.16.1.18 | 255.255.255.252
 Москва | 1001 | R20 | e0/0 | 172.16.1.22 | 255.255.255.252
 Москва | 1001 | R14 | e1/0 | 172.16.1.25 | 255.255.255.252
 Москва | 1001 | R15 | e1/0 | 172.16.1.26 | 255.255.255.252

 ## Выделенные адреса в г.Санкт-Петербург:
 **Город** | **AS№** | **Устройство** | **Интерфейс** | **ip address** | **Маска подсети**
 --- | --- | --- | --- | --- | -- 
 Санкт-Петербург | 2042 | VPC8 | eth0 | 172.20.0.2 | 255.255.255.252
 Санкт-Петербург | 2042 | VPC | eth0 | 172.20.0.6 | 255.255.255.252
 Санкт-Петербург | 2042 | R17 | e0/0 | 172.20.0.1 | 255.255.255.252
 Санкт-Петербург | 2042 | R17 | e0/1 | 172.20.1.6 | 255.255.255.252
 Санкт-Петербург | 2042 | R16 | e0/0 | 172.20.0.5 | 255.255.255.252
 Санкт-Петербург | 2042 | R16 | e0/1 | 172.20.1.2 | 255.255.255.252
 Санкт-Петербург | 2042 | R16 | e0/3 | 172.20.1.9 | 255.255.255.252
 Санкт-Петербург | 2042 | R18 | e0/0 | 172.20.1.1 | 255.255.255.252
 Санкт-Петербург | 2042 | R18 | e0/1 | 172.20.1.5 | 255.255.255.252
 Санкт-Петербург | 2042 | R18 | e0/2 | 10.100.110.1 | 255.255.255.252
 Санкт-Петербург | 2042 | R18 | e0/3 | 10.100.110.5 | 255.255.255.252
 Санкт-Петербург | 2042 | R32 | e0/0 | 172.20.1.10 | 255.255.255.252
 
 ## Выделенные адреса в г.Чокурдах:
 **Город** | **AS№** | **Устройство** | **Интерфейс** | **ip address** | **Маска подсети**
 --- | --- | --- | --- | --- | -- 
 Чокурдах | - | VPC30 | eth0 | 172.31.0.2 | 255.255.255.248
 Чокурдах | - | VPC | eth0 | 172.31.0.3 | 255.255.255.248
 Чокурдах | - | R28 | e0/0 | 172.31.132.1 | 255.255.255.252
 Чокурдах | - | R28 | e0/1 | 172.31.132.5 | 255.255.255.252
 Чокурдах | - | R28 | e0/2 | 172.31.0.1 | 255.255.255.248
 
 ## Выделенные адреса в г.Лабытнанги:
 **Город** | **AS№** | **Устройство** | **Интерфейс** | **ip address** | **Маска подсети**
 --- | --- | --- | --- | --- | --- 
 Лабытнанги | - | R27 | e0/0 | 10.111.112.2 | 255.255.255.252

 ## Выделенные адреса Триада:
 **Город** | **AS№** | **Устройство** | **Интерфейс** | **ip address** | **Маска подсети**
 --- | --- | --- | --- | --- | --- 
 Триада | 520 | R23 | e0/0 | 101.10.1.6 | 255.255.255.252 
 Триада | 520 | R23 | e0/1 | 11.1.110.1 | 255.255.255.252
 Триада | 520 | R23 | e0/2 | 11.1.110.5 | 255.255.255.252
 Триада | 520 | R24 | e0/0 | 172.110.0.2 | 255.255.255.252
 Триада | 520 | R24 | e0/1 | 11.1.110.9 | 255.255.255.252
 Триада | 520 | R24 | e0/2 | 11.1.110.6 | 255.255.255.252
 Триада | 520 | R24 | e0/3 | 10.100.110.2 | 255.255.255.252
 Триада | 520 | R25 | e0/0 | 11.1.110.2 | 255.255.255.252
 Триада | 520 | R25 | e0/1 | 10.111.112.1 | 255.255.255.252
 Триада | 520 | R25 | e0/2 | 11.1.110.14 | 255.255.255.252
 Триада | 520 | R25 | e0/3 | 172.31.132.6 | 255.255.255.252
 Триада | 520 | R26 | e0/0 | 11.1.110.10 | 255.255.255.252
 Триада | 520 | R26 | e0/1 | 172.31.132.2 | 255.255.255.252
 Триада | 520 | R26 | e0/2 | 11.1.110.13 | 255.255.255.252
 Триада | 520 | R26 | e0/3 | 10.100.110.6 | 255.255.255.252

 ## Выделенные адреса Ламас:
 **Город** | **AS№** | **Устройство** | **Интерфейс** | **ip address** | **Маска подсети**
 --- | --- | --- | --- | --- | --- 
 Ламас | 301 | R21 | e0/0 | 10.110.111.6 | 255.255.255.252
 Ламас | 301 | R21 | e0/1 | 101.10.1.2 | 255.255.255.252
 Ламас | 301 | R21 | e0/2 | 172.110.0.1 | 255.255.255.252

 ## Выделенные адреса Киторн:
 **Город** | **AS№** | **Устройство** | **Интерфейс** | **ip address** | **Маска подсети**
 --- | --- | --- | --- | --- | --- 
 Киторн | 101 | R22 | e0/0 | 10.110.111.2 | 255.255.255.252
 Киторн | 101 | R22 | e0/1 | 101.10.1.1 | 255.255.255.252
 Киторн | 101 | R22 | e0/2 | 101.10.1.5 | 255.255.255.252

 # Настройка политики маршрутизации в офисе Чокурдах
  - необходимо настроить:
  1. Политику маршрутизации для сетей офиса.
  2. Распределить трафик между двумя линками с провайдером.
  3. Настроить отслеживание линка через технологию IP SLA.(только для IPv4)
  4. Настроить для офиса Лабытнанги маршрут по-умолчанию.
  - Конфигурация маршрутизатора R28:
```
interface Ethernet0/0
 ip address 172.31.132.1 255.255.255.252
!
interface Ethernet0/1
 ip address 172.31.132.5 255.255.255.252
!
interface Ethernet0/2
 ip address 172.31.0.1 255.255.255.248
 ip policy route-map TEST
!
interface Ethernet0/3
 no ip address
 shutdown
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown
!         
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
ip route 0.0.0.0 0.0.0.0 172.31.132.2 10
ip route 0.0.0.0 0.0.0.0 172.31.132.6 10
!
ip access-list standard ACL1
 permit 172.31.0.3
ip access-list standard ACL2
 permit 172.31.0.2
!
ip sla 1
 icmp-echo 172.31.132.2 source-ip 172.31.132.1
 frequency 10
ip sla schedule 1 life forever start-time now
ip sla 2
 icmp-echo 172.31.132.6 source-ip 172.31.132.5
 frequency 11
ip sla schedule 2 life forever start-time now
!
route-map TEST permit 10
 match ip address ACL1
 set ip next-hop 172.31.132.6
!
route-map TEST permit 20
 match ip address ACL2
 set ip next-hop 172.31.132.2
!
route-map TEST deny 30
```
- Конфигурация маршрутизатора R27:
```
interface Ethernet0/0
 ip address 10.111.112.2 255.255.255.252
!
interface Ethernet0/1
 no ip address
 shutdown
!         
interface Ethernet0/2
 no ip address
 shutdown
!
interface Ethernet0/3
 no ip address
 shutdown
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown 
!
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
ip route 0.0.0.0 0.0.0.0 10.111.112.1 name default
```
- Результат:
1. VPC30:
```
VPCS> sh ip

NAME        : VPCS[1]
IP/MASK     : 172.31.0.2/30
GATEWAY     : 172.31.0.1
DNS         : 
MAC         : 00:50:79:66:68:1e
LPORT       : 20000
RHOST:PORT  : 127.0.0.1:30000
MTU         : 1500

VPCS> trace 10.111.112.2
trace to 10.111.112.2, 8 hops max, press Ctrl+C to stop
 1   172.31.0.1   2.373 ms  1.776 ms  1.486 ms
 2   172.31.132.2   20.109 ms  3.058 ms  4.091 ms
 3   11.1.110.14   8.481 ms  3.485 ms  4.360 ms
 4   *10.111.112.2   4.331 ms
```
2. VPC31:
```
VPCS> sh ip

NAME        : VPCS[1]
IP/MASK     : 172.31.0.3/29
GATEWAY     : 172.31.0.1
DNS         : 
MAC         : 00:50:79:66:68:06
LPORT       : 20000
RHOST:PORT  : 127.0.0.1:30000
MTU         : 1500

VPCS> trace 10.111.112.2
trace to 10.111.112.2, 8 hops max, press Ctrl+C to stop
 1   172.31.0.1   1.102 ms  1.145 ms  1.606 ms
 2   172.31.132.6   3.060 ms  3.625 ms  3.083 ms
 3   *10.111.112.2   5.945 ms
```
3. Результат IP SLA на R28:
```
Router#show ip sla statistics 
IPSLAs Latest Operation Statistics

IPSLA operation id: 1
Latest RTT: 1 milliseconds
Latest operation start time: 10:08:10 UTC Tue Jul 9 2024
Latest operation return code: OK
Number of successes: 74
Number of failures: 1
Operation time to live: Forever

IPSLA operation id: 2
Latest RTT: 2 milliseconds
Latest operation start time: 10:08:11 UTC Tue Jul 9 2024
Latest operation return code: OK
Number of successes: 46
Number of failures: 0
Operation time to live: Forever
```
# Настройка маршрутизации в офисе г.Москва
- Необходимо выполнить следующие условия:
1. Маршрутизаторы R14-R15 находятся в зоне 0 - backbone.
2. Маршрутизаторы R12-R13 находятся в зоне 10. Дополнительно к маршрутам должны получать маршрут по умолчанию.
3. Маршрутизатор R19 находится в зоне 101 и получает только маршрут по умолчанию.
4. Маршрутизатор R20 находится в зоне 102 и получает все маршруты, кроме маршрутов до сетей зоны 101

![alt-dtp](https://github.com/vk1391/OTUS_network/blob/main/ospf.jpg)

- конфигурация R14
```
interface Loopback0
 ip address 14.14.14.14 255.255.255.255
!
interface Ethernet0/0
 ip address 172.16.1.2 255.255.255.252
!
interface Ethernet0/1
 ip address 172.16.1.9 255.255.255.252
!
interface Ethernet0/2
 ip address 10.110.111.1 255.255.255.252
!
interface Ethernet0/3
 ip address 172.16.1.17 255.255.255.252
!
interface Ethernet1/0
 ip address 172.16.1.25 255.255.255.252
!
interface Ethernet1/1
 no ip address
 shutdown
!
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown
!
router ospf 1
 router-id 14.14.14.14
 area 101 stub no-summary
 network 14.14.14.14 0.0.0.0 area 0
 network 172.16.1.0 0.0.0.3 area 10
 network 172.16.1.8 0.0.0.3 area 10
 network 172.16.1.16 0.0.0.3 area 101
 network 172.16.1.24 0.0.0.3 area 0
```
- Конфигурация R15:
```
interface Loopback0
 ip address 15.15.15.15 255.255.255.255
!
interface Ethernet0/0
 ip address 172.16.1.14 255.255.255.252
!
interface Ethernet0/1
 ip address 172.16.1.6 255.255.255.252
!
interface Ethernet0/2
 ip address 10.110.111.5 255.255.255.252
!
interface Ethernet0/3
 ip address 172.16.1.21 255.255.255.252
!
interface Ethernet1/0
 ip address 172.16.1.26 255.255.255.252
!
interface Ethernet1/1
 no ip address
 shutdown
!
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown
!
router ospf 1
 router-id 15.15.15.15
 area 0 filter-list prefix filter-area102 out
 network 15.15.15.15 0.0.0.0 area 0
 network 172.16.1.4 0.0.0.3 area 10
 network 172.16.1.12 0.0.0.3 area 10
 network 172.16.1.20 0.0.0.3 area 102
 network 172.16.1.24 0.0.0.3 area 0
 default-information originate
!
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
ip route 0.0.0.0 0.0.0.0 10.110.111.6
!
!
ip prefix-list filter-area102 seq 5 deny 172.16.1.16/30
```
- Конфигурация R12:
```
interface Loopback0
 ip address 12.12.12.12 255.255.255.255
!
interface Ethernet0/0
 ip address 172.16.0.1 255.255.255.252
!
interface Ethernet0/1
 no ip address
 shutdown
!
interface Ethernet0/2
 ip address 172.16.1.1 255.255.255.252
!
interface Ethernet0/3
 ip address 172.16.1.5 255.255.255.252
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!
interface Ethernet1/2
 no ip address
 shutdown
!         
interface Ethernet1/3
 no ip address
 shutdown
!
router ospf 1
 router-id 12.12.12.12
 network 12.12.12.12 0.0.0.0 area 10
 network 172.16.0.0 0.0.0.3 area 10
 network 172.16.1.0 0.0.0.3 area 10
 network 172.16.1.4 0.0.0.3 area 10
```
- Конфигурация R13:
```
interface Loopback0
 ip address 13.13.13.13 255.255.255.255
!
interface Ethernet0/0
 ip address 172.16.0.5 255.255.255.252
!
interface Ethernet0/1
 no ip address
 shutdown
!
interface Ethernet0/2
 ip address 172.16.1.13 255.255.255.252
!
interface Ethernet0/3
 ip address 172.16.1.10 255.255.255.252
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!
interface Ethernet1/2
 no ip address
 shutdown
!         
interface Ethernet1/3
 no ip address
 shutdown
!
router ospf 1
 router-id 13.13.13.13
 network 13.13.13.13 0.0.0.0 area 10
 network 172.16.0.4 0.0.0.3 area 10
 network 172.16.1.8 0.0.0.3 area 10
 network 172.16.1.12 0.0.0.3 area 10
```
- Конфигурация R19:
```
interface Loopback0
 ip address 19.19.19.19 255.255.255.255
!
interface Ethernet0/0
 ip address 172.16.1.18 255.255.255.252
!
interface Ethernet0/1
 ip address 10.0.0.1 255.255.255.252
!
interface Ethernet0/2
 no ip address
 shutdown
!
interface Ethernet0/3
 no ip address
 shutdown
!
router ospf 1
 router-id 19.19.19.19
 area 101 stub no-summary
 network 19.19.19.19 0.0.0.0 area 101
 network 172.16.1.16 0.0.0.3 area 101
```
- Таблица маршрутизации R19:
 ```
O*IA  0.0.0.0/0 [110/11] via 172.16.1.17, 01:09:58, Ethernet0/0
      19.0.0.0/32 is subnetted, 1 subnets
C        19.19.19.19 is directly connected, Loopback0
      172.16.0.0/16 is variably subnetted, 2 subnets, 2 masks
C        172.16.1.16/30 is directly connected, Ethernet0/0
L        172.16.1.18/32 is directly connected, Ethernet0/0
```
В таблице маршрутизации присутствует только маршрут по умолчанию,соответственно условие задачи выполнено
- Конфигурация R20:
```
interface Loopback0
 ip address 20.20.20.20 255.255.255.255
!
interface Ethernet0/0
 ip address 172.16.1.22 255.255.255.252
!
interface Ethernet0/1
 no ip address
 shutdown
!
interface Ethernet0/2
 no ip address
 shutdown
!
interface Ethernet0/3
 no ip address
 shutdown
!
router ospf 1
 router-id 20.20.20.20
 network 20.20.20.20 0.0.0.0 area 102
 network 172.16.1.20 0.0.0.3 area 102
```
- база данных ospf маршрутизатора R20:
```
Summary Net Link States (Area 102)

Link ID         ADV Router      Age         Seq#       Checksum
12.12.12.12     15.15.15.15     1817        0x80000002 0x0008BC
13.13.13.13     15.15.15.15     1817        0x80000002 0x00D9E6
172.16.0.0      15.15.15.15     1817        0x80000002 0x00F43D
172.16.0.4      15.15.15.15     1817        0x80000002 0x00CC61
172.16.1.0      15.15.15.15     1817        0x80000002 0x00E947
172.16.1.4      15.15.15.15     1817        0x80000002 0x005DD9
172.16.1.8      15.15.15.15     1817        0x80000002 0x00998F
172.16.1.12     15.15.15.15     1817        0x80000002 0x000D22
```
- таблица маршрутизации R20:
```
Router#sh ip route
Codes: L - local, C - connected, S - static, R - RIP, M - mobile, B - BGP
       D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area 
       N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2
       E1 - OSPF external type 1, E2 - OSPF external type 2
       i - IS-IS, su - IS-IS summary, L1 - IS-IS level-1, L2 - IS-IS level-2
       ia - IS-IS inter area, * - candidate default, U - per-user static route
       o - ODR, P - periodic downloaded static route, H - NHRP, l - LISP
       a - application route
       + - replicated route, % - next hop override

Gateway of last resort is 172.16.1.21 to network 0.0.0.0

O*E2  0.0.0.0/0 [110/1] via 172.16.1.21, 01:13:04, Ethernet0/0
      12.0.0.0/32 is subnetted, 1 subnets
O IA     12.12.12.12 [110/21] via 172.16.1.21, 01:04:41, Ethernet0/0
      13.0.0.0/32 is subnetted, 1 subnets
O IA     13.13.13.13 [110/21] via 172.16.1.21, 01:04:42, Ethernet0/0
      20.0.0.0/32 is subnetted, 1 subnets
C        20.20.20.20 is directly connected, Loopback0
      172.16.0.0/16 is variably subnetted, 8 subnets, 2 masks
O IA     172.16.0.0/30 [110/30] via 172.16.1.21, 01:04:41, Ethernet0/0
O IA     172.16.0.4/30 [110/30] via 172.16.1.21, 01:04:41, Ethernet0/0
O IA     172.16.1.0/30 [110/30] via 172.16.1.21, 01:04:41, Ethernet0/0
O IA     172.16.1.4/30 [110/20] via 172.16.1.21, 01:04:41, Ethernet0/0
O IA     172.16.1.8/30 [110/30] via 172.16.1.21, 01:04:41, Ethernet0/0
O IA     172.16.1.12/30 [110/20] via 172.16.1.21, 01:04:41, Ethernet0/0
C        172.16.1.20/30 is directly connected, Ethernet0/0
L        172.16.1.22/32 is directly connected, Ethernet0/0
```
Как видим, сеть 172.16.1.16/30 отсутствует, соответсвенно условие поставленной задачи выполнено.

# Настройка маршрутизации в офисе Триада
- Необходимо выполнить следующие условия:
1. Настроите IS-IS в ISP Триада.
2. R23 и R25 находятся в зоне 2222.
3. R24 находится в зоне 24.
4. R26 находится в зоне 26.

![alt-dtp](https://github.com/vk1391/OTUS_network/blob/main/isis.jpg)

Конфигурация R23:
```
interface Loopback0
 ip address 23.23.23.23 255.255.255.255
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/0
 ip address 101.10.1.6 255.255.255.252
 ip router isis 1
 isis circuit-type level-1
!         
interface Ethernet0/1
 ip address 11.1.110.1 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/2
 ip address 11.1.110.5 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/3
 no ip address
 shutdown
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown
!
router isis 1
 net 49.2222.0000.0000.0000.0023.00
```

- таблица соседства isis R23:
```
Tag 1:
System Id      Type Interface   IP Address      State Holdtime Circuit Id
Router         L2   Et0/2       11.1.110.6      UP    8        Router.03          
Router         L2   Et0/1       11.1.110.2      UP    8        Router.01  
```
- Конфигурация R24:
```
interface Loopback0
 ip address 224.24.24.24 255.255.255.255
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/0
 ip address 172.110.0.2 255.255.255.252
 ip router isis 1
 isis circuit-type level-1
!         
interface Ethernet0/1
 ip address 11.1.110.9 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/2
 ip address 11.1.110.6 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/3
 ip address 10.100.110.2 255.255.255.252
 ip router isis 1
 isis circuit-type level-1
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!         
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown
!
router isis 1
 net 49.0024.0000.0000.0000.0024.00
```
- таблица соседства isis R24:
```
Tag 1:
System Id      Type Interface   IP Address      State Holdtime Circuit Id
Router         L2   Et0/2       11.1.110.5      UP    25       Router.03          
Router         L2   Et0/1       11.1.110.10     UP    9        Router.01
```
- Конфигурация R25:
```
interface Loopback0
 ip address 25.25.25.25 255.255.255.255
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/0
 ip address 11.1.110.2 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!         
interface Ethernet0/1
 ip address 10.111.112.1 255.255.255.252
 ip router isis 1
 isis circuit-type level-1
!
interface Ethernet0/2
 ip address 11.1.110.14 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/3
 ip address 172.31.132.6 255.255.255.252
 ip router isis 1
 isis circuit-type level-1
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!         
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown
!
router isis 1
 net 49.2222.0000.0000.0000.0025.00
!
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
ip route 172.31.0.0 255.255.255.248 172.31.132.5
```
- таблица соседства isis R25:
```
Tag 1:
System Id      Type Interface   IP Address      State Holdtime Circuit Id
Router         L2   Et0/0       11.1.110.1      UP    29       Router.01          
Router         L2   Et0/2       11.1.110.13     UP    6        Router.03
```
- Конфигурация R26:
```
interface Loopback0
 ip address 26.26.26.26 255.255.255.255
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/0
 ip address 11.1.110.10 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!         
interface Ethernet0/1
 ip address 172.31.132.2 255.255.255.252
 ip router isis 1
 isis circuit-type level-1
!
interface Ethernet0/2
 ip address 11.1.110.13 255.255.255.252
 ip router isis 1
 isis circuit-type level-2-only
!
interface Ethernet0/3
 ip address 10.100.110.6 255.255.255.252
 ip router isis 1
 isis circuit-type level-1
!
interface Ethernet1/0
 no ip address
 shutdown
!
interface Ethernet1/1
 no ip address
 shutdown
!         
interface Ethernet1/2
 no ip address
 shutdown
!
interface Ethernet1/3
 no ip address
 shutdown
!
router isis 1
 net 49.0026.0000.0000.0000.0026.00
!
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
ip route 172.31.0.0 255.255.255.248 172.31.132.1
```
- таблица соседства isis R26:
```
Tag 1:
System Id      Type Interface   IP Address      State Holdtime Circuit Id
Router         L2   Et0/0       11.1.110.9      UP    28       Router.01          
Router         L2   Et0/2       11.1.110.14     UP    25       Router.03
```

# Настройка маршрутизации в офисе Санкт-Петербург
- Необходимо выполнить следующие условия:
1. В офисе С.-Петербург настроить EIGRP.
2. R32 получает только маршрут по умолчанию.
3. R16-17 анонсируют только суммарные префиксы.
4. Использовать EIGRP named-mode для настройки сети.
5. Настройка осуществляется одновременно для IPv4 и IPv6.

![alt-dtp](https://github.com/vk1391/OTUS_network/blob/main/eigrp.jpg)

- Конфигурация R16:
```
interface Loopback0
 ip address 16.16.16.16 255.255.255.255
!
interface Ethernet0/0
 ip address 172.20.0.5 255.255.255.252
!
interface Ethernet0/1
 ip address 172.20.1.2 255.255.255.252
 ipv6 address FE80::16 link-local
!
interface Ethernet0/2
 no ip address
!
interface Ethernet0/3
 ip address 172.20.1.9 255.255.255.252
 ipv6 address FE80::16 link-local
!
!
router eigrp SPB
 !
 address-family ipv4 unicast autonomous-system 1
  !
  af-interface Ethernet0/1
   summary-address 172.20.0.0 255.255.254.0
   authentication key-chain SPB
  exit-af-interface
  !       
  af-interface Ethernet0/3
   authentication key-chain SPB
  exit-af-interface
  !
  topology base
   distribute-list prefix DefR out Ethernet0/3
  exit-af-topology
  network 172.20.0.0
  eigrp router-id 16.16.16.16
 exit-address-family
 !
 address-family ipv6 unicast autonomous-system 1
  !
  topology base
  exit-af-topology
  eigrp router-id 16.16.16.16
 exit-address-family
!
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
!
!
ip prefix-list DefR seq 10 permit 0.0.0.0/0
```
- таблица сосдства eigrp R16:
```
Router#sh ip eigrp neighbors 
EIGRP-IPv4 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
1   172.20.1.10             Et0/3                    14 01:08:59   11   100  0  5
0   172.20.1.1              Et0/1                    11 01:14:40 1284  5000  0  7

Router#sh ipv6 eigrp neighbors 
EIGRP-IPv6 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
1   Link-local address:     Et0/3                    10 00:12:31    6   100  0  1
    FE80::32
0   Link-local address:     Et0/1                    12 00:14:21   11   100  0  1
    FE80::18
```
- Конфигурация R17:
```
interface Loopback0
 ip address 17.17.17.17 255.255.255.255
!
interface Ethernet0/0
 ip address 172.20.0.1 255.255.255.252
!
interface Ethernet0/1
 ip address 172.20.1.6 255.255.255.252
 ipv6 address FE80::17 link-local
!
interface Ethernet0/2
 no ip address
 shutdown
!
interface Ethernet0/3
 no ip address
 shutdown
!
!
router eigrp SPB
 !
 address-family ipv4 unicast autonomous-system 1
  !
  af-interface Ethernet0/1
   summary-address 172.20.0.0 255.255.254.0
   authentication key-chain SPB
  exit-af-interface
  !
  af-interface Ethernet0/0
   summary-address 172.20.0.0 255.255.254.0
  exit-af-interface
  !
  network 172.20.0.0
  network 172.20.0.0 0.0.0.3
  eigrp router-id 17.17.17.17
 exit-address-family
 !
 address-family ipv6 unicast autonomous-system 1
  !
  topology base
  exit-af-topology
  eigrp router-id 17.17.17.17
 exit-address-family
!
ip forward-protocol nd
```
- таблица сосдства eigrp R17:
```
EIGRP-IPv4 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
0   172.20.1.5              Et0/1                    14 01:01:02    6   100  0  14
Router#sh ipv6 eigrp neighbors 
EIGRP-IPv6 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
0   Link-local address:     Et0/1                    10 01:25:21    1  3000  0  2
    FE80::18
```
- Конфигурация R18:
```
interface Loopback0
 ip address 18.18.18.18 255.255.255.255
!
interface Ethernet0/0
 ip address 172.20.1.1 255.255.255.252
 ipv6 address FE80::18 link-local
!
interface Ethernet0/1
 ip address 172.20.1.5 255.255.255.252
 ipv6 address FE80::18 link-local
!
interface Ethernet0/2
 ip address 10.100.110.1 255.255.255.252
!
interface Ethernet0/3
 ip address 10.100.110.5 255.255.255.252
!
!
router eigrp SPB
 !
 address-family ipv4 unicast autonomous-system 1
  !
  af-interface Ethernet0/0
   summary-address 172.20.0.0 255.255.254.0
   authentication key-chain SPB
  exit-af-interface
  !       
  af-interface Ethernet0/1
   summary-address 172.20.0.0 255.255.254.0
   authentication key-chain SPB
  exit-af-interface
  !
  topology base
   redistribute static
  exit-af-topology
  network 172.20.0.0
  eigrp router-id 18.18.18.18
 exit-address-family
 !
 address-family ipv6 unicast autonomous-system 1
  !
  topology base
  exit-af-topology
  eigrp router-id 18.18.18.18
 exit-address-family
!
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
ip route 0.0.0.0 0.0.0.0 10.100.110.2
```


- таблица сосдства eigrp R18:
```
Router#sh ip eigrp neighbors 
EIGRP-IPv4 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
1   172.20.1.6              Et0/1                    14 01:04:43   12   100  0  8
0   172.20.1.2              Et0/0                    10 02:29:02    5   100  0  19
Router#sh ipv6 eig
Router#sh ipv6 eigrp ne
Router#sh ipv6 eigrp neighbors 
EIGRP-IPv6 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
1   Link-local address:     Et0/1                    13 01:27:55    1  3000  0  1
    FE80::17
0   Link-local address:     Et0/0                    10 01:28:27   11   100  0  1
    FE80::16
```
- Конфигурация R32:
```
interface Loopback0
 ip address 32.32.32.32 255.255.255.255
!
interface Ethernet0/0
 ip address 172.20.1.10 255.255.255.252
 ipv6 address FE80::32 link-local
!
interface Ethernet0/1
 no ip address
 shutdown
!
interface Ethernet0/2
 no ip address
 shutdown
!
interface Ethernet0/3
 no ip address
 shutdown
!
!
router eigrp SPB
 !
 address-family ipv4 unicast autonomous-system 1
  !
  af-interface Ethernet0/0
   authentication key-chain SPB
  exit-af-interface
  !
  topology base
  exit-af-topology
  network 172.20.0.0
  eigrp router-id 32.32.32.32
 exit-address-family
 !
 address-family ipv6 unicast autonomous-system 1
  !
  topology base
  exit-af-topology
  eigrp router-id 32.32.32.32
 exit-address-family
!
ip forward-protocol nd
!
!
no ip http server
no ip http secure-server
```
- таблица сосдства eigrp R32:
```
Router#sh ip eigrp neighbors 
EIGRP-IPv4 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
0   172.20.1.9              Et0/0                    12 02:24:55    9   100  0  15
Router#sh ipv6 eigrp neighbors 
EIGRP-IPv6 VR(SPB) Address-Family Neighbors for AS(1)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
0   Link-local address:     Et0/0                    11 01:28:12   13   100  0  2
    FE80::16
```
- таблица маршрутизации R32:
```
D*EX  0.0.0.0/0 [170/2048000] via 172.20.1.9, 02:26:09, Ethernet0/0
      32.0.0.0/32 is subnetted, 1 subnets
C        32.32.32.32 is directly connected, Loopback0
      172.20.0.0/16 is variably subnetted, 2 subnets, 2 masks
C        172.20.1.8/30 is directly connected, Ethernet0/0
L        172.20.1.10/32 is directly connected, Ethernet0/0
```
В таблице маршрутизатора R32 отсутвует маршрут кроме маршрута по умолчанию, что удовлетворяет требованиям
  
# BGP основы
- необходимо выполнить следующие условия:
  1. Настроите eBGP между офисом Москва и двумя провайдерами - Киторн и Ламас.
  2. Настроите eBGP между провайдерами Киторн и Ламас.
  3. Настроите eBGP между Ламас и Триада.
  4. Настроите eBGP между офисом С.-Петербург и провайдером Триада.
  5. Организуете IP доступность между пограничным роутерами офисами Москва и С.-Петербург

![alt-dtp](https://github.com/vk1391/OTUS_network/blob/main/BGP1.jpg)
каждый из роутеров имеет loopback address типа: R14 - 14.14.14.14/32,R15 - 15.15.15.15/32 и.т.д

- Конфигурация BGP R14(Москва):
```
Router#sh run | sec bgp
router bgp 1001
 bgp log-neighbor-changes
 network 14.14.14.14 mask 255.255.255.255
 neighbor 10.110.111.2 remote-as 101
```
- Конфигурация BGP R15(Москва):
```
Router#sh run | sec bgp
router bgp 1001
 bgp log-neighbor-changes
 network 15.15.15.15 mask 255.255.255.255
 neighbor 10.110.111.6 remote-as 301
```
- Конфигурация BGP R21(Ламас):
```
Router#sh run | sec bgp
router bgp 301
 bgp log-neighbor-changes
 network 21.21.21.21 mask 255.255.255.255
 neighbor 10.110.111.5 remote-as 1001
 neighbor 101.10.1.1 remote-as 101
 neighbor 172.110.0.2 remote-as 520
```
- Конфигурация BGP R22(Киторн):
```
Router#sh run | sec bgp
router bgp 101
 bgp log-neighbor-changes
 network 22.22.22.22 mask 255.255.255.255
 neighbor 10.110.111.1 remote-as 1001
 neighbor 101.10.1.2 remote-as 301
```
- Конфигурация BGP R24(Триада):
```
router bgp 520
 bgp log-neighbor-changes
 network 24.24.24.24 mask 255.255.255.255
 neighbor 10.100.110.1 remote-as 2042
 neighbor 172.110.0.1 remote-as 301
```
- Конфигурация BGP R18(СПБ):
```
router bgp 2042
 bgp log-neighbor-changes
 network 18.18.18.18 mask 255.255.255.255
 neighbor 10.100.110.2 remote-as 520
```
- таблица маршрутизации R18:
```
Router#sh ip route
Codes: L - local, C - connected, S - static, R - RIP, M - mobile, B - BGP
       D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area 
       N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2
       E1 - OSPF external type 1, E2 - OSPF external type 2
       i - IS-IS, su - IS-IS summary, L1 - IS-IS level-1, L2 - IS-IS level-2
       ia - IS-IS inter area, * - candidate default, U - per-user static route
       o - ODR, P - periodic downloaded static route, H - NHRP, l - LISP
       a - application route
       + - replicated route, % - next hop override

Gateway of last resort is 10.100.110.2 to network 0.0.0.0

S*    0.0.0.0/0 [1/0] via 10.100.110.2
      10.0.0.0/8 is variably subnetted, 6 subnets, 2 masks
C        10.100.110.0/30 is directly connected, Ethernet0/2
L        10.100.110.1/32 is directly connected, Ethernet0/2
C        10.100.110.4/30 is directly connected, Ethernet0/3
L        10.100.110.5/32 is directly connected, Ethernet0/3
B        10.110.111.0/30 [20/0] via 10.100.110.2, 00:25:39
B        10.110.111.4/30 [20/0] via 10.100.110.2, 00:26:10
      11.0.0.0/30 is subnetted, 2 subnets
B        11.1.110.4 [20/0] via 10.100.110.2, 00:24:19
B        11.1.110.8 [20/0] via 10.100.110.2, 00:24:19
      14.0.0.0/32 is subnetted, 1 subnets
B        14.14.14.14 [20/0] via 10.100.110.2, 00:39:28
      15.0.0.0/32 is subnetted, 1 subnets
B        15.15.15.15 [20/0] via 10.100.110.2, 00:39:28
      18.0.0.0/32 is subnetted, 1 subnets
C        18.18.18.18 is directly connected, Loopback0
      21.0.0.0/32 is subnetted, 1 subnets
B        21.21.21.21 [20/0] via 10.100.110.2, 00:39:28
      22.0.0.0/32 is subnetted, 1 subnets
B        22.22.22.22 [20/0] via 10.100.110.2, 00:39:28
      24.0.0.0/32 is subnetted, 1 subnets
B        24.24.24.24 [20/0] via 10.100.110.2, 00:39:28
      101.0.0.0/30 is subnetted, 2 subnets
B        101.10.1.0 [20/0] via 10.100.110.2, 00:26:10
B        101.10.1.4 [20/0] via 10.100.110.2, 00:25:39
      172.20.0.0/16 is variably subnetted, 5 subnets, 3 masks
D        172.20.0.0/23 is a summary, 02:20:04, Null0
C        172.20.1.0/30 is directly connected, Ethernet0/0
L        172.20.1.1/32 is directly connected, Ethernet0/0
C        172.20.1.4/30 is directly connected, Ethernet0/1
L        172.20.1.5/32 is directly connected, Ethernet0/1
      172.110.0.0/30 is subnetted, 1 subnets
B        172.110.0.0 [20/0] via 10.100.110.2, 00:24:19
```
- Ping R14 с R18:
```
Router#ping 14.14.14.14 source 18.18.18.18
Type escape sequence to abort.
Sending 5, 100-byte ICMP Echos to 14.14.14.14, timeout is 2 seconds:
Packet sent with a source address of 18.18.18.18
!!!!!
Success rate is 100 percent (5/5), round-trip min/avg/max = 2/4/8 ms
```
- таблица маршрутизации R14:
```
Router#sh ip route
Codes: L - local, C - connected, S - static, R - RIP, M - mobile, B - BGP
       D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area 
       N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2
       E1 - OSPF external type 1, E2 - OSPF external type 2
       i - IS-IS, su - IS-IS summary, L1 - IS-IS level-1, L2 - IS-IS level-2
       ia - IS-IS inter area, * - candidate default, U - per-user static route
       o - ODR, P - periodic downloaded static route, H - NHRP, l - LISP
       a - application route
       + - replicated route, % - next hop override

Gateway of last resort is not set

      10.0.0.0/8 is variably subnetted, 4 subnets, 2 masks
B        10.100.110.0/30 [20/0] via 10.110.111.2, 00:25:47
C        10.110.111.0/30 is directly connected, Ethernet0/2
L        10.110.111.1/32 is directly connected, Ethernet0/2
B        10.110.111.4/30 [20/0] via 10.110.111.2, 00:27:21
      11.0.0.0/30 is subnetted, 2 subnets
B        11.1.110.4 [20/0] via 10.110.111.2, 00:25:47
B        11.1.110.8 [20/0] via 10.110.111.2, 00:25:47
      14.0.0.0/32 is subnetted, 1 subnets
C        14.14.14.14 is directly connected, Loopback0
      18.0.0.0/32 is subnetted, 1 subnets
B        18.18.18.18 [20/0] via 10.110.111.2, 00:40:25
      21.0.0.0/32 is subnetted, 1 subnets
B        21.21.21.21 [20/0] via 10.110.111.2, 00:53:23
      22.0.0.0/32 is subnetted, 1 subnets
B        22.22.22.22 [20/0] via 10.110.111.2, 00:52:52
      24.0.0.0/32 is subnetted, 1 subnets
B        24.24.24.24 [20/0] via 10.110.111.2, 00:44:10
      101.0.0.0/30 is subnetted, 2 subnets
B        101.10.1.0 [20/0] via 10.110.111.2, 00:27:21
B        101.10.1.4 [20/0] via 10.110.111.2, 00:27:21
      172.16.0.0/16 is variably subnetted, 6 subnets, 2 masks
C        172.16.1.0/30 is directly connected, Ethernet0/0
L        172.16.1.2/32 is directly connected, Ethernet0/0
C        172.16.1.8/30 is directly connected, Ethernet0/1
L        172.16.1.9/32 is directly connected, Ethernet0/1
C        172.16.1.16/30 is directly connected, Ethernet0/3
L        172.16.1.17/32 is directly connected, Ethernet0/3
      172.110.0.0/30 is subnetted, 1 subnets
B        172.110.0.0 [20/0] via 10.110.111.2, 00:27:21
```
- Ping R18 c R14:
```
Router# ping 18.18.18.18 source 14.14.14.14
Type escape sequence to abort.
Sending 5, 100-byte ICMP Echos to 18.18.18.18, timeout is 2 seconds:
Packet sent with a source address of 14.14.14.14
!!!!!
Success rate is 100 percent (5/5), round-trip min/avg/max = 4/8/25 ms
```
# Масштабируемость и дизайн iBGP
 - необходимо выполнить следующие условия:
  1. Настроите iBGP в офисом Москва между маршрутизаторами R14 и R15.
  2. Настроите iBGP в провайдере Триада, с использованием RR
  3. Настройте офиса Москва так, чтобы приоритетным провайдером стал Ламас.
  4. Настройте офиса С.-Петербург так, чтобы трафик до любого офиса распределялся по двум линкам одновременно.
  5. Все сети в лабораторной работе должны иметь IP связность.

![alt-dtp](https://github.com/vk1391/OTUS_network/blob/main/BGP2.jpg)

1. Настроите iBGP в офисом Москва между маршрутизаторами R14 и R15.
- Конфигурация BGP R14:
```
Router#sh run | sec bgp
router bgp 1001
 bgp log-neighbor-changes
 network 14.14.14.14 mask 255.255.255.255
 neighbor 10.110.111.2 remote-as 101
 neighbor 10.110.111.2 route-map RM-LAMAS-OUT out
 neighbor 172.16.1.26 remote-as 1001
route-map RM-LAMAS-OUT permit 10
 set as-path prepend 1001 1001
```
- Конфигурация BGP R15:
```
router bgp 1001
 bgp log-neighbor-changes
 network 15.15.15.15 mask 255.255.255.255
 neighbor 10.110.111.6 remote-as 301
 neighbor 10.110.111.6 route-map RM-LAMAS-IN in
 neighbor 172.16.1.25 remote-as 1001
route-map RM-LAMAS-IN permit 10
 set local-preference 110
```
- таблица соседства BGP R14:
```
Router#sh ip bgp sum
BGP router identifier 14.14.14.14, local AS number 1001
BGP table version is 21, main routing table version 21
6 network entries using 840 bytes of memory
10 path entries using 800 bytes of memory
10/6 BGP path/bestpath attribute entries using 1440 bytes of memory
8 BGP AS-PATH entries using 192 bytes of memory
0 BGP route-map cache entries using 0 bytes of memory
0 BGP filter-list cache entries using 0 bytes of memory
BGP using 3272 total bytes of memory
BGP activity 8/2 prefixes, 15/5 paths, scan interval 60 secs

Neighbor        V           AS MsgRcvd MsgSent   TblVer  InQ OutQ Up/Down  State/PfxRcd
10.110.111.2    4          101    1810    1796       21    0    0 1d03h           4
172.16.1.26     4         1001    1786    1787       21    0    0 1d02h           5
```
2. Настроите iBGP в провайдере Триада, с использованием RR
В качестве Route-reflector был выбран R23
 - Конфигурация BGP R23:
 ```
Router#sh run | sec bgp
router bgp 520
 bgp log-neighbor-changes
 neighbor IBGP peer-group
 neighbor IBGP remote-as 520
 neighbor IBGP update-source Loopback0
 neighbor IBGP route-reflector-client
 neighbor IBGP next-hop-self
 neighbor 24.24.24.24 peer-group IBGP
 neighbor 25.25.25.25 peer-group IBGP
 neighbor 26.26.26.26 peer-group IBGP
 neighbor 101.10.1.5 remote-as 101
```
- Конфигурация BGP R24:
```
router bgp 520
 bgp router-id 24.24.24.24
 bgp log-neighbor-changes
 network 24.24.24.24 mask 255.255.255.255
 neighbor 10.100.110.1 remote-as 2042
 neighbor 23.23.23.23 remote-as 520
 neighbor 23.23.23.23 update-source Loopback0
 neighbor 23.23.23.23 next-hop-self
 neighbor 172.110.0.1 remote-as 301
```
- Конфигурация BGP R25:
```
Router#sh run | sec bgp
router bgp 520
 bgp log-neighbor-changes
 neighbor 23.23.23.23 remote-as 520
 neighbor 23.23.23.23 update-source Loopback0
 neighbor 23.23.23.23 next-hop-self
```
- Конфигурация BGP R26:
```
Router(config-router)#do sh run | sec bgp
router bgp 520
 bgp log-neighbor-changes
 neighbor 10.100.110.5 remote-as 2042
 neighbor 23.23.23.23 remote-as 520
 neighbor 23.23.23.23 update-source Loopback0
 neighbor 23.23.23.23 next-hop-self
```
- Таблица соседства R23:
```
Router#sh ip bgp sum
BGP router identifier 23.23.23.23, local AS number 520
BGP table version is 18, main routing table version 18
6 network entries using 840 bytes of memory
10 path entries using 800 bytes of memory
7/5 BGP path/bestpath attribute entries using 1008 bytes of memory
6 BGP AS-PATH entries using 144 bytes of memory
0 BGP route-map cache entries using 0 bytes of memory
0 BGP filter-list cache entries using 0 bytes of memory
BGP using 2792 total bytes of memory
BGP activity 6/0 prefixes, 19/9 paths, scan interval 60 secs

Neighbor        V           AS MsgRcvd MsgSent   TblVer  InQ OutQ Up/Down  State/PfxRcd
24.24.24.24     4          520     109     108       18    0    0 01:29:18        5
25.25.25.25     4          520     101     108       18    0    0 01:29:18        0
26.26.26.26     4          520     103     111       18    0    0 01:29:18        1
101.10.1.5      4          101     178     173       18    0    0 02:29:14        4
```
3.Настройте офиса Москва так, чтобы приоритетным провайдером стал Ламас.
 - На маршрутизаторах R14 и R15 были созданы route map,для R15 на входящий трафик,для R14 на исходящий трафик
 - Для R15 был увеличен local-preference в сторону Ламас
 - таблица маршрутов BGP R15:
```
Router#sh ip bgp
BGP table version is 20, local router ID is 15.15.15.15
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

     Network          Next Hop            Metric LocPrf Weight Path
 *>i 14.14.14.14/32   172.16.1.25              0    100      0 i
 *>  15.15.15.15/32   0.0.0.0                  0         32768 i
 * i 18.18.18.18/32   10.110.111.2             0    100      0 101 520 2042 i
 *>                   10.110.111.6                  110      0 301 520 2042 i
 * i 21.21.21.21/32   10.110.111.2             0    100      0 101 301 i
 *>                   10.110.111.6             0    110      0 301 i
 * i 22.22.22.22/32   10.110.111.2             0    100      0 101 i
 *>                   10.110.111.6                  110      0 301 101 i
 * i 24.24.24.24/32   10.110.111.2             0    100      0 101 520 i
 *>                   10.110.111.6                  110      0 301 520 i
```
Из таблицы видно что маршруты до сетей с наибольшим префиксом помечены как best(>) и ,соответственно, будут приорететны
- для маршрутизатора R14 был сделан prepend as-path в сторону Киторн,для того что бы искуственно увеличить кол-во хопов до заданного узла
- таблица маршрутов BGP R22:
```
Router#sh ip bgp
BGP table version is 24, local router ID is 22.22.22.22
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

     Network          Next Hop            Metric LocPrf Weight Path
 *   14.14.14.14/32   101.10.1.6                             0 520 301 1001 i
 *>                   101.10.1.2                             0 301 1001 i
 *                    10.110.111.1             0             0 1001 1001 1001 i
 *   15.15.15.15/32   101.10.1.6                             0 520 301 1001 i
 *>                   101.10.1.2                             0 301 1001 i
 *                    10.110.111.1                           0 1001 1001 1001 i
 *>  18.18.18.18/32   101.10.1.6                             0 520 2042 i
 *                    101.10.1.2                             0 301 520 2042 i
 *   21.21.21.21/32   101.10.1.6                             0 520 301 i
 *>                   101.10.1.2               0             0 301 i
 *>  22.22.22.22/32   0.0.0.0                  0         32768 i
 *>  24.24.24.24/32   101.10.1.6                             0 520 i
 *                    101.10.1.2                             0 301 520 i
```
Как видно из таблицы ,best выбирается тот путь у которого путь до конечного узла меньше
Таким образоим входящий и исходящий трафик для офиса в Москве, при условии что маршрутизаторы R14 и R15 работают, будет идти через Ламас на маршрутизатор R15

4. Настройте офиса С.-Петербург так, чтобы трафик до любого офиса распределялся по двум линкам одновременно.
Для реализации этого условия необходимо включить multipath на маршрутизаторе R18
- конфигурация BGP R18:
```
Router#sh run | sec bgp
router bgp 2042
 bgp log-neighbor-changes
 bgp bestpath as-path multipath-relax
 network 18.18.18.18 mask 255.255.255.255
 neighbor 10.100.110.2 remote-as 520
 neighbor 10.100.110.6 remote-as 520
 maximum-paths 2
```
- таблица маршрутов BGP R18:
```
Router#sh ip bgp
BGP table version is 30, local router ID is 18.18.18.18
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

     Network          Next Hop            Metric LocPrf Weight Path
 *m  14.14.14.14/32   10.100.110.6                           0 520 301 1001 i
 *>                   10.100.110.2                           0 520 301 1001 i
 *m  15.15.15.15/32   10.100.110.6                           0 520 301 1001 i
 *>                   10.100.110.2                           0 520 301 1001 i
 *>  18.18.18.18/32   0.0.0.0                  0         32768 i
 *m  21.21.21.21/32   10.100.110.6                           0 520 301 i
 *>                   10.100.110.2                           0 520 301 i
 *m  22.22.22.22/32   10.100.110.6                           0 520 101 i
 *>                   10.100.110.2                           0 520 101 i
 *m  24.24.24.24/32   10.100.110.6                           0 520 i
 *>                   10.100.110.2             0             0 520 i
```

# BGP. Фильтрация
 - необходимо выполнить следующие условия:
   1. Настроить фильтрацию в офисе Москва так, чтобы не появилось транзитного трафика(As-path).
   2. Настроить фильтрацию в офисе С.-Петербург так, чтобы не появилось транзитного трафика(Prefix-list).
   3. Настроить провайдера Киторн так, чтобы в офис Москва отдавался только маршрут по умолчанию.
   4. Настроить провайдера Ламас так, чтобы в офис Москва отдавался только маршрут по умолчанию и префикс офиса С.-Петербург.

![alt-dtp](https://github.com/vk1391/OTUS_network/blob/main/BGP2.jpg)

1.Конфигурация BGP R14:
```
Router#sh run | sec access-list
ip as-path access-list 1 permit ^$
Router#sh run | sec bgp        
router bgp 1001
 bgp log-neighbor-changes
 network 14.14.14.14 mask 255.255.255.255
 neighbor 10.110.111.2 remote-as 101
 neighbor 10.110.111.2 route-map RM-LAMAS-OUT out
 neighbor 10.110.111.2 filter-list 1 out
 neighbor 172.16.1.26 remote-as 1001
```
- Конфигурация BGP R15:
```
Router#sh run | sec access-list
ip as-path access-list 1 permit ^$
Router#sh run | sec bgp
router bgp 1001
 bgp log-neighbor-changes
 network 15.15.15.15 mask 255.255.255.255
 neighbor 10.110.111.6 remote-as 301
 neighbor 10.110.111.6 route-map RM-LAMAS-IN in
 neighbor 10.110.111.6 filter-list 1 out
 neighbor 172.16.1.25 remote-as 1001
```
- таблица bgp R21:
```
Router#sh ip bgp
BGP table version is 21, local router ID is 21.21.21.21
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

     Network          Next Hop            Metric LocPrf Weight Path
 *>  14.14.14.14/32   10.110.111.5                           0 1001 i
 *>  15.15.15.15/32   10.110.111.5             0             0 1001 i
 *   18.18.18.18/32   101.10.1.1                             0 101 520 2042 i
 *>                   172.110.0.2                            0 520 2042 i
 *>  21.21.21.21/32   0.0.0.0                  0         32768 i
 *   22.22.22.22/32   172.110.0.2                            0 520 101 i
 *>                   101.10.1.1               0             0 101 i
 *   24.24.24.24/32   101.10.1.1                             0 101 520 i
 *>                   172.110.0.2              0             0 520 i
```
- таблица bgp R22:
```
Router#sh ip bgp
BGP table version is 25, local router ID is 22.22.22.22
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

     Network          Next Hop            Metric LocPrf Weight Path
 *   14.14.14.14/32   101.10.1.6                             0 520 301 1001 i
 *>                   101.10.1.2                             0 301 1001 i
 *                    10.110.111.1             0             0 1001 1001 1001 i
 *   15.15.15.15/32   101.10.1.6                             0 520 301 1001 i
 *                    10.110.111.1                           0 1001 1001 1001 i
 *>                   101.10.1.2                             0 301 1001 i
 *>  18.18.18.18/32   101.10.1.6                             0 520 2042 i
 *                    101.10.1.2                             0 301 520 2042 i
 *   21.21.21.21/32   101.10.1.6                             0 520 301 i
 *>                   101.10.1.2               0             0 301 i
 *>  22.22.22.22/32   0.0.0.0                  0         32768 i
 *>  24.24.24.24/32   101.10.1.6                             0 520 i
 *                    101.10.1.2                             0 301 520 i
```
2. Конфигурация BGP R18:
```
Router#sh run | sec ip prefix-list
ip prefix-list NO-TRAN seq 5 permit 18.18.18.18/32
Router#sh run | sec bgp
router bgp 2042
 bgp log-neighbor-changes
 bgp bestpath as-path multipath-relax
 network 18.18.18.18 mask 255.255.255.255
 neighbor 10.100.110.2 remote-as 520
 neighbor 10.100.110.2 prefix-list NO-TRAN out
 neighbor 10.100.110.6 remote-as 520
 neighbor 10.100.110.6 prefix-list NO-TRAN out
 maximum-paths 2
```
3-4. 3. Настроить провайдера Киторн так, чтобы в офис Москва отдавался только маршрут по умолчанию.<br>
     4. Настроить провайдера Ламас так, чтобы в офис Москва отдавался только маршрут по умолчанию и префикс офиса С.-Петербург.
- Конфигурация BGP R22:
```
Router#sh run | sec route-map
 neighbor 10.110.111.1 route-map REJ out
route-map REJ deny 10
Router#sh run | sec bgp      
router bgp 101
 bgp log-neighbor-changes
 network 22.22.22.22 mask 255.255.255.255
 neighbor 10.110.111.1 remote-as 1001
 neighbor 10.110.111.1 default-originate
 neighbor 10.110.111.1 route-map REJ out
 neighbor 101.10.1.2 remote-as 301
 neighbor 101.10.1.6 remote-as 520
```
- Конфигурация BGP R21:
```
Router#sh run | sec route-map
 neighbor 10.110.111.5 route-map MSK out
route-map MSK permit 10
 match as-path 1
Router#sh run | sec access   
Router#sh run | sec access-list
ip as-path access-list 1 permit _2042$
Router#sh run | sec route-map  
 neighbor 10.110.111.5 route-map MSK out
route-map MSK permit 10
 match as-path 1
Router#sh run | sec bgp
router bgp 301
 bgp log-neighbor-changes
 network 21.21.21.21 mask 255.255.255.255
 neighbor 10.110.111.5 remote-as 1001
 neighbor 10.110.111.5 default-originate
 neighbor 10.110.111.5 route-map MSK out
 neighbor 101.10.1.1 remote-as 101
 neighbor 172.110.0.2 remote-as 520
```
- таблица анонсированных маршрутов R21:
```
Router#sh ip bgp neighbors 10.110.111.5 advertised-routes 
BGP table version is 9, local router ID is 21.21.21.21
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

Originating default network 0.0.0.0

     Network          Next Hop            Metric LocPrf Weight Path
 *>  18.18.18.18/32   172.110.0.2                            0 520 2042 i

Total number of prefixes 1
```
- таблица маршрутов BGP R15:
```
Router#sh ip bgp
BGP table version is 45, local router ID is 15.15.15.15
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

     Network          Next Hop            Metric LocPrf Weight Path
 r>  0.0.0.0          10.110.111.6                  110      0 301 i
 *>i 14.14.14.14/32   172.16.1.25              0    100      0 i
 *>  15.15.15.15/32   0.0.0.0                  0         32768 i
 *>  18.18.18.18/32   10.110.111.6                  110      0 301 520 2042 i
```
- таблица анонсированных маршрутов R22:
```
Router#sh ip bgp neighbors 10.110.111.1 advertised-routes 
BGP table version is 23, local router ID is 22.22.22.22
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

Originating default network 0.0.0.0

     Network          Next Hop            Metric LocPrf Weight Path

Total number of prefixes 0
```
- таблица BGP R14:
```
Router#
*Aug 30 07:38:01.654: %IPRT-3-RIB_LOOP: Resolution loop formed by routes in RIB
Router#sh ip bgp
BGP table version is 127, local router ID is 14.14.14.14
Status codes: s suppressed, d damped, h history, * valid, > best, i - internal, 
              r RIB-failure, S Stale, m multipath, b backup-path, f RT-Filter, 
              x best-external, a additional-path, c RIB-compressed, 
Origin codes: i - IGP, e - EGP, ? - incomplete
RPKI validation codes: V valid, I invalid, N Not found

     Network          Next Hop            Metric LocPrf Weight Path
 * i 0.0.0.0          10.110.111.6             0    110      0 301 i
 *>                   10.110.111.2                           0 101 i
 *>  14.14.14.14/32   0.0.0.0                  0         32768 i
 *>i 15.15.15.15/32   172.16.1.26              0    100      0 i
 * i 18.18.18.18/32   10.110.111.6             0    110      0 301 520 2042 i
```



   
