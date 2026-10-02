# ISYN Co. | Briefing Inteligente

Aplicação web da ISYN Co. para coletar o briefing estratégico de clientes e transformá-lo no **Cérebro do Cliente**.

**Versão publicada (claude.ai):** https://claude.ai/artifact/3sYmNzvXB95bN7fSXwZjG8

## O que tem

- **Briefing em 8 etapas:** marca, posicionamento, público, personalidade, objetivos, conteúdo, referências e operação. Salvamento automático e retomada de onde parou.
- **Tela de conclusão:** "Agora começa a estratégia."
- **Central Estratégica** (só equipe ISYN): lista de clientes por status, respostas completas e o botão **Gerar Cérebro**, que monta as 20 seções do Cérebro do Cliente sem inventar dados. O que faltar aparece como `[NECESSÁRIO CONFIRMAR]`.

## Arquivos

| Arquivo | Conteúdo |
| --- | --- |
| `index.html` | A aplicação inteira (HTML, CSS e JS em um arquivo, logo embutida) |
| `assets/isyn-logo.png` | Logo ISYN Co. com fundo transparente |

## Onde roda

A aplicação usa recursos do claude.ai (banco de dados compartilhado, identificação do usuário e geração com o Claude). Por isso o fluxo completo funciona na versão publicada no claude.ai.

Aberto direto pelo `index.html` (ou em qualquer hospedagem estática), o briefing funciona em modo local: as respostas ficam salvas no navegador e, ao final, o cliente recebe um código para enviar à ISYN. A Central Estratégica e o Gerar Cérebro não aparecem nesse modo.

## Próximos passos

Para atender clientes externos em escala: backend próprio (banco de dados e autenticação) e integração direta com a API do Claude para gerar o Cérebro. Depois, os módulos seguintes da plataforma: Estratégia → Conteúdo → Aprovação → Métricas.
