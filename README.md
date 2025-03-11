# 🩸 Blood Hunt - O Jogo de Assassinos no Discord

## 📖 Sobre o Bot
**Blood Hunt** é um bot de RPG para Discord onde os jogadores assumem o papel de assassinos caçando uns aos outros e NPCs. O sangue derramado se torna a moeda do jogo, permitindo a compra de armas, equipamentos e melhorias. O jogo possui um sistema de evolução baseado em contratos e missões, além de um ranking para os assassinos mais letais. Há também um sistema VIP, oferecendo vantagens exclusivas e gerando receita para o servidor.

## 🎭 Classes de Assassinos
Os jogadores podem escolher entre diferentes classes de assassinos, cada uma com habilidades únicas:

### 🔪 **O Fantasma**
- **Habilidade Passiva:** +10% de esquiva em batalhas.
- **Habilidade Ativa:** "Desaparecer" – Fica imune a ataques por 1 rodada (Cooldown: 3 caçadas).

### 🪓 **O Açougueiro**
- **Habilidade Passiva:** +15% de dano em ataques corpo a corpo.
- **Habilidade Ativa:** "Massacre" – O próximo ataque causa dano dobrado (Cooldown: 5 caçadas).

### 🕷 **A Viúva Negra**
- **Habilidade Passiva:** +5% de roubo de sangue ao atacar.
- **Habilidade Ativa:** "Veneno Mortal" – O alvo perde 100 Sangue a cada turno por 3 turnos (Cooldown: 4 caçadas).

## 📜 Planejamento dos Comandos do Blood Hunt

## 1. Comandos de Jogo 🎮

### `/caçar @usuário`
- **Descrição:** Ataca outro jogador para roubar sangue.
- **Requisitos:** Deve ter pelo menos uma arma equipada.
- **Cooldown:** 5 minutos.
- **Resultado:** Se vencer, rouba até 20% do sangue do alvo.

💬 **Exemplo de resposta:**
> 🔪 **@Player1 emboscou @Player2 e coletou 250 Sangue!**  
> 🩸 **Sangue Atual:** 3.500  

---

### `/caçar npc`
- **Descrição:** Ataca um alvo gerado pelo bot.
- **Requisitos:** Custa 100 Sangue para iniciar uma caçada.
- **Resultado:** O jogador pode ganhar sangue e itens raros.

💬 **Exemplo de resposta:**
> ☠️ **Você caçou um mercenário solitário e coletou 500 Sangue!**

---

### `/ranking`
- **Descrição:** Exibe os assassinos mais perigosos do servidor.

---

### `/contrato aceitar`
- **Descrição:** Pega um contrato aleatório para assassinar um alvo NPC.
- **Resultado:** O jogador recebe uma missão e pode ganhar sangue ao completar.

---

### `/contrato concluir`
- **Descrição:** Conclui a missão e recebe a recompensa.

---

## 🔧 Mecânica de Evolução
Os jogadores podem subir de nível e desbloquear novas habilidades ao acumular sangue e concluir contratos.
- **Níveis:** Cada 10.000 Sangue coletado = 1 nível.
- **Benefícios:** Novas habilidades e melhorias nas armas.

## ⚔️ Sistema de Contratos e Missões
Os contratos são desafios que garantem recompensas maiores.
- **Missões Simples:** Eliminando NPCs específicos.
- **Contratos de Caçada:** Encontrar jogadores específicos e derrotá-los.
- **Missões Especiais:** Eventos semanais com desafios únicos.

## 🛒 Itens e Equipamentos
Itens que podem ser adquiridos na loja:

```
🩸 LOJA DO MERCADO NEGRO 🩸
1️⃣ Punhal Envenenado - 500 Sangue
2️⃣ Revólver Silenciado - 1.200 Sangue
3️⃣ Máscara do Carniceiro - 2.500 Sangue
```

## 4. Comandos VIP (Monetização) 💎
### `/vip comprar`
- **Descrição:** Mostra os benefícios da versão VIP e permite a compra.

💬 **Exemplo de resposta:**
```
💎 VIP BLOOD HUNT 💎
✅ +10% de Sangue em caçadas.
✅ Acesso exclusivo a skins lendárias.
✅ Cooldown reduzido em 50%.
💲 Preço: R$ 19,90/mês.
```
