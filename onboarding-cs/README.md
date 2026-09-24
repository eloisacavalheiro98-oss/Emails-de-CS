# Sequência de e-mails — Onboarding CS

16 e-mails de onboarding e boas-vindas, no estilo visual da newsletter (Inter, paleta Razonet). Placeholder `[Nome]` para personalização.

## 1. Ativação da conta (D+0 a D+17)

Enviar em sequência para todo cliente novo contratante, na ordem abaixo.

| Ordem | Arquivo | Quando enviar | Assunto sugerido |
|---|---|---|---|
| 1 | `onboarding-00-boas-vindas.html` | D+0 a D+1 | Boas-vindas à Razonet! Seu acesso já está liberado |
| 2 | `onboarding-01-cofre-documentos-fiscais.html` | D+8 a D+9 | Como funciona o Cofre de Documentos Fiscais |
| 3 | `onboarding-02-prolabore-folha.html` | D+12 a D+13 | Pró-labore e Folha de Pagamento: como lançar |
| 4 | `onboarding-03-contabil-despesas.html` | D+14 a D+15 | Gestão Contábil e Despesas: como registrar |
| 5 | `onboarding-04-distribuicao-lucros.html` | D+16 a D+17 | Distribuição de Lucros isenta de IR: como funciona |
| 6a | `onboarding-05-notas-fiscais-impostos-opcao1.html` | Após abertura/desenquadramento (versão completa) | Emissão de Notas e o seu Imposto (DAS) |
| 6b | `onboarding-05-notas-fiscais-impostos-opcao2.html` | Após abertura/desenquadramento (versão resumida — alternativa à opção 1) | Seu CNPJ está ativo: notas e DAS |
| 7 | `onboarding-rotinas-mensais.html` | Reforço periódico do calendário mensal | Seu calendário mensal com a Razonet |

## 2. Boas-vindas por tipo de entrada

Disparo único, conforme o tipo de cadastro do cliente (mutuamente exclusivos).

| Arquivo | Quando enviar | Assunto sugerido |
|---|---|---|
| `boas-vindas-constituidas.html` | Empresa recém-constituída, CNPJ pronto | Seu CNPJ está pronto! |
| `boas-vindas-desenquadradas.html` | Empresa desenquadrada para o Simples Nacional | Agora você faz parte do Simples Nacional! |
| `boas-vindas-mei-cliente-novo.html` | Cliente novo MEI | Seja bem-vindo à Razonet! |
| `migracao-mei-para-simples.html` | Cliente contratou migração de MEI para Simples Nacional | Vamos migrar seu MEI para o Simples Nacional |
| `boas-vindas-sem-cnpj.html` | Cliente sem CNPJ, abertura de empresa em andamento | Vamos abrir a sua empresa |
| `troca-de-contabilidade.html` | Cliente migrando de outra contabilidade | Bem-vindo(a) à Razonet! |

## 3. Cross-sell / apresentação de serviços

Podem ser enviados a qualquer momento do relacionamento, independente da etapa de onboarding.

| Arquivo | Assunto sugerido |
|---|---|
| `juridico-onboarding.html` | Proteção jurídica para o seu negócio |
| `asaas-btg-onboarding.html` | Centralize suas cobranças e sua conta PJ |

## Pendências de conteúdo

- `migracao-mei-para-simples.html`: incluir o link/anexo do "Guia de Desenquadramento" mencionado no conteúdo original (marcado com comentário `TODO` no HTML).
