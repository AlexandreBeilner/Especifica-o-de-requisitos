# Título do Projeto de Software: 
Connect and Share

# Nome dos Desenvolvedores:
- Alexandre Beilner
- Evandro Weissheimer
- Gabriel Marino da Silva
- Matheus Eickhoff

# Introdução:
## Resumo do Projeto - Descrição Textual:
O usuário vai acessar o fórum e optar entre fazer login ou se cadastrar, se ele escolher fazer login, vai poder optar entre administrador ou usuário comum. Com tudo, se optar por ter acesso a uma conta como administrador, ele poderá fazer o gerenciamento de usuários e conteúdo. No gerenciamento de conteúdo ele conseguirá fazer o controle das publicações que estiver fora do escopo do fórum, publicações de má índole entre outras. Já no gerenciamento de usuário ele conseguirá fazer o bloqueio de usuários e tornar usuários comuns como administradores, além de ter todas as funcionalidades do usuário comum.
Se optar por se cadastrar, o usuário terá que preencher campos como o nome completo, idade, email e senha. Assim que concluir o cadastro terá acesso ao seu perfil, que poderá adicionar mais informações pessoais, como cursos superiores, especializações e interesses. Também terá uma página chamada início onde será possível ver postagens relacionadas a práticas sustentáveis na inovação e infraestrutura, como materiais sustentáveis, energias renováveis e outras soluções eco-amigáveis, tendo como interagir através de comentários, reações e compartilhamentos, dessa forma podendo gerar discussões sobre os assuntos abordados, compartilhamento de experiências e motivar projetos colaborativos. Além disso, você poderá fazer suas próprias publicações, que posteriormente aparecerão no seu perfil e para outros usuários.

## Atores
Aqui estão exemplificados os Atores do nosso projeto
- Administrador
- Usuário

## Principais Abas do Site
Aqui nos Falamos das Principais Abas do site do nosso projeto
- Forum
- Aba de log-in/sign-in
- Perfil do usuário
- Painel do administrador
- Página do projeto

# Design Thinking
O Design Thinking demonstra a ideia Geral do nosso Projeto
![Design Thinking](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/127603510/03c1e62c-0e8c-4934-886b-e4a4da378cd1)

# Matriz CSD
A Matriz CSD Demonstra as Nossas Certezas, Incertezas e Duvidas Referentes ao Nosso Projeto
![Matriz CSD](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/127603510/1a95ff6c-ceeb-4f75-bb5d-6d49c08f7d24)

# BPMN
O BPMN serve para nos conseguirmos rastrear por onde um usuário comum vai usar o nosso site
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/127603510/93e5a5f7-be34-4892-997b-f22799163e4a)


## Plataforma de Desenvolvimento:
A plataforma será desenvolvida utilizando tecnologias web, incluindo HTML, CSS, JavaScript, e frameworks de desenvolvimento web. O banco de dados será implementado usando um sistema de gerenciamento de banco de dados relacional. Além disso, a plataforma será hospedada em servidores web compatíveis com as tecnologias selecionadas.

## Plataforma de Operação:
Os usuários da plataforma poderão acessá-la por meio de navegadores da web em seus dispositivos, como computadores, tablets e smartphones. Não é necessária a instalação de nenhum software adicional no dispositivo do usuário para operar a plataforma.

## Definições e Siglas:
- ER: Elicitação de Requisitos
- UML: Unified Modeling Language
- BPM: Business Process Model and Notation

# Perspectiva do Produto
## Modos de Operação:
A plataforma terá os seguintes modos de operação:
- Back-end: Gerenciamento e manutenção do sistema.
- Front-end: Interação dos usuários com a interface da plataforma.
- Móvel: Acesso à plataforma por meio de dispositivos móveis.

## Requisitos de Adaptação ao Ambiente:
A plataforma deve estar em conformidade com as regulamentações e leis ambientais relevantes. Além disso, ela deve ser capaz de se adaptar a ambientes de operação críticos, como a indústria, e suportar protocolos de comunicação específicos quando necessário.

## Funções do Produto:
Principais funções da plataforma:
- Compartilhamento de projetos sustentáveis.
- Criação de discussões e fóruns de discussão.
- Perfis de usuário personalizáveis.
- Notificações de atividade na plataforma.

## Características dos Usuários:
Os usuários da plataforma podem incluir profissionais da área da construção, engenheiros, arquitetos, ambientalistas e qualquer pessoa interessada em práticas sustentáveis na infraestrutura. As características dos usuários podem variar em termos de cargo, permissões de acesso, frequência de uso, nível de instrução e experiência em informática.

## Restrições:
A plataforma deve cumprir todas as regulamentações legais, incluindo a Lei Geral de Proteção de Dados (LGPD) e outras legislações relacionadas à privacidade e segurança de dados. Restrições técnicas e gerenciais podem impactar o desenvolvimento, mas serão abordadas conforme necessário.

## Hipóteses de Trabalho:
As hipóteses de trabalho incluem a seleção do sistema operacional, versões de ferramentas de software, licenças de bibliotecas e subsistemas compatíveis com as tecnologias escolhidas para o desenvolvimento da plataforma.

# Requisitos Específicos
## Interfaces Externas
### Visão Geral:
A plataforma terá interfaces gráficas de usuário para permitir a interação dos usuários com a plataforma. Isso incluirá a capacidade de criar e compartilhar projetos, participar de discussões, notificações de atividade e acesso aos perfis de usuário.

### Requisitos para Interfaces Gráficas de Usuário:
Para as interfaces gráficas, serão incluídos mockups e wireframes que representam o layout sugerido da interface. Além disso, serão descritos relacionamentos com outras interfaces, diagramas de estados/atividades, campos de dados, comandos e fluxos de processos de negócios.

## Requisitos Funcionais:
### Diagramas de Casos de Uso:
Serão desenvolvidos diagramas de casos de uso modelados no formato UML, identificando todas as funcionalidades a serem implementadas na plataforma.
![Fórum Connect and Share(1)](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/127603510/48e550db-745f-401d-8afc-18802be87bf3)

### Fluxos dos Casos de Uso:
Os casos de uso serão detalhados, incluindo pré-condições, fluxo principal, fluxos alternativos, descrições formais, diagramas de estado ou atividade, quando necessário, e observações.

## Requisitos Não-funcionais:
### Requisitos de Desempenho:
Os requisitos de desempenho, como velocidade de banda, tempo de resposta das interfaces e impressão de relatórios, serão especificados de forma quantitativa e mensurável.

### Requisitos de Dados Persistentes:
A estrutura de dados persistente, incluindo o modelo de banco de dados, será descrita para manter informações relevantes sobre projetos, usuários e atividades na plataforma.

### Restrições ao Desenho:
Restrições de projeto impostas por padrões externos e legislação serão observadas e incorporadas ao desenvolvimento da plataforma.

### Atributos de Qualidade:
Usabilidade, eficiência, confiabilidade, manutenibilidade, portabilidade e segurança.

## Objetos/Classes:
### Modelo Conceitual:
É uma representação visual simplificada e abstrata de um sistema ou domínio. Ele descreve os conceitos principais, as relações entre eles e as propriedades essenciais, fornecendo uma visão geral compreensível do sistema antes de se aprofundar nos detalhes de implementação.
![Classe UML](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/127603510/54b84a72-c90c-463d-8014-3d2191f60e8f)

### Wireframes ou mockups:
Link do projeto no canva: https://www.canva.com/design/DAF1rqMJTWs/N_11LXsBcVRB9KvYf-XMdw/edit?utm_content=DAF1rqMJTWs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton


![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/373aef7f-a461-40aa-9fba-0a316c99a4dd)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/ea507280-7f5d-4831-b7f8-8cdc59ee24b0)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/5f11bad0-c617-4921-a82d-134bda5879fe)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/d479e452-8ec2-4371-8e26-4ed966c2e2c4)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/9beb77a4-a50f-4891-a697-df85c3f8e513)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/f46a4237-d42f-4a4b-9f2a-54ed1486ab32)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/b467e323-6280-404f-995f-77acb2541000)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/05a4f04f-72e9-4d73-b1a7-a7804fb8a98a)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/8ebbcdde-81ec-4fa4-93ff-1bfb3a488558)
![image](https://github.com/AlexandreBeilner/Especifica-o-de-requisitos/assets/134701937/a2459fae-bcfb-47e1-bbe9-25a34e317d07)



# Referências:
- IEEE Std. 830 – 1993. IEEE Recommended Practice for Software Requirements Specifications.

Este modelo de especificação de requisitos será complementado e detalhado ao longo do desenvolvimento do projeto, de acordo com as necessidades e evolução do mesmo.
