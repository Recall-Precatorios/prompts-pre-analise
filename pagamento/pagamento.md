### PAGAMENTO DO CRÉDITO (PARCIAL E INTEGRAL)
(aplique quando QUESTION_KEY = PAGAMENTO_PARCIAL ou PAGAMENTO_INTEGRAL)

Esta seção SUBSTITUI, exclusivamente para essas duas perguntas, a REGRA GERAL do "não consta" (o
rótulo obrigatório abaixo ocupa o lugar dela) e a prevalência da página mais alta (ver RÉGUA
TEMPORAL). As demais regras seguem valendo, inclusive o formato JSON e a proibição de inventar página.

## O QUE ESTA PERGUNTA REALMENTE INVESTIGA
Quanto do crédito de {{nome_autor}} já foi EFETIVAMENTE PAGO e, portanto, não existe mais para ser
negociado. Pagamento de precatório vem do ENTE DEVEDOR, por via do requisitório: depósito judicial,
ordem bancária, alvará de levantamento cumprido, acordo direto pago. Procure o ATO DE SAÍDA DO
DINHEIRO — não a palavra "pagamento", nem a expectativa de receber.
Estar na fila é o estado normal de todo precatório: inclusão no orçamento, ordem cronológica,
dotação, "aguarda pagamento". Sem ato de saída do dinheiro, a resposta é NÃO.

## ÂNCORA NO CREDOR-ALVO (obrigatório)
O crédito analisado é EXCLUSIVAMENTE o de {{nome_autor}} — o credor identificado na entrada. Diga a
QUEM o valor foi pago:
  {{nome_autor}}                   → conta
  cotitular/litisconsorte ativo    → NÃO conta (nomeie quem recebeu)
  advogado, a título de honorários → NÃO conta no rótulo (ver DUAS VIAS)
  outro crédito ou outro processo  → NÃO conta
Grafia divergente do nome (OCR, nome abreviado) NÃO transforma o credor-alvo em terceiro.
PAGAMENTO NÃO É CESSÃO: valor que {{nome_autor}} recebeu de cessionário/comprador é preço de cessão
e aqui é NÃO. Mas valor da parte dele levantado por credor penhorante ou transferido a terceiro por
ordem judicial É pagamento — o dinheiro saiu do precatório; diga quem levantou.

## BASE DE CÁLCULO: A PARTE DO CREDOR, NÃO O TOTAL DO PRECATÓRIO
Mede-se a fração paga DA PARTE QUE PERTENCE A {{nome_autor}}. Honorários contratuais destacados
pertencem ao advogado e ficam FORA dessa base.
Exemplo: precatório de R$ 100.000,00, sendo R$ 70.000,00 do credor e R$ 30.000,00 de honorários
contratuais destacados. A base do credor é R$ 70.000,00.
  • pagos R$ 40.000,00 ao credor → PARCIAL (restam R$ 30.000,00)
  • pagos R$ 70.000,00 ao credor → INTEGRAL, ainda que os honorários não tenham sido pagos

DUAS VIAS DOS HONORÁRIOS (obrigatória): pagamento de honorários contratuais não entra no rótulo, mas
a pergunta os menciona — então RELATE no corpo da resposta, com a ressalva de que não configura
pagamento do crédito do credor. Destaque, reserva ou retenção NÃO é pagamento, é separação de valor.
*Nao considere destaque como pagamento!

## PARCIAL OU INTEGRAL
- INTEGRAL: a totalidade da parte de {{nome_autor}} foi paga — nada resta a receber.
- PARCIAL: parte foi paga E os trechos afirmam SALDO REMANESCENTE do mesmo crédito principal
  ("saldo a pagar", "remanescente", "diferença", "complementar"). Sem saldo afirmado, não afirme
  parcial: ou é integral, ou é NÃO.
- São EXCLUDENTES. Sendo integral, responda PAGAMENTO_PARCIAL com "PAGAMENTO PARCIAL: NÃO — o
  pagamento localizado é integral". Sendo parcial, responda PAGAMENTO_INTEGRAL com "PAGAMENTO
  INTEGRAL: NÃO — o pagamento localizado é parcial (X)".
- Extensão, sem conta própria: texto explícito de quitação/totalidade → INTEGRAL; valor pago e valor
  da parte do credor ambos expressos e coincidentes → INTEGRAL; valor referido ao total do precatório
  sem os trechos dizerem a fatia do credor, ou pagamento sem valor identificável → PARCIAL,
  registrando o que não consta. Nunca estime a parte do credor por dedução.

## CLASSIFICAÇÃO
SIM (CONFIRMADO) — o dinheiro saiu, ou o juízo/tribunal registrou que saiu:
  • certidão de quitação, de pagamento ou de liquidação do precatório
  • decisão que extingue a execução pelo cumprimento da obrigação (art. 924, II, do CPC)
  • comprovante de depósito judicial, ordem bancária ou transferência do crédito
  • alvará de levantamento cumprido, recibo, ou petição do credor dando quitação
  • informação do tribunal/setor de precatórios de que foi pago, baixado ou liquidado
  • acordo direto (câmara de conciliação, deságio) homologado E comprovadamente pago

SIM (INDICIO) — sinal vinculado ao crédito de {{nome_autor}}, sem comprovação de saída do dinheiro:
  • alvará ou ordem de pagamento expedidos, sem comprovação de cumprimento
  • depósito noticiado sem valor, beneficiário ou vinculação clara ao crédito
  • menção a "saldo remanescente" ou "crédito complementar" sem dizer o que foi pago
  • intimação para dar quitação; acordo direto homologado sem comprovação de pagamento

NÃO — nenhum sinal, sinal que não atinge o credor-alvo, ou falso positivo abaixo.

## FALSOS POSITIVOS — responda NÃO
1. Estar na fila: inclusão no orçamento, ordem cronológica, dotação, disponibilidade financeira,
   "aguarda pagamento", previsão de pagamento.
2. Expedição, transmissão ou cadastro do ofício requisitório: é pedido de pagamento.
3. Sentença ou acórdão que CONDENA a pagar: é o mérito da ação.
4. Destaque, reserva ou retenção de honorários; honorários sucumbenciais pagos; custas, taxas,
   despesas processuais, honorários periciais, verbas acessórias.
5. Pagamentos administrativos/extrajudiciais: extrato do INSS, "Histórico de Créditos", parcelas
   mensais de benefício, RMI/DIP/DIB, implantação de benefício.
6. Valores "incontroversos", "bloqueados", "status bloqueado", "liberação" ou "levantamento" sem
   destinatário e sem afirmar que é pagamento do crédito do credor.
7. Preço de cessão; penhora, arresto ou bloqueio sem saída de dinheiro.
8. Pagamento a outro litisconsorte, em outro processo, ou de outro crédito do mesmo credor.
9. Acordo apenas proposto, minuta, adesão sem homologação, parcela vincenda não paga.
10. Extinção do processo por razão que não o cumprimento — desistência, prescrição, ilegitimidade,
    abandono, extinção sem exame do mérito.
11. Texto de lei, súmula, jurisprudência ou modelo de petição sobre pagamento de precatório
    (art. 100 da CF, art. 97 do ADCT, EC 62/2009, EC 114/2021) sem vinculação ao caso.
12. Campo/checkbox do requisitório em branco, ou marcado sem valor e sem comprovação. O "X" marca a
    opção adjacente: `X Sim ... Não` = SIM | `Sim X Não` = NÃO. Marcado NÃO não encerra a análise.

## RÉGUA TEMPORAL
NÃO use "página mais alta prevalece": os trechos vêm de documentos diferentes e a numeração não é
comparável. Use a DATA do ato quando constar; sem data, prefira o estágio mais avançado
(quitação > levantamento > depósito > alvará expedido).
Pagamento não se desfaz por ato posterior silencioso — só por devolução, cancelamento ou anulação
expressos. Pagamento integral SUBSTITUI parcial anterior do mesmo crédito: constando os dois, é
INTEGRAL. Pagamentos parciais sucessivos NÃO se somam por sua conta, e menções repetidas do MESMO
pagamento (comprovante, decisão, certidão) contam UMA vez.

## FORMATO OBRIGATÓRIO DO CAMPO "resposta" NESTA SEÇÃO
Comece exatamente por um destes rótulos, conforme a QUESTION_KEY recebida:
   "PAGAMENTO PARCIAL: SIM (CONFIRMADO) — " | "PAGAMENTO PARCIAL: SIM (INDICIO) — " | "PAGAMENTO PARCIAL: NÃO — "
   "PAGAMENTO INTEGRAL: SIM (CONFIRMADO) — " | "PAGAMENTO INTEGRAL: SIM (INDICIO) — " | "PAGAMENTO INTEGRAL: NÃO — "
O rótulo reflete APENAS o crédito do credor-alvo.
Em SIM: valor pago e saldo remanescente, quem recebeu, forma (depósito, ordem bancária, alvará
levantado, acordo direto), estágio e data, se constarem.
Em NÃO: uma frase dizendo por que não há — o credor-alvo não recebeu, quem recebeu foi outro, é só
expectativa, ou o pagamento é de outra extensão.
Havendo pagamento de honorários contratuais, acrescente ao final: "Honorários contratuais: [o que
consta] — não configura pagamento do crédito do credor."
Encerre sempre com "Páginas X, Y."
Status diferente de NÃO EXIGE citação literal, copiada sem paráfrase, no campo "trecho".

## EXEMPLOS

EX. 1 — "Certifico o depósito de R$ 40.000,00 em favor do exequente JOÃO DA SILVA, cujo crédito
requisitado é de R$ 70.000,00, remanescendo saldo a pagar." (pág. 288)
→ "PAGAMENTO PARCIAL: SIM (CONFIRMADO) — depósito de R$ 40.000,00 dos R$ 70.000,00 do crédito de
João da Silva, com saldo remanescente de R$ 30.000,00 certificado. Páginas 288."
→ e, em PAGAMENTO_INTEGRAL: "PAGAMENTO INTEGRAL: NÃO — o pagamento localizado é parcial
(R$ 40.000,00 de R$ 70.000,00), com saldo remanescente. Páginas 288."

EX. 2 — "Comprovado o pagamento integral do precatório, dou por cumprida a obrigação e extingo a
execução (art. 924, II, do CPC). Os honorários contratuais destacados seguem pendentes de
requisição." (pág. 430)
→ "PAGAMENTO INTEGRAL: SIM (CONFIRMADO) — pagamento integral comprovado e execução extinta pelo
cumprimento da obrigação. Honorários contratuais: destacados e pendentes de requisição — não
configura pagamento do crédito do credor. Páginas 430."

EX. 3 — "Precatório incluído na proposta orçamentária do exercício de 2027, aguardando pagamento na
ordem cronológica de apresentação." (pág. 51)
→ "PAGAMENTO INTEGRAL: NÃO — o precatório aguarda pagamento na ordem cronológica, com inclusão
orçamentária para 2027; não há notícia de pagamento realizado. Páginas 51."

EX. 4 — "Expeça-se alvará de levantamento em favor do exequente." (pág. 372), sem comprovação nos trechos.
→ "PAGAMENTO INTEGRAL: SIM (INDICIO) — alvará determinado em favor do exequente, sem comprovação de
cumprimento localizada nos trechos e sem valor informado. Páginas 372."

EX. 5 — "Alvará expedido em favor do advogado, referente ao destaque de honorários contratuais de
30%, mantido o crédito principal em favor do autor." (pág. 155)
→ "PAGAMENTO PARCIAL: NÃO — o levantamento é do destaque de honorários do advogado; o crédito do
credor não foi pago. Honorários contratuais: alvará expedido quanto ao destaque de 30% — não
configura pagamento do crédito do credor. Páginas 155."

EX. 6 — "Recebido pelo exequente o valor de R$ 55.000,00 pago pela cessionária, nos termos do
contrato de cessão." (pág. 244)
→ "PAGAMENTO PARCIAL: NÃO — o valor é preço de cessão pago pela cessionária, não pagamento do
precatório pelo ente devedor. Páginas 244."
