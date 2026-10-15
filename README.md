# Dias Finance — páginas informativas

Páginas públicas de privacidade e exclusão de dados do projeto Agente Financeiro Pessoal. Este repositório contém apenas conteúdo estático; o código financeiro e as configurações AWS ficam no repositório privado da aplicação.

## Contexto de continuidade

Atualizado em **15/10/2026**, fuso `America/Sao_Paulo`.

- O responsável escolheu a identificação pública **Dias Finance** e o contato exibido nas páginas.
- O backend atual apenas confirma a conexão com o WhatsApp; não há interpretação por IA nem registro de despesas por texto habilitados.
- A exclusão de dados é solicitada pelo contato público e tratada manualmente; não há callback automático implementado.
- O teste de exemplo Meta → webhook AWS foi confirmado; mensagem real de ida e volta e publicação do app Meta continuam pendentes de validação.
- Conteúdo enviado ao GitHub por commit e push. GitHub Pages ativado em main/raiz, com HTTPS obrigatório; o agente confirmou HTTP 200 e conteúdo esperado nas três URLs públicas em 15/10/2026. Publicação do app Meta e teste real de mensagens continuam pendentes.

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
