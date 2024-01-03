```mermaid
flowchart TD
subgraph Administration
Ruud
end

Administration ---
Tech_Group & Site_Group

subgraph Site_Group

Antik --- Mod_Team

subgraph Mod_Team
MichelleG
Xylinna
Thekingoflorda
end

Mod_Team --- Community_Team
subgraph Community_Team
Tenthrow
Ickplant
Ohmyiv
TheGiantKorean
Serinus
JordanLund
end
end

subgraph Tech_Group
subgraph Tech_Lead
Jelloeater
end
Tech_Lead --- Software_Team & Infra_Team
subgraph Software_Team
subgraph Dev_Lead
Rooki
end
Poopsmith
Travis
Keith
Jasper
Justin_K
Carson
Brandon
end
subgraph Infra_Team
subgraph Sr_Infra
Fury
CountVonn
end
Nicholas
Jon
Ben
Eli
Chris
end
end
```
