# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real

Preparar a aula semanal de Inteligência Artificial dos sábados. É um trabalho que se repete toda semana: definir o tema, montar o roteiro, escolher uma atividade prática e preparar os exemplos. Vale a pena delegar a primeira versão à IA porque a estrutura é sempre parecida, e o meu tempo vai para a revisão e para adaptar à turma, que é o que só eu posso fazer.

### Meus Atalhos

Adaptei dois modelos do kit: o de **bom pedido** (contexto + instrução + objetivo + formato) virou um atalho de roteiro de aula, e o **Pare, Confira, Use** virou um atalho de revisão do material antes de usar. Os trechos entre colchetes são as variáveis que troco a cada uso.

**Atalho 1: Roteiro de aula**

```text
Você é um assistente de preparação de aulas. Preciso do roteiro de uma aula de [DISCIPLINA] para [PÚBLICO: faixa etária e nível].

Tema da aula: [TEMA]
Duração: [DURAÇÃO]
Objetivo: ao final, o aluno será capaz de [OBJETIVO].

Monte: abertura (5 min), explicação com um exemplo do dia a dia, uma atividade prática em duplas e um fechamento com 3 perguntas de revisão.
Separe claramente o que são fatos e o que são sugestões suas.
Não invente dados nem fontes. Se faltar informação, pergunte antes.
```

- **Fica fixo:** a estrutura (abertura, explicação, prática, fechamento), a separação entre fato e sugestão e a regra de não inventar.
- **Muda a cada uso:** disciplina, público, tema, duração e objetivo.

**Atalho 2: Revisão do material antes de usar**

```text
Revise o roteiro abaixo como um professor experiente.
1. Aponte erros ou afirmações que eu precise conferir.
2. Diga o que está longo demais para [DURAÇÃO].
3. Sugira uma forma mais simples de explicar o ponto mais difícil.
Não reescreva tudo: liste só os ajustes.

[COLE O ROTEIRO]
```

- **Fica fixo:** os três pontos de revisão e a regra de listar só os ajustes.
- **Muda a cada uso:** a duração e o roteiro colado.

### Minha Delegação

```text
Objetivo: preparar o roteiro da minha aula de Inteligência Artificial deste sábado, sobre «Como pedir bem à IA (prompts)».

Contexto: aula semanal para alunos iniciantes, de 1h30. Eles ainda não viram nada sobre prompts. Quero uma aula prática, com linguagem simples.

Recursos: não precisa pesquisar na internet. Use só conhecimento geral e o modelo de bom pedido (contexto + instrução + objetivo + formato).

Limites: não envie mensagem a ninguém, não altere arquivos nem calendário e não use nomes de alunos ou dados pessoais. Antes de começar, mostre o plano em passos e espere a minha aprovação.

Critério de sucesso: roteiro pronto para usar, com abertura (5 min), explicação com exemplo do dia a dia, atividade prática em duplas e fechamento com 3 perguntas de revisão. Separe o que é fato do que é sugestão sua e marque o que eu preciso conferir.
```

### O Plano da IA

Antes de executar, a IA devolveu este plano:

1. **Abertura (5 min):** uma pergunta provocadora, «por que a mesma IA dá respostas boas para uns e ruins para outros?».
2. **Explicação (25 min):** o modelo contexto + instrução + objetivo + formato, com um exemplo do dia a dia mostrando um pedido ruim e um bom.
3. **Atividade em duplas (40 min):** cada dupla reescreve um pedido fraco, testa na IA e compara os resultados.
4. **Compartilhamento (15 min):** duas ou três duplas mostram o antes e o depois.
5. **Fechamento (5 min):** 3 perguntas de revisão e um lembrete de conferir antes de usar.
6. **Entrega:** roteiro completo, com fatos e sugestões separados e uma lista curta do que conferir.

A IA também confirmou que não enviaria nada a ninguém nem mexeria em arquivos. **Ajustes que fiz:** aprovei o plano sem mudanças, mantendo a atividade em duplas como parte principal da aula.

### O Resultado

<details>
<summary>Roteiro entregue pela IA (clique para abrir)</summary>

**Aula: Como pedir bem à IA (prompts) · 1h30 · iniciantes**

**1. Abertura (5 min).** Pergunta: «por que a mesma IA dá respostas boas para uns e ruins para outros?». Deixe 2 ou 3 alunos responderem.

**2. Explicação (25 min).** Apresente as quatro partes de um bom pedido: contexto, instrução, objetivo e formato.

- Pedido ruim: «Faz um cardápio.»
- Pedido bom: «Tenho dois filhos e R$ 200 por semana para o jantar (contexto). Monte um cardápio de segunda a sexta (instrução) simples e rápido, para eu reduzir o desperdício (objetivo), em tabela com ingredientes e tempo de preparo (formato).»

Mostre as duas respostas lado a lado e peça que os alunos apontem a diferença.

**3. Atividade em duplas (40 min).** Cada dupla recebe um pedido fraco: «Me ajuda com meu currículo», «Explica o que é internet» ou «Cria um treino».

- 10 min: reescrever o pedido com as quatro partes.
- 10 min: testar na IA.
- 10 min: comparar com o pedido original.
- 10 min: melhorar uma vez mais com base no que a resposta trouxe.

**4. Compartilhamento (15 min).** Duas ou três duplas mostram o antes e o depois e dizem o que mudou na resposta.

**5. Fechamento (5 min).** Perguntas de revisão:

1. Quais são as quatro partes de um bom pedido?
2. Por que a primeira resposta da IA é só um ponto de partida?
3. O que devo conferir antes de usar uma resposta da IA?

**Fatos (para conferir se quiser):** o modelo contexto + instrução + objetivo + formato é o usado nas aulas do bootcamp; respostas de IA podem conter erros e devem ser conferidas antes de usar.

**Sugestões da IA:** a divisão dos tempos, os exemplos (cardápio, currículo, internet, treino) e a pergunta de abertura.

**Para eu conferir:** se os tempos cabem na minha turma; se os exemplos fazem sentido para o público; se todos os alunos têm acesso a uma IA durante a atividade; testar os pedidos de exemplo na IA antes da aula.

</details>

**Como conferi antes de usar:** li o roteiro inteiro, testei os dois pedidos de exemplo (o ruim e o bom) na IA para ver se a diferença aparece, ajustei os tempos para a minha turma e só então usei.

### Como Foi para Você

A primeira versão do roteiro chegou pronta em poucos minutos, e o meu tempo passou a ir para a revisão e para adaptar à turma. O que mais ajudou foi pedir o plano antes da execução e separar o que é fato do que é sugestão da IA.
