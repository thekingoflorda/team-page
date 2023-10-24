---
title: "🗺 Org Chart"
weight: 3
---

{{< mermaid >}}

%%{ init : {'theme': 'neutral', "flowchart" : { "curve" : "stepAfter" }}}%%

flowchart TD
subgraph Administration
Ruud
end

Administration ---
Tech_Group & Site_Group

subgraph Site_Group

AvaddonLFC & Antik --- Mod_Team

subgraph Mod_Team
MichelleG & Xylinna & Quinten & Thekingoflorda
end

Mod_Team --- Community_Team
subgraph Community_Team
?
end
end

subgraph Tech_Group
Jelloeater --- Software_Team & Infra_Team
subgraph Software_Team
Rooki
Poopsmith
end
subgraph Infra_Team
Fury
Travis
CountVonn
end
end

{{< /mermaid >}}
