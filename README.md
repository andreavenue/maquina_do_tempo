# Chatbot de Viagem no Tempo

## Prepare-se para uma Jornada Inimaginável Através do Tempo!

**Abrace a História como nunca antes!** Nosso chatbot de viagem no tempo oferece uma oportunidade única de conversar com as mentes mais brilhantes e figuras mais fascinantes da história. Imagine debater filosofia com Sócrates, decifrar hieróglifos com Cleópatra, ou desvendar os mistérios do universo com Albert Einstein! 

**Uma Experiência Interativa e Divertida:** Escolha sua época, selecione seu personagem e mergulhe em um diálogo envolvente e cheio de surpresas. Cada resposta molda o curso da conversa, criando uma aventura personalizada e memorável.

## Recursos Exclusivos:

*   **Diálogos ramificados:** Suas escolhas influenciam o rumo da conversa, revelando novos aspectos dos personagens e da época.
*   **Humor e inteligência:** Personagens históricos ganham vida com personalidades cativantes, repletas de humor, ironia e referências inteligentes à cultura moderna. 
*   **Atividades interativas:**  Decifre enigmas, participe de jogos e embarque em missões que aprofundam sua imersão na história.

## Prepare-se para:

*   **Expandir seus conhecimentos:**  Aprenda sobre história, cultura, ciência e arte através de conversas envolventes e informativas.
*   **Testar sua inteligência:**  Desafie-se com enigmas e jogos criados pelas mentes mais brilhantes da história.
*   **Rir e se divertir:**  Experimente a história de uma maneira leve e divertida, com personagens cativantes e diálogos cheios de humor.

**Embarque nesta aventura inesquecível e reescreva a história com suas próprias mãos!**

## Descrição

Este projeto em Python utiliza a API do Google Gemini para simular uma viagem no tempo através de um chatbot interativo. O objetivo é proporcionar uma experiência imersiva, permitindo que o usuário converse com figuras históricas renomadas como se estivesse realmente dialogando com elas. 

O chatbot é capaz de gerar diálogos autênticos e coerentes, respondendo a perguntas, fornecendo informações relevantes e mantendo a personalidade do personagem escolhido.

## Funcionamento

O código define um conjunto de personagens históricos disponíveis para interação:

* **Moisés:** O profeta bíblico, figura central no Antigo Testamento.
* **Cleópatra:** A última faraó do Egito, conhecida por sua inteligência e poder político.
* **Leonardo da Vinci:** Artista, inventor e cientista renascentista, considerado um dos maiores gênios da história.
* **Albert Einstein:** Físico revolucionário do século XX, famoso por sua Teoria da Relatividade.

Após a escolha do personagem, o chatbot apresenta um menu de tópicos relacionados à vida e obra da figura histórica selecionada. O usuário pode navegar por esses tópicos, fazendo perguntas e recebendo respostas detalhadas. As respostas são elaboradas pelo modelo de linguagem do Google Gemini, que garante a precisão histórica e a fluidez da conversa.

## Tecnologias Utilizadas

* **Python:** Linguagem de programação utilizada para desenvolver o chatbot.
* **Google Gemini:** Modelo de linguagem avançado, responsável pela geração de texto, compreensão da linguagem natural e personalização dos diálogos.
* **IPython:** Biblioteca que permite a exibição de texto formatado com Markdown, proporcionando uma interface mais agradável para o usuário.

## Como Usar

1. **Instalar Dependências:** 
    * Certifique-se de ter o Python instalado em seu sistema.
    * Instale a biblioteca `google-generativeai` executando o seguinte comando:
      ```bash
      pip install -q -U google-generativeai
      ```

2. **Configurar a Chave de API:**
    * Obtenha sua chave de API do Google Gemini.
    * Substitua o texto `'COLE_A_API_AQUI'` no código pela sua chave de API.

3. **Executar o Script:**
    * Execute o arquivo `maquina_do_tempo_chatbot.py`.

4. **Interagir com o Chatbot:**
    * Siga as instruções fornecidas pelo chatbot, escolhendo um personagem e navegando pelos tópicos disponíveis.
    * Digite suas perguntas e explore a história através das respostas geradas.

## Personalização

O código pode ser personalizado para:

* **Adicionar Novos Personagens:** Inclua mais figuras históricas, expandindo as opções de interação.
* **Criar Novos Tópicos:** Amplie as opções de conversa para cada personagem, aprofundando o nível de detalhes.
* **Ajustar a Criatividade:** Modifique os parâmetros `temperature` e `candidate_count` na seção `generation_config` para controlar a criatividade e o número de respostas geradas.
* **Refinar a Segurança:** Utilize as configurações de segurança em `safety_settings` para garantir que as respostas sejam adequadas ao público-alvo.

## Observações

* Este projeto demonstra o potencial da API do Google Gemini para criar experiências interativas e educativas. 
* A qualidade das respostas depende da qualidade dos dados utilizados no treinamento do modelo. 
* O Google Gemini está em constante desenvolvimento, o que significa que a precisão e a fluidez dos diálogos podem melhorar com o tempo.
