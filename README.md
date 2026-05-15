# ChargeGrid Intelligence

---

Equipe Grupo 03

Lucas Klein da Veiga - RM 570029

Pedro Andreassa Zamai - RM 569318

Pedro Yoshikado Garcia - RM 570449

Thiago Maluf Hofmann - RM 569852

Rafael Ferreirinha Quaresma - RM 571949

---

**1. Problema e Justificativa**

* **O aumento da frota de veículos elétricos gera um paradoxo:** como carregar todos simultaneamente sem derrubar a rede ou pagar multas altíssimas?

* **Picos de Demanda:** O custo da energia e o estresse na rede não são constantes. Sem gestão, o eletroposto paga caro pela "Ultrapassagem de Demanda".

* **Subutilização:** Em horários de baixo movimento, o capital investido no eletroposto fica parado e sem gerar receita.

---

**Proposta: ChargeGrid Intelligence**

Nossa solução atua em duas frentes principais para garantir a viabilidade do negócio:

* **Tarifa Dinâmica:** Implementamos um modelo econômico onde o preço do kWh flutua conforme a demanda. Isso incentiva o motorista a carregar em horários ociosos (preços baixos) e gerencia a carga em horários de pico (preços premium).

* **Controle Ativo (Smart Charging):** Através de algoritmos de software, o sistema limita a potência de saída de cada carregador em tempo real. Se 10 carros conectarem, o sistema distribui a carga de forma que a soma total nunca ultrapasse o limite contratado com a concessionária.

---

**Tecnologias e Sustentabilidade**

* **Hardware (GoodWe):** Uso de inversores e baterias para armazenar energia barata e injetar no sistema durante a Tarifa Premium, maximizando o lucro e a eficiência.

* **Software (Orquestração):** Camada de inteligência que processa os dados de consumo e ajusta os preços e a distribuição de carga automaticamente.

* **Sustentabilidade:** Ao "achatar" a curva de consumo através da tarifa dinâmica, evitamos a sobrecarga da rede urbana e otimizamos o uso da infraestrutura existente, evitando reformas desnecessárias e desperdício de energia.
