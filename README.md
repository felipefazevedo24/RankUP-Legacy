# RankUP-Legacy

# 🌺 RankUP Flowers - Game Design Document

O **RankUP Flowers** é um servidor de Minecraft focado em uma economia temática onde as flores são o centro da jogabilidade e progressão. O ambiente mistura elementos medievais com fantasia em um cenário de jardim épico.

---

## 🏛️ Estrutura Elementar
As flores são o foco principal da jogabilidade e economia. Toda a decoração segue o estilo jardim medieval com elementos de fantasia.

### 💰 Economias e Moedas
1.  **Coins:** Moeda padrão obtida via mineração, venda de colheitas, drops de spawners/máquinas, crates, caixas misteriosas e eventos.
2.  **Golds:** Moeda rara. Obtida em crates raras, missões completas, eventos e compra no site. Usada no `/shop`.
3.  **Pétalas:** Recurso essencial para evolução de Rank.
    * Colha flores no **Mundo de Plantações**.
    * Obtenha **Flores Brilhantes** (variação rara).
    * Troque com a NPC **Flora – Sábia das Pétalas** na Feira das Flores.

**⚠️ Limite de Compra:** Sistema para limitar a compra de spawners e máquinas. Obtido em crates, pesca e matando bosses.

---

## 🌻 Sistema de Ranks
A jornada floral é dividida em níveis de prestígio (III, II, I) baseados em flores:

| Rank | Descrição | Cor Sugerida |
| :--- | :--- | :--- |
| **Dente-de-Leão** | Simples, início da jornada | Branco (`&f`) |
| **Tulipa** | Colorida e versátil | Roxo (`&5`) |
| **Margarida** | Discreta e firme | Amarelo (`&e`) |
| **Hibisco** | Tropical e vibrante | Vermelho (`&c`) |
| **Sakura** | Rara e elegante | Rosa (`&d`) |
| **Orquídea** | Misteriosa e refinada | Azul (`&9`) |
| **Rosa Negra** | Símbolo de domínio e respeito | Preto (`&0`) |
| **Flor Eterna** | O auge lendário da jornada | Laranja/Ouro (`&6`) |

---

## 🚜 Mundo de Plantações
O coração da economia. As flores crescem apenas nesta dimensão dedicada.

### Tabela de Lucro (Exemplos de Valores)
| Flor | Comum | VIP | MVP | MVP+ |
| :--- | :--- | :--- | :--- | :--- |
| **Tulipa** | 10 - 25 | 13 - 35 | 20 - 45 | 25 - 60 |
| **Allium** | 35 - 100 | 45 - 120 | 55 - 150 | 65 - 200 |
| **Roseira** | 125 - 300 | 175 - 360 | 225 - 415 | 250 - 500 |
| **Peônia** | 400 - 1250 | 435 - 2K | 500 - 3K | 650 - 4.5K |
| **Girassol** | 2000 - 4250 | 3K - 5K | 4K - 6K | 5K - 8K |

### Evolução do Jardim
1.  **Jardim Broto:** Desbloqueia Tulipa (Replantio: 60s).
2.  **Jardim Rústico:** Desbloqueia Allium (Replantio: 55s).
3.  **Jardim de Rosas:** Desbloqueia Roseira (Replantio: 50s).
4.  **Jardim Aromático:** Desbloqueia Peônia (Replantio: 45s).
5.  **Jardim Solar:** Desbloqueia Girassol (Replantio: 40s).

---

## ⛏️ Mineração e Combate
Progressão via NPC "Guardião Raiz".
* **Minas:** Silvestre, Nebulosa, Âmbar, Rubra, Orquídea e Estelar.
* **Mina PvP:** Área central de alto risco. Jogadores podem perder Flores Brilhantes ao serem derrotados.

---

## 🐝 Máquinas e Pets
### Máquinas (Melificadoras)
Produzem **Potes de Mel**, usados para alimentar e evoluir pets.

### Pets
Possuem 5 níveis de evolução.
* **Espécies:** Joaninha, Pinguim, Guaxinim, Raposa e Abelha (Lendária).
* **Evolução:** Requer **Mel Encantado** (nível 5).

---

## 🛡️ Habilidades e Bosses
* **Skills:** Mineração, Escavação, Herbalismo, Espadas, Arqueiro e Alquimia.
* **Bosses:** Invocados por itens ou eventos. Dropam fragmentos de armaduras e itens de Gold.

---

## ⌨️ Comandos Principais
* `/plantacoes`: Teleporte para o mundo de cultivo.
* `/feira`: Hub de NPCs e trocas.
* `/skills`: Menu de habilidades.
* `/pet`: Gerenciamento de companheiros.
* `/shop`: Itens exclusivos com Gold.

---
