# WiFi analyzer
* Python codes provide read  access to a wireless network card’s capabilities using OS WiFi Extensions.
* winwifi_scanner.py is a wifi scanner wrapped for wlanapi.dll, tested on MS Windows 10 and  Python 3.7 
* wifi_snifer.py wrappers runs natively on Windows/Linux using scapy API 

### winwifi_scanner.py
```
 Rssi:-66 dbm   Freq: 2.412 GHz  type: 802.11n  algo: 1  rate: 12  BSSID: 24:A4:3C:42:2D:BB  SSID:scb2-f2-1-wifi
 Rssi:-65 dbm   Freq: 2.437 GHz  type: 802.11n  algo: 1  rate: 12  BSSID: 68:72:51:26:FA:D7  SSID:Design-UDRU-Wifi
 Rssi:-66 dbm   Freq: 2.437 GHz  type: 802.11n  algo: 1  rate: 12  BSSID: 24:A4:3C:42:28:5A  SSID:scb2-f3-1-wifi
 Rssi:-87 dbm   Freq: 2.437 GHz  type: 802.11n  algo: 1  rate: 12  BSSID: C8:D3:A3:74:E2:EA  SSID:ScB2_3
 Rssi:-84 dbm   Freq: 2.437 GHz  type: 802.11n  algo: 1  rate: 12  BSSID: 24:A4:3C:42:2D:76  SSID:scb1-wifi3
 Rssi:-78 dbm   Freq: 2.437 GHz  type: 802.11n  algo: 1  rate: 4  BSSID: DC:F7:19:B6:B1:A2  SSID:UDRU-Wifi By TRUE
 Rssi:-77 dbm   Freq: 2.437 GHz  type: 802.11n  algo: 6  rate: 4  BSSID: DC:F7:19:B6:B1:A3  SSID:UDRU-NET By TRUE
 Rssi:-83 dbm   Freq: 2.437 GHz  type: 802.11n  algo: 1  rate: 4  BSSID: DC:F7:19:B6:B1:A4  SSID:eduroam By TRUE
 Rssi:-82 dbm   Freq: 5.745 GHz  type: 802.11n  algo: 6  rate: 8  BSSID: 24:A4:3C:8C:59:98  SSID:food-tech-send
 Rssi:-69 dbm   Freq: 5.64 GHz  type: 802.11ac  algo: 6  rate: 4  BSSID: 34:F8:E7:11:77:6B  SSID:eduroam By TRUE
 Rssi:-64 dbm   Freq: 5.64 GHz  type: 802.11ac  algo: 4  rate: 4  BSSID: 34:F8:E7:11:77:6C  SSID:UDRU-NET By TRUE
 Rssi:-66 dbm   Freq: 5.64 GHz  type: 802.11ac  algo: 1  rate: 4  BSSID: 34:F8:E7:11:77:6D  SSID:UDRU-Wifi By TRUE
```
### wifi_sniffer.py 
 ```
 [+] Sniffing on interface Wi-Fi 14:
 [+] Sniffing on channel 1
    Ether / ARP who has 10.1.142.200 says 10.1.142.124
    Ether / IP / UDP / DNS Qry "b'_spotify-connect._tcp.local.'"
    Ether / ARP who has 192.168.3.254 says 192.168.3.230 / Padding
    Ether / ARP who has 10.1.142.200 says 10.1.142.124
    Ether / IP / UDP 10.1.142.181:57621 > 10.1.142.255:57621 / Raw


 0000  53 70 6F 74 55 64 70 30 EB FE 1B 58 1F CD 78 E0  SpotUdp0...X..x.
 0010  00 01 00 04 48 95 C2 03 0C FF 58 D9 5E D6 DC AF  ....H.....X.^...
 0020  A2 51 59 1F 8F 57 A9 FE E9 6B AB 83              .QY..W...k..
 None
```
