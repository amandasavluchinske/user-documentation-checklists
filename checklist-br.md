## Checklist de documentação para usuários

- [ ] Se esse é o primeiro pedaço de documentação que você está escrevendo, por favor tente pensar sobre estrutura. Estrutura é extremamente importante para que usuários possam encontrar facilmente o que estão procurando. Você pode ter a melhor documentação do mundo, se você não aliar isso com uma boa estrutura de informação seus usuários podem terminar frustrados como se você não tivesse nenhuma.
- [ ] Aqui estão alguns links sobre como construir uma boa estrutura de informação para a sua documentação:
   - [ ] [Best Practices to Improve Knowledge Base Information Architecture](https://document360.io/blog/knowledge-base-information-architecture/)
   - [ ] [9 tips for awesome user documentation (with examples)](https://www.techsmith.com/blog/awesome-user-documentation/)
   - [ ] [How to build the best user documentation](https://www.techsmith.com/blog/user-documentation/)
   - [ ] [4 steps to creating great user documentation](https://formidableforms.com/4-steps-to-creating-great-end-user-documentation/)
- [ ] Você também pode se inspirar olhando boas documentações de produtos por aí:
   - [ ] [Skype for Windows](https://support.skype.com/en/skype/windows-desktop/) - Note como a estrutura dessa documentação é limpa. Tem ícones grandes e legendas que representam as maiores preocupações dos usuários.
   - [ ] [Asana](https://asana.com/pt/guide) - O Asana por si só já é bem autoexplicativo e usuários com frequência só precisam de algum tempo de exploração antes de usar o produto. De toda forma, eles têm uma estrutura de documentação bem feita, cobrindo dos usuários mais iniciantes até os avançados que procuram executar ações mais complexas. Grande kudos pela quantidade de vídeos e imagens!
   - [ ] [Todoist](https://doist.com/blog/how-to-use-todoist-effectively/) - Essa é uma peça de documentação que foca em introduzir o produto para novos usuários. É limpa e objetiva!
- [ ] Se certifique que você está sendo objetivo. Você precisa manter leitores interessados e ajudá-los a achar o que precisam com facilidade.
- [ ] Pense sobre a sua formatação, ela é extremamente importante! Por exemplo, observe como essa pequena mudança faz o texto ficar muito mais compreensível:

- [ ] RUIM:
   
   ## Linha do tempo

   In this screen, you can view your timeline, which contains the most relevant
   Tweets from everyone you follow. You can also interact with these Tweets by:
   liking them, which you can do by clicking at the heart button in the Tweet's card.
   It will send a notification out to the writer of the Tweet if your Twitter
   is set to public, if it's set to private this notification will not be sent,
   unless the writer of the Tweet follows you. Every time you like a Tweet, it
   will also appear under your liked Tweets in your profile page. Please note that
   everyone will be able to see which Tweets you've liked if your Twitter account
   is set to public. If it's set to private only your followers will be able to
   see your liked Tweets; retweeting them. You can retweet Tweets by clicking at
   the two revolving arrows button in the Tweet's card. This will make the retweeted
   Tweets appear in your own profile, and send out a notification to the Tweet's writer
   if your Twitter account is set to public. If it's set to private it will not send
   a notification to the writer unless they follow you; or replying to them...

- [ ] BOM:

   ## Linha do tempo

   In this screen, you can view your timeline, which contains the most relevant Tweets
   from everyone you follow. You can also interact with these Tweets in various ways.

   ### Curtindo Tweets:
   You can like Tweets by clicking at the heart button in the Tweet's card [image here].
   
   If your Twitter account is set to public, it will send a notification out to the writer
   of the Tweet. If your Twitter account is set to private, this notification will *not* be sent,
   unless the writer of the Tweet follows you.

   #### Tweets Curtidos:
    Every time you like a Tweet it will also appear under your Liked Tweets in your profile
    page. Please note that everyone will be able to see which Tweets you've liked if your
    Twitter account is set to public. If it's set to private only your followers will be
    able to see your liked Tweets.

   ### Retweetando Tweets:
     You can retweet Tweets by clicking at the two revolving arrows button in the Tweet's card [image here].
     This will make the retweeted Tweets appear in your own profile, and send out a notification to the
     Tweet's writer if your Twitter account is set to public. If it's set to private it will not send
     a notification to the writer unless they follow you.

- [ ] Pense nos casos de uso das funcionalidades do seu produto. **Faça uma lista e se certifique que todos os casos estão cobertos.** Ter experiência em primeira mão ajuda muito, então teste todos os fluxos no seu sistema. Depois disso, foque em escrever as _consequências_ de cada caso e suas ações.
   - [ ] Pode te ajudar se você escrever uma lista de todas as ações que podem ser performadas dentro de uma certa funcionalidade!
- [ ] Certifique-se de que você está explicando coisas (relevantes) completamente e não presuma as coisas como dadas. Por favor lembre-se que você, como desenvolvedor ou escritor técnico, é enviesado.
   - [ ] Talvez seja óbvio para você que executando uma determinada ação, um email será disparado para certos usuários. Sempre explique esses tipos de comportamento que possam parecer óbvios para você mas que não são para o usuário final.
- [ ] Reflita sobre a linguagem que você quer usar. Se a sua audiência é técnica, seja técnico. Se sua audiência não é técnica, não use termos técnicos a não ser que seja necessário (e mesmo assim, explique o que eles significam!) e pense no que realmente importa para o leitor.
- [ ] Como extensão do tópico anterior, certifique-se que você está usando uma linguagem com a qual seu usuário está acostumado.
   - [ ] Pode se chamar "profile `title`" no seu banco de dados, mas dizer isso quando o usuário conhece o termo como "Page name" é ineficiente. Tenha cuidado para não deixar essas palavras escaparem quando escrever seus docs.
- [ ] Se você se encontrar tentando explicar um fluxo que se termina se tornando extenso como esse: `Primeiro acesse o menu clicando no ícone de engrenagem, depois navegue para Ver meu perfil. Depois dessa só clique` it might be better to include a GIF recording of the flow **along with the text**.
   - [ ] "Here's how to change your Twitter username: In the sidebar menu, click on the 'More' option and navigate to 'Settings and privacy'. Click on 'Account' and proceed to change your username by going under 'Login and security' and clicking on username. Don't forget to save after changing it!"
![Changing Twitter username](https://i.ibb.co/0KC7FY4/gifntext-gif.gif)
- [ ] Images are underestimated. Humans are visual beings and inserting a picture or a recording of your product **along with its textual counterpart** will make users better understand what you're meaning to say.
- [ ] Try to have another person look at your documentation to ensure everything looks good. If it's a good practice to have PR reviews, it's also a good practice to have Documentation reviews!
- [ ] If you can, run some documentation testing by asking regular people to read your docs and try to use the feature you're writing docs for. Watch them using the product and don't interfere. Observe and write down what they had trouble with and ask them about it in the end. This way you'll be able to identify blind spots in your documentation.


- [ ] Sources:

   - [ ] [Create Killer SaaS Product Documentation for Your Customers](https://document360.io/blog/saas-product-documentation-software/)

   - [ ] [Building better documentation](https://www.atlassian.com/software/confluence/documentation)

   - [ ] [10 tips for structuring your product documentation](https://developerhub.io/blog/10-tips-for-structuring-your-product-documentation/)

   - [ ] [12 Best Examples of Product Documentation and Help Guides](https://documentor.in/2148/best-examples-product-documentation-guides/)

   - [ ] [5 Steps to Create Technical Documentation That’s (Actually) Helpful](https://plan.io/blog/technical-documentation/)

   - [ ] [6 Tips for Creating Meaningful Product Documentation](http://www.novatekcom.com/blog/bid/379708/6-tips-for-creating-product-documentation-that-talks-to-your-customer)
