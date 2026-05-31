# Game Assets Structure

Organização de assets do jogo.

## Estrutura de Pastas

```
/Player/        - Sprites do personagem jogável
/Enemies/       - Sprites de inimigos
/UI/            - Elementos de interface (menus, botões, etc)
/Tilesets/      - Tiles e backgrounds
/Weapons/       - Sprites de armas
/Skills/        - Sprites de habilidades e efeitos
/NPCs/          - Sprites de NPCs
```

## Convenções de Nomenclatura

- Use nomes descritivos em inglês
- Use hífens para separar palavras: `idle-animation.png`
- Inclua dimensões se relevante: `16x32-idle-sheet.png`
- Para sheet animations: `{name}-sheet.png`

## Próximas Etapas

⚠️ **Importante**: Os sprite sheets originais ainda estão na raiz do repositório:
- `16x32 Idle-Sheet.png`
- `16x32 Jump-Sheet.png`
- `16x32 Run-Sheet.png`
- `16x32 Walk-Sheet.png`

Para completar a organização, você precisa:
1. Fazer download dos arquivos da raiz
2. Fazer upload deles na pasta `/Player/` com os nomes reformatados
3. Deletar os originais da raiz

Ou você pode fazer isso diretamente pela interface do GitHub.