# Routerns uppgift

Förr i tiden var det vanligt att det endast fanns en internetuppkopplad dator i hemmet. Den kopplades då direkt till modemet eller det dedikerade uttaget. Nu för tiden, när vi har många internetuppkopplade enheter, tar routern den plats som datorn tidigare hade. Sedan ansluter vi i stället alla datorer och andra nätverksenheter till routern.

Routern har en funktion som kallas _NAT_ (Network Address Translation). Det är tack vare den som vi kan ha fler internetanslutna enheter än antalet möjliga IPV4-adresser. Med hjälp av Nat skapar routern ett eget nätverk som den agerar operatör för. När ­datorer sedan använder DHCP för att be om IP-adresser tilldelas de IP-adresser av routern (i stället för av internetoperatören). Dessa IP-adresser börjar vanligtvis på 192.168.0. eller 192.168.1. Routern kan exempelvis ge en ansluten dator IP-adressen 192.168.0.100 och en annan ansluten dator 192.168.0.101. Runt om i världen finns nästintill oändligt många datorer som har dessa IP-adresser. Trots det uppstår inga IP-adresskonflikter. Datorerna har nämligen endast dessa IP-adresser inuti sina respektive lokala nätverk. När de går ut på internet är det deras routers IP-adress som används.

![Router](https://lernia.itslearning.com/data/1821/C33240/IT%20och%20automation/bilder/router.png)
