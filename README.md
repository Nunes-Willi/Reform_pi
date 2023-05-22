o# Projeto Integrador - Modelo

Início de projeto 27/02/2023.

Alunos: Murilo Watanabe(https://github.com/MuriloWatanabe), Phelipi Moser (https://github.com/PhelipiM) e William Nunes (https://github.com/Nunes-Willi)

Links do projeto:

-   [Link do projeto](https://github.com/MuriloWatanabe/pi_modelo)

<!-- # Como usar esse modelo para o Projeto Integrador

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instalada a extensão [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) no seu editor de texto.
5. Edite o arquivo README.md com as informações do seu projeto.
   

# Desenvolvimento

-   As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
-   Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

# Modelos de Sistemas

**Nessa parte a equipe deve escolher um dos modelos de sistemas para desenvolver o projeto. Ao escolher, escreva uma breve descrição do sistema e o motivo da escolha e pode apagar os outros modelos.**

## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma padaria**

O nosso cliente, Sr. Genival, tem uma padaria de bairro chamada padaria Pão Genial e, devido a qualidade de seus produtos, ela está crescendo rapidamente. Recentemente, ele contratou mais funcionários para atendimento, caixa, panificação, etc.
Assim, atualmente, ele consegue concentrar seus esforços para melhorar a gestão da padaria. Para isso, ele quer instalar um sistema de controle de vendas que permita ao caixa lançar as vendas realizadas. Como sua intenção
é melhorar a gestão do negócio, é muito importante que ele consiga ter
relatórios, como por exemplo, de vendas.

## 2- Empréstimo

**Gerenciamento de uma biblioteca**

Uma ONG, chamada Sala Arco Íris, ajuda crianças de baixa renda em sua educação básica. Atualmente, recebeu uma doação de mais de 1000 livros e está montando a sua biblioteca. Eles querem emprestar os livros para as crianças e os pais das crianças. Apesar de
terem um computador e as estantes necessárias à disposição nessa nova biblioteca, não possuem verba suficiente para um leitor de impressão digital ou para produção
de carteirinhas para todas as crianças. Para isso, eles precisam de um sistema que gerencie todo o acervo, empréstimos, livros disponíveis, etc. mas que isso ocorra de maneira simples e sem necessidade de novos gastos. Também é importante que haja relatórios, permitindo o controle dos empréstimos e dos livros disponíveis no acervo.

## 3- Ordem de Serviço (O.S.)

**Manutenção de computadores**

Sr. Sálvio, nosso cliente, fez um curso de manutenção de celulares e smartphones e decidiu abrir um negócio, onde ele é responsável pelos consertos e sua esposa Marília realiza os atendimentos aos clientes. Com sua visão empreendedora, ele sentiu a necessidade de um software que auxilie
sua esposa nas tarefas diárias. Para isso, ele deseja um sistema que gerencie os clientes, orçamentos, serviços e retirada dos equipamentos. Sendo um negócio pequeno, é muito importante que ele consiga ter relatórios que lhe ajudem na gestão da
empresa, como dos status dos serviços. -->

# Situação Problema

<!-- **Nessa parte a equipe deve descrever a situação problema que será resolvida pelo sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.**

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")

Descrevem o que acontece atualmente na empresa em um contexto global,
abordando o funcionamento da empresa como um todo, não apenas os “problemas” que lá ocorrem.

Sabendo disso, seu papel é **detalhar o funcionamento da empresa escolhida na
atualidade, ou seja, antes de seu novo software**, usando como base a situação que passamos, mas aprofundando os detalhes de como as coisas acontecem.

-   Pesquise sobre empresas do ramo escolhido
    para entender como funcionam;
-   Aproveite seus conhecimentos previamente adquiridos na área da empresa que escolheu, se houver;
-   Simule uma situação real. Lembre-se que são
    propostas com empresas fictícias, sendo assim,
    você terá que tomar certas decisões sobre como
    a empresa funciona em relação às coisas que
    não estão definidas no documento base (por
    exemplo, no caso da padaria, dizemos que seu
    Genival contratou mais funcionários, mas saber
    quantos e o que fazem pode ser relevante para o software), então tente “visualizar” a
    empresa funcionando, como se você estivesse lá acompanhando o dia-a-dia;

Seguindo essas dicas, você deve ser capaz de descrever o dia-a-dia da empresa selecionada. E para ajudar na organização do texto, indicamos uma abordagem em 3 etapas: -->

-   **Introdução**: Olá nós somos a empresa RevCar, trabalhamos com revenda de carro desde 27/02/2023.Os donos da empresa são: Murilo Watanabe, Phelipi Moser e William Nunes. E ao todo possuimos três funcionários: Atendente(Vendedor); Gerente de  Estoque.
  
-   **Situação-problema**: <!--Aborde em detalhes como a empresa funciona, procurando seguir umaordem lógica dos acontecimentos e organizando parágrafos diferentes para cada coisa diferente que for explicar (como faria em uma redação);--> A empresa funciona da seguinte forma, um cliente procura um carro à venda pelo site/app, após encontrar um carro de seu interesse ele vai até a loja física visualizar o veículo que lhe chamou a atenção com maiores detalhes, o atendente ô recepiciona, criando no sistema um orçamento em cima do veículo, ao terminar o processo de anotação no sistema o atendente pergunta a forma de pagamento, após o cliente específicar sua forma de pargar pelo veículo o atendente deverá jogar no sistema que buscará pelos documentos do veículo que serão impressos na entrega, seguindo pós comprae e remoção do veículo da concessionária o atendente cofirmará a venda do veículo que será removido do catálogo da(o) web/app, tendo as informações que foram anotadas enviadas para um sistema de relatórios.
  
   **Conclusão**: <!--tenha um parágrafo de conclusão focando nos problemas que você notou dentro da situação problema analisada e aponte brevemente como um software poderia ajudar a resolvê-los.;--> A ideia do software é de sistematizar o processo de gerenciação de relatórios, dada as informações do cliente e do estoque, o foco do software é de facilitar as informações dos carros que entram e saiem da concessionária e do estoque. E a ideia do app/web é de mostrar os carros á venda na concessionária e no "estoque" (caso haja um).

# Descrição da proposta

A nossa proposta de solução para a empresa é implementar um sistema integrado que automatize o processo de venda de veículos, incluindo o registro digital das características do veículo pelo atendente, análise de crédito automatizada, notificações automáticas para o vendedor, documentação digitalizada e agendamento automatizado de revendas. Essas soluções visam agilizar o processo, reduzir o uso de papel e aumentar a eficiência operacional da empresa.
<!-- Após entender o problema, proponha uma solução que será útil nos aspectos de dificuldade encontrados. Assim, aqui você deverá **explicar de maneira resumida, e preferencialmente mais textual, como o software funcionará**. Pense nesse texto como uma **introdução ao seu cliente** do que você pretende fazer por ele, para que ele confirme se realmente está dentro do
desejado e permita sua continuidade.

**Alguns pontos importantes a se destacar são:** -->

  **Qual o foco de ação do software**
  
  Foco principal do software e de procurar, listar e organizar a pesquisa dos carros para os clintes. Assim facilitando na hora da venda do carro
    <!--relacionado com os problemas levantados na análise da situação-problema. O que realmente o software vai fazer. Por exemplo, o foco de ação do Gmail é permitir o envio e recebimento de e-mails. -->

**Os níveis de usuário do sistema**. 
   
   A prioridade da parte de funcionário é que o acesso em geral de aceitação de venda, compra de veículos seja do atendente e de demais funcionário envolvidos com a venda ò tenha. Já a prioridade da parte de cliente é a visualização dos veículos a venda.<!--Somente o gestor tem acesso? E os funcionários? Talvez seja para ambos, ou para funcionários de cargos diferentes, etc.-->

**O que poderá ser feito no software**.
Orçamento,ánalise de compra e venda, e gerenciamento de informações do cliente.
<!-- Apenas o principal, sem pensar em
    telas ou detalhes específicos, pois isso será feito em outro momento. -->

 **Se houver mais de um nível de usuário**

 As principais diferenças entre os niveis de atendente e gerente de estoque seria a manipulação de informações entre cliente e veículo, por exemplo o atendente lidaria com o orçamento e pesquisa de dados atendidos pelos clientes,e o gerente lidaria com gerenciamento de dados sobre os veículos (entrada,saída,data,características,valor e etc..)

 <!-- ressaltar as diferenças entre
        eles na descrição da proposta.

Tenha em mente que essa é uma etapa relativamente breve. Não é necessário um texto gigantesco, apenas dar uma noção do funcionamento do sistema. Mais adiante
miprecisaremos ser bem detalhistas, todavia agora a intenção é apenas fazer algo que permita ao cliente nos dizer se estamos no caminho certo. -->


**Regras de negócio**

  - **Regra de negócio de entrada de dados dos veiculos**

RN001- Entrada de veículo: quando cliente aparecer com uma venda de veículo presencial ou virtual (virtual seria o envio de imagens do veiculo), o atendente deve anotar todas as informações do veiculo para determinar o valor de compra.

RN002- Pós análise: Após as anotações de todas informações do veiculo o atendente deve justificar cada detalhe e falha do veiculo para determinar o valor final de compra.

RN003- Finalização de compra: feita a compra do veiculo o atendente deve resgitrar todos os dados do veiculo na concessionária ou no estoque.
   
 - **Regra de negócio de compra e saída de dados dos veiculos**
  
RN01- Iniciando a compra: O cliente que pode o não ter vindo por um anuncio do site falará com o atendente.Onde o funcionário fala dos veículos que estão na concessionária e no estoque, para que o cliente anasalise e escolha o veículo que deseja(caso não tenha vindo com o carro em mente do site);

RN02- Verificação no estoque: Após a escolha, o gerente envia para o gerenciador de estoque o veículo escolhido pelo cliente (em caso do veículo não estar na loja diretamente);

RN03- Após verificação do estoque: O gerenciador do estoque vai alertar se há o veículo desejado. Caso haja o produto seguir para a quarta regra, caso oposto encerrar compra;

RN04- Coleta de dados: Para a continuação da compra o gerente deve pegar todos os dados do cliente e de seu veículo desejado, após a coleta de dados confirmar a compra;

RN05- Transferência de documetos: Após a confirmação do compra o gerente deve fazer as tranferência dos documentos do carro para o cliente;

RN06- Após transferência dos documentos o atendente deve confirmar a aprovação do veículo para o cliente;

 - **Regra de negócio visualização do site/app**
  
RN00- Login cliente: O cliente pode se cadastrar no site/app para que possa salvar os carros que gostou, comentar sobre os veículos e começar a conversa com atendente sobre a comprar de um veículo de forma virtual(os processosmais "radicais" terão de ser feito presencialmente).

RN00- Venda de seu veículo: Caso o cliente tenha um veículo que queira vender, ele pode simplesmente tirar e mandar fotos de seu veículo juntamente com a documentação do  para que seja análisada pelo gerente geral.

RN00- Após analise: Se o gerente querer comprar o veículo para a sua concessionária ele confirmara com o cliente a compra e o sistema deve postar o "novo" carro na lsita de carros a venda no site/app.


<!-- RN006- Esteja presente nas redes sociais: Use as redes sociais para divulgar seus carros e manter seus clientes informados sobre novidades, promoções e eventos.

RN007- Ofereça financiamento: Para atender às necessidades de todos os clientes, ofereça opções de financiamento e leasing.

RN008- Invista em publicidade: Invista em publicidade em canais estratégicos, como revistas de carros, jornais locais, rádio e televisão.

RN009- Ofereça serviços adicionais: Ofereça serviços adicionais, como seguro de carro, transferência de propriedade, revisões e manutenção.

RN010- Atenda bem seus clientes: Treine sua equipe para atender bem seus clientes e estar sempre disponível para ajudá-los em suas necessidades. A boa reputação e o boca-a-boca são fundamentais para o sucesso de qualquer negócio. -->

**5.4 Requisitos funcionais**

<!-- **Etrada e saída de Veículos**
RF00 - Em caso da compra de algum veículo o sistema deve permitir o cadastro do mesmo com as seguintes informações: Marca, Modelo, Ano , Cor, Quilometrageme outras informações.

RF00 - Após marcar as informações da compra do veículo o sistema deve criar um perfil para a revenda do carro e mandalo para o estoque. -->

**Etrada**

- **Quais os tipos de funcionarios**
  
<!-- RF00 - Sistema de cadastro de clientes: O sistema deve permitir o cadastro de clientes com as seguintes informações: Dados necessários: nome completo, cpf, endereço, número de telefone, e-mail e outras informações relevantes. Usuários: Vendedor/Administrador

RF00 - Gerenciamento de conta do cliente: um sistema para que os administradores possam gerenciar suas contas, atualizando suas informações dos clientes como dados pessoais, dados de pagamento, histórico de compras e outras informações. -->


RF00 - Autenticação dos funcionários: um sistema para autenticar os funcionários diferentes, ao fazer login em sua conta antes de realizar uma venda o funcionário poderá ver os dados dos carros que o mesmo  vendeu, Essas informações serão utilizadas no relatório final do mês.

**Saída**

- **Venda e forma de pagamentos**

RF00 - Venda:

RF00 - pagamentos: o sistema  para processar os pagamentos dos clientes por meio de várias opções, como cartões de crédito, PayPal, dinheiro vivo ou outros métodos de pagamento. Tendo as opções de pagar à vista ou parcelado.


- **Tela de transferência de documentos**

RF00 - Confirmação de compra: o sistema deve abrir uma janela para enviar uma confirmação do compra do cliente, incluindo informações sobre o produto, preço total e informações de transferências de documentos.

RF00 - Transferência de documentos: Após a confrimação, sistema deverá abrir uma nova janela pedindo os documentos do veículo que será impresso além de ser enviado uma cópia para o email do cliente e do vendedor.

- **Relatórios**
  
RF00 - O sistema deve enviar um email para o dono/gerente da loja que informe a quantia de carros vendidos, qual foi o mais vendido, nome funciónario que vedeu e o nome do cliente que comprou, formas e tipos de pagamento, lucro e prejuízo.

RF00 - O sistema deve fixar no final do relatório os funcionários que tiraram mais feriados, folgas, horas extras e atestados.

RF00 - O sistema deve enviar um relatório geral e um relatório individual de cada funcionário para o gerente, também enviando os relatórios individuaís de cada funcionário para o mesmo.

<!-- Um requisito funcional deve ser estruturado da seguinte forma:

Nome do requisito funcional: descrição do requisito.
Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.

*5.4.1 Nome do requisito funcional*

<!-- R.F. 99 - Nome do requisito funcional: é o nome da função que o software terá. Sugerimos, por padronização, que tenha o prefixo R.F. (requisito funcional) seguida da numeração, para melhor identificação do requisito, acrescido do formato “Substantivo + onde será feita a ação”. Por exemplo:

R.F. 01 - Registro de Funcionários
R.F. 15 - Gerenciamento de consultas
R.F. 04 - Débito em conta corrente
Deixe para definir as numerações ao final, tendo em vista que mudanças podem acontecer e não é prático sempre ficar reajustando os números. -->

<!-- *5.4.2 Descrição do requisito funcional*

Descrição do requisito: local para descrever a função deste requisito.

Sempre se preocupe em esclarecer dois pontos: o que o requisito faz e o motivo de sua existência. Isso é especialmente importante se a ação executada nesse requisito não for algo que já acontece naturalmente na empresa. Um exemplo é um Registro de funcionários, que talvez não exista hoje mas para o software é necessário para viabilizar uma autenticação de usuários. Outro exemplo é algo que faz sentido apenas para um software, como a própria autenticação. --> -->

**6.4 Estrutura do requisito não funcional**

RNF 01 - Sistema operacional: O sistema deverá ser usado em sistemas operacionais windows, linux.

RNF 02 - Processador: É recomendado para o sistema no mínimo um processador Intel i3, similar ou superior a geração 7100, para que o servidor funcione em sua melhor performance.

RNF 03 - Memória RAM: é recomendável que o sistema possua no mínimo 2GB de Ram para melhor performance.

RNF 04 - Acessibilidade: O Sistema deve ser feito de forma que todos os funcionarios consigam usa-lo sem dificuldade. 

RNF 05 - Segurança: Cada senha de funcionario deve ter no minimo 6 caracteres.

RNF 06 - Navegadores: O sistema deve funcionar em tudos os navegadores sendo eles(Google, Firefox,Microsoft EDGE, Opera).

<!-- RNF 01 - Navegador homologado: O sistema deverá ser homologado somente para o navegador Google Chrome.

RNF 02 - Processador: É recomendado para o sistema no mínimo um processador Intel i3, similar ou superior a geração 7100 ou AMD Ryzen 3 da geração similar ou superior ao 3100, para que o servidor funcione em sua melhor performance.

RNF 03 - Memória RAM: é recomendável que o sistema possua no mínimo 2GB de Ram para melhor performance.

RNF 04 - Arquitetura: A arquitetura que será utilizada para criação do sistema será Rest.

RNF 05 - Conexão com banco de dados: Para conexão com o banco de dados, o sistema utilizará a ferramenta de MySQL Connector.

RNF 06 - Desempenho: Para a utilização correta e com uma qualidade e eficiência melhor, é recomendado que se use o SO mais atualizado, com recursos de hardware equivalentes a um processador intel i3 5°Gen ou semelhante, e 8GB de memória RAM, assim como os navegadores homologados.

Sistema de Ordem de Serviço:

RNF 01 - O sistema deverá rodar em qualquer navegador como Chrome, Opera, Fire Fox, Safari e Microsoft Edge

RNF 02 - Tecnologia Front-end: Para a exibição em front-end, o software utilizará o CSS3 e o HTML5, além das bibliotecas de jQuery e Javascript.

RNF 03- Tecnologia Back-end: O software será desenvolvido pela linguagem de programação Java.

RNF 04- Interoperabilidade: O banco de dados será o Mysql, com a linguagem SQL de banco, sendo todo produzido através do mysql Workbench.

RNF 05- Forma de uso do software: O sistema por fazer parte de um ambiente interno, provavelmente será utilizado de acordo com as horas de trabalho da empresa, mas estará ativo 24 horas por dia em 7 dias por semana.

RNF 06- Desempenho: Para a utilização correta e com uma qualidade e eficiência melhor, é recomendado que se use o SO mais atualizado, com recursos de hardware equivalentes a um processador intel i3 5°Gen ou semelhante, e 8GB de memória RAM, assim como os navegadores homologados. -->