# 🌍 Guia do Mochileiro Nacional – 1 ou 2 pessoas

[![NotebookLM](https://img.shields.io/badge/NotebookLM-Google-blue)](https://notebooklm.google.com)
[![DIO](https://img.shields.io/badge/DIO-Desafio%20Projeto-purple)]()

## 📌 Contexto e Objetivos

Este projeto faz parte do desafio **"Criando um Caderno Temático com NotebookLM"** da DIO.  
O tema escolhido foi **planejamento financeiro para viagens nacionais econômicas**, com foco em quem acabou de terminar os estudos e quer desbravar o Brasil com pouco dinheiro.

**Persona real:** Um jovem recém-formado que sonha em fazer uma viagem de mochileiro, mas não sabe como transformar R$ 100 guardados por mês em uma experiência real. O caderno foi pensado tanto para viajantes solo quanto para casais.

**Objetivos do caderno temático:**
- Ensinar um passo a passo prático de preparação financeira para uma viagem nacional.
- Comparar custos reais de transporte, hospedagem e alimentação usando dados de plataformas como Decolar, Airbnb, Trivago e ClickBus.
- Fornecer um orçamento-modelo (São Paulo → Florianópolis, 10 dias) que qualquer pessoa possa adaptar.
- Consolidar dicas e um checklist reutilizável em um miniguia de bolso.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM, foram selecionadas **5 fontes abertas e confiáveis**, todas em português e com dados reais de mercado:

1. **Decolar – Blog e página de passagens**  
   *Dicas de antecedência de compra (30-90 dias), opções de pagamento parcelado e busca de voos econômicos.*  
   🔗 [Link da página utilizada] <!-- substitua pelo link exato que você usou -->

2. **Airbnb – Central de Ajuda: Como funcionam as reservas**  
   *Informações sobre pagamento via Pix, política de cancelamento e tipos de acomodação.*  
   🔗 [Link da página utilizada]

3. **ClickBus – Relatório de Mercado Rodoviário (PDF)**  
   *Dados estatísticos: preço médio da passagem de ônibus no Brasil (R$ 101,77) e valores por região.*  
   🔗 [Link do PDF utilizado]

4. **Trivago – Comparador de hotéis**  
   *Ferramenta de busca e filtros de preço em mais de 100 sites, base para o comparativo de hospedagem.*  
   🔗 [Link da página utilizada]

5. **Ministério do Turismo – Guia “Dicas para Atender Bem Turistas”**  
   *Cartilha oficial com orientações sobre planejamento de viagens e segurança.*  
   🔗 [Link do PDF utilizado]

*(Opcional) Transcrição de vídeo:*  
📹 Vídeo do YouTube sobre “planejamento financeiro para viajar barato” – convertido em texto via `youtranscript.com` e adicionado como fonte complementar.

Todas as fontes foram carregadas no NotebookLM, gerando automaticamente um resumo que serviu de base para as respostas.

---

## 🧪 Engenharia de Prompts e “Cicatrizes”

Aqui está o diário de bordo das interações com o NotebookLM, incluindo os prompts, as dificuldades e os aprendizados.

### Primeira tentativa (conversa natural)
O notebook foi criado vazio e o assistente alertou que sem fontes as respostas seriam genéricas.  
**Prompt inicial:** *“Quais as praias mais baratas para viajar?”*  
**Resposta:** Lista de destinos (João Pessoa, Maceió, Cabo Frio) sem valores exatos.  
**Cicatriz:** A IA pediu que eu fizesse upload de fontes para ancorar os dados. Fiz a curadoria de PDFs e páginas web.

### Iteração principal – Prompt estruturado (11 seções)
Com as fontes carregadas, submeti um prompt longo solicitando um guia completo dividido em 11 seções, desde a introdução motivacional até um prompt reutilizável.  
**Resposta obtida:** O NotebookLM gerou o **Guia do Mochileiro Nacional** exatamente como pedido, com tabelas, comparativos e citações das fontes (ex: “segundo a ClickBus”, “no Airbnb”).  

**Aha moment:** Os números reais apareceram (média da passagem de ônibus R$ 101,77; refeição R$ 40,64).  
**Alucinação detectada:** Em uma versão anterior, a IA sugeriu valores de hotel que não batiam com o Trivago. Refinei o prompt pedindo “dados exclusivamente das fontes” e o problema foi corrigido.

### Geração de materiais complementares (Estúdio)
Testei os recursos de **Áudio, Vídeo, Flashcards e Tabela de Dados** do NotebookLM.  
**Prompts utilizados:**
- Para áudio: *“Crie um podcast estilo Deep Dive com foco em dicas financeiras para mochileiros.”*  
- Para vídeo: *“Gere um vídeo Explainer sobre o passo a passo da preparação financeira.”*  
- Para flashcards: *“Perguntas essenciais de planejamento de viagem nacional.”*

**Dificuldade:** O vídeo ainda é experimental; a qualidade visual depende muito do formato escolhido (Whiteboard foi o que melhor se adaptou). Aprendi que é crucial descrever o foco dos “apresentadores de IA” para direcionar a conversa.

---

## 📘 Miniguia de Estudo (Entrega Final)

> *Este guia foi elaborado para você, que acabou de concluir seus estudos e quer desbravar o Brasil com inteligência financeira. Utilizando dados reais das principais plataformas de viagem, mostramos que o "mochilão" dos sonhos é viável com organização.*

---

### 1. Introdução Motivacional
Viajar pelo Brasil representa a conquista da liberdade e a chance de expandir horizontes após anos de dedicação aos estudos. O orçamento curto não deve ser um bloqueio, mas um convite ao planejamento criativo. Nosso país possui um dos mercados rodoviários mais **democráticos do mundo**, atendendo a mais de 4.600 destinos, o que permite que viajantes com poucos recursos consigam chegar a lugares incríveis de forma digna e acessível.

### 2. Passo a Passo da Preparação Financeira
1.  **Definição do Teto de Gastos:** Estabeleça quanto você pode gastar no total antes de escolher o destino.
2.  **Antecedência Estratégica:** No setor aéreo, comprar entre **30 a 40 dias antes** pode gerar uma economia de até **800%**. Para ônibus, a compra online antecipada garante assentos em datas de alta procura.
3.  **Uso de Filtros de Busca:** Utilize ferramentas como o **trivago** para comparar preços de mais de 100 sites simultaneamente, focando no filtro "Preço e sugestões".
4.  **Pagamento Inteligente:** A Decolar oferece a opção de **boleto parcelado**, ideal para quem não quer comprometer o limite do cartão de crédito. No Airbnb, utilize o **Pix** para pagamentos rápidos no Brasil.

### 3. Categorias de Gastos e Faixas de Preço
Baseado nas médias nacionais das fontes:
*   **Transporte Rodoviário:** Preço médio nacional de **R$ 101,77**.
*   **Transporte Aéreo:** Média doméstica de **R$ 349,14** (podendo variar drasticamente sem antecedência).
*   **Hospedagem:** Diárias no Airbnb a partir de **R$ 60**. Hotéis 3 estrelas em capitais econômicas como Curitiba custam em média **R$ 367**.
*   **Alimentação:** Custo médio de uma refeição no Brasil é de **R$ 40,64**.
*   **Seguro e Imprevistos:** Recomenda-se reservar **10% do orçamento total** para emergências.

### 4. Comparativo de Transportes (Trecho de 800 km)
Considerando o trajeto de Manaus x Boa Vista (782 km):

| Modal | Previsibilidade Financeira | Custo Médio (1 pessoa) | Custo Médio (Casal) |
| :--- | :--- | :--- | :--- |
| **Ônibus** | Alta (Preços estáveis) | ~R$ 137,37 | ~R$ 274,74 |
| **Avião** | Baixa (Varia com antecedência) | ~R$ 349,14 | ~R$ 698,28 |
| **Carro** | Média (Combustível em alta) | Alto (Aluguel + Gasolina) | Vantajoso se dividido |

**Veredito:** O ônibus é a opção mais econômica, custando geralmente **1/3 do valor do avião**. Além disso, evita "custos ocultos" como taxas de bagagem e deslocamento caro até aeroportos afastados.

### 5. Comparativo de Hospedagem (Salvador - 7 dias)
| Tipo de Estadia | Valor Médio Diária | Total 7 dias (Casal) | Diferencial |
| :--- | :--- | :--- | :--- |
| **Airbnb (Espaço Inteiro)** | R$ 173 | R$ 1.211 | Possui cozinha equipada para economizar. |
| **Airbnb (Quarto Comp.)** | R$ 60 | R$ 420 | Opção mais barata disponível. |
| **Hotel 3\* (Trivago)** | R$ 240 a R$ 685 | R$ 1.680 a R$ 4.795 | Café da manhã e serviço de quarto. |

**Melhor custo-benefício para casal:** **Airbnb (Espaço Inteiro)**, pela privacidade e economia ao cozinhar em casa.

### 6. Dicas para Alimentação e Lazer
*   **Almoço Econômico:** Priorize restaurantes **"por quilo"**, ocupando o prato com saladas para não pesar na balança e evitar bebidas calóricas.
*   **Regra de Ouro:** O almoço é sempre mais barato que o jantar devido aos menus executivos.
*   **Supermercados:** Faça uma visita ao mercado local para abastecer o frigobar e fazer piqueniques.
*   **Passeios Gratuitos:** Explore centros históricos e trilhas autoguiadas, que reduzem o custo de lazer.

### 7. Orçamento Detalhado: São Paulo x Florianópolis (10 dias)

| Categoria | 1 Pessoa (Mochileiro) | Casal (Econômico) |
| :--- | :--- | :--- |
| **Transporte (Bus Ida/Volta)** | R$ 380,00 | R$ 760,00 |
| **Hospedagem (Airbnb)** | R$ 1.000,00 | R$ 1.730,00 |
| **Alimentação** | R$ 600,00 | R$ 1.200,00 |
| **3 Passeios Pagos** | R$ 300,00 | R$ 600,00 |
| **Seguro Viagem** | R$ 100,00 | R$ 200,00 |
| **Reserva Emergência (10%)** | R$ 238,00 | R$ 449,00 |
| **TOTAL** | **R$ 2.618,00** | **R$ 4.939,00** |

### 8. Diferenças entre Viajar Sozinho e em Casal
*   **Divisão de Custos:** Viajar em casal permite dividir a diária do Airbnb e o aluguel de carros, reduzindo o custo por pessoa.
*   **Perfil:** 80% dos viajantes online viajam sozinhos, sendo que 60% são mulheres.
*   **Segurança Solo:** Mulheres sozinhas enfrentam desafios como medo de violência de gênero. Recomenda-se usar ferramentas de **compartilhamento de trajeto em tempo real** e evitar cantos isolados em restaurantes.

### 9. Formas Realistas de Levantar Dinheiro Extra
*(Sugestões de senso comum, pois não detalhadas nas fontes)*:
1.  **Venda de Desapegos:** Utilize apps para vender roupas e eletrônicos que não usa mais.
2.  **Freelance Pós-Estudos:** Ofereça serviços de monitoria, redação ou design para alunos mais novos.
3.  **Economia Reversa:** Crie um "fundo de viagem" cortando assinaturas de streaming por 6 meses antes da partida.

### 10. Checklist Financeiro Pré-Embarque
*   [ ] **Confirmação de Reserva:** Verifique se o pagamento no Airbnb ou Decolar foi aprovado para evitar cancelamentos de última hora.
*   [ ] **Documentação Original:** RG ou CNH com foto são obrigatórios para embarque rodoviário e aéreo.
*   [ ] **App do Banco:** Habilite o uso do cartão em outras cidades e verifique o limite do Pix.
*   [ ] **Aplicativo de Transporte:** Tenha o app da viação (ex: 1001) para bilhete eletrônico e embarque direto.
*   [ ] **Seguro Ativado:** Verifique se o seu cartão de crédito oferece seguro viagem gratuito ou se o seguro da viação está incluso na taxa.

### 11. Prompt Reutilizável
> "Você é um consultor financeiro de turismo. Com base em fontes de economia real, crie um guia de viagem econômico de **[NÚMERO]** dias para **[DESTINO]** para **[QUANTIDADE]** pessoas. Inclua comparativo de transporte (bus vs avião), sugestão de Airbnb vs Hotel via Trivago e um orçamento diário focado no perfil mochileiro recém-formado."

**Boa jornada, mochileiro! O Brasil é enorme e está ao seu alcance.**

---

## 🧠 Aprendizados e Metodologia para Estudos com IA
Este projeto mostrou que o NotebookLM é muito mais que um gerador de texto: é uma ferramenta de **aprendizagem ativa** quando alimentada com boas fontes.  
Minha metodologia:
1. **Curadoria intencional** – escolher fontes variadas (blogs, PDFs de mercado, guias oficiais) para evitar viés.
2. **Engenharia de prompts progressiva** – partir do geral para o específico, sempre exigindo citações.
3. **Validação cruzada** – conferir manualmente se os números gerados batem com a realidade (ex: entrar no site da ClickBus para ver o preço real da passagem).
4. **Síntese multimídia** – usar os recursos do Estúdio (áudio, vídeo, flashcards) para reforçar o aprendizado.
completo. Projeto realizado no NotebookLM com foco em acessibilidade e aplicação prática."*

Feito isso, é só comemorar! Seu projeto está pronto para decolar. ✈️
