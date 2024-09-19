# Guia de Padronização de Branches

Neste projeto, utilizamos um padrão de branches para facilitar o desenvolvimento e o controle de versões. As branches
devem seguir um formato consistente para manter o histórico claro e compreensível.

## Estrutura da Branch
Cada branch deve seguir o seguinte formato:

`<tipo>/<nome-da-task>`

## Exemplo de branch válida

`feat/add-jwt-authentication`

### Tipos de Branches
As branches devem começar com um dos seguintes tipos, conforme o propósito da tarefa:

- feat: Para desenvolvimento de novas funcionalidades.
  - Exemplo: feat/add-payment-method


- fix: Para correções de bugs.
  - Exemplo: fix/correct-login-error


- docs: Para atualizações na documentação.
  - Exemplo: docs/update-readme


- style: Para ajustes de formatação e estilo, sem alterar a funcionalidade do código.
  - Exemplo: style/apply-css-fixes


## Regras Gerais
1. Tipo de branch: A branch deve começar com o tipo de mudança, como feat, fix, docs, etc.
2. Nome da task: O nome da task deve ser descritivo e em inglês, separado por hífens (-), sem espaços ou caracteres
especiais.
3. Linguagem: O nome da branch deve ser sempre em inglês.

Com esse padrão de branches, mantemos o fluxo de trabalho organizado e consistente, facilitando o desenvolvimento
colaborativo e a gestão de releases no projeto.
