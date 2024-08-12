name: Issue Template
description: Template padrão para novas issues.

labels:
  - bug
  - enhancement

body:
  - type: markdown
    attributes:
      value: |
        ### Descrição
        Descreva o problema ou sugestão de melhoria:

  - type: textarea
    id: title
    attributes:
      label: Título da Issue
      description: Resuma a issue em uma frase curta.
      placeholder: "Descreva o título da issue aqui"
      value: ''

  - type: dropdown
    id: priority
    attributes:
      label: Prioridade
      description: Selecione a prioridade da issue.
      options:
        - Low
        - Medium
        - High
      value: Medium

  - type: textarea
    id: steps
    attributes:
      label: Passos para Reproduzir (se aplicável)
      description: Descreva os passos para reproduzir o problema.
      placeholder: "Passo 1, Passo 2, Passo 3..."
      value: ''

  - type: textarea
    id: expected
    attributes:
      label: Resultado Esperado
      description: Descreva o resultado esperado.
      placeholder: "Descreva o que deveria acontecer..."
      value: ''

  - type: textarea
    id: actual
    attributes:
      label: Resultado Real
    attributes:
      label: "Resultado Real"
      description: "Descreva o que realmente aconteceu."
      placeholder: "Descreva o que realmente aconteceu..."
      value: ''

  - type: input
    id: environment
    attributes:
      label: Ambiente
      description: Descreva o ambiente onde o problema ocorreu (sistema operacional, versão do software, etc.).
      placeholder: "Ambiente"
      value: ''
