IA_Prompt_Project - README

Este projeto em Python oferece um prompt interativo no Google Colab para interação com a API do Google GENAI, utilizando modelos de linguagem avançados.


Descrição:

O programa configura um modelo de prompt no código e estabelece uma conexão com a API do Google GENAI, permitindo que os usuários interajam com o modelo através de um prompt intuitivo. As respostas geradas pelo modelo são exibidas de forma clara, proporcionando uma experiência de conversação fluida.


Funcionalidades:

Configuração simplificada: O código inclui instruções passo-a-passo para configurar a API Key do Google, garantindo um processo de instalação fácil e rápido.

Listagem de modelos: O programa lista os modelos disponíveis no Google GENAI que suportam a geração de conteúdo, permitindo que os usuários escolham o modelo mais adequado para suas necessidades.

Prompt interativo: O programa oferece um prompt interativo no Google Colab, onde os usuários podem inserir suas perguntas e receber respostas do modelo em tempo real.

Personalização: É possível ajustar as configurações de segurança e geração, adaptando o comportamento do modelo às suas preferências.

Visualização aprimorada: O programa usa formatação Markdown para exibir o histórico de conversação de forma organizada e fácil de ler.



Pré-requisitos:

 - Conta do Google com acesso ao Google Colab
 - API Key do Google Generative AI

Instalação:

1 - Abra o arquivo IA_Prompt_Project.ipynb no Google Colab.

2 - Execute a célula de código para instalar o SDK do Google Generative AI.

3 - Insira sua API Key do Google na célula de código correspondente.

4 - Execute as células de código restantes para configurar o modelo e iniciar o prompt interativo.

Utilização:

1 - Insira sua pergunta no prompt interativo.

2 - Pressione Enter para enviar a pergunta ao modelo.

3 - O modelo gerará uma resposta, que será exibida no prompt.

4 - Continue a inserir perguntas e receber respostas até desejar sair do prompt.

5 - Para sair do prompt, digite "fim" e pressione Enter.


Personalização:

Você pode personalizar o comportamento do modelo ajustando as configurações de segurança e geração nas células de código correspondentes. Consulte a documentação do Google GENAI para obter mais informações sobre as opções disponíveis.

Exemplo:

Esperando prompt: Me diga algumas curiosidades sobre a Rússia.

Resposta: * A Rússia é o maior país do mundo em área terrestre...

Esperando prompt: fim

Observações:

Este programa utiliza o modelo "gemini-1.0-pro" por padrão, mas você pode escolher outro modelo da lista de modelos disponíveis.
As configurações de segurança estão definidas para permitir todos os tipos de conteúdo. Você pode ajustar essas configurações de acordo com suas preferências.
A temperatura define a criatividade do modelo. Uma temperatura mais alta resulta em respostas mais criativas, enquanto uma temperatura mais baixa resulta em respostas mais deterministas.

Suporte:

Se você encontrar algum problema ao usar este programa, consulte a documentação do Google GENAI ou entre em contato com o suporte do Google Cloud.
