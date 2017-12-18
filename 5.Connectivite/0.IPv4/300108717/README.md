hello Flore 

## Schema

![alt tag](./300108717.png)

## Connectivite

| Reseau:             |  Passerelle | Commentaires (i.e. ping 192.168.100.254)|
|---------------------|-------------|-----------------------------------------| 
| 192.168.100.0/24    | [Ping]      |                                         |
| 192.168.101.0/24    | [Ping]      |                                         |
| 192.168.102.0/24    | [Ping]      |                                         |

| Reseau:             |  Routeur    | Commentaires (i.e. ping 10.10.10.5 )    |
|---------------------|-------------|-----------------------------------------| 
| 192.168.100.0/24    | [None]      | .5  `Passerelle non connectee`          |
| 192.168.101.0/24    | [None]      | .6  `Passerelle non connectee`          |
| 192.168.101.0/24    | [None]      | .9  `Passerelle non connectee`          |
| 192.168.102.0/24    | [None]      | .10 `Passerelle non connectee`          |

| Reseau:             |  Routeur    | Commentaires (i.e. ping 10.10.10.5 )    |
|---------------------|-------------|-----------------------------------------| 
| 10.10.10.4/30       | [Ping]      |    => .6  `nom Routeur R0>`             |
| 10.10.10.4/30       | [Ping]      | .5 => .10 `nom Routeur R1>`             |
| 10.10.10.8/30       | [Ping]      |    => .9  `nom Routeur R2>`             |
