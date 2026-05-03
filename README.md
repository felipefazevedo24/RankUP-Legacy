# 🏰 RankUP Legacy - Game Design Document

> Documento oficial de design do servidor RankUP Legacy  
> Estrutura completa para desenvolvimento, balanceamento e implementação.

---

# 📌 1. VISÃO GERAL

O RankUP Legacy é um servidor baseado em progressão contínua, onde o jogador evolui através de mineração, geração passiva de recursos e otimização de eficiência econômica.

A experiência é construída em torno de um sistema de ranks lineares (A → Z), com desbloqueio progressivo de conteúdo e aumento escalável de ganhos.

---

# 🔁 2. CORE LOOP

O gameplay segue o ciclo abaixo:

1. Minerar blocos nas minas
2. Obter Coins
3. Executar /rankup
4. Desbloquear novos sistemas:
   - Minas mais lucrativas
   - Spawners
   - Máquinas
5. Aumentar geração de renda
6. Repetir com maior eficiência

---

# 💰 3. ECONOMIA

## 3.1 Moedas

### 🪙 Coins
- Moeda principal do servidor
- Utilização:
  - Rankup
  - Loja (/loja)
  - Compra de spawners
  - Upgrades de máquinas

### 💎 Cash
- Moeda premium
- Origem:
  - Loja externa
  - Crates raras
- Utilização:
  - /shop
  - Boosters
  - Itens exclusivos

---

# 🏆 4. SISTEMA DE RANKS

## 4.1 Estrutura

- Progressão linear: A → Z
- Cada rank exige Coins
- Escala exponencial

## 4.2 Recompensas por rank

Cada rank desbloqueia:

- Nova mina
- Novos spawners disponíveis
- Acesso a upgrades adicionais
- Aumento de eficiência econômica (multiplicadores internos)

## 4.3 Exemplo de Progressão

| Rank | Custo |
|------|------|
| A | Inicial |
| B | 10M |
| C | 50M |
| D | 200M |
| E | 1B |
| F | 5B |
| ... | Escalável até Z |

---

# ⛏️ 5. MINAS

## 5.1 Sistema Geral

- Cada rank possui uma mina exclusiva
- Blocos regeneram automaticamente
- Sistema de reset automático (30s – 60s)

## 5.2 Estrutura Progressiva

| Rank | Composição |
|------|-----------|
| A | Pedra, carvão |
| B | Ferro, carvão |
| C | Ferro, ouro |
| D | Ouro, redstone |
| E | Diamante |
| F+ | Diamante + esmeralda |
| Late Game | Blocos custom (alto valor) |

## 5.3 Mecânicas

- Venda automática (VIP/perk)
- Blocos especiais:
  - Chance de drop raro
  - Valor elevado
- Multiplicadores por rank

---

# ⚔️ 6. MINA PVP

## 6.1 Características

- PvP ativado
- Drop total ao morrer
- Proteção inicial: 15s
- Logout = morte automática

## 6.2 Recompensas

- Coins elevados
- Chaves
- Tokens
- Chance de drop de itens do jogador

---

# 🏝️ 7. PLOTS

## 7.1 Estrutura

- Tamanho: 51x51
- Comando: /plot auto
- Limite inicial: 1

## 7.2 Funções

- Instalação de spawners
- Instalação de máquinas
- Construções

## 7.3 Expansão

- Via VIP
- Via compra no /shop

---

# 🧬 8. GERADORES

---

## 8.1 Spawners

### Funcionamento:

- Spawn automático de mobs
- Drops enviados para armazenamento interno

### Mecânicas:

- Stack infinito
- Venda:
  - Limitada por padrão
  - Ilimitada com upgrade

---

## 8.2 Máquinas

Sistema de produção passiva.

### Exemplo: Melificadora

#### Produção base:
- Ciclo: 30 segundos

#### Atributos:

- Produção por ciclo
- Chance de duplicação
- Consumo de combustível
- Velocidade

#### Upgrades:

- Redução de tempo
- Aumento de produção
- Eficiência energética

#### Stack:

- Produção soma proporcionalmente

---

# 📦 9. CRATES

## 9.1 Tipos

- Comum
- Rara
- Épica
- Lendária
- Vote
- VIP

## 9.2 Sistema

- Abertura via chave
- Sistema de chances (%)

## 9.3 Drops

- Coins
- Cash
- Spawners
- Máquinas
- Boosters
- Itens raros

---

# 👑 10. BOSSES

## 10.1 Sistema

- Invocação via item
- HP elevado
- IA custom

## 10.2 Mecânicas

- Habilidades especiais
- Área de combate dedicada

## 10.3 Recompensas

- Chaves
- Coins
- Cash
- Boosters
- Itens raros

---

# 🎣 11. PESCA

## 11.1 Sistema

- Minigame passivo
- Chance baseada em RNG

## 11.2 Drops

- Peixes (venda)
- Chaves
- Boosters
- Coins

---

# 🐾 12. PETS

## 12.1 Função

Boost de performance do jogador.

## 12.2 Tipos de bônus

- +Coins
- +Drops
- +Velocidade
- +Eficiência

## 12.3 Mecânicas

- Evolução por níveis
- Sistema de alimentação
- 1 ativo por jogador

---

# 🎯 13. EVENTOS

## 13.1 Fixos

- Frequência: 2h
- Recompensas maiores

## 13.2 Aleatórios

- Frequência variável
- Recompensas menores

## 13.3 Exemplos

- TNT Run
- Corrida
- Eventos de chat
- Mineração bônus

---

# 🛒 14. LOJA (/loja)

Compra com Coins:

- Blocos
- Ferramentas
- Combate
- Utilitários

---

# 💎 15. SHOP (/shop)

Compra com Cash:

- Equipamentos OP
- Boosters
- Packs
- Benefícios

---

# 📅 16. MISSÕES

## 16.1 Diárias

- Minerar
- Matar mobs
- Pescar
- Vender itens

## 16.2 Semanais

- Rankup
- Grandes quantidades de farm
- Eventos

---

# ⚙️ 17. SISTEMAS ADICIONAIS

## Boosters

- Multiplicador de Coins
- Multiplicador de drops

## Leaderboards

- Top Coins
- Top Rank
- Top Boss

## Feedback visual

- Action bar
- Hologramas
- Mensagens dinâmicas

---

# 🧩 18. DIRETRIZES DE DESENVOLVIMENTO

- Sistema modular
- Alta performance
- Escalabilidade
- Baixo uso de entidades
- Interfaces simples

---

# 🚀 19. MONETIZAÇÃO

## VIP

Benefícios:

- Acesso antecipado a conteúdos
- Multiplicadores
- Limites maiores
- Kits exclusivos

## Loja externa

- Venda de:
  - Cash
  - Chaves
  - Boosters
  - Spawners

---

# 📊 20. BALANCEAMENTO (DIRETRIZ)

- Economia inflada (OP)
- Progressão crescente
- Early game rápido
- Mid game médio
- Late game lento

---

# ✅ STATUS

Documento pronto para implementação.

---
