# 🏎️ Simulador de Corridas do Mario Kart com Node.js | DIO

Este repositório contém **duas versões** do simulador de corrida inspirado no universo do *Mario Kart*:

- A **versão original**, desenvolvida no desafio da DIO.  
- A **minha versão expandida**, com melhorias, mais lógica, mais personagens e um sistema muito mais completo.

---

## 🍄 Projeto Original da DIO  
![Mario](./docs/mario.gif)                                  

O projeto original da DIO propõe a criação de um simulador simples de corrida entre **dois personagens**, utilizando atributos básicos e rodadas aleatórias.

### 🎯 **Objetivo do Projeto Original**
Criar uma corrida com regras simples, onde:
- Dois players competem.
- A pista tem 5 rodadas.
- Cada rodada sorteia um tipo de bloco:
  - **Reta** → usa *Velocidade*
  - **Curva** → usa *Manobrabilidade*
  - **Confronto** → usa *Poder* (quem perde pode perder 1 ponto)
- O dado é somado ao atributo correspondente.
- A pontuação não pode ser negativa.
- Quem tem mais pontos no final, vence.

### 👥 **Personagens Disponíveis**
| Personagem   | Velocidade | Manobrabilidade | Poder |
|--------------|------------|-----------------|-------|
| Mario        | 4          | 3               | 3     |
| Peach        | 3          | 4               | 2     |
| Yoshi        | 2          | 4               | 3     |
| Bowser       | 5          | 2               | 5     |
| Luigi        | 3          | 4               | 4     |
| Donkey Kong  | 2          | 2               | 5     |

---

# 🧪 Minhas Contribuições (Versão Aprimorada)  
![Yoshi](./docs/yoshi.gif)

Além da lógica da DIO, desenvolvi uma versão **muito mais robusta**, permitindo corridas completas entre *todos* os personagens, exibição de ranking e diversos ajustes inteligentes.

### ✨ **Melhorias Implementadas**
- 🚀 **Corrida com TODOS os personagens ao mesmo tempo**  
- 🏆 **Ranking parcial exibido a cada rodada**  
- 🎲 **Sistema universal que funciona com qualquer número de competidores**  
- 📊 **Feedbacks no terminal mais visuais**  
- 📁 **Código separado da versão original em um arquivo próprio (`minhas_contribuicoes.js`)**  
- 🔧 **Lógica mais organizada e escalável**

---

# 📂 Estrutura do Projeto

```
mario-kart-sim/
│
│
├── src/
│   ├── index.js                 # Versão original da DIO
│   ├── minhas_contribuicoes.js  # Minha versão expandida

```

---

# 🚀 Tecnologias Utilizadas

- JavaScript  
- Node.js  

---

# ▶️ Como Executar o Projeto

### **Clone o repositório**
```
git clone https://github.com/iAiBel/mario-kart-sim.git
```

### **Acesse o diretório**
```
cd mario-kart-sim/src
```

### **Execute a versão original**
```
node index.js
```

### **Execute a minha versão com melhorias**
```
node minhas_contribuicoes.js
```

---

# 💡 Observações

Não tive dificuldades na lógica básica porque já possuo conhecimento em SQL e organização de dados pela pós-graduação - isso ajudou muito a estruturar atributos, regras e validações da corrida.

---

# 🏁 Resultado Final

Um simulador totalmente funcional, com lógica expandida, ranking dinâmico, múltiplos competidores e maior previsibilidade.  
A versão aprimorada permite testar cenários mais complexos e explorar o equilíbrio entre atributos dos personagens.

