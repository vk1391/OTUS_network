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
# Настройка маршрутизации в офисе Москва
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
