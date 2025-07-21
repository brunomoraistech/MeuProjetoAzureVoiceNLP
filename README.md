# MeuProjetoAzureVoiceNLP
MeuProjetoAzureVoice
Análise de Sentimentos com Language Studio no Azure AI
Análise de Sentimentos com Language Studio no Azure AI. Praticar e aprofundar o uso das ferramentas Azure Speech Studio e Language Studio, focando na análise de fala e linguagem natural.

Sentiment and opinion mining é uma solução da plataforma Language Studio, da Azure, que permite detectar sentimentos positivos, negativos e neutros a partir de sentenças.

Static Badge Static Badge Static Badge Static Badge

Criar um recurso Azure Language Service
Para usar o Language Studio, é preciso que você possua um recurso para a plataforma associado a sua conta Azure. siga os seguintes passos:

Acessar https://portal.azure.com
Criar um novo recurso Language Service através da opção Create Resource.
Esperar o deploy do recurso terminar.
Com o recurso Language Service criado, é preciso conecta-lo ao Language Studio. Para isso, basta seguir os seguintes passos:
-Acessar o Language Studio.
-Na página inicial, acessar os recursos criados através do botão "Select a resouce". 5.Selecionando e testando o serviço no Language Studio Ao retornar a página inicial após concluídos os passos anteriores, é possível ver a lista de serviços disponíveis para teste na plataforma. Nesse experimento foi usado o serviço "Analyze sentiment and mine opinions", na aba "Classify text". 6.Resultados Ao acessar o serviço é possível carregar o texto a ser analisado, selecionar sua linguagem e também ativar a opção de opinion mining.

Conclusão e Insights
Ferramentas de análise de sentimentos e opiniões podem ser muito úteis na automação de análises de feedbacks para serviços. Apesar desse recurso funcionar muito bem para textos que claramente visam expressar sentimentos, como é o caso de comentários e avaliações de produtos, a ferramenta não parece se sair tão bem em textos onde essa expressão não é tão clara. Acredito que esse resultado se deve ao fato de que a ferramenta analisa apenas uma sentença por vez e não parece levar em consideração todo o contexto. Penso que uma tecnologia capaz de estabelecer conexões entre sentenças e obter um entendimento geral sobre o contexto de todo o texto possivelmente seria mais bem sucedida nessa análise.
