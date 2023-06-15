# Disaster-recovery-Keepalived  
**Задание 1.**  
Настройка маршрутизатора:  
`Router1#configure terminal`  
`Enter configuration commands, one per line.  End with CNTL/Z.`  
`Router1(config)#interface GigabitEthernet0/0`  
`Router1(config-if)#ip address 192.168.0.3 255.255.255.0`  
`Router1(config-if)#duplex auto`  
`Router1(config-if)#speed auto`  
`Router1(config-if)#standby version 2`  
`Router1(config-if)#standby 0 ip 192.168.0.1`  
`Router1(config-if)#standby preempt`  
`Router1(config-if)#standby 0 track`  
`% Incomplete command.`  
`Router1(config-if)#standby 0 track GigabitEthernet0/0`  
`Router1(config-if)#exit`  
`Router1(config)#exit`  
`Router1#`  

Скрин с прохождением пинга
![изображение](https://github.com/Copakaban/Disaster-recovery-Keepalived/assets/118304300/88b616e1-0911-4333-90e1-1171fdbcfa63)  
[Схема с разорванной связью и проходящим пингом на сервер](https://github.com/Copakaban/Disaster-recovery-Keepalived/raw/main/Z1.pkt)

**Задание 2.**  

![изображение](https://github.com/Copakaban/Disaster-recovery-Keepalived/assets/118304300/d87062db-ab44-4af7-b8f9-7dd40fb82274)  
![изображение](https://github.com/Copakaban/Disaster-recovery-Keepalived/assets/118304300/25b4b5c1-037f-4d54-a2d6-fa32f571d3cf)  
