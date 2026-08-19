### 6) CESSÃO DE CRÉDITO (PARCIAL E INTEGRAL)
(aplique quando QUESTION_KEY = CESSAO_PARCIAL ou CESSAO_INTEGRAL)

Esta seção SUBSTITUI, exclusivamente para essas duas perguntas:
- a REGRA GERAL do "não consta" (o rótulo obrigatório abaixo ocupa o lugar dela);
- a prevalência da página mais alta.
As demais regras seguem valendo, inclusive o formato JSON, a proibição de inventar página e
"na dúvida, responder de forma conservadora".

## O QUE ESTA PERGUNTA REALMENTE INVESTIGA
Quanto do crédito de {{nome_autor}} já foi VENDIDO a terceiro e, portanto, não lhe pertence mais.
A cessão de precatório tem um roteiro típico: um terceiro interessado compra o crédito (todo ou
parte dele) por escritura pública ou contrato de cessão de precatórios e, depois, se habilita nos
autos, requerendo ao juízo ou ao setor de precatórios do tribunal que o habilite e
homologue/aprove a cessão. Procure o INSTRUMENTO e o ATO de habilitação/homologação — não a
palavra "cessão".

## ÂNCORA NO CREDOR-ALVO (obrigatório)
O crédito analisado é EXCLUSIVAMENTE o de {{nome_autor}} — o credor identificado na entrada. Ele é
a prioridade absoluta da análise. Antes de classificar, diga de QUEM é a parcela cedida:
  {{nome_autor}}                            → conta
  cotitular/litisconsorte ativo             → NÃO conta (nomeie quem cedeu)
  apenas honorários contratuais do advogado → NÃO conta aqui (pertence a HONORARIOS_STATUS)
  outro crédito ou outro processo           → NÃO conta
Havendo litisconsórcio ativo, cada credor cede a SUA quota-parte individualmente: a cessão de um
não atinge os demais.
Grafia divergente do nome (OCR, nome abreviado) NÃO transforma o credor-alvo em terceiro.

## BASE DE CÁLCULO: A PARTE DO CREDOR, NÃO O TOTAL DO PRECATÓRIO
O que se mede é a fração cedida DA PARTE QUE PERTENCE A {{nome_autor}} — não do valor total do
precatório. Honorários contratuais destacados pertencem ao advogado e ficam FORA dessa base.

Exemplo de referência: precatório de R$ 100.000,00, sendo R$ 70.000,00 do credor e R$ 30.000,00 de
honorários contratuais destacados ao advogado. A base do credor é R$ 70.000,00.
  • credor cede R$ 40.000,00  → PARCIAL (restam R$ 30.000,00 com ele)
  • credor cede R$ 70.000,00  → INTEGRAL (nada resta com ele), ainda que os R$ 30.000,00 de
    honorários contratuais sigam resguardados ao advogado

## PARCIAL OU INTEGRAL

- INTEGRAL: {{nome_autor}} cedeu a totalidade da sua parte — nada resta para ele. Vale tanto quando
  o instrumento diz "integralidade/totalidade/100% do crédito do credor" quanto quando todo o
  precatório é vendido de uma vez (credor ou credores em litisconsórcio E honorários contratuais).
  Honorários contratuais que permaneçam com o advogado NÃO descaracterizam a integralidade.

- PARCIAL: parte da parcela de {{nome_autor}} foi cedida e parte permanece com ele (percentual,
  valor fixo ou fração da quota). É o caso comum em que o terceiro compra apenas o crédito do
  credor originário, resguardados os honorários contratuais do advogado — e também o inverso,
  compra dos honorários contratuais com o percentual do credor resguardado (neste inverso, aplique
  a âncora: sem cessão da parte do credor-alvo, a resposta é NÃO nas duas perguntas).

- As duas são EXCLUDENTES para o mesmo crédito. Se a cessão localizada é integral, responda
  CESSAO_PARCIAL com "CESSÃO PARCIAL: NÃO — a cessão localizada é integral". Se é parcial,
  responda CESSAO_INTEGRAL com "CESSÃO INTEGRAL: NÃO — a cessão localizada é parcial (X)".

- IDENTIFICAÇÃO DA EXTENSÃO — sem conta própria:
  • texto explícito de totalidade da parte do credor ("a integralidade do crédito do exequente",
    "todo o seu crédito", "100% da quota do autor") → INTEGRAL;
  • valor ou percentual cedido expresso E valor da parte do credor expresso nos trechos, ambos
    coincidindo → INTEGRAL; coincidindo apenas em parte → PARCIAL;
  • percentual referido ao TOTAL do precatório, sem que os trechos digam qual fatia é do credor
    → PARCIAL, registrando que a base do credor não consta;
  • cessão comprovada sem valor nem percentual identificável → PARCIAL, dizendo que a extensão
    não consta.
  Nunca estime a parte do credor por dedução, nem some percentuais que os trechos não afirmem.

## CLASSIFICAÇÃO

SIM (CONFIRMADO) — instrumento somado a ato do juízo/tribunal, ou efeito já produzido:
  • decisão que homologa/aprova a cessão ou defere a habilitação do cessionário
  • escritura pública ou contrato de cessão nos autos com o correspondente deferimento
  • ofício requisitório, alvará, ordem de pagamento ou cadastro do precatório em nome do cessionário
  • certidão ou informação do setor de precatórios registrando a cessão

SIM (INDICIO) — sinal vinculado ao crédito de {{nome_autor}}, sem ato conclusivo:
  • escritura ou contrato de cessão juntado, sem decisão localizada nos trechos
  • petição do cessionário requerendo habilitação e homologação, ainda sem decisão
  • qualificação de {{nome_autor}} como cedente, ou de terceiro como cessionário, vinculada a este crédito
  • intimação das partes ou do ente devedor para se manifestar sobre a cessão

NÃO — nenhum sinal, sinal que não atinge o credor-alvo, ou falso positivo abaixo.

## FALSOS POSITIVOS — responda NÃO
1. Cláusula contratual padrão: "obriga as partes, seus herdeiros e cessionários a qualquer título".
2. Texto de lei, súmula, jurisprudência, doutrina ou modelo de petição sobre cessão (art. 286 do
   CC, §§ 13 e 14 do art. 100 da CF, EC 62/2009) sem vinculação ao caso concreto.
3. Cessão APENAS de honorários, contratuais ou sucumbenciais — pertence a HONORARIOS_STATUS.
4. Destaque ou reserva de honorários, penhora, arresto, bloqueio: constrição não é cessão.
5. Procuração, ainda que com poderes para "ceder e transferir créditos": poder não é cessão realizada.
6. Proposta, minuta, e-mail comercial ou instrumento sem assinatura e sem qualificação das partes.
7. Cessão rejeitada, indeferida por decisão expressa, rescindida, revogada, anulada ou objeto de
   desistência.
8. Campo/checkbox do ofício requisitório sobre cessão em branco, ou marcado sem instrumento e sem
   cessionário identificado.
   Leitura do "X": o "X" marca a opção adjacente a ele. `X Sim ... Não` = SIM | `Sim X Não` = NÃO.
   Marcado SIM só confirma se houver, junto, o cessionário identificado. Marcado NÃO não encerra a
   análise: a cessão pode estar nos outros documentos.
9. Sub-rogação legal, compensação tributária ou dação em pagamento ao ente devedor: não é cessão a
   terceiro adquirente.

## RESSALVA À PREVALÊNCIA TEMPORAL
Nesta seção, NÃO use "página mais alta prevalece": os trechos vêm de documentos diferentes e a
numeração de página não é comparável entre eles. Cessão homologada não se desfaz por ato posterior
silencioso — apenas por rescisão, anulação ou indeferimento expressos nos autos.

Cessões parciais sucessivas da parte do mesmo credor SOMAM apenas se os trechos as identificarem
como cessões DISTINTAS — instrumentos, datas ou cessionários diferentes. Menções repetidas da MESMA
cessão (contrato, decisão homologatória, intimação, ofício) contam UMA vez. Na dúvida sobre serem a
mesma cessão, trate como uma só e responda PARCIAL. Sendo distintas e esgotando juntas a parte de
{{nome_autor}} — com os valores afirmados nos trechos, sem conta sua —, a classificação é INTEGRAL.

## FORMATO OBRIGATÓRIO DO CAMPO "resposta" NESTA SEÇÃO
O campo "resposta" DEVE começar exatamente por um destes rótulos, conforme a QUESTION_KEY recebida:
   "CESSÃO PARCIAL: SIM (CONFIRMADO) — " | "CESSÃO PARCIAL: SIM (INDICIO) — " | "CESSÃO PARCIAL: NÃO — "
   "CESSÃO INTEGRAL: SIM (CONFIRMADO) — " | "CESSÃO INTEGRAL: SIM (INDICIO) — " | "CESSÃO INTEGRAL: NÃO — "

Depois do rótulo, em SIM: quem cedeu, quem é o cessionário, valor ou percentual cedido e o que
restou ao credor, instrumento (escritura pública ou contrato), estágio (contrato juntado /
habilitação requerida / cessão homologada / requisitório em nome do cessionário) e data, se constarem.
Depois do rótulo, em NÃO: uma frase dizendo por que não há — o credor-alvo não cedeu, quem cedeu
foi outro, ou a cessão localizada é de outra extensão.
Encerre sempre com "Páginas X, Y."

Status diferente de NÃO EXIGE citação literal, copiada sem paráfrase, no campo "trecho".
Sem citação literal, a resposta é "NÃO".

## EXEMPLOS

EX. 1 — "Homologo a cessão de R$ 40.000,00 do crédito do exequente JOÃO DA SILVA — cujo valor
requisitado é de R$ 70.000,00, além de R$ 30.000,00 de honorários contratuais destacados — em favor
de FOMENTO ALFA LTDA, na forma da escritura pública de fls. 310, deferida a habilitação da
cessionária." (pág. 355) — credor-alvo JOÃO DA SILVA
→ "CESSÃO PARCIAL: SIM (CONFIRMADO) — cessão de R$ 40.000,00 dos R$ 70.000,00 do crédito de João da
Silva à Fomento Alfa Ltda por escritura pública, homologada, com habilitação da cessionária
deferida; remanescem R$ 30.000,00 com o credor. Páginas 310, 355."
→ e, na pergunta CESSAO_INTEGRAL: "CESSÃO INTEGRAL: NÃO — a cessão localizada é parcial
(R$ 40.000,00 de R$ 70.000,00). Páginas 355."

EX. 2 — "Homologo a cessão da integralidade do crédito do exequente JOÃO DA SILVA à FOMENTO ALFA
LTDA, permanecendo íntegro o destaque de honorários contratuais em favor do patrono." (pág. 401)
→ "CESSÃO INTEGRAL: SIM (CONFIRMADO) — João da Silva cedeu a integralidade do seu crédito à Fomento
Alfa Ltda, cessão homologada; os honorários contratuais destacados seguem com o advogado e não
integram a parte do credor. Páginas 401."

EX. 3 — "Requisição de pagamento expedida em favor de BETA ADMINISTRAÇÃO DE ATIVOS LTDA,
cessionária da integralidade do precatório, conforme contrato de cessão homologado, nele incluídos
os honorários contratuais destacados." (pág. 412)
→ "CESSÃO INTEGRAL: SIM (CONFIRMADO) — integralidade do precatório cedida à Beta Administração de
Ativos Ltda, incluída a parte do credor e os honorários contratuais destacados; requisitório
expedido em nome da cessionária. Páginas 412."

EX. 4 — "Petição de habilitação: a cessionária GAMA S/A requer o reconhecimento da cessão firmada
com o exequente, juntando instrumento particular de cessão." (pág. 208), sem decisão nos trechos.
→ "CESSÃO PARCIAL: SIM (INDICIO) — habilitação de cessionária requerida com contrato de cessão
juntado, sem decisão localizada nos trechos e sem valor ou percentual informado. Páginas 208."

EX. 5 — "Homologada a cessão da quota-parte do litisconsorte PEDRO SOUZA; os demais autores seguem
titulares de suas quotas." (pág. 190) — credor-alvo MARIA LIMA
→ "CESSÃO PARCIAL: NÃO — a cessão homologada é da quota do litisconsorte Pedro Souza; a quota da
credora Maria Lima permanece com ela. Páginas 190."

EX. 6 — "O advogado cede os honorários contratuais destacados à DELTA FOMENTO, mantido o crédito
principal em favor do autor." (pág. 77)
→ "CESSÃO PARCIAL: NÃO — a cessão é dos honorários contratuais do advogado; a parte do credor não
foi cedida. Páginas 77."

EX. 7 — "Outorga poderes para transigir, dar quitação, ceder e transferir créditos." (pág. 12)
→ "CESSÃO PARCIAL: NÃO — cessão inexistente; trata-se de cláusula de procuração com poderes para
ceder. Páginas 12."
