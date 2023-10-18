---
title: "Meet the team"
weight: 1
---

## Staff


🧑 [@Ruud](https://lemmy.world/u/ruud)

🧑 [@Antik](https://lemmy.world/u/antik)

🧑 [@MichelleG](https://lemmy.world/u/MichelleG)

🧑 [@AvaddonLFC](https://lemmy.world/u/clueless_stoner)

🧑 [@Xylinna](https://lemmy.world/u/xylinna)

🧑 [@Quinten](https://lemmy.world/u/Quinten)

🧑 [@Jelloeater](https://lemmy.world/u/jelloeater85)

🧑 [@Rooki](https://lemmy.world/u/Rooki)

🧑 [@Thekingoflorda](https://lemmy.world/u/Thekingoflorda)

🧑 [@MrCenny](https://lemmy.world/u/MrCenny)

🧑 [@poopsmith](https://lemmy.world/u/poopsmith)

🧑 [@Fury](https://lemmy.world/u/fury)

🧑 [@Travis](https://lemmy.world/u/tjkessler)

🧑 [@CountVon](https://sh.itjust.works/u/CountVon)

🧑 Ocelot

🧑 Snoltz

## Organization Structure

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
