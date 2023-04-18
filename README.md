# Grafeat: Parte da Arte (Back-End)
## ![WhatsApp Image 2023-03-30 at 11 11 35](https://user-images.githubusercontent.com/123910027/229203596-92f71f75-9f66-42eb-b159-7d43e1e6f6ad.jpeg)


![Badge Concluido](http://img.shields.io/static/v1?label=STATUS&message=%20CONCLUÍDO&color=GREEN&style=flat-square)
![Badge Java](http://img.shields.io/static/v1?label=JAVA&message=v11&color=blue&style=flat-square)
![Badge Spring](http://img.shields.io/static/v1?label=SPRING&message=v2.7.9&color=blue&style=flat-square)
![Badge MySQL](http://img.shields.io/static/v1?label=MYSQL&message=v8.0.28&color=blue&style=flat-square)
![Badge Insomnia](http://img.shields.io/static/v1?label=INSOMNIA&message=v2023.1.0&color=blue&style=flat-square)

- [Introdução](#introdução)
- [Front-End Interface visual](https://github.com/SammyLexa/projetoIntegrador-grafeat-FRONTEND)
- [Funcionalidades](#funcionalidades-crud-create--read--update-delete-)
- [Documentação](#documenta%C3%A7%C3%A3o-do-grafeat)
- [Diagrama de Classes](https://github.com/SammyLexa/projetoIntegrador-grafeat/blob/main/DiagramaClasses.md)
- [Testes com o Framework Insomnia](https://github.com/SammyLexa/projetoIntegrador-grafeat/blob/main/Testes.md)
- [O que é o programa da Generation Brasil Devesenvolvedor Java Full-Stack?](#o-que-%C3%A9-o-programa-da-generation-brasil-devesenvolvedor-java-full-stack)
- [Equipe de Desenvolvedores:](#equipe-de-desenvolvedores)
    - [Caroline Viana](#caroline-viana)
    - [Giyo Dias](#giyo-dias)
    - [Leticia Pires de Souza](#leticia-pires-de-souza)
    - [Pedro Azevedo](#pedro-azevedo)
    - [Samantha Alexandra Pereira](#samantha-alexandra-pereira)
    - [Wallace Silva Brito](#wallace-silva-brito)

## Introdução

A ODS (Objetivos de Desenvolvimento Sustentável¹) 10: “Reduzir a desigualdade dentro dos países e entre eles” possui dez metas a serem alcançadas até 2030, sendo as principais delas: reduzir as desigualdades de renda ; promover a inclusão social, econômica e política universal; garantir oportunidades iguais e acabar com a discriminação;

De acordo com o estudo pelo FGV Social, “O contingente de pessoas com renda domiciliar per capita de até R$ 497 mensais atingiu 62,9 milhões de brasileiros em 2021, o que representa 29,6% da população total do país”, o que denota uma disparidade econômica e social, resultando na dificuldade no alcance e sustentação do crescimento da renda exigido pela ODS. 

## Desenvolvimento:
O software é um e-commerce focado na venda e promoção de produtos artesanais produzidos por pessoas em vulnerabilidade econômica e social. Na versão inicial do projeto focaremos na comunidade do grafite e suas confecções. 

Nosso projeto terá um foco em comunidades periféricas, atraindo jovens e adultos para que possam obter sustento digno e responsável através de suas habilidades e possibilitar a inclusão na arte e cultura. 

Nosso site servirá de vitrine para todos os produtos relacionados à arte e grafite, onde o vendedor poderá criar um usuário e adicionar uma breve biografia, seus produtos e características. Quando os produtos já estiverem cadastrados será possível realizar consulta e atualização por nome, categoria, preço, e, se necessário, realizar a exclusão de itens. O projeto será sem fins lucrativos, cobrando apenas uma pequena taxa dos produtos para manutenção do site.

## Conclusão:
Consequentemente, resultando na conclusão das metas da ODS através de: visibilidade e renda para as comunidades vulneráveis sociais e econômica a respeito de seus trabalhos; Incentivar a cultura, e confecções locais; Criar um ambiente empoderador em que se possa ter a possibilidade de viver a partir do seu próprio trabalho;

#### Dicionário: 1 - Os Objetivos de Desenvolvimento Sustentável são um apelo global da ONU(Organização das Nações Unidas) à ação para acabar com a pobreza, proteger o meio ambiente e o clima e garantir que as pessoas, em todos os lugares, possam desfrutar de paz e de prosperidade.

## Bibliografia:

NAÇÕES UNIDAS NO BRASIL (Brasil) (org.). Redução das desigualdades. Disponível em: https://brasil.un.org/pt-br/sdgs/10. Acesso em: 29 mar. 2023.

WIKIPEDIA (Brasil) (comp.). Objetivo de Desenvolvimento Sustentável 10. Disponível em: https://pt.wikipedia.org/wiki/Objetivo_de_Desenvolvimento_Sustent%C3%A1vel_10. Acesso em: 29 mar. 2023.

MARCELO NERI (Brasil). Mapa da Nova Pobreza. Disponível em: https://cps.fgv.br/MapaNovaPobreza. Acesso em: 29 mar. 2023.


## Funcionalidades: CRUD (Create ![icons8-adicionar-24](https://user-images.githubusercontent.com/123910027/232769100-ebea4240-baa4-4239-8a76-cb1655de6bb5.png), Read ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232769155-b691ca1b-4c23-4ae8-a774-7e720e2a30f7.png), Update ![icons8-atualizações-disponíveis-24 (1)](https://user-images.githubusercontent.com/123910027/232769223-7ba3c31d-94c9-4fa7-bdee-db0bf50a5dee.png), Delete ![icons8-remover-24](https://user-images.githubusercontent.com/123910027/232769270-4be8ca16-82a4-4b97-b898-aae2d8ccc355.png))

- Cadastra Produto ![icons8-adicionar-24](https://user-images.githubusercontent.com/123910027/232767758-0aba231c-2f00-485f-b781-6fd29d25605a.png)
- Cadastra Categoria ![icons8-adicionar-24](https://user-images.githubusercontent.com/123910027/232767758-0aba231c-2f00-485f-b781-6fd29d25605a.png)
- Cadastra Vendedor ![icons8-adicionar-24](https://user-images.githubusercontent.com/123910027/232767758-0aba231c-2f00-485f-b781-6fd29d25605a.png)

</br>

- Consulta por ID de Produto ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768360-f1212e5f-a367-4edd-9a07-e8d95d19bb7d.png)

- Consulta por ID de Categoria ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)
- Consulta por ID de Vendedor ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)
- Consulta por Nome de Produto ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)
- Consulta por Descrição de Produto ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)
- Consulta por Nome de Categoria ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)
- Consulta Todos os Produtos ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)
- Consulta Todas as Categorias ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)
- Consulta Todos os Vendedores ![icons8-leitura-24 (1)](https://user-images.githubusercontent.com/123910027/232768531-ea201a85-7ebc-4243-9cc5-3e68406c9e43.png)

</br>

- Atualiza Produto ![icons8-atualizações-disponíveis-24 (1)](https://user-images.githubusercontent.com/123910027/232768932-93ce24e1-284c-4ce9-b172-65cd089df9b9.png)

- Atualiza Categoria ![icons8-atualizações-disponíveis-24 (1)](https://user-images.githubusercontent.com/123910027/232768941-675b1039-090b-4822-a65f-97f20bb7f110.png)

- Atualiza Vendedor ![icons8-atualizações-disponíveis-24 (1)](https://user-images.githubusercontent.com/123910027/232768976-4c38784c-75f9-4b70-92ed-ad71b3c49589.png)



</br>

- Deleta Produto ![icons8-remover-24](https://user-images.githubusercontent.com/123910027/232768785-afe76432-44f0-49ed-9408-504aa962dcd6.png)

- Deleta Categoria ![icons8-remover-24](https://user-images.githubusercontent.com/123910027/232768794-fa0f1620-c42a-4abb-8c71-db575fa72b02.png)

- Deleta Vendedor ![icons8-remover-24](https://user-images.githubusercontent.com/123910027/232768804-a949cade-ebb0-4783-8d06-9628ecc69b88.png)


# Documentação do Grafeat


![image](https://user-images.githubusercontent.com/123910027/231561684-47b13bc5-6be8-42d1-ae99-0305c6045ef0.png)

![image](https://user-images.githubusercontent.com/123910027/231561878-ee3d7d9c-f6e8-49a8-b262-1caf77a90b02.png)

![image](https://user-images.githubusercontent.com/123910027/231562016-a10d2f11-9a35-47f2-888f-83b847af2219.png)

![image](https://user-images.githubusercontent.com/123910027/231562090-dbbf4e29-24fb-4123-9ba8-9dd5d4907bd6.png)

<h3>Ferramentas, Linguagens, Frameworks e Banco de Dados utilizados:</h3>
<br>

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Insomnia](https://img.shields.io/badge/insomnia-39457E?style=for-the-badge&=insomniaColor=white)
![MySQL](https://img.shields.io/badge/MySQL-ffa500?style=for-the-badge&logo=mysql&logoColor=0000FF)

##

<h3>O que é o programa da Generation Brasil Devesenvolvedor Java Full-Stack?🎓</h3>

O programa prático da Generation tem duração de 3 meses (447 H) e ensina as habilidades técnicas e comportamentais para ser um desenvolvedor Java Full-Stack com sessões interativas e práticas.


- Fundamentos de programação, Estrutura de dados, Banco de Dados, Java, HTML + CSS + Javascript, Programação Avançada, Metodologia SCRUM.

- Comunicação, Proatividade, Trabalho em equipe, Orientação ao detalhe, Responsabilidade pessoal, Persistência, Orientação ao futuro, Mentalidade de crescimento.


##
## Equipe de Desenvolvedores:
<br>
  <img width="200px" src="https://user-images.githubusercontent.com/123910027/227731448-d2d5f056-e4cd-4751-bd9f-ff2ae49ec699.jpg" alt="Imagem de Caroline Viana">
  
  - <a href="https://www.linkedin.com/in/caroline-viana-de-medeiros/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
  - <a href="https://github.com/Caroline-Viana" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
  <h3>Caroline Viana</h3>
  <h3>Sobre mim</h3>
  <p>Olá, meu nome é Caroline Viana de Medeiros e tenho 22 anos. Sou formada em Gestão de Turismo, pelo Instituto Federal de São Paulo e, apesar de ter adorado a área, sempre tive um grande amor pela tecnologia. Por isso, decidi fazer uma transição de carreira para a programação e hoje estou me qualificando com o objetivo de trabalhar nesse campo!</p>

  <p>Durante a faculdade, trabalhei como monitora na disciplina de pesquisa de mercado e pude desenvolver minhas habilidades de comunicação e atenção aos detalhes. Essas habilidades têm sido muito úteis na minha carreira de programadora, já que a comunicação efetiva e a atenção aos detalhes são fundamentais para o desenvolvimento de softwares de qualidade.</p

  <p>Eu tenho um grande interesse em aprender novas linguagens de programação e, atualmente, conheço bem as ferramentas de programação Java, JavaScript, HTML, CSS, Bootstrap, MySQL, Spring Boot, Sass e Scss. Além disso, possuo habilidades em liderança, trabalho em equipe, métodos ágeis (Scrum), orientação para o futuro, e sou muito persistente em busca de soluções.</p>

  <p>Fora isso, gosto de ler livros, assistir a documentários, e me exercitar ao ar livre. No geral, sou uma pessoa curiosa, dedicada e apaixonada pelo mundo da tecnologia, sempre procurando novas oportunidades para aprender e crescer.</p>


##

<img width="200px" src="https://user-images.githubusercontent.com/123910027/227813701-6e3a47a9-65cb-4d7f-bb24-2814a031f4c7.jpg" alt="Imagem de Giyo Dias"></br>
  - <a href="https://www.linkedin.com/in/giyodias/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
  - <a href="https://github.com/giyodias" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
<h3>Giyo Dias</h3>
<h3>Sobre mim</h3>
Olá, Sou o Giyo, tenho 19 anos e estou em transição de carreira para a área tech. Adoro estudar e aprender coisas novas em diversas áreas, principalmente em programação. Curso ADS na FATEC e estou no bootcamp Java Full-Stack da Generation Brasil.
Tenho soft skills bem desenvolvidas e sou um membro proativo de grupos, possuo capacidade de liderança e analítica, empatia, e tenho experiência em resolução de problemas.

Aberto a propostas de emprego! Então, se estiver interessade em meu perfil, me mande uma mensagem e vamos trabalhar juntes!

##

<img width="200px" src="https://user-images.githubusercontent.com/123910027/227977478-28ec7b2e-7a22-4908-b7a0-b024b83c44bf.jpg" alt="Leticia Pires de Souza"></br>
  - <a href="https://www.linkedin.com/in/leticia-pires-de-souza-5a1031203/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
  - <a href="https://github.com/LeticiaPires12" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
<h3>Leticia Pires de Souza</h3>
<h3>Sobre mim</h3>
Estou em transição de carreira e atualmente sou estudante do curso fornecido pela Generation Brasil - Java Full Stack Júnior, sou esforçada e autodidata. Gosto de ler, praticar esportes e defendo open source. Atualmente estudo o universo Java, Spring e Microservices. Tenho interesse em ser inserida no mercado de trabalho. Meu maior desafio é desenvolver um portfólio pessoal.

##

<img width="200px" src="https://user-images.githubusercontent.com/123910027/227933299-9c3ec1c6-f11f-4214-8597-6d055618ac28.jpg" alt="Pedro"></br>
  - <a href="https://www.linkedin.com/in/pedro-azevedo-2147661b5/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
  - <a href="https://github.com/pedroapinheiro" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
<h3>Pedro Azevedo</h3>
<h3>Sobre mim</h3>
Sou o Pedro, tenho 23 anos e estou em transição de carreira para a área tecnologia. Sou formado em gestão de eventos e desde então comecei a ter a contato com a tecnologia a cada trabalho desenvolvido, isso me trouxe uma imensa vontade de conhecer melhor a área e hoje estou finalizando o curso de Desenvolvedor JAVA Full Stack pela Generation Brasil. 

Soft skills: sei trabalhar em equipe, liderança desenvolvida em cargos que já atuei, empatia e orientação aos detalhes.

Ficou interessade em meu perfil e quer conhecer mais sobre minha jornada? Te convido a entrar em contato pelos links abaixo. Meu GitHub para ver meus projetos, mande uma mensagem ou me envie um e-mail e vamos trabalhar juntes! ;D

##

<img width="200px" src="https://user-images.githubusercontent.com/123910027/227732191-4385c938-5b77-4feb-8d64-a5b486763fdd.jpg" alt="Imagem de Samantha Alexandra Pereira"></br>
  - <a href="https://www.linkedin.com/in/samantha-alexandra-pereira/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
  - <a href="https://github.com/SammyLexa" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
<h3>Samantha Alexandra Pereira</h3>
<h3>Sobre mim</h3>
Sou aspirante a Desenvolvedora Web Full-Stack, estou ansiosa para aprender e crescer na área de desenvolvimento web. Minha paixão por criar páginas web envolventes, acessíveis e fáceis de usar me levou a seguir a carreira de desenvolvimento.💻

Embora eu seja nova no área, concluí cursos de HTML, CSS, JavaScript, Java e também ganhei experiência trabalhando em projetos pessoais para aprimorar minhas habilidades. Estou familiarizada com os framework React, Spring e Insomnia, e me sinto confortável trabalhando com várias ferramentas de desenvolvimento, como Git, VSCode, STS ou Eclipse.💜

Estou animada para contribuir com minhas habilidades e aprender com desenvolvedores experientes para criar aplicativos da Web de ponta. Possuo um perfil com disposição para o aprendizado e aprimoramento contínuos que me permite aprender novas tecnologias com facilidade e velocidade.

Entendo que esta profissão requer um alto nível de adaptabilidade e habilidades de resolução de problemas, e estou confiante em minhas capacidades. Não tenho medo de fazer perguntas ou buscar ajuda quando necessário e estou empenhada em me manter atualizada com as últimas tendências e melhores práticas para ser uma desenvolvedora bem-sucedida e de excelência.

##
<img width="200px" src="https://user-images.githubusercontent.com/123910027/227934144-deab4127-fa4a-48e3-9653-71033e1ba670.jpg" alt="Wallace"></br>
  - <a href="https://www.linkedin.com/in/wallacesb/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
  - <a href="https://github.com/Wall90s" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
<h3>Wallace Silva Brito</h3>
<h3>Sobre mim</h3>
Invenções e Tecnologias são dois assuntos que sempre fizeram meus olhos brilharem, me fazendo pesquisar e/ou conversar por horas. Depois de um tempo entendi que poderia unir os dois na área de desenvolvimento, desde que é claro, me dedicasse bastante, e é isso que tenho feito. Estudar todos os dias, conhecer novas tecnologias e aplicações, praticar o que já conheço, são alguns itens da minha rotina. Nisso vão horas com palestras, cursos e exercícios, que só me deixam mais interessado por esse oceano de possibilidades, e me ajudará a ser um ótimo Desenvolvedor de Sistemas Full Stack.

##


