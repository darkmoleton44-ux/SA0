# PLAYER - Componentes de Personagem

Este diretório contém os ativos visuais necessários para a criação e customização de personagens no SA0.

## 📋 Estrutura de Arquivos

### Personagens Base (`char_*_humn_*.png`)
Arquivos que representam os **personagens humanos em estado parado** na tela de criação de personagem.

- **Nomenclatura**: `char_a_p1_0bas_humn_v##.png`
  - `char` = Character (Personagem)
  - `a` = Tipo de personagem
  - `p1` = Posição 1
  - `0bas` = Base (estado parado)
  - `humn` = Humano
  - `v##` = Versão (v00, v01, v02, etc.)

**Uso**: Estes são os modelos padrão dos personagens que ficam **imóveis/parados** durante o processo de criação e personalização. Eles servem como base visual para que o jogador veja como fica seu personagem.

**Total de variações**: 11 versões (v00 a v10)

---

### 📁 Pasta `hairs/`
Contém os **estilos de cabelo** disponíveis para customizar o personagem durante a criação.

- Cada arquivo representa um estilo diferente de cabelo
- O jogador pode escolher entre os cabelos disponíveis nesta pasta para definir a aparência do seu personagem
- **Função**: Possibilita variedade visual na criação de personagens

---

### 📁 Pasta `cloths/`
Contém as **roupas e vestuário** disponíveis para customizar o personagem durante a criação.

- Cada arquivo representa um conjunto de roupas diferente
- O jogador pode escolher entre as roupas disponíveis nesta pasta para definir o look do seu personagem
- **Função**: Permite personalização de vestuário na criação de personagens

---

## 🎨 Fluxo de Criação de Personagem

```
1. Personagem Base (humn) é exibido parado
   ↓
2. Jogador escolhe CABELO da pasta (hairs/)
   ↓
3. Jogador escolhe ROUPA da pasta (cloths/)
   ↓
4. Personagem é criado com a combinação escolhida
```

---

## 📝 Notas
- Os arquivos de personagem base mantêm o personagem em estado **parado/idle** para melhor visualização durante a criação
- A customização ocorre através da seleção de arquivos dos diretórios `hairs/` e `cloths/`
- Todos os assets são em formato PNG para suportar transparência
