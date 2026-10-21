# Dias Finance — páginas informativas

Páginas públicas de privacidade e exclusão de dados do projeto Agente Financeiro Pessoal. Este repositório contém apenas conteúdo estático; o código financeiro e as configurações AWS ficam no repositório privado da aplicação.

## Contexto de continuidade

Atualizado em **18/10/2026**, fuso `America/Sao_Paulo`.

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

Páginas revisadas para descrever OpenRouter e o modelo OpenAI pela rota Microsoft/Azure quando a interpretação estiver habilitada: texto atual, categorias e rascunho necessário, sem acrescentar perfil ou histórico completo à chamada; validação e cálculos continuam no backend. Texto e categorias podem conter dados pessoais. Roteamento exige ZDR/coleta negada, mas não promete ausência de metadados de cobrança/segurança dos fornecedores. Resultados estruturados e controles de uso no backend não possuem TTL; exclusão integral segue manual e considera esses controles.

Publicação antecipada das informações antes da ativação. Chave, avaliação do modelo real e ativação ainda pendentes no projeto privado. Nenhum dado financeiro ou credencial foi copiado. As notas anteriores descrevem o histórico dos incrementos.

A avaliação do projeto privado detectou que a rota direta OpenAI não atendia à exigência ZDR. Rota fixada em Azure (Microsoft) para o mesmo modelo OpenAI, preservando ZDR/coleta negada e teto de preço; páginas ajustadas antes da ativação. Credencial substituída manualmente pelo responsável; nenhuma chave foi copiada para este repositório. Avaliação fictícia passou 15/15 cenários no modelo real. Implantação da IA e ajuste final confirmados UPDATE_COMPLETE no projeto privado; worker Active/Successful e hash verificado em 16/10/2026 às 15h52min33s de São Paulo. Teste WhatsApp da IA ainda precisa ser relatado pelo proprietário. A chamada inclui também indicador booleano de lançamento recente, sem enviar seus detalhes, para interpretar correções com contexto mínimo.

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

## Conversa contextual — 18/10/2026

Revisão antecipada das páginas para o fluxo contextual aprovado no projeto privado: além da mensagem atual e categorias, a IA pode receber duas trocas curtas, a tarefa incompleta e resumos do gasto selecionado e de até cinco opções do próprio participante. Não acrescentar perfil, identificadores internos ou histórico financeiro completo. Validade lógica de 30 minutos renovada pela interação não equivale a exclusão física automática. A seleção permite referências naturais e opções temporárias; mudanças e exclusões continuam com prévia e confirmação. Observação preserva item/local mesmo com categoria reconhecida. Modelo, rota Azure e limites não são alterados por essa revisão.

Validação fictícia da conversa no projeto privado e testes locais aprovados; implantação contextual ainda pendente nesta publicação. A consulta natural anterior foi confirmada pelo proprietário. Nenhuma conversa, despesa ou identificação de participante foi publicada.

## Ordem de interpretação — 18/10/2026

Após teste de uso, o responsável aprovou interpretar mensagens livres pela IA antes de registrar e impedir fallback financeiro quando o modelo falhar/atingir a cota. Texto/contexto limitado e mesmos fornecedores/tetos; comandos determinísticos seguros continuam locais. Páginas atualizadas antes da correção de produção; teste WhatsApp após a correção ainda pendente. Nenhum dado financeiro ou conversa real foi copiado.

Correção da ordem de interpretação ativada e verificada no projeto privado em 18/10/2026 às 09h47min56s (America/Sao_Paulo), com mesmos modelo e tetos. Testes fictícios da rota numérica e 427 testes locais aprovados; novo teste pelo WhatsApp ainda pendente. A primeira versão apresentou falha no uso real, corrigida após aprovação do responsável; isso não representa garantia de interpretação perfeita. Nenhum gasto real foi excluído pelo agente.


## Controles mensais — 21/10/2026

Páginas atualizadas antes da ativação para descrever exclusão lógica de todos os próprios gastos de um mês/ano, com prévia e confirmação específica, preservando cadastro, categorias e outros meses. Registros anteriores e histórico técnico permanecem; eliminação pessoal continua pelo contato público.

Relatório opcional com dia por participante de 1 a 31, às 9h de São Paulo, sobre o mês anterior; dia inexistente usa o último dia do mês de envio. Checagem diária e controle lógico de entrega por pessoa/período. Alterar só o dia preserva consentimento; pedido de receber autoriza o envio. Mesmos modelo/provedor/tetos. Projeto privado validou fluxos fictícios e DynamoDB Local; implantação dos controles ainda pendente nesta publicação. Nenhum cadastro, conversa, gasto ou credencial foi publicado.
