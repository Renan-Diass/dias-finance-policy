# Dias Finance — páginas informativas

Páginas públicas de privacidade e exclusão de dados do projeto Agente Financeiro Pessoal. Este repositório contém apenas conteúdo estático; o código financeiro e as configurações AWS ficam no repositório privado da aplicação.

## Contexto de continuidade

Atualizado em **16/10/2026**, fuso `America/Sao_Paulo`.

- O responsável escolheu a identificação pública **Dias Finance** e o contato exibido nas páginas.
- Páginas revisadas para o incremento de despesas por texto: valores/descrições/categorias/datas, confirmações e contexto persistido. Incremento implantado em 16/10/2026; teste real de despesa ainda pendente. Sem chamadas IA, integração bancária ou movimentação financeira.
- A exclusão de dados é solicitada pelo contato público e tratada manualmente; não há callback automático implementado.
- App Meta publicado e ida e volta de conexão confirmada pelo proprietário em 15/10/2026; teste real de despesas depende do incremento.
- Conteúdo enviado ao GitHub por commit e push. GitHub Pages ativado em main/raiz, com HTTPS obrigatório; o agente confirmou HTTP 200 e conteúdo esperado nas três URLs públicas em 15/10/2026. A revisão de 16/10 atualiza o escopo de tratamento; o agente confirmou HTTP 200 e novo conteúdo nas três URLs após o push.

## Piloto de cinco amigos — 16/10/2026

Páginas revisadas para o piloto com proprietário e até cinco amigos, cadastro aberto com nome/e-mail antes do uso financeiro, categorias por participante e resumos do mês. A identificação do acesso vem do WhatsApp; e-mail é validado só por formato e não é credencial. Etapas/respostas de cadastro podem permanecer armazenadas mesmo sem conclusão; exclusão é solicitada ao contato público e administrada manualmente. Cadastros, despesas e categorias não devem ser copiados para este repositório.

Deploy do piloto confirmado no projeto privado em 16/10/2026; teste real do cadastro/resumo pelo WhatsApp ainda pendente. Textos estáticos são publicados antecipadamente para descrever o novo tratamento antes da ativação. As notas anteriores são histórico do incremento de despesas para proprietário.

## Evolução financeira — 16/10/2026

Usuário confirmou cadastro e resumo no WhatsApp. Nova revisão das páginas descreve observações, gerenciamento de categorias, consultas detalhadas e correções/exclusões lógicas. A exclusão integral dos dados pessoais permanece manual e distinta de remover um gasto dos totais.

Relatório mensal opcional: autorização por participante, fechamento anterior no dia 1 às 9h de São Paulo, cancelamento pelo chat e modelo Meta aprovado antes de qualquer disparo. Modelo submetido e observado como PENDING/UTILITY durante a preparação. Backend confirmado implantado em 16/10/2026; agendamento mensal habilitado e preferências do proprietário autorizadas por solicitação explícita. Modelo Meta ainda PENDING na última consulta, sem relatório enviado. Amigos devem autorizar pelo chat. Nenhum cadastro, telefone de participante, dado financeiro real ou credencial foi incluído neste repositório.

## Interpretação assistida por IA — 16/10/2026

Páginas revisadas para descrever OpenRouter e OpenAI quando a interpretação estiver habilitada: texto atual, categorias e rascunho necessário, sem acrescentar perfil ou histórico completo à chamada; validação e cálculos continuam no backend. Texto e categorias podem conter dados pessoais. Roteamento exige ZDR/coleta negada, mas não promete ausência de metadados de cobrança/segurança dos fornecedores. Resultados estruturados e controles de uso no backend não possuem TTL; exclusão integral segue manual e considera esses controles.

Publicação antecipada das informações antes da ativação. Chave, avaliação do modelo real e ativação ainda pendentes no projeto privado. Nenhum dado financeiro ou credencial foi copiado. As notas anteriores descrevem o histórico dos incrementos.

## Arquivos

- `index.html`: apresentação do projeto e navegação.
- `privacidade.html`: política de privacidade.
- `exclusao.html`: instruções de exclusão.
- `styles.css`: apresentação responsiva, sem scripts ou rastreamento próprio.
- `.nojekyll`: disponibilização de arquivos estáticos sem processamento Jekyll.

## Ativar GitHub Pages

No repositório, abrir **Settings → Pages → Build and deployment** e selecionar **Deploy from a branch**, branch **main**, pasta **/(root)**, e salvar. Aguardar o deploy e verificar acesso HTTPS sem login.

URLs públicas verificadas com HTTP 200:

- https://renan-diass.github.io/dias-finance-policy/
- https://renan-diass.github.io/dias-finance-policy/privacidade.html
- https://renan-diass.github.io/dias-finance-policy/exclusao.html

Usar as duas últimas URLs nos campos de Política de Privacidade e URL de instruções de exclusão de dados da Meta; manter a modalidade de instruções, pois não há callback automático de exclusão. Aprovação/publicação do app depende também dos demais requisitos apresentados pela conta.

## Manutenção

Os textos-fonte e o gerador ficam no projeto financeiro, em `docs/publicacao` e `scripts/build-policy-pages.mjs`. Para mudanças futuras, revisar o funcionamento real, atualizar os textos, executar `npm run pages:build` na cópia que contém o gerador e sincronizar apenas os cinco arquivos estáticos. Não publicar `.env`, tokens, dados de mensagens, artefatos AWS ou documentação interna.
