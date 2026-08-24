## 1. Modelo de Workflow
Adotamos o GitHub Flow. A branch `main` guarda o código final e estável. Novas implementações são desenvolvidas em branches separadas criadas a partir da `main`.

## 2. Estratégia de Branches
- `main`: Código final aprovado.
- `feature/nome-da-feature`: Para criar telas ou partes do site (ex.: `feature/secao-grid`).
- `fix/nome-do-ajuste`: Para correção de bugs.

### Tipos Comuns:
- `feat`: Adição de nova funcionalidade.
- `fix`: Correção de erros.
- `docs`: Alterações na documentação.
- `style`: Ajustes visuais (CSS, cores, layout).
- `refactor`: Reorganização de código sem alterar o funcionamento.

## 3. Política de Commits Semânticos
Estrutura das mensagens: `<tipo>: <descrição>`

### Tipos Inéditos Pedido:
1. `art-asset`: Usado exclusivamente para adicionar ou alterar imagens de obras e autores na pasta `img/`.
2. `exhibit`: Usado para criar ou modificar a estrutura das seções no HTML (Grid, Obra e Autores).
3. `gallery-style`: Usado para estilos específicos da exposição (molduras, grid responsivo de imagens).