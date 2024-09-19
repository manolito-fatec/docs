# Guia de Padronização de Commits

Neste projeto, seguimos a convenção de commits baseada no Conventional Commits, utilizando Gitmoji para facilitar a
identificação visual do tipo de mudança. Todos os commits devem ser feitos em inglês.

## Estrutura do Commit

Cada commit deve seguir o seguinte formato:

`<gitmoji> <tipo>: <descrição>`

### Exemplo de commit válido

`✨ feat: add JWT support for user login`

### Tipos de Commits

Os tipos de commit seguem a especificação do Conventional Commits, com algumas adições específicas para o projeto:

- feat (✨): Adição de uma nova funcionalidade.
    - Exemplo: ✨ feat: add PayPal integration


- fix (🐛): Correção de um bug.
    - Exemplo: 🐛 fix: correct user profile image upload


- docs (📝): Alterações na documentação.
    - Exemplo: 📝 docs: update installation instructions


- style (🎨): Alterações que não afetam o comportamento do código (espaços em branco, formatação, etc.).
    - Exemplo: 🎨 style: apply eslint rules to project

## Regras Gerais

1. **Linguagem**: Todos os commits devem ser feitos em inglês.
2. **Gitmoji**: Cada commit deve iniciar com o emoji correspondente ao tipo de mudança.
3. **Descrição clara**: A descrição deve ser curta e objetiva, explicando a mudança feita no código.

Com esse padrão, garantimos que o histórico de commits será claro, padronizado e fácil de entender por qualquer membro
da equipe, além de facilitar o rastreamento de mudanças no projeto.