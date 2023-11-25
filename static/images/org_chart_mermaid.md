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
MichelleG & Xylinna & Quinten & Thekingoflorda
end

Mod_Team --- Community_Team
subgraph Community_Team
?
end
end

subgraph Tech_Group

subgraph Software_Team
subgraph Dev_Lead
Rooki
end
Poopsmith
Travis
Keith
Jasper
Justin
Carson
end
subgraph Infra_Team
subgraph Infra_Lead
Jelloeater
end
subgraph Sr_Infra
Fury
CountVonn
end
Nicholas
Jon
Chris
Ben
Eli
end
end
```
