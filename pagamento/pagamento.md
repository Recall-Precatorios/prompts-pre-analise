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

## COMO O PRECATÓRIO É PAGO NA PRÁTICA (use para reconhecer a hipótese)
O DISCRIMINADOR é sempre o SALDO: sobrou parte do mesmo crédito a receber → PARCIAL; não sobrou
nada → INTEGRAL. As hipóteses abaixo estão em ordem de frequência real. Reconhecer a hipótese
NÃO dispensa o ato de saída do dinheiro: identificada a modalidade sem pagamento efetivado, o
rótulo é NÃO (ou INDICIO, conforme a CLASSIFICAÇÃO), nunca SIM (CONFIRMADO).

### PARCIAL — hipótese principal: SUPERPREFERÊNCIA ACIMA DO LIMITE (art. 100, § 2º, CF)
É a causa mais frequente de pagamento parcial. Crédito de natureza alimentar cujo titular
(originário ou por sucessão hereditária) tem 60 anos ou mais, é portador de doença grave ou é
pessoa com deficiência é pago com preferência sobre os demais débitos ATÉ o limite fixado pelo
ente devedor (o triplo do teto da RPV daquele ente), admitido o fracionamento para essa
finalidade. O que EXCEDER o limite é pago na ordem cronológica de apresentação.
Logo: crédito de valor SUPERIOR ao limite → paga-se o limite e o excedente segue na fila = PARCIAL.
Exemplo: precatório de R$ 200.000,00, teto de superpreferência do ente de R$ 100.000,00 — pagos
R$ 100.000,00 como superpreferência e R$ 100.000,00 remetidos à ordem cronológica.
Sinais: "superpreferência", "super preferência", "preferência do § 2º do art. 100 da CF",
deferimento de preferência por idade (60+), doença grave ou deficiência; "fracionamento do crédito
para pagamento da preferência"; "até o limite/teto", "triplo do valor da RPV"; "o valor
excedente/remanescente será pago na ordem cronológica"; expedição de requisitório COMPLEMENTAR ou
de SALDO.
Cuidados: superpreferência DEFERIDA não é pagamento — sem valor pago, o rótulo não é CONFIRMADO.
Se o crédito couber INTEGRALMENTE no limite, é integral (ver adiante), não parcial. Nunca calcule
nem estime o teto do ente: só conclua parcial se o próprio texto indicar excedente, saldo,
remanescente ou pagamento limitado ao teto.

### PARCIAL — hipóteses secundárias
- RATEIO / PAGAMENTO PROPORCIONAL: quando a dotação anual do ente não cobre todos os precatórios
  da fila, alguns tribunais pagam proporcionalmente entre os credores da mesma classe/ano,
  quitando parte de cada um. Sinais: "rateio", "pagamento proporcional", "insuficiência de
  dotação orçamentária", "quitação parcial no exercício", com saldo para o exercício seguinte.
- PAGAMENTO EM DUAS OU MAIS PARCELAS NO MESMO EXERCÍCIO: tribunais que dividem o pagamento do
  ano orçamentário (p. ex. uma parcela em março e outra em novembro). Parcela paga com parcela
  pendente = PARCIAL; todas as parcelas previstas pagas = INTEGRAL.
- PARCELAMENTO DO § 20 DO ART. 100 DA CF: precatório superior a 15% do montante apresentado —
  15% pagos até o fim do exercício seguinte e o restante em cinco parcelas anuais, com juros e
  correção. Enquanto houver parcela vincenda = PARCIAL.
- LEVANTAMENTO PARCIAL autorizado em favor de {{nome_autor}}, com o restante mantido em conta
  judicial ou remetido à fila.

### INTEGRAL — hipóteses principais
a) QUITAÇÃO NA ORDEM CRONOLÓGICA: o precatório chegou a sua vez na fila e foi pago. É o caso
   típico. Sinais: despacho ou certidão do tribunal informando o pagamento; comprovante de
   transferência ou depósito do valor; alvará de levantamento cumprido; "precatório quitado",
   "crédito satisfeito", "baixado", "liquidado"; extinção da execução pelo cumprimento da
   obrigação (art. 924, II, do CPC) e arquivamento definitivo.
b) ACORDO DIRETO COM DESÁGIO (art. 100, § 20, CF): acordo perante Juízo/Câmara Auxiliar de
   Conciliação de Precatórios, com redução de até 40% do valor atualizado, para recebimento
   antecipado. Sinais: "acordo direto", "juízo auxiliar de conciliação de precatórios",
   "deságio", "redução de 30%/40%", "renúncia ao excedente", homologação seguida de pagamento.
   REGRA IMPORTANTE: o acordo QUITA o precatório inteiro. O DESÁGIO NÃO É SALDO REMANESCENTE —
   o credor abriu mão do percentual e nada segue na fila. Acordo homologado e pago = INTEGRAL,
   nunca parcial.
c) SUPERPREFERÊNCIA DENTRO DO LIMITE (art. 100, § 2º, CF): mesmo instituto da hipótese principal
   de parcial, resultado oposto. Se o crédito total é igual ou inferior ao limite de
   superpreferência do ente, o precatório inteiro é pago à frente da fila, sem excedente. Sinais:
   preferência deferida e paga, com indicação de que o pagamento abrangeu a totalidade, sem
   remanescente e sem requisitório complementar. Havendo excedente ou saldo → PARCIAL.

### INTEGRAL — hipótese secundária
d) RPV (Requisição de Pequeno Valor): crédito abaixo do teto de pequeno valor (60 salários
   mínimos na esfera federal; limites próprios em Estados e Municípios) é pago integralmente, em
   regra em até 60 dias, sem fila cronológica e sem fracionamento. Consequência prática: em RPV,
   quando o pagamento ocorre, ele é integral — não há pagamento parcial por insuficiência de fila.
   ATENÇÃO: ser RPV NÃO prova que houve pagamento. A natureza de RPV apenas afasta a hipótese de
   fracionamento; a conclusão de pagamento integral continua exigindo ato concreto de quitação.
   RPV apenas expedida, requisitada ou transmitida = NÃO.

## CLASSIFICAÇÃO
SIM (CONFIRMADO) — o dinheiro saiu, ou o juízo/tribunal registrou que saiu:
  • certidão de quitação, de pagamento ou de liquidação do precatório
  • decisão que extingue a execução pelo cumprimento da obrigação (art. 924, II, do CPC)
  • comprovante de depósito judicial, ordem bancária ou transferência do crédito
  • alvará de levantamento cumprido, recibo, ou petição do credor dando quitação
  • informação do tribunal/setor de precatórios de que foi pago, baixado ou liquidado
  • acordo direto (câmara de conciliação, deságio) homologado E comprovadamente pago
  • pagamento de superpreferência efetivado, com o excedente remetido à ordem cronológica

SIM (INDICIO) — sinal vinculado ao crédito de {{nome_autor}}, sem comprovação de saída do dinheiro:
  • alvará ou ordem de pagamento expedidos, sem comprovação de cumprimento
  • depósito noticiado sem valor, beneficiário ou vinculação clara ao crédito
  • menção a "saldo remanescente" ou "crédito complementar" sem dizer o que foi pago
  • intimação para dar quitação; acordo direto homologado sem comprovação de pagamento
  • rateio ou parcela do exercício noticiados sem valor e sem comprovação

NÃO — nenhum sinal, sinal que não atinge o credor-alvo, ou falso positivo abaixo.

## FALSOS POSITIVOS — responda NÃO
1. Estar na fila: inclusão no orçamento, ordem cronológica, dotação, disponibilidade financeira,
   "aguarda pagamento", previsão de pagamento.
2. Expedição, transmissão ou cadastro do ofício requisitório: é pedido de pagamento. Vale também
   para a RPV expedida e não paga.
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
    abandono, extinção sem exame do mérito. "Processo extinto", isolado e sem dizer que a extinção
    decorreu do pagamento, NÃO é pagamento integral.
11. Texto de lei, súmula, jurisprudência ou modelo de petição sobre pagamento de precatório
    (art. 100 da CF, art. 97 do ADCT, EC 62/2009, EC 114/2021) sem vinculação ao caso — inclusive
    a transcrição dos §§ 2º e 20 do art. 100 num requerimento de preferência ou de acordo.
12. Campo/checkbox do requisitório em branco, ou marcado sem valor e sem comprovação. O "X" marca a
    opção adjacente: `X Sim ... Não` = SIM | `Sim X Não` = NÃO. Marcado NÃO não encerra a análise.
13. Requerimento ou deferimento de superpreferência, de habilitação em acordo direto ou de
    prioridade por idade/doença/deficiência, sem pagamento: é posição na fila, não pagamento.
14. Deságio, renúncia ao excedente ou redução percentual em acordo tratados como saldo
    remanescente: não são — quem fez acordo não tem saldo a receber na fila.

## RÉGUA TEMPORAL
NÃO use "página mais alta prevalece": os trechos vêm de documentos diferentes e a numeração não é
comparável. Use a DATA do ato quando constar; sem data, prefira o estágio mais avançado
(quitação > levantamento > depósito > alvará expedido).
Onde procurar: pagamento aparece no FIM da tramitação. O precatório é a última obrigação a ser
satisfeita — pago o precatório, o processo é extinto. Trechos de fases anteriores (conhecimento,
liquidação, expedição do requisitório) não provam pagamento.
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
levantado, acordo direto), a modalidade quando identificável (superpreferência, rateio, parcela do
exercício, acordo com deságio, RPV), estágio e data, se constarem.
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

EX. 7 — "Deferida a preferência do art. 100, § 2º, da CF. Pago o valor de R$ 100.000,00, limite de
superpreferência do ente, seguindo o saldo de R$ 100.000,00 na ordem cronológica de apresentação."
(pág. 402)
→ "PAGAMENTO PARCIAL: SIM (CONFIRMADO) — superpreferência paga até o limite de R$ 100.000,00, com
saldo de R$ 100.000,00 remetido à ordem cronológica. Páginas 402."

EX. 8 — "Homologado o acordo direto celebrado perante o Juízo Auxiliar de Conciliação de
Precatórios, com deságio de 40%. Comprovado o depósito e dada a quitação." (pág. 511)
→ "PAGAMENTO INTEGRAL: SIM (CONFIRMADO) — acordo direto homologado e pago, com deságio de 40%; o
acordo quita o precatório inteiro e a redução não constitui saldo remanescente. Páginas 511."

EX. 9 — "Deferido o pagamento prioritário por idade ao autor. Aguarde-se a disponibilização de
recursos pelo ente devedor." (pág. 288)
→ "PAGAMENTO PARCIAL: NÃO — a preferência por idade foi deferida, mas não há pagamento efetivado;
o crédito segue aguardando disponibilização de recursos. Páginas 288."

EX. 10 — "Em razão da insuficiência da dotação do exercício, procedeu-se ao rateio proporcional
entre os precatórios da classe, pago a este credor 32% do valor requisitado, com o saldo
transferido para o exercício seguinte." (pág. 366)
→ "PAGAMENTO PARCIAL: SIM (CONFIRMADO) — pagamento por rateio proporcional de 32% do valor
requisitado, por insuficiência de dotação, com saldo transferido ao exercício seguinte.
Páginas 366."
