# 🏰 RankUP Legacy — Game Design Document (Versão Final Completa)

---

## 📌 1. VISÃO GERAL

O RankUP Legacy é um servidor baseado em progressão infinita, onde o jogador evolui através de múltiplos sistemas interligados.

A progressão é estruturada em torno de:

- Sistema de ranks numéricos (0 → 1.000.000+)
- Sistema de prestígio escalável
- Economia dupla (Coins + Aura)
- Mineração ativa (sistema principal)
- Sistema avançado de farm
- Geração passiva (spawners e máquinas)
- Sistemas secundários (pesca, caixas, eventos, pets)

---

### 🎯 Objetivo do jogador

Durante sua jornada, o jogador deve:

- Minerar para gerar Coins e Aura  
- Subir de rank  
- Evoluir sua mina  
- Melhorar sua picareta  
- Utilizar sistemas passivos  
- Aproveitar sistemas secundários  
- Evoluir pets  
- Alcançar prestígios  

---

## 🔁 2. CORE LOOP
MINERAR → GANHAR COINS + AURA → /RANKUP
↓
DESBLOQUEAR MELHORIAS
↓
AUMENTAR EFICIÊNCIA
↓
MINERAR MAIS RÁPIDO
↓
REPETIR

---

## 🏆 3. SISTEMA DE RANKS

### 📊 Estrutura

- Ranks: 0 até 1.000.000+
- Progressão contínua
- Escala exponencial

---

### 💸 Requisitos

- Coins  
- Aura  

---

### 📐 Fórmula

Coins = base × (rank ^ 1.35)  
Aura = base × (rank ^ 1.15)

---

### 🎯 Função

- Controlar progressão  
- Definir dificuldade  
- Liberar conteúdo  

---

## ⭐ 4. SISTEMA DE PRESTÍGIO

### 📏 Fórmula

Limite = Prestígio × 100

---

### 🔁 Reset

- Rank volta para 0  
- Mantém progresso estrutural  

---

### 🚀 Benefícios

- +1% Coins por prestígio  
- +0.5% Aura por prestígio  

---

## 💰 5. ECONOMIA

### 🪙 Coins

Obtido por:

- Mineração  
- Spawners  
- Pesca  
- Eventos  

---

### ✨ Aura

Obtido por:

- Mineração  
- Blocos especiais  
- Spawners  
- Pesca  
- Caixas  

---

## 🧪 6. SISTEMA DE AURA

Chance base:

0,05% por bloco

---

### 💎 Blocos especiais

- Fraco → 1 a 3 Aura  
- Médio → 5 a 10 Aura  
- Forte → 25 a 50 Aura  
- Núcleo → 100 a 250 Aura  

---

## ⛏️ 7. SISTEMA DE MINA

Nível da Mina: 1 até 1000

---

### 🔓 Desbloqueios

A cada 10 níveis:

- Novos blocos  
- Mais lucro  
- Mais Aura  

---

### 🔄 Reset

- 60 segundos  
- Ou 80% minerado  

---

## 🌱 8. SISTEMA DE FARM (AVANÇADO)

O sistema de farm transforma a mineração em algo dinâmico e estratégico.

---

### 🔁 Sistema de Combo

- Cada bloco aumenta combo  
- Parar → perde combo  

#### 📊 Bônus

| Combo | Bônus |
|------|------|
| 10 | +5% |
| 50 | +15% |
| 100 | +30% |
| 250 | +75% |
| 500 | +150% |
| 1000+ | +300% |

---

### 💥 Eventos da Mina

Eventos aleatórios:

- Tempestade → 2x Coins  
- Surto de Aura → mais Aura  
- Explosão → quebra em massa  
- Fenda → spawn raro  

---

### 💎 Qualidade dos blocos

| Tipo | Efeito |
|-----|--------|
| Raro | 2x |
| Épico | 5x |
| Lendário | 10x |
| Mítico | 25x |

---

### ⚡ Overdrive

- +200% Coins  
- +100% Aura  
- Duração: 30s  
- Cooldown: 5min  

---

### ⚙️ Upgrades da mina

- Chance de Aura  
- Bloco raro  
- Reset mais rápido  
- Multiplicador  

---

## 🧰 9. PICARETA EVOLUTIVA

- Permanente  
- Evolutiva  

---

### Encantamentos

Eficiência  
Fortuna  
Inquebrável  

---

### Avançados

Explosão  
Laser  
Chuva  
Tornado  
Buraco Negro  

---

## 🏝️ 10. PLOTS

- 51x51  
- 1 inicial  

Função:

- Farm passivo  
- Construção  

---

## 🧬 11. SPAWNERS

- Geração automática  
- Drops armazenados  

---

### Aura

- 0.25% → básico  
- 2% → supremo  

---

## ⚙️ 12. MÁQUINAS

- Produção automática  
- Evolutivas  

---

## 🐾 13. PETS

Pets são sistemas de melhoria permanente.

---

### Benefícios

- +Coins  
- +Aura  
- +Velocidade  
- +Drops  

---

### Função

- Aumentar eficiência  
- Criar estratégia  

---

## 🎣 14. PESCA

Sistema alternativo.

---

### Nível

1 → 500

---

### XP

Comum → 5  
Raro → 25  
Épico → 75  
Lendário → 500  

---

### Peixes

Comum → 1K  
Raro → 50K  
Épico → 250K  
Lendário → 1M  
Mítico → 5M + Aura  

---

### Tesouros

- Chaves  
- Aura  
- Boosters  
- Pets  

---

## 📦 15. CAIXAS

Tipos:

- Mineração  
- Legacy  
- Prestígio  
- Lendária  
- VIP  

## 🌱 SISTEMA DE FARM (MINERAÇÃO AVANÇADA)

O sistema de farm é o núcleo da progressão ativa do servidor.

Ele foi projetado para ir além da simples mineração, introduzindo mecânicas que recompensam habilidade, consistência e estratégia.

---

### 🔁 1. SISTEMA DE COMBO

O jogador acumula combo ao minerar continuamente.

- Cada bloco quebrado aumenta o combo em +1  
- Parar de minerar por alguns segundos reseta o combo  

---

#### 📊 Efeito do combo

O combo aumenta diretamente os ganhos:

| Combo | Bônus |
|------|------|
| 10 | +5% Coins |
| 50 | +15% Coins |
| 100 | +30% Coins |
| 250 | +75% Coins |
| 500 | +150% Coins |
| 1000+ | +300% Coins e bônus de Aura |

---

### 💥 2. EVENTOS DA MINA

Durante a mineração, eventos aleatórios podem acontecer.

---

#### 🌪️ Tempestade de Blocos
Todos os blocos valem o dobro por alguns segundos.

#### 💎 Surto de Aura
Chance de ganhar Aura aumenta drasticamente.

#### 💣 Explosão Global
Explosões automáticas quebram múltiplos blocos.

#### 🌌 Fenda de Aura
Blocos raros aparecem na mina.

---

### 💎 3. QUALIDADE DOS BLOCOS

Blocos podem surgir com raridades especiais:

| Tipo | Efeito |
|-----|--------|
| Normal | padrão |
| Raro | 2x Coins |
| Épico | 5x Coins |
| Lendário | 10x Coins + Aura |
| Mítico | 25x Coins + alta Aura |

---

### ⚡ 4. OVERDRIVE DA MINA

Modo especial ativado manualmente.

- +200% Coins  
- +100% Aura  
- Aumento na ativação de encantamentos  

Duração: 30 segundos  
Cooldown: 5 minutos  

---

### 🧬 5. INTEGRAÇÃO COM PETS

Os pets influenciam diretamente o farm:

- Aumento de Coins  
- Aumento de Aura  
- Manutenção de combo  
- Ativação de habilidades  

---

### ⚙️ 6. UPGRADES DA MINA

A mina pode ser melhorada com upgrades específicos:

- Aumento de chance de Aura  
- Aumento de chance de blocos raros  
- Redução do tempo de reset  
- Multiplicador base de Coins  
