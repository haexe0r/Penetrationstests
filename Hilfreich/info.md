**Vorhandene Geräte im Netzwerk erkennen**
 
    root@Kali: ~# nmap -sP 192.168.1.0/24

Mit dem Befehlt `192.168.1.0/24` werden alle IP Bereiche von 192.168.1.0 - 192.168.1.255 gescannt. Als Output bekommt man den Anzeigenamen des Gerätes im Netzwerk, die IP Adresse, die Latency sowie die MAC Adresse. Das sind die wichtigsten Informationen.

> Nmap scan report for *Devicename* (*192.168.1.1*)
> 
>Host is up ( *0.000* s latency).
> 
> MAC Address: *00:0A:00:0A:00:0A* (*xy*)

weitere Optionen, um die Suche zu optimiren, erhaltet ihr mir

    root@Kali: ~# nmap -h

----------

