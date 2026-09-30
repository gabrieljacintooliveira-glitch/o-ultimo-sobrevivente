# 🔫 Jogo 3D de Tiro — Zombie Survival

Jogo de tiro em primeira pessoa (FPS) no navegador, feito com **HTML**, **CSS**, **JavaScript** e **Three.js**.

Sobreviva a **15 ondas** de zumbis, compre cartas de upgrade, equipe armas míticas e derrote o **chefe final**.

---

## ▶️ Como jogar

1. Baixe ou clone o repositório
2. Abra o arquivo `jogo-3d-tiro.html` no navegador (Chrome, Edge, Firefox, etc.)
3. Clique em **INICIAR JOGO**
4. Clique na tela para capturar o mouse (Pointer Lock)

> Não precisa instalar nada. É um único arquivo HTML.

---

## 🎮 Controles

| Tecla / Ação | Função |
|--------------|--------|
| **W A S D** | Andar |
| **Mouse** | Olhar / mirar |
| **Clique esquerdo** (segurar) | Atirar |
| **R** | Recarregar |
| **Espaço** | Pular |

---

## 🧟 Modo de jogo

### Ondas (1 a 15)
- Cada onda traz **mais zumbis**, com mais vida e velocidade
- Ao limpar a onda, abre a **loja de cartas**
- Complete as **15 ondas** e derrote o chefe para vencer

### Tipos de inimigos
| Tipo | Características |
|------|-----------------|
| Zumbi comum | Persegue o jogador |
| 💨 Corredor | Muito rápido |
| 👮 Policial | Armadura, muita vida |
| 🔫 Armado | Atira (só com visão livre) |
| 👑 **Chefe final** | 35.000 HP, escudo, bazuca one-shot |

### Chefe final (onda 15)
- **35.000 de vida**
- **Escudo** (porta de carro): recebe só 25% do dano
- **Bazuca**: foguete com explosão em área — **morte instantânea** se te acertar
- Barra de vida no topo da tela
- **2% de chance** de dropar a bazuca ao morrer

---

## 🃏 Loja de cartas

Entre as ondas você gasta **pontos** em cartas.

### Cartas normais (todas as ondas)
- Vida, cura, dano, velocidade, munição, escudo, etc.

### Cartas míticas de arma (ordem fixa)

| Onda | Carta | Efeito |
|------|--------|--------|
| **5** | 🔫 MP40 Mítica | Tiro rápido, mais dano, 20 munição |
| **10** | 💥 Escopeta + upgrades | Dano alto / upgrades de arma |
| **15** | ☠️ Metralhadora | Tiro insano, 100 munição |
| **15** | 🌟 **SUPER Metralhadora** | A mais forte: tiro extremo, 120 munição, recarga 4,5s |

---

## 🔫 Armas

| Arma | Como obter | Destaque |
|------|------------|----------|
| Pistola | Inicial | Equilibrada |
| MP40 | Carta onda 5 | Rápida |
| Escopeta | Carta onda 10 | Muito dano por tiro |
| Metralhadora | Carta onda 15 | 100 munição |
| SUPER Metralhadora | Carta super mítica onda 15 | A mais forte do jogador |
| Bazuca do chefe | Drop 2% ao matar o chefe | Foguetes em área |

---

## ✨ Power-ups no mapa

Cubos coloridos espalhados pela arena:

- ❤️ Vida  
- 🔫 Munição  
- ⚡ Velocidade  
- 🔥 Tiro rápido  
- 💥 Dano duplo  
- 🛡️ Invencível  

---

## 🛠️ Tecnologias

- **Three.js** (r128) — render 3D
- **Pointer Lock API** — controle de mouse
- HTML / CSS / JavaScript puro (um único arquivo)
- Sistema próprio de colisão, partículas e ondas

---

## 📁 Arquivos

```
jogo-3d-tiro.html   → jogo completo (abra no navegador)
README.md           → este arquivo
```

---

## 🏆 Vitória e restart

Ao derrotar o chefe e terminar a onda 15:

1. Aparece a tela de vitória  
2. Clique em **🔄 JOGAR DE NOVO** para resetar tudo e recomeçar da onda 1  

---

## 📌 Dicas

- Use paredes contra zumbis armados e foguetes do chefe  
- Guarde pontos para a **SUPER Metralhadora** na onda 15  
- Power-up de **escudo** salva do foguete one-shot do chefe  
- Corredores são frágeis, mas muito rápidos — priorize eles  

---

Feito com Three.js para rodar direto no navegador.
