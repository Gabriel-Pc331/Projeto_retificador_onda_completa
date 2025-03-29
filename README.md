# 🔌 Projeto de Fonte 5V com 7805

Este projeto consiste em uma **fonte de alimentação linear simples**, utilizando:

- Um transformador
- Ponte retificadora
- Regulador de tensão 7805
- Capacitores de filtragem/desacoplamento
- LED indicador

🎯 **Objetivo**: Obter uma saída de **5V DC** estável, adequada para alimentar pequenos projetos eletrônicos.

---

## 📚 Índice de Seções

1. [🎯 Objetivo do Projeto](#-objetivo-do-projeto)
2. [🧰 Componentes Utilizados](#-componentes-utilizados)
3. [📘 Esquemático](#-esquemático)
4. [🧩 PCB](#-pcb)
5. [🔍 Visualização 3D](#-visualização-3d)
6. [🛠️ Prática (Montagem Breadboard)](#️-prática-montagem-breadboard)
7. [👤 Autor e Data](#-autor-e-data)

---

## 🎯 Objetivo do Projeto

O objetivo é demonstrar a montagem de uma fonte linear que:

- 🔻 Reduz a tensão da rede elétrica por meio de um transformador (ex: 110/220VAC para 9VAC ou 12VAC)  
- 🔁 Retifica a saída do transformador com uma ponte retificadora (BR1)  
- ⚡ Filtra a tensão DC resultante com capacitores (C1, C2, C3)  
- 🔧 Regula a tensão para **5V estáveis** com o regulador linear 7805 (U1)  
- 💡 Indica a presença de tensão de saída com um LED (D1) em série com um resistor de 220 Ω (R1)

---

## 🧰 Componentes Utilizados

| Componente       | Valor / Modelo      | Função                                      |
|------------------|---------------------|---------------------------------------------|
| Transformador     | 110/220VAC → 9V/12V | Redução da tensão da rede                   |
| Ponte Retificadora | BR1                | Conversão de AC para DC                     |
| Regulador de Tensão | 7805 (U1)         | Regulação da tensão para 5V                 |
| Capacitor C1       | 1 µF               | Filtro principal / desacoplamento           |
| Capacitor C2       | 22 nF              | Filtro de alta frequência (entrada do 7805) |
| Capacitor C3       | 22 nF              | Filtro de alta frequência (saída do 7805)   |
| LED Vermelho (D1)  | -                  | Indicação de funcionamento                  |
| Resistor R1        | 220 Ω              | Limitador de corrente para o LED            |
| J1 / J2            | -                  | Conectores de entrada e saída               |

---

## 📘 Esquemático

📷 **Diagrama Elétrico do Circuito**:

![Esquematico](Portfólio/Esquematico/captura_de_tela2.png)

🔌 Explicação:
- J1 recebe a tensão AC do transformador  
- A ponte retificadora (BR1) converte AC em DC pulsante  
- O capacitor C1 realiza a filtragem inicial  
- C2 e C3 atuam como filtros de alta frequência próximos ao 7805  
- A saída do 7805 alimenta o LED (D1) com o resistor R1  
- J2 disponibiliza a saída regulada de **5V**

---

## 🧩 PCB

📐 **Layout da Placa de Circuito Impresso** (criado no Proteus 8):

![pcb](Portfólio/PCB/captura.png)

📝 Detalhes Técnicos:
- Dimensões estimadas: **50 mm x 30 mm**
- Conectores J1 (entrada) e J2 (saída) posicionados para fácil acesso
- Trilhas organizadas e bem distribuídas
- O regulador 7805 (U1) está centralizado para melhor dissipação térmica

---

## 🔍 Visualização 3D

🧱 **Modelo Tridimensional da Placa**:

![3d1](Portfólio/3D/captura3d1.png)  
![3d2](Portfólio/3D/captura3d2.png)

🔎 Destaques:
- Ponte retificadora (BR1) próxima ao conector de entrada  
- Capacitores (C1, C2, C3) nas posições otimizadas para filtragem  
- LED (D1) e resistor (R1) bem localizados  
- Conector de saída (J2) pronto para integração com outros projetos

---

## 🛠️ Prática (Montagem Breadboard)

📸 **Montagem do circuito em protoboard para testes**:

![teste1](Portfólio/Pratica/imagem1.jpg)  
![protoboard](Portfólio/Pratica/imagem3.jpg)  
![teste2](Portfólio/Pratica/imagem2.jpg)

✅ **Validações feitas**:
- Transformador fornece tensão AC à protoboard  
- Ponte retificadora, capacitores e 7805 conectados conforme o esquemático  
- LED vermelho aceso confirma que os 5V estão presentes  
- Medição com multímetro: saída entre **4,96V e 5,01V**

---

## 👤 Autor e Data

- **Autor**: Gabriel Pierin Caurio  
- 📅 **Data**: Março / 2025

