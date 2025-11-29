# Projeto: Formulário de Matrículas

Aplicação front-end simples de um formulário de matrícula para a escola "Estrelas do Amanhã". É um projeto estático composto por HTML, CSS e assets (ícones e imagens).

## Visualização
Abra [index.html](index.html) no navegador (duplo clique no arquivo ou use um servidor estático).

## Estrutura principal
- `index.html` — marcação da página principal.
- `styles/` — estilos:
  - `styles/index.css` — ponto de entrada que importa os demais estilos.
  - `styles/global.css` — variáveis CSS e reset/global.
  - `styles/layout.css` — grid principal e layout.
  - `styles/forms.css` — estilos de formulário (importa `styles/fields/index.css`).
  - `styles/fields/index.css` — estilos de campos (importa `styles/fields/droparea.css`).
  - `styles/fields/droparea.css` — estilo do componente de upload (dropzone).
- `assets/` — ícones, logo e ilustrações usadas pela página.

## Notas de implementação
- Variáveis de tema e tipografia estão em [`styles/global.css`](styles/global.css).
- O arquivo [`styles/index.css`](styles/index.css) importa os estilos em ordem: global → layout → forms.
- O campo de upload usa markup em [`index.html`](index.html) e estilos em [`styles/fields/droparea.css`](styles/fields/droparea.css).
- Inputs com `disabled` e validação básica estão estilizados em [`styles/fields/index.css`](styles/fields/index.css).

## Como contribuir
1. Crie uma branch com sua feature/fix.
2. Faça commits pequenos e claros.
3. Abra um PR descrevendo a mudança.

## Sugestões futuras
- Adicionar validação JS no formulário.
- Suporte a servidor local para testes (ex: Live Server ou `npx serve`).
- Melhorar acessibilidade (labels, aria-attributes, foco visível).

## Licença
Sem licença definida — adicionar se necessário.
