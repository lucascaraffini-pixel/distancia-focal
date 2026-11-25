# 📷 Calculadora de Distância Focal e Enquadramento

Uma ferramenta web interativa, leve e gratuita para calcular exatamente a que distância você precisa se posicionar do seu assunto para obter um enquadramento específico, levando em conta a milimetragem da lente, o tamanho do sensor da câmera e as dimensões reais da cena.

🔗 **Acesse a ferramenta online:** [https://lucascaraffini-pixel.github.io/distancia-focal/](https://lucascaraffini-pixel.github.io/distancia-focal/)

---

## 🎯 O que é este projeto?

A **Calculadora de Distância Focal e Enquadramento** é uma aplicação web desenvolvida em um único arquivo HTML (sem necessidade de instalação ou servidor complexo). Ela traduz a óptica fotográfica em números práticos: em vez de testar lentes por tentativa e erro no local do ensaio ou evento, você informa o tamanho da área que deseja fotografar (por exemplo, um painel de 3m × 2m ou uma pessoa de corpo inteiro) e o sistema calcula a distância exata em metros necessária para cada lente.

---

## ⚙️ Como funciona?

O cálculo é feito em tempo real utilizando a relação trigonométrica entre o tamanho físico do sensor da câmera, a distância focal real da lente e as dimensões do retângulo alvo:

1. **Escolha o Sensor:** Selecione entre os principais formatos do mercado (**APS-C 1.5x**, **Full Frame 35mm**, **APS-C 1.6x** e **Micro 4/3**).
2. **Defina a Lente (mm):** Use o controle deslizante (10 mm a 600 mm), digite um valor exato ou clique nos atalhos das lentes mais comuns.
3. **Configure o Alvo (Proporção 3:2 ou 2:3):** Informe a largura e a altura desejadas em metros e alterne entre orientação **Vertical (2:3)** ou **Horizontal (3:2)**, com opção de travar a proporção.
4. **Visualize os Resultados:**
   - **Distância exata** em metros e estimativa em passos.
   - **Distância focal equivalente** (em Full Frame) e **ângulos de visão** (horizontal e vertical).
   - **Prévia interativa do visor** com regra dos terços e silhueta humana de referência.
   - **Diagrama lateral do cone óptico** mostrando a relação câmera-alvo.
   - **Tabela comparativa** com todas as principais distâncias focais lado a lado.

---

## 💡 Por que eu escrevi este projeto?

Na prática fotográfica — especialmente em eventos, corridas, ensaios externos e espaços com restrição física —, nem sempre temos liberdade para recuar o quanto queremos. 

Este projeto nasceu de uma necessidade real: **saber com precisão a quantos metros de distância eu precisava ficar para enquadrar uma pessoa dentro de uma área específica de 3 metros de altura por 2 metros de largura (proporção 2:3 na vertical)** usando diferentes lentes do meu kit. Em vez de fazer contas manuais ou descobrir só na hora do clique que a parede atrás de mim não deixava espaço suficiente para uma 135mm ou 85mm, criei esta calculadora visual para planejar o posicionamento com antecedência.

---

## 👥 Quem pode usar?

- **Fotógrafos de eventos e esportes:** para planejar pontos de cobertura (pórticos, chegadas, palcos, backdrops).
- **Fotógrafos de retrato e estúdio:** para saber se o tamanho da sala comporta o uso de teleobjetivas ou lentes fixas em fotos de corpo inteiro.
- **Videomakers e diretores de fotografia:** para prever o espaço físico necessário para cenas e entrevistas.
- **Estudantes e entusiastas de fotografia:** para entender de forma visual como o fator de corte (*crop factor*) e a distância focal alteram o campo de visão.

---

## 📅 Quando usar?

- **No pré-planejamento (visita técnica):** antes de ir para um evento ou locação, para decidir quais lentes levar na mochila.
- **Na montagem de estúdios ou fundos fotográficos:** para garantir que o recuo disponível na sala é suficiente para cobrir a largura/altura do fundo sem vazar as bordas.
- **Antes de comprar uma lente nova:** para simular na prática se uma 50mm, 85mm ou 135mm vai se adaptar aos espaços onde você costuma trabalhar.
- **Em campo, pelo celular:** para checar rapidamente qual lente sacar da bolsa conforme a distância disponível até o assunto.

---

## ✅ Benefícios de usar

- **Precisão no planejamento:** elimina o "achismo" e evita surpresas por falta de espaço físico no local.
- **Economia de tempo e peso:** ajuda a escolher apenas as lentes que realmente vão funcionar naquela locação.
- **Comparação imediata:** a tabela integrada permite ver, em segundos, a diferença de distância entre uma 24mm, 50mm, 85mm e 135mm para o mesmo enquadramento.
- **100% gratuito e acessível:** roda direto no navegador do computador ou celular, sem anúncios, sem cadastro e podendo até ser salvo para uso offline.

---

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3** (layout responsivo)
- **JavaScript** (cálculos ópticos em tempo real e manipulação de gráficos **SVG**)
- Hospedado gratuitamente via **GitHub Pages**.
