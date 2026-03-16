# 🃏 Super Trunfo - Capitais Brasileiras
## 📋 Sobre o Projeto
Este é um jogo **Super Trunfo** desenvolvido em C, onde você pode comparar as 27 capitais brasileiras (incluindo Brasília) em diversos atributos. O jogo carrega os dados de um arquivo JSON e permite confrontos emocionantes entre as capitais!

### 🎯 Objetivo do Jogo

O objetivo é simples: escolha duas capitais e um atributo para comparar. A capital com o melhor atributo vence a rodada! Perfeito para testar seus conhecimentos sobre as capitais do Brasil.

## ✨ Funcionalidades

- ✅ **27 capitais brasileiras** completas
- ✅ **7 atributos diferentes** para comparar
- ✅ **Leitura de dados via JSON** (fácil de modificar)
- ✅ **Suporte completo a acentuação** (UTF-8)
- ✅ **Interface amigável** no terminal
- ✅ **Cálculo automático** de densidade demográfica e PIB per capita
- ✅ **Organização por regiões** (Norte, Nordeste, Centro-Oeste, Sudeste, Sul)

## 📊 Atributos Comparáveis

| # | Atributo | Critério |
|---|----------|----------|
| 1 | População | Maior vence |
| 2 | Área | Maior vence |
| 3 | PIB | Maior vence |
| 4 | Pontos Turísticos | Maior vence |
| 5 | IDH | Maior vence |
| 6 | Densidade Demográfica | **Menor** vence |
| 7 | PIB per capita | Maior vence |

## 🚀 Como Executar

### Pré-requisitos

- Compilador C (GCC recomendado)
- Git (opcional, para clonar)

### Passo a Passo
```bash
# 1. Clone o repositório
git clone https://github.com/devWillvasconcelos/super-trunfo.git

# 2. Entre no diretório
cd super-trunfo

# 3. Compile o programa
gcc super_trunfo.c -o super_trunfo

# 4. Execute
./super_trunfo     # Linux/Mac
# ou
super_trunfo.exe   # Windows
