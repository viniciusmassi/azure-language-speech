# Aplicação Azure: Language & Speech

Atividade referente ao Lab do módulo: [Seus Primeiros Passos com IA](https://web.dio.me/project/analise-de-sentimentos-com-language-studio-no-azure-ai/learning/8c520fa1-cfbc-4214-b155-f98a36f49f51?back=/track/randstad-analise-de-dados&tab=undefined&moduleId=undefined). 

[![Link do DIO](https://img.shields.io/badge/Acesse%20a%20Plataforma%20DO%20CURSO-E94D5F?style=for-the-badge)](https://web.dio.me/track/randstad-analise-de-dados)

## Language: Analisando uma grande quantidade de comentários
1. Com uma assinatura ativa, é necessário ativar o recurso que vamos utilizar no Azure. No nosso caso será a **Microsoft.CognitiveServices**.
---
2. Primeiro, no [Portal da Azure](https://portal.azure.com/) é necessário encontrar a assinatura que vamos trabalhar, na barra de pesquisa basta digitar *'Subscription'*: <br>
![Assinatura](images/picture1.png) <br>
---
3. Dentro da assinatura, na barra lateral esquerda, encontrar *'Resource providers'*, procurar o Provedor que vamos utilizar (**Microsoft.CognitiveServices**) e apertar em *Registrar* para poder utilizar o recurso.<br> 
![Resource providers](images/picture2.png)<br>
---
4. Primeiro passo é criar o recurso, pela barra lateral esquerda, selecionar *Language Service*, completar as informações e **criar**.<br>
![Criar recurso](images/picture3.png)<br>
---
5. Conferindo quais recursos foram criados ou estão ativos: <br>
![Check](images/picture4.png)<br>
---
6. Agora é necessário entrar no portal da funcionalidade que vamos utilizar, nesse primeiro caso o [Portal Language](https://language.cognitive.azure.com/home).
---
7. Agora linkando o portal com o Azure e escolhendo a opção para trabalhar, para analisar comentários vamos em *Análise de sentimentos*: <br>
![credenciais](images/Picture5.png)<br>
![classificando texto](images/Picture6.png)<br>
---
8. Aqui quando entramos com um texto: <br>
![entrada de texto](images/Picture7.png)<br>
Recebemos uma análise:<br> 
![Saída de análise](images/Picture8.png)<br>
---
9. Para automatizar, utilizar o campo abaixo: <br>
![automatização](images/Picture9.png)<br>
Algumas maneiras de trabalhar aqui encontramos no [GitHub - Análise de sentimentos](https://aka.ms/analyze-sentiment-samples).


## Speech: Transformando fala em texto em tempo real (facilitar análises de recados falados)

Passos de 1 a 5 continuam os mesmos, então seguindo:

6. Entrar no [Portal da Funcionalidade Speech](speech.microsoft.com)
---
7. Nas configurações, conferir se existe recurso criado para a funcionalidade, caso não tenha criar e selecionar: <br>
![recurso speech](images/Picture11.png)<br>
---
8. Aqui podemos inputar audios, no idioma indicado e ter uma análise, como no language: <br>
![input audios](images/Picture12.png)<br>
--- 
9. Abaixo vemos o campo para automatizar: <br>
![automarizar](images/Picture13.png)<br>
Também temos maneiras de fazer isso no [GitHub - Transformar fala em texto](https://github.com/Azure-Samples/cognitive-services-speech-sdk)