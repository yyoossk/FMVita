# FMVita

FMVita é um fork do **VitaShell** com foco em:
- Suporte a GIF animado e PNG como background
- Interface semi-transparente com backgrounds de imagem
- Correções de touch nos botões de confirmação (Yes/No)
- Sistema de Undo (recuperação de exclusão)
- Visualização em colunas (Column Mode)
- Remoção do sistema de lixeira (exclusão permanente)
- Tema escuro e cores ajustadas via `colors.txt`
- Scroll clipping corrigido
- Integração com `ux0:FMVita/` como diretório padrão de dados

## Comparação com VitaShell original

| Recurso | VitaShell | FMVita |
|---------|-----------|--------|
| Background animado | GIF apenas | GIF + PNG |
| Interface semi-transparente | Não | Sim (com bg de imagem) |
| Lixeira | Sim | Removida (exclui direto) |
| Undo | Não | Sim |
| Column Mode | Finder View | Column View |
| Tema escuro integrado | Sim | Sim + helpers de tema |

## Building

```bash
mkdir build && cd build && cmake .. && make
```

Requer [vitasdk](https://github.com/vitasdk).

## Créditos

- **TheFloW** — VitaShell original
- **Team Molecule** — HENkaku
- **xerpi** — ftpvitalib e vita2dlib
- **WolffsRoom** — modificações FMVita
