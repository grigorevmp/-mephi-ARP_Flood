# ARP_Flood
Simple script to send random arp packets

Usage: arpflood [options]

Options:

  -h, --help            show this help message and exit
  
  --t=TYPE, --type=TYPE
  
                        [response (default), request] - type of sending packet
                        
  --n=NUMBER, --num=NUMBER
  
                        number of sending packets
                        
  --gr, --gratuitous    gratuitous arp sending
  
  --tara=TARGET_ARP, --target_arp=TARGET_ARP
  
                        target arp packet ip or [random (default)]
                        
  --srca=SOURCE_ARP, --source_arp=SOURCE_ARP
  
                        source arp packet ip or [random (default)]
                        
  --dst=DESTINATION, --destination=DESTINATION
  
                        target mac or broadcast (default)
                        
  --src=SOURCE, --source=SOURCE
  
                        source mac, your mac by default
                        
  --i=INTERFACE, --interface=INTERFACE
  
                        interface to send packets
