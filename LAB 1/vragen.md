# Vragen

1. Waarom is er een L3-verbinding tussen de MLSen?

> Zodat VRRP kan worden toegepast. 

2. Hoe kan je de etherchannel load-balancing beïnvloeden? 

> De flow-tuple (mac-adres source/dest, ip-adres source/dest).

3. Wat is het voordeel van VRRP?

> Het is niet eigendom van Cisco en beidt failover zonder downtime.

4. Hoe controleer je dat de “load-balancing” over de MLSen m.b.v.STP correct geconfigureerd is?

> Met het commando `> show spanning-tree interface`

5. Waartoe dient interface tracking bij VRRP?

> Zodat als er een link faalt de failover zonder downtime kan. 