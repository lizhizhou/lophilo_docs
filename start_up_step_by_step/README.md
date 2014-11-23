# Start up step by step
1 Plug in the power cable, usb and net cable

2 Press the power button.

3 login the console

4 get the ip address from console
 Run ifconfig in shell console
  ```
root@hostname:~$ ifconfig
eth0     Link encap:Ethernet  HWaddr 48:02:2a:b6:0c:0a
          inet addr:192.168.2.109  Bcast:192.168.2.255  Mask:255.255.255.0
          UP BROADCAST RUNNING MULTICAST  MTU:1500  Metric:1
          RX packets:35765 errors:0 dropped:355449 overruns:0 frame:0
          TX packets:3800 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:1000
          RX bytes:10828535 (10.8 MB)  TX bytes:703119 (703.1 KB)
lo        Link encap:Local Loopback
          inet addr:127.0.0.1  Mask:255.0.0.0
          UP LOOPBACK RUNNING  MTU:16436  Metric:1
          RX packets:153 errors:0 dropped:0 overruns:0 frame:0
          TX packets:153 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:0
          RX bytes:12822 (12.8 KB)  TX bytes:12822 (12.8 KB)
miniand@miniand:~$
```
The ip address of the broad is 192.168.2.109

5 get the ip address from router
  You can also get the ip address of the broad from you router in the DHCP servier-> client list
 ```
ID	客户端名	MAC 地址	IP 地址	有效时间
1	lizhizhdeiPhone	0C-3E-9F-55-39-23	192.168.2.100	01:47:32
2	lizhizhou	60-45-BD-E9-29-BA	192.168.2.104	01:29:52
3	miniand	48-02-2A-B6-0C-0A	192.168.2.109	01:41:03
4	android-d005d5d5cbb83cc9	00-24-25-0E-E7-C8	192.168.2.101	01:53:23
5	ubuntu	00-0C-29-38-00-E1	192.168.2.102	01:15:16

```
The ip address of the broad is 192.168.2.109

6 load the Arduino IDE from the browser

7 Load a example

8 Edit the code

9 Check the api doc

10 run the code

11
