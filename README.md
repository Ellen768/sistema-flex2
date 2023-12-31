# sistema-flex2
UNIVERSIDADE COMUNITÁRIA          
REGIONAL DE CHAPECÓ - UNOCHAPECÓ

ESCOLA POLITÉCNICA

Título: SITEMA FLEX - S.F.

1. Introdução

*1.1 Resumo do Projeto:*
   Um sistema criado para ajudar colaboradores de empresa com relatórios e ações através de um levantamento de dados colhidos pelo software, é uma ferramenta essencial para a gestão de uma organização. Essa plataforma é projetada para coletar, processar e apresentar informações críticas de negócios de forma organizada e compreensível, A plataforma deve ser acessível em vários dispositivos, como computadores, tablets e smartphones, para permitir que os usuários acessem informações quando e onde precisarem, os usuários devem poder criar consultas personalizadas e aplicar filtros para extrair os dados relevantes para seus relatórios.


*1.2 Plataforma de desenvolvimento:*

Uma combinação de Python, JavaScript e Ruby on Rails para desenvolver aplicativo web
abrangente e escalável.
Hardware necessário: Um computador com capacidade de 16 a 32 GB de RAM, 256GB de SSD, I7,
com Acesso a Internet e a virtualuização AWS.
Python:
IDE: Visual Studio Code ou Jupyter Notebook. Frameworks: Django, para desenvolvimento
web. Gerenciador de pacotes: pip e virtualenv para gerenciar dependências e ambientes
virtuais. Banco de dados: MySQL para produção.
JavaScript:
IDE: Visual Studio Code. Frameworks: React para desenvolvimento de interfaces de usuário
interativas. Gerenciador de pacotes: npm (Node Package Manager) para gerenciar
dependências. Banco de dados: MySQL.
Ruby on Rails:
IDE: RubyMine e Visual Studio Code. Framework: Ruby on Rails para desenvolvimento web.
Gerenciador de pacotes: Bundler para gerenciar as dependências do projeto. Banco de
dados: MySQL, para ambiente de produção.
Desenvolvedor/es: Desenvolvedor Full Stack, Desenvolvedor Mobile, Desenvolvedor de Banco de
Dados, Gerente de Projeto, Engenheiro-Arquiteto de Software, Analista de Testes, com único
desenvolvedor assumindo estes múltiplos papéis.


*1.3 Plataforma de operação:*

A plataforma de operação refere-se ao ambiente em que o sistema ou aplicativo é executado no
equipamento do colaborador abaixo estão exemplos de tecnologias para a operacionalização em diferentes plataformas.

1. Operação em Computadores:
Hardware: Processador Intel Core i5, 8 GB de RAM, disco rígido de 500 GB. Sistema
Operacional: Windows 10, macOSX, Ubuntu Linux. Navegador Web: Google Chrome, Mozilla
Firefox, Microsoft Edge. Banco de Dados: MySQL. Linguagens de Programação: Python,
JavaScript, Ruby. Frameworks e Bibliotecas: Django (Python), React (JavaScript), Ruby on Rails
(Ruby).

2. Operação para Dispositivos Móveis:
Hardware: Processador Qualcomm Snapdragon, 4 GB de RAM, armazenamento interno de 64
GB. Sistema Operacional: Android, iOS. Navegador Web: Google Chrome, Safari. Banco de
Dados: SQLite. Linguagens de Programação: Python, JavaScript, Ruby. Frameworks e
Bibliotecas: Django (Python), React Native (JavaScript), RubyMotion (Ruby).

3. Operação para Servidores Web:
Hardware: Servidores em nuvem. Sistema Operacional: Linux Ubuntu Server. Servidor Web:
Nginx, Apache. Banco de Dados: MySQL. Linguagens de Programação: Python, JavaScript,
Ruby. Frameworks e Bibliotecas: Django (Python), Node.js (JavaScript), Ruby on Rails (Ruby).
A plataforma de operação deve ser suficiente para atender a uma variedade de dispositivos,
garantindo a acessibilidade e a usabilidade do sistema para o maior número possível de
usuários.


*1.4 Definições e siglas:*

S.F - SISTEMA FLEX.


*1.5 Perspectiva do produto:*



1.5.1 Modos de operação:
1. Modo de operação baseado em interface gráfica de usuário: o sistema é acessado por um software que está no computador ou tablet do colaborador, com abas e várias ações onde a pessoa pode personalizar do jeito que ela se entende melhor e para melhorar a forma dela trabalhar...

2. Modo de operação baseado em aplicativos móveis: o sistema é acessado por meio de um
aplicativo móvel instalado em um dispositivo móvel. os usuários interagem com o sistema por
meio da interface do aplicativo.

3.Modo de operação baseado em navegador web: o sistema é acessado por meio de um
navegador web em um dispositivo conectado à internet.

*1.6 Funções do produto:*

   No geral, o sistema deve fazer:
R1.0 Coleta de Dados: O sistema deve ser capaz de coletar dados de várias fontes, como bancos de dados, sistemas de gestão de recursos humanos, sistemas de contabilidade, sistemas de produção, entre outros.
R1.1 Processamento de Dados: O sistema deve ser capaz de processar dados, o que pode incluir cálculos, agregações, filtragem e transformações para preparar os dados para a geração de relatórios.
R1.2 Geração de Relatórios: O sistema deve permitir a criação de vários tipos de relatórios, como gráficos, tabelas, dashboards e documentos exportáveis em formatos como PDF, Excel, CSV, entre outros.
R1.3 Personalização de Relatórios: Os usuários devem ter a capacidade de personalizar relatórios de acordo com suas necessidades, incluindo a seleção de métricas, datas, intervalos de tempo e outros parâmetros.
R1.4 Compartilhamento de Relatórios: Os relatórios gerados devem ser facilmente compartilháveis com outros usuários ou partes interessadas por meio de links, e-mails ou outros mecanismos.
R1.5 Análise de Dados: Além de apenas gerar relatórios, o sistema deve permitir análises mais aprofundadas, como a criação de gráficos de tendências, análise de dados históricos e a identificação de insights a partir dos dados.
R1.6 Melhorias Contínuas: O sistema deve ser atualizado e melhorado ao longo do tempo com base no feedback do usuário e nas necessidades da organização.


*1.7 Características dos usuários:*
USUÁRIO: Iniciam sessão no sistema usando suas credenciais para acessar as funcionalidades autorizadas, também inserem informações no sistema, como dados de clientes, transações financeiras, registros de produção, detalhes de pedidos e etc. Dependendo das funções, os usuários podem interagir com sistemas empresariais interconectados, como sistemas de CRM, ERP e outros, garantindo a consistência e integridade dos dados.
SISTEMA: A função do sistema é fornecer ferramentas e recursos que melhoram a eficiência operacional, facilitam a tomada de decisões informadas e permitem que as organizações alcancem seus objetivos de negócios de maneira mais eficaz e eficiente. Eles desempenham um papel crucial na gestão e na competitividade das empresas.


*2.1.1 Visão geral:*

Trazendo uma visão geral do meu software, basicamente é um sistema empresarial onde os colaboradores tem acessos através de usuários e senhas, e nele há várias ações que são criadas e alimentadas pelos dados da empresa, nele se pode tirar relatórios também, para ajudar no trabalho.


*2.2 Requisitos funcionais:*

*2.2.1 Diagramas de casos de uso (Modelo UML de Casos de Uso)*
O sistema inicia quando o usuário digita seu nome e senha, dentro do sistema são divididas ações e cada ação é dividida por um número , porém, dependendo o setor que a pessoa trabalha é preciso que um master libere. Você pode favoritar as mais usadas, para facilitar na hora de trabalhar…

![image](https://github.com/Ellen768/sistema-flex2/assets/148002304/425297c4-2f0d-4c35-965f-8bc2944417b6)

@startuml

top to bottom direction

!define BACKGROUND_COLOR white
skinparam backgroundColor BACKGROUND_COLOR

actor US                           #green;line:green;line.bold;text:purple


rectangle "SISTEMA FLEX " as Sistema   #white;line:black;line.bold;text:black; {
    usecase "Abrir sistema" as At             #lightgreen;line:blue;line.bold;text:blue
    usecase "Digitar us. e senha" as Card        #lightgreen;line:blue;line.bold;text:blue
    usecase "Digitar a ação" as Sol           #lightgreen;line:blue;line.bold;text:blue
    usecase "Ação 300" as Pag                      #lightgreen;line:blue;line.bold;text:blue
    usecase "Tirar rel." as Ag            #lightgreen;line:blue;line.bold;text:blue
    usecase "Enviar Rel." as Env  #lightgreen;line:blue;line.bold;text:blue
   
US --  At                              #blue;line:blue;line.bold;text:blue

At ..> Card                               #blue;line:blue;text:blue
Card ..> Sol                       #blue;line:blue;text:blue
Sol ..> Pag                      #blue;line:blue;text:blue
Pag ..> Ag                      #blue;line:blue;text:blue
Ag ..> Env                      #blue;line:blue;text:blue

@enduml

2.2.2 Fluxos dos casos de uso (Casos de Uso Expandidos e Diagramas de
Atividades
Descreve como o usuario entra, se caso não tiver um usuario criado ou uma ação liberada o master faz isso,  e mosta também como gera um relatório.

![image](https://github.com/Ellen768/sistema-flex2/assets/148002304/72d2efe6-646e-4a8c-a3a9-3c21d326df9a)
skinparam backgroundcolor transparent
|usuario|
start
:entra no sistema;
|master|
:cria um usuario;
:libera a ação;

|#lightgreen|Sistema|
:Digita us e a senha]
:pesquisa a ação;
:entra na ação e gera um relatório;

|usuario|
:manda o relatório por e-mail;


2.2.2.1 Caso de Uso expandido "Gerar relatórios":
Caso de Uso: Gerar relatório.
Atores: usuario e master.
Propósito: liberar ação e gerar relatório.
Descrição: a pessoa entra no software do sistema flex e digita o seu usuario e ao entrar pesquisa a ação e gera um relatório.

|                   Ação do Usuario                                      |            Resposta do Sistema         |
|------------------------------------------------------------------------|----------------------------------------|
| 1- O usuario entra no sistema e didgita uma senha;                     | - Usuario não existe;                  |
| 2- O usuario master cria um usuario;                                   | - Cria uma senha nova;                 |
| 3- O usuario digita uma ação;                                          | - Ação não encontrada;                 |
| 4- Digita a ação de novo;                                              | - Abre a ação;                         |
| 5- "Gerar relatório;                                                   | - Gera;                                |
| 6- O usuario decide se quer no excel;                                  | - Abre o relatório ne excel;           |
| 7- Manda no e-mail;                                                    |                                        |
|------------------------------------------------------------------------|----------------------------------------|

2.4 Objetos/Classes

2.4.1 Modelo Conceitual/Classes de Análise/Modelo de Domínio (Classes,
Associações, nomes das associações, Multiplicidades e Atributos)
@startuml
!theme carbon-gray
!define BACKGROUND_COLOR white
skinparam backgroundColor BACKGROUND_COLOR

' Definindo as classes

class master {
  - nome: String
  - criarUsuario(): String
  - liberarAcoes(): String
}

class Usuario {
  - nome: String
  - senha: String
  - acoes: String
}

class Sistema {
  - usuario: String
  - senha: String
}

class Acoes {
  - nome: String
  - numero: String
}

class Relatorio {
  - editar(): String
}

class Enviar {
  - salvar(): String
}

class Email {
  - nome: String
  - enderecoEmail: String
}

class Excel {
  - nome: String
}

class Imprimir {
  - nomeDaImpressora: String
}

class Salvar {
  - nome: String
}

' Relações de associação com multiplicidades e direções

master "1" --> "0..*" Usuario : controla
Usuario "1" --> "1" Sistema : acessa
Usuario "1" --> "0..*" Acoes : possui
Acoes "1" --> "0..1" Relatorio : edita
Enviar "1" --> "1" Email : envia
Enviar "1" --> "1" Excel : envia
Imprimir "1" --> "1" Salvar : imprime
@enduml
![image](https://github.com/Ellen768/sistema-flex2/assets/148002304/05157288-ca57-4136-aeb1-5603de8e6514)
