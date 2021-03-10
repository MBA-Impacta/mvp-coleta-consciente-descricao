# MVP (Minimum Viable Product / Mínimo Produto Viável)

### Proposta de Valor

* Problema
    - Pilhas e baterias são considerados resíduos sólidos urbanos altamente impactantes ao meio ambiente, por conter inúmeras substâncias químicas, tais como metais pesados (ex. chumbo, cádmio e mercúrio).
    - Segundo pesquisa realizada em 2016, apenas 6% da população faz o descarte adequado de pilhas e baterias
    - A pesquisa também demonstra que em média, 80% da população sabe que não deve descartar pilhas e baterias em lixos comuns, mas não o fazem por falta de conhecimento dos locais de coleta para reciclagem
    - O aproveitamente de reciclagem de pilhas e baterias é de quase 100%

* Solução
    - Site e Aplicativo com localização de postos de coleta
    - Não obrigar fidelidade, ou seja, não é necessário se cadastrar, facilitar interação usuário
    - Usuário pode "cadastrar" uma localização e outros usuários podem dar like ou deslike, ou apontar que o local não existe mais, sistema se retro alimenta
    - Dicas de como fazer o descarte correto

### Público Alvo

* Consumidores de eletroeletronicos, eletrodomésticos, eletroportáveis etc.
* Principalmente região urbana, onde o consumo é maior
* Responsável por descarte do lixo em suas residências
* Autonimia para locamoção aos locais de descarte


### Período de Teste

* lançamento de Teste web e app versão Alpha e Beta
    - Fase Alpha -> Disponível Apenas via apk e link
    - Fase Beta -> Disponível para público geral, possível lançamento na play store

### Feedbaks

* Serão coletados os feedbacks para melhoria contínua

>> "Voltado para o mercado consumidor de pilhas e bateria, o Coleta Consciente é um aplicativo que ajuda a localizar postos de coleta, diferente de outros aplicativos, não exige cadastro e foca em facilitar ao máximo a coleta sustentável."

* O que é/Não é
  - <b>É</b> um aplicativo que ajuda a localizar locais de coleta de pilhas e baterias
  - <b>Não é</b> voltado a descarte de grandes quantidades provindo de estabelecimentos comerciais

* Faz/Não Faz
  - <b>Faz</b>
    * Localiza a posição de postos de coleta próximos;
    * Usuário podem inserir nova localidades de postos;
    * Usuário pode dar like ou deslike no posto de coleta;
    * Manutenção dos locais baseado no feedback (Ou seja, se tiver likes, o posto é válido, se tiver mtos deslikes a marcação do mapa é removida);
  - <b>Não Faz</b>
    * Não difere usuários, todos podem se cadastrar ou não, dar like e deslike (Mesmo que não esteja cadastrado);
    * Não faz manutenção dos locais cadastrados, os responsáveis por isso são os próprios usuários;

* Tem/Não tem
  - <b>Tem</b>
    * Cadastro de usuários;
    * Localização do usuário e local de coleta (GPS);
    * Mapa com localização dos postos (Estático ou não);
    * Funcionalidade de likes e desliker, anonimos ou não;
    * Login Social;
    * Coleta de Feedbacks;
    * Dicas de descarte;
  - <b>Não tem</b>
    * Interação entre usuários;


## Qual a vantagem de se cadastrar?
* Poder cadastrar pontos de coleta
* Poder comentar
* Receber dicas de descarte consciente
* Receber notificações



Fontes:

    https://www.ibeas.org.br/congresso/Trabalhos2016/III-044.pdf
    https://www.brazilianjournals.com/index.php/BRJD/article/view/8758/7506
    https://www.ecycle.com.br/188-descarte-de-pilhas.html
    https://goo.gl/Ke5o8v (https://www.google.com/maps/d/u/0/viewer?hl=pt&mid=1wyqQ4uE-80x9BEkkv4en6UAQ_fU&ll=-23.530279686293518%2C-46.65500982784427&z=11)
    https://revistapegn.globo.com/Como-comecar/noticia/2016/06/5-passos-para-fazer-um-produto-minimo-viavel-mvp.html



##frontend 

https://firebase.google.com/docs/firestore

react native 

https://reactnative.dev/

react js
https://reactjs.org/


##Resumo
Kanban

O kanban utiliza sistema de cartões de cores para designar e especificar tarefas, aprimorando a administração e sinalizando o controle de fluxos, evidenciando as tarefas que devem ser feitas e as que já estão concluídas e a movimentação das tarefas. As fases são determinadas por to do (por fazer), doing (fazendo/em execução) e done (feito/concluído). 

A escolha dessa metodologia foi escolhida para ficar mais fácil a demonstração das etapas das tarefas, designando para cada participante a tarefa a executar em que status ela se encontra, dessa forma fica mais fácil a troca de informação para desta forma sincronizar o conteúdo para finalizar o material final.


Tecnologias

A escolha das tecnologias se deve ao fato de o sistema possa ser usado nas plataformas web e mobile, por ser uma plicação para o usuário final  que terá ter fácil acesso, desta forma o sistema terá de ficar disponível 24/7. 

Para o front foi escolhido os fraeworks vue e bootstrap, que facilita na hora de implementar os componentes visuais e fazer a integração com backend e a utilização das funções, para aperfeiçoamento do layout será utilizado html e css.

Para o back utilizará java/kotlin, para integração com base de dados, chamadas de api e controle de microserviços, se optou por esta maneira para não utilizar um sdk integrado no qual existe algumas limitações de uso desse modo também caso seja necessário pode se desacoplar uma parte do sistema que caso não esteja tendo um bom desempenho posso ser trocado por uma api ou tecnologia mais nova ou com melhor desempenho.

As base de dados utilizadas para o projeto serão postgress/mysql banco de dados relacionais que no formato sql sendo bancos estáticos e de fácil utilização será a fonte de dados principal, saída de dados e armazenamento final. Enquanto isso o mongo/db será utilizado por ser nosql e cross platform, ele fará uma ponte a base de dados e backend, sendo utilizado na passagem de dados de entrada do usuário no sistema e a visualização de dados no front end da aplicação.



Descarte de pilha 

A escolha do tema tem como objetivo desenvolver um sistema onde mostre os pontos de coleta para pilha para que seja feito o descarte apropriado deste material. Os principais motivos para escolha do tema é que se descartadas incorretamente causam grande perigo a natureza e riscos a saúde existem muitas causas mas principal está que metais pesado causam câncer e mutações genéticas. 

O descarte errado delas podem causar acerações na cápsula sendo amassados, estourar deixando vazar o líquido tóxico, nesse processo a junção de resíduos ao longo do tempo contamina lençóis freáticos no qual prejudica a agricultura e hidrografia. 

 Desta forma este projeto visa mostrar e informar as pessoas onde está localizados os pontos de coleta para o descarte apropriado visando evitar os problemas descritos que podem ocorrer caso não seja feito da maneira correta. Tendo em vista a preservação do meio ambiente e conscientização da população.


