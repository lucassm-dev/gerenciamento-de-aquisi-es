# Roteiro de fala — Gerenciamento de Aquisições aplicado ao O Gerente

Abrir `apresentacao-aquisicoes-o-gerente.html` no navegador em tela cheia (F11). Navegar com ← →.
**Tecla N** abre e fecha as notas de fala do slide atual (o mesmo texto deste roteiro).
Para revisar tudo revelado, abra o arquivo com `?all` no fim do endereço.

> O conteúdo aparece **por etapas**. Cada → mostra o próximo bloco e, depois do último, passa de slide.
> Os pontinhos laranja no rodapé mostram quantas etapas faltam. Abaixo, cada **→** marca um clique.

**A história:** nós somos a empresa que constrói o O Gerente para o Seu Ricardo e precisamos comprar 6 coisas (nuvem, app mobile, consultoria agronômica, pentest, ferramentas SaaS e tablet). Cada conceito aparece quando a história precisa dele.

| Parte | Quem | Slides | Tempo |
|---|---|---|---|
| Abertura, contexto, conceito e ordem dos processos | Rhiady Vieira | 01–05 | ~3:00 |
| Planejar e Conduzir no nosso projeto | Lucas Mendes | 06–09 | ~3:00 |
| Controlar, prós e contras, contratos | João Augusto | 10–13 | ~3:15 |
| Orçamento, HealthCare.gov, sucesso e encerramento | Jhonatan Zago | 14–18 | ~3:15 |

Total: 18 slides (14 de conteúdo + 4 com o nome de quem vai falar), ~12–13 min.

---

## Rhiady Vieira

**01 · Capa**
"Olá, professor e turma. Somos Lucas, Rhiady, João e Jhonatan, e o nosso tema é Gerenciamento de Aquisições. Em vez de só passar a teoria, vamos aplicar cada conceito no O Gerente, o sistema de gestão agrícola que a gente já planejou para o senhor no trabalho anterior."

**02 · Vez da Rhiady** (slide com o nome) — "Eu começo apresentando o nosso projeto, o conceito e a ordem dos processos."

**03 · Nós somos a empresa do Seu Ricardo** (2 cliques)
"Lembrando o projeto: o Seu Ricardo tem 12 alqueires de laranja em Urânia e controla tudo no caderno. Perde o controle do diesel, não sabe quanto vai faturar e não tem histórico de defensivos." — **→** "Nós somos a empresa que vai resolver isso com um sistema de 8 módulos em Angular, Spring Boot e PostgreSQL, rodando em Docker." — **→** "Mas tem coisa que a nossa equipe não faz. E é aí que entra o Gerenciamento de Aquisições."

**04 · Conceito e lista de compras** (2 cliques)
"Segundo o PMBOK, gerenciamento de aquisições são os processos para comprar produtos, serviços ou resultados de fora da equipe do projeto. O PMBOK olha tudo pelo lado de quem compra, que é o nosso lado aqui." — **→** "No O Gerente, a gente precisa comprar: nuvem para rodar o sistema, um app mobile para o Luciano usar no campo e uma consultoria agronômica para validar as regras de defensivos." — **→** "E também um teste de segurança, as ferramentas do dia a dia e um tablet robusto. São seis compras, e cada uma vai ensinar um conceito."

**05 · Ordem dos processos** (3 cliques)
"O PMBOK organiza a área em três processos. Primeiro, o 12.1 Planejar: antes de falar com qualquer fornecedor, decidimos o que comprar, como e com que contrato." — **→** "Depois, o 12.2 Conduzir: o mercado manda propostas, escolhemos e assinamos." — **→** "Por fim, o 12.3 Controlar: acompanhar o fornecedor até o fim." — **→** "A seta tracejada mostra que, no controle, mudanças voltam para negociação. E tudo termina com o contrato encerrado. Na 5ª edição o encerramento era um quarto processo, e na 6ª faz parte do Controlar. Agora o Lucas mostra isso no nosso cronograma."

---

## Lucas Mendes

**06 · Vez do Lucas** (slide com o nome) — "Agora eu mostro como planejamos e conduzimos as compras do O Gerente."

**07 · Aquisições no cronograma** (3 cliques)
"Aqui está o nosso cronograma do Monday, com as fases. O planejamento das compras acontece logo no começo, no levantamento e na análise." — **→** "A condução acontece em momentos diferentes: a consultoria logo cedo, o app antes da implementação, o pentest nos testes e a nuvem e o tablet perto da implantação." — **→** "E o controle vai da implementação até o encerramento." — **→** "Tudo isso para não atrasar o piloto de 4 de março. Ou seja, aquisição não é um momento só: ela acompanha o projeto inteiro."

**08 · 12.1 Planejar: fazer ou comprar** (3 cliques)
"A principal ferramenta do planejamento é a análise fazer ou comprar. Login a gente faz: já sabemos Spring Security." — **→** "O servidor a gente compra: um servidor na fazenda cai junto com a internet rural. E como o sistema roda em Docker, dá para trocar de provedor depois. O app mobile também compramos, porque ninguém da equipe faz mobile." — **→** "As regras de defensivos precisam de agrônomo. E o Monday, que usamos no trabalho passado, já foi uma decisão de comprar." — **→** "Decidido o que comprar, escrevemos a declaração do trabalho, o SOW: o que o app faz, como vamos aceitar e as cláusulas. Também saem daqui os documentos de licitação (RFI, RFQ e RFP) e os critérios de escolha."

**09 · 12.2 Conduzir: RFP para 3 fábricas** (2 cliques)
"Com o SOW pronto, mandamos um pedido de proposta para três fábricas de software. Se fosse só pelo preço, a fábrica A ganharia, com R$ 33 mil." — **→** "Mas o critério, definido antes, era 60% técnica e 40% preço. A A nunca fez app offline e cai para último. A B, que já fez app de campo, ganha com 9,03. Pagamos R$ 3.400 a mais, mas no talhão sem sinal o offline é tudo." — **→** "Na negociação, fechamos por hora com teto de R$ 40 mil, entrega por sprint e pagamento só do que for aceito. Saída do processo: fornecedor escolhido e contrato assinado. Agora o João mostra como a gente controla isso."

---

## João Augusto

**10 · Vez do João** (slide com o nome) — "Contrato assinado. E agora, como a gente controla?"

**11 · 12.3 Controlar: as 5 cenas** (5 cliques)
"O controle garante que o combinado está sendo cumprido. Vamos ver cinco situações do nosso projeto." — **→** "Cena 1: na sprint 3, a fábrica faturou 130 horas, mas só entregou o equivalente a 100. Pela análise de valor agregado, o CPI é 0,77: cada real pago virou 77 centavos de entrega. E a integração com a API é atividade crítica, com folga zero no nosso cronograma." — **→** "Cena 2: o Seu Ricardo pediu alerta de boleto, que estava fora do escopo. Isso vira um pedido de mudança e, se for aprovado, um aditivo no contrato." — **→** "Cena 3: a fatura da nuvem subiu por transferência de dados. Por isso temos alerta de orçamento." — **→** "Cena 4: o pentest achou uma falha. Só pagamos depois do reteste e do aceite." — **→** "Cena 5: no encerramento, recebemos o código e a documentação, revogamos acessos e registramos as lições aprendidas."

**12 · Vantagens e desvantagens** (1 clique)
"Comprar de fora tem vantagens claras, e todas aparecem no nosso projeto: especialistas que não temos, velocidade, menos custo fixo com a nuvem, risco transferido nos contratos de preço fixo, foco no que sabemos fazer e competição entre fornecedores." — **→** "Mas tem desvantagens, e para cada uma a gente tem uma resposta. Ficar preso à AWS? O sistema roda em Docker. Menos controle sobre o código? Demo por sprint. Dados da fazenda com terceiros? NDA e LGPD. E o contrato por hora com teto deixa espaço para mudanças como o alerta de boleto."

**13 · Contratos e seleção** (3 cliques)
"A escolha mais importante do planejamento é o tipo de contrato, porque ele decide quem paga se der errado. No preço fixo, o risco é do fornecedor. Usamos na consultoria e no pentest, que têm escopo claro." — **→** "No tempo e material, paga-se por hora e o risco é dividido. É o caso do app, em que o escopo pode mudar. Por isso colocamos um teto." — **→** "Nos custos reembolsáveis, o risco fica todo com quem compra. Não usamos em nenhuma compra. Seria para algo muito incerto, como uma pesquisa com IA." — **→** "E para cada compra usamos um método de seleção diferente: menor preço no tablet, qualificação na agrônoma, técnica e preço no app, orçamento fixo no pentest e fonte única no domínio. Agora o Jhonatan mostra quanto tudo isso custa."

---

## Jhonatan Zago

**14 · Vez do Jhonatan** (slide com o nome) — "Para fechar, vou mostrar quanto tudo isso custa e um caso real em que deu errado."

**15 · Quanto custam as aquisições** (2 cliques)
"Pesquisamos preços reais de mercado. A nuvem sai por cerca de R$ 1.650 por ano, o domínio R$ 40, as ferramentas R$ 2.450 no semestre, o tablet R$ 2.700, a consultoria R$ 3.200, o pentest R$ 12 mil e o app R$ 36.400. No total, cerca de R$ 58 mil." — **→** "Olhem o tamanho do app: 62% de tudo. É onde o controle precisa ser mais forte." — **→** "E é exatamente o tipo de compra que deu errado num caso real muito famoso."
*Se perguntarem se dava para fazer mais barato:* "GitHub e Monday têm planos gratuitos. Economizaríamos uns R$ 2 mil, mas perderíamos o Gantt e as dependências. É uma decisão consciente de fazer ou comprar."

**16 · HealthCare.gov × O Gerente** (4 cliques)
"O HealthCare.gov foi o portal do governo americano para contratar planos de saúde. O contrato da fornecedora CGI foi de 56 para mais de 209 milhões de dólares, era de custos reembolsáveis (com o risco todo com o governo), teve cerca de 40 mudanças aprovadas sem autoridade, e a CGI acabou substituída." — **→** "Comparando com o que fizemos: no planejamento, eles não tinham estratégia. A gente fez fazer ou comprar e o SOW." — **→** "Na condução, eles assinaram sem escopo claro. A gente definiu os pesos antes e colocou teto." — **→** "No controle, eles pagaram mesmo com entrega ruim. A gente acompanha o CPI e só paga o que foi aceito." — **→** "A conclusão oficial é que a falha foi de gestão, não de tecnologia."

**17 · Como a boa gestão leva ao sucesso** (4 cliques)
"Então, como uma boa gestão de aquisições leva ao sucesso?" — **→** "O custo fica sob controle, com teto e alerta de fatura. E o prazo também, porque as entregas da fábrica estão amarradas ao nosso caminho crítico." — **→** "A qualidade é garantida com critério de aceite e reteste, e o risco é dividido de propósito, escolhendo o contrato certo." — **→** "Temos segurança jurídica. E a área se integra com todas as outras que os colegas apresentaram." — **→** "Para lembrar: o O Gerente só chega na mão do Luciano porque a gente comprou bem e controlou cada compra. Quem gerencia bem o que compra controla o projeto inteiro."

**18 · Obrigado e referências**
"Nossa base foi o Guia PMBOK, 6ª edição, os relatórios oficiais sobre o HealthCare.gov e o nosso próprio projeto. Obrigado pela atenção. Ficamos à disposição para perguntas."

---

## Perguntas prováveis

- **"Esses valores são reais?"** Os preços de nuvem, ferramentas, domínio e tablet são de lista, pesquisados em nov/2026. A hora da fábrica, o pentest e a consultoria estão dentro das faixas de mercado. Horas e notas técnicas das 3 fábricas são um cenário simulado.
- **"Por que não usar custos reembolsáveis?"** Nenhuma das nossas compras tem escopo tão incerto. É o contrato que deixa todo o risco com quem compra, o mesmo do HealthCare.gov.
- **"O que é CPI?"** Índice de desempenho de custo = valor entregue ÷ custo real. Abaixo de 1 significa que se está pagando mais do que recebe.
- **"Qual a diferença entre RFI, RFQ e RFP?"** RFI pede informação (quem faz?), RFQ pede cotação (quanto custa?, usado no tablet) e RFP pede proposta completa (como, quando e quanto?, usado no app).
