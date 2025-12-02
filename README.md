
  # Proposta Visual — Catálogo de Peças Automotivas

  > Proposta visual para licitação (Compras.gov) — Município de Santa Helena

  Este repositório contém a proposta visual (protótipo e implementação front-end) do *Catálogo de Peças Automotivas*, preparada para apresentação em processo licitatório ao Compras.gov pelo Município de Santa Helena.


  ## Resumo do projeto

  - Objetivo: Apresentar um catálogo de peças automotivas com interface clara, acessível e responsiva, permitindo consulta de peças, criação de orçamentos e gestão de clientes.
  - Público-alvo: Usuários municipais, técnicos de manutenção e profissionais de compras do município.
  - Entregáveis: protótipo (Figma), código front-end (React + Vite), kit de componentes (UI), documentação de uso e instruções de implantação.

  ## Escopo da proposta

  - Landing / catálogo de peças
  - Páginas para Clientes, Orçamentos, Relatórios e Configurações
  - Componentes reutilizáveis (UI Kit) para acelerar integrações
  - Documentação para validação e entrega
  - Observações de acessibilidade (WCAG) e performance

  ## Critérios de aceitação (sugestão)

  1. Layout responsivo para mobile, tablet e desktop
  2. Compatibilidade com browsers modernos (Chrome, Edge, Firefox)
  3. Bom desempenho (tempo de carregamento e navegação) em conexões lentas
  4. Requisitos mínimos de acessibilidade (contraste, navegação por teclado)
  5. Entrega de código-fonte, design em Figma e assets (SVG/PNG/ICONS)

  ## Entregáveis (detalhado)

  - Protótipo interativo no Figma (telas navegáveis)
  - Código front-end (React + TypeScript) pronto para deploy estático
  - Kit de componentes reutilizáveis (pasta `src/ui`)
  - Documentação técnica (README, Guidelines, Attributions)
  - Recursos gráficos e exportações finais (SVGs, PNGs)

  ## Arquitetura técnica (resumo)

  - Framework: React + Vite
  - Estilo: Tailwind CSS (utilizando `tailwind-merge` e classes utilitárias)
  - Componentes UI: implementados em `src/ui` e `components`
  - Dados de exemplo: `src/data/mockData.ts`

  ## Como visualizar a proposta (local)

  Requisitos:
  - Node.js (versão 18+ recomendada)

  Passos:
  ```powershell
  npm install
  npm run dev
  # Abra http://localhost:5173 no seu navegador (Vite padrão)
  ```

  ## Deploy para Vercel (opcional)

  O projeto está preparado para deploy estático no Vercel. Para garantir deploy automático:

  - O `vite.config.ts` foi ajustado para gerar saída em `dist`.
  - Um arquivo `vercel.json` foi adicionado para configurar a saída do build em `dist`.

  Recomendações (caso faça manualmente no painel do Vercel):

  1. No painel Vercel, escolha o repositório `bonacciniWd/Autopecas-PRO`.
  2. Build Command: `npm run build`.
  3. Output Directory: `dist`.
  4. Deploy.

  Observação: Se preferir manter `build` como saída, ajuste a opção "Output Directory" no painel do projeto na Vercel para `build` (ao invés de `dist`).

  ## Como revisar/avaliar

  - Use o protótipo no Figma para validar o fluxo
  - Valide páginas-chave: catálogo, busca, página de peça, orçamentos e relatórios
  - Teste em dispositivos móveis e navegadores
  - Revise a documentação, guidelines e attributions

  ## Acessibilidade e desempenho

  - A proposta inclui considerações de acessibilidade (WCAG 2.1 AA) — contraste de cores, navegação por teclado, roles ARIA nos componentes onde necessário.
  - Recomenda-se rodar uma auditoria Lighthouse para validar desempenho e acessibilidade em cada entrega.

  ## Licenciamento, propriedade intelectual e entrega para licitação

  - Este repositório contém a proposta visual. O licitante (fornecedor) entregará o código-fonte e os arquivos finais ao Município mediante assinatura de contrato.
  - Recomendamos incluir cláusula contratual que transfira propriedade intelectual e garanta a cessão de direitos de uso do material para o Município de Santa Helena.
  - Para detalhes contratuais, consulte o setor jurídico do Município — o conteúdo aqui é uma sugestão técnica e não substitui orientação jurídica.



  ## Observações finais

  - O design e código são entregáveis mínimos para a licitação; ajustes técnicos, integrações com sistemas municipais e serviços de backend devem ser negociados à parte.
  - Para suporte à implantação, podemos fornecer pacotes de treinamento e documentação técnica adicional sob demanda.

  ---

  Se quiser, posso adaptar o texto de 'Critérios de aceitação', expandir a seção de 'Entregáveis' com listas de arquivos finais a serem entregues, ou gerar uma proposta formal em PDF pronta para a licitação. Diga o que prefere a seguir.
  
