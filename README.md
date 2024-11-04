|| Leggenda Simboli                              | esempio                  |
|------------------|-----------------------------|--------------------------|
| >                | terminale non privilegiato  | `{HOSTNAME}>`            |
| #                | terminale con privilegi     | `{HOSTNAME}#`            |
| $                | terminale config            | `{HOSTNAME}(config)#`    |
| &                | terminal config interfaccia | `{HOSTNAME}(config-if)#` |

| Comando                                         | Descrizione                                               | Alias                     |
|-------------------------------------------------|-----------------------------------------------------------|---------------------------|
| `> enable`                                      | Passa alla modalità di privilegio elevato                 | `> en`                    |
| `# configure terminal`                          | Accede alla modalità di configurazione globale            | `# conf term`             |
| `$ interface FastEthernet0/1`                   | Accede alla configurazione di una specifica interfaccia   | `$ in f0/1`               |
| `$ hostname NomeSwitch`                         | Assegna un nome allo switch                               |                           |
| `& description descrizione_esempio`             | Aggiunge una descrizione alla porta                       |                           |
| `> show mac-address-table`                      | Visualizza la MAC table                                   | `> sh mac-`               |
| `> show version`                                | Mostra varie informazioni                                 | `> sh ve`                 | 
| `# show spanning-tree`                          | Visualizza informazioni sullo spanning-tree               | `# sh sp`                 |
| `& speed 100`                                   | Imposta una velocità di una porta (es. 10, 100, auto)     | `& spe 100`               |
| `& shutdown`                                    | Spegne la porta che si sta configurando                   |                           |
| `& no shutdown`                                 | Nega lo stato di spenta                                   |                           |
| `& spanning-tree vlan 1 priority 4096`          | Imposta la priorita dello switch                          | `& sp v 1 p 4096`         |
| `> ping 192.168.1.2`                            | Esegue il ping verso l'indirizzo specificato              |                           |
| `# show interfaces status`                      |                                                           |                           |
| `# copy running-config startup-config`          |                                                           |                           |
| `> show interfaces FastEthernet 0/1`            |                                                           |                           |