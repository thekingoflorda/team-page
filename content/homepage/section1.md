---
title: "Organization Structure"
weight: 2
---

{{< mermaid >}}

flowchart TD
subgraph Administration
Ruud
end

Administration -->
Tech_Group & Site_Group

subgraph Site_Group
AvaddonLFC --> US_Team
Antik --> EU_Team

subgraph US_Team
MichelleG & Xylinna
end
subgraph EU_Team
Quinten & Thekingoflorda
end

US_Team & EU_Team --> Community_Team
subgraph Community_Team
MrCenny
end
end


subgraph Tech_Group
Jelloeater --> Software_Team & Infra_Team
subgraph Software_Team
Rooki
Poopsmith
end
subgraph Infra_Team
Fury
Travis
CountVonn
Ocelot
Snoltz
end
end
{{< /mermaid >}}
