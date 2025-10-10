A infraestrutura da AWS é composta por **Regiões (Regions)** e **Zonas de Disponibilidade (Availability Zones ou AZs)**.

* **Regions**: São locais geográficos independentes ao redor do mundo. Cada região é totalmente isolada das outras. Isso garante que, se um desastre afetar uma região, os serviços em outras regiões não sejam impactados. Para escolher uma região, é essencial considerar fatores como: **Compliance**, **Disponibilidade de Serviços**, **Custo** e **Latência**.

* **Availability Zones (AZs)**: São data centers localizados dentro de uma região. Cada região é composta por, no mínimo, duas AZs. Elas são fisicamente separadas, mas próximas o suficiente para ter conexões de rede de baixa latência. Essa separação física ajuda a proteger contra falhas como incêndios ou inundações em um único data center.
