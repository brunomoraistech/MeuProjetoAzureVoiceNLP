# MeuProjetoAzureVoiceNLP

Avaliação de Sentimentos com o Azure AI Language Studio
Este projeto visa aprimorar o domínio das plataformas Azure Speech Studio e Language Studio, com foco na análise de linguagem natural e fala, especialmente para a detecção de sentimentos.

A funcionalidade "Sentiment and opinion mining", parte integrante do Azure Language Studio, permite identificar emoções positivas, negativas e neutras presentes em frases.

Configurando um Serviço de Linguagem no Azure
Para utilizar o Language Studio, é necessário vincular um recurso de serviço de linguagem à sua conta Azure. Siga estes passos:

Acesse o portal Azure em https://portal.azure.com.

Crie um novo recurso de "Language Service" através da opção "Criar Recurso".

Aguarde a conclusão da implantação do recurso.

Após a criação do recurso "Language Service", é preciso conectá-lo ao Language Studio. Para isso, basta seguir estes passos: 

Visite o Language Studio em https://language.cognitive.azure.com/home.

Na tela inicial, utilize o botão "Selecionar um recurso" para acessar os recursos que você criou.

Teste e Seleção do Serviço no Language Studio
Ao retornar à página principal, após completar os passos anteriores, você verá uma lista de serviços disponíveis para experimentação. Neste teste, optamos pelo serviço "Analisar sentimento e minerar opiniões", localizado na seção "Classificar texto".

Resultados Obtidos
Ao acessar o serviço, é possível carregar o texto a ser examinado, definir o idioma e ativar a opção de mineração de opinião.

# Conclusões e Percepções

Ferramentas para análise de sentimentos e opiniões podem ser extremamente valiosas para automatizar a avaliação de retornos de clientes sobre serviços. Embora essa funcionalidade se mostre bastante eficaz com textos que expressam sentimentos de forma clara, como comentários e reviews de produtos, a ferramenta não parece ter o mesmo desempenho em textos onde a expressão emocional não é tão evidente. Acredito que isso ocorra porque a ferramenta avalia apenas uma frase por vez, sem considerar o contexto mais amplo. Uma tecnologia capaz de estabelecer conexões entre as sentenças e obter uma compreensão geral de todo o texto, em minha opinião, teria um sucesso maior nessa análise.
