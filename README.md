# 🎓 EduSales AI

## Copiloto de Vendas com IA para Atendimento ao Cliente

O EduSales AI é uma solução de Inteligência Artificial desenvolvida para apoiar equipes comerciais de instituições de ensino no atendimento e na venda de cursos.

A solução funciona como um copiloto para vendedores e atendentes, ajudando a compreender as necessidades dos potenciais alunos, identificar objeções, recomendar cursos e sugerir o próximo passo da negociação.

---

## 🎯 Problema

Durante um atendimento comercial, o vendedor precisa compreender rapidamente o perfil do potencial aluno, identificar suas necessidades, responder dúvidas, lidar com objeções e escolher o momento adequado para apresentar uma oferta.

Quando esse processo é realizado sem uma estrutura adequada, podem ocorrer:

- Respostas genéricas;
- Recomendações inadequadas;
- Falta de personalização;
- Dificuldade para lidar com objeções;
- Informações comerciais incorretas;
- Abordagens excessivamente agressivas.

---

## 💡 Solução

O EduSales AI utiliza Inteligência Artificial como apoio ao vendedor.

Em vez de substituir o profissional, a IA analisa a conversa e fornece orientações para que o vendedor possa tomar uma decisão mais adequada.

O sistema segue uma abordagem consultiva:

**Compreender → Identificar → Recomendar → Conduzir**

---

## 👥 Público-alvo

O projeto foi desenvolvido pensando principalmente em:

- Vendedores;
- Atendentes;
- Equipes comerciais;
- Instituições de ensino;
- Empresas que comercializam cursos.

---

## 🤖 Funcionalidades

O EduSales AI é capaz de:

- Identificar o objetivo do potencial aluno;
- Identificar seu interesse;
- Analisar seu nível de conhecimento;
- Identificar possíveis objeções;
- Avaliar a intenção de compra;
- Recomendar cursos compatíveis;
- Sugerir respostas para o vendedor;
- Sugerir o próximo passo do atendimento;
- Evitar informações comerciais inventadas.

## 🛠️ Tecnologias e recursos.

## 🧠 Prompt final utilizado

O prompt final utilizado para orientar o EduSales AI está disponível no arquivo:

`prompts/prompt-copiloto.md`

O prompt define:

- O papel da IA como copiloto de vendas;
- A utilização da base de conhecimento;
- O processo de análise do cliente;
- A identificação de informações faltantes;
- O tratamento de objeções;
- Os critérios para recomendação de cursos;
- As regras de segurança comercial;
- O formato obrigatório das respostas;
- O tom de voz do atendimento.

### Princípio central

> Compreender primeiro. Recomendar depois. Conduzir somente quando fizer sentido.

O prompt completo utilizado no desenvolvimento e nos testes está disponível em `prompts/prompt-copiloto.md`.

---

## 🧠 Base de conhecimento

O projeto utiliza uma base de conhecimento fictícia da instituição educacional Educa+.

A base contém:

### Contexto do negócio

Informações sobre a Educa+, seu público-alvo, modelo de atendimento e princípios comerciais.

### Cursos

Informações sobre os cursos disponíveis:

- Inglês para Comunicação;
- Inteligência Artificial para Profissionais;
- Marketing Digital;
- Excel para o Mercado de Trabalho;
- Design Gráfico.

### Perguntas frequentes

Informações sobre modalidade, acesso, certificado, matrícula, conhecimento prévio e outras dúvidas comuns.

### Objeções comerciais

Estratégias para lidar com objeções como:

- "Está muito caro";
- "Vou pensar";
- "Não tenho tempo para estudar";
- "Vou pesquisar outras escolas";
- "Não sei se esse curso vai me ajudar";
- "Não tenho experiência nessa área";
- "Preciso conversar com outra pessoa antes".

---

## 🔒 Regras de segurança comercial

O EduSales AI não deve:

- Inventar preços;
- Inventar descontos;
- Inventar condições de pagamento;
- Inventar prazos;
- Inventar políticas de cancelamento;
- Inventar características dos cursos;
- Prometer emprego;
- Prometer aumento salarial;
- Prometer promoção;
- Fazer afirmações negativas sobre concorrentes;
- Pressionar o cliente.

Quando uma informação não estiver disponível na base de conhecimento, a IA deve orientar o vendedor a verificar a informação antes de responder.

---

## 🧩 Funcionamento

O fluxo de análise do EduSales AI segue estas etapas:

1. **Compreender o cliente**
2. **Identificar informações faltantes**
3. **Identificar objeções**
4. **Recomendar um curso quando houver informações suficientes**
5. **Conduzir para o próximo estágio quando fizer sentido**

A IA também utiliza uma pergunta principal por vez quando ainda são necessárias informações para compreender o cliente.

---

## 📝 Formato da resposta

O copiloto organiza suas respostas em quatro partes:

### Análise do cliente

Identificação do objetivo, interesse, nível de conhecimento, disponibilidade, objeções, intenção de compra e estágio da decisão.

### Estratégia recomendada

Orientação sobre a abordagem que o vendedor deve utilizar.

### Resposta sugerida

Mensagem que pode ser adaptada e enviada ao potencial aluno.

### Próximo passo

Indicação de uma única ação principal para continuar o atendimento.

---

## 🧪 Testes

O comportamento do EduSales AI foi testado utilizando diferentes situações de atendimento.

Entre os cenários testados está um potencial aluno interessado em Inteligência Artificial que questiona a necessidade de pagar por um curso, pois acredita que pode aprender utilizando vídeos gratuitos no YouTube.

Nesse teste, a IA:

- Identificou corretamente o interesse em Inteligência Artificial;
- Identificou a objeção relacionada ao valor percebido;
- Não desvalorizou os conteúdos gratuitos;
- Utilizou informações presentes na base de conhecimento;
- Não inventou descontos ou condições comerciais;
- Sugeriu uma pergunta para compreender melhor a necessidade do cliente;
- Indicou como próximo passo a investigação da objeção.

## 💬 Demonstração

### Situação

Um potencial aluno demonstra interesse no curso de Inteligência Artificial, mas questiona a necessidade de pagar por uma formação, pois acredita que pode aprender utilizando vídeos gratuitos no YouTube.

### Entrada do cliente

> "Eu gostei do curso de IA, mas sinceramente acho que consigo aprender tudo isso sozinho usando vídeos gratuitos no YouTube. Por que eu deveria pagar por um curso?"

### Análise gerada

- **Objetivo:** Aprender Inteligência Artificial.
- **Interesse:** Inteligência Artificial para Profissionais.
- **Possível objeção:** Percepção de que conteúdos gratuitos podem atender à necessidade sem investimento financeiro.
- **Intenção de compra:** Interesse no curso, mas questiona o valor do investimento.
- **Estágio da decisão:** Consideração/comparação.

### Estratégia

Não desvalorizar conteúdos gratuitos nem simplesmente defender o preço do curso.

A IA deve compreender o que o cliente considera importante em uma formação e identificar quais características de uma formação estruturada são relevantes para sua necessidade.

### Resposta sugerida

> "Faz sentido pensar assim. Existem mesmo muitos conteúdos gratuitos sobre IA, e vale a pena comparar as opções antes de investir.
>
> A questão é entender o que você procura em um curso. No caso da nossa formação, ela aborda fundamentos de IA, IA generativa, engenharia de prompts, ferramentas de IA, automação de tarefas e aplicações profissionais.
>
> Para você, o que seria mais importante em uma formação: ter um conteúdo mais estruturado ou conseguir aplicar o que aprende diretamente no seu trabalho?"

### Próximo passo

**Investigar a objeção.**

O objetivo é entender o que o potencial aluno considera necessário para que um curso de IA tenha valor para ele.

## 📁 Estrutura do projeto

```text
edusales-ai/
│
├── knowledge/
│   ├── contexto-do-negocio.md
│   ├── cursos.md
│   ├── perguntas-frequentes.md
│   └── objecoes.md
│
├── prompts/
│   └── prompt-copiloto.md
│
├── exemplos/
│   ├── atendimento-01.md
│   ├── atendimento-02.md
│   ├── atendimento-03.md
│   └── atendimento-04.md
│
└── README.md
