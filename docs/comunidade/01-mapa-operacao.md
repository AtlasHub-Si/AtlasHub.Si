# Exercício 01 · Mapa de uma operação em 30 minutos
**Resultado:** uma página que mostra o processo atual, o problema e uma primeira melhoria testável.
Caso fictício: uma pequena loja recebe pedidos de orçamento por email e perde tempo a pedir as mesmas informações.

## 1. Defina o início e o fim
Preencha:
- Processo:
- Pessoa responsável:
- Começa quando:
- Termina quando:
- Pessoa que recebe o resultado:
- Quantidade de casos por semana, se conhecida:
Não invente números de produtividade; escreva “não medido” se necessário.

## 2. Descreva o caminho atual
| Etapa | Entrada | Ação | Saída | Quem decide | Falha frequente |
|---|---|---|---|---|---|
| 1 | Pedido por email | Ler e classificar | Tipo de pedido | Atendimento | Falta informação |
| 2 | Pedido incompleto | Pedir dados | Resposta do cliente | Atendimento | Perguntas repetidas |
| 3 | Dados completos | Preparar rascunho | Proposta para revisão | Comercial | Preço incorreto |
| 4 | Proposta revista | Autorizar envio | Proposta enviada | Responsável humano | Envio sem revisão |

## 3. Escolha uma tarefa pequena
No exemplo, o primeiro agente pode **preparar perguntas sobre dados em falta**. Ainda não escolhe preços nem envia emails.
Registe:
- Tarefa proposta:
- Entrada mínima:
- Resultado esperado:
- Ação que exige pessoa:
- Ações proibidas:
- Como reverter ou interromper:

## 4. Faça três ensaios
1. Pedido completo: não deve pedir os mesmos dados novamente.
2. Pedido incompleto: deve indicar apenas o necessário.
3. Pedido confuso: deve assinalar incerteza e pedir revisão.

## Entrega para o portfólio
Mapa, três exemplos de entrada/saída e uma melhoria que pretende testar. A evidência é o resultado observado, não uma promessa de poupança futura.
