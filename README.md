# 37-LutoKunkel
Nome da equipe:LutoKunkel
Lista de integrantes com suas funções:(Caio:programador;Diogo:arquitetura;João:designer;Carol:designer;Felipe:arquitetura.

 Escopo do Projeto
Problema:
Muitos produtores rurais possuem dificuldades para interpretar análises de solo, planejar culturas, avaliar riscos climáticos e tomar decisões de manejo de forma rápida e organizada. Isso pode gerar perdas de produtividade, desperdício de insumos e aumento dos custos de produção.

Solução Proposta:
O AgroInteligente é um sistema web de gestão rural que centraliza informações da propriedade, análise de solo, culturas agrícolas e condições climáticas. Com base nos dados informados pelo produtor, o sistema gera um relatório agronômico contendo recomendações de correção do solo, manejo, adubação, produtividade esperada, riscos climáticos e próximos passos para melhoria da produção.

 Stack Tecnológica:

O sistema AgroInteligente foi desenvolvido utilizando tecnologias web voltadas para simplicidade, desempenho e fácil manutenção.

Linguagens de Programação
HTML5 – estrutura das páginas do sistema.
CSS3 – estilização da interface e design responsivo.
JavaScript (ES6) – implementação das funcionalidades, validações e processamento dos dados.
Banco de Dados
LocalStorage (Navegador Web) – utilizado para armazenar usuários, propriedades rurais, análises e configurações localmente no navegador.
Frameworks

Atualmente o projeto não utiliza frameworks, sendo desenvolvido com JavaScript puro (Vanilla JavaScript).

Bibliotecas
Google Fonts – utilizada para carregamento da fonte Playfair Display.
Recursos nativos do navegador para manipulação de dados e interface.
APIs

Atualmente o sistema não possui integração com APIs externas. 

Arquitetura:

A arquitetura do sistema AgroInteligente segue o modelo de aplicação web em camadas, onde o usuário interage com a interface gráfica, os dados são processados pela lógica de negócio e armazenados localmente para posterior consulta.

Diagrama da Arquitetura
┌─────────────────────────┐
│         Usuário         │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│ Interface Web           │
│ HTML + CSS              │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│ Camada de Aplicação     │
│ JavaScript              │
│ (Regras de Negócio)     │
└────────────┬────────────┘
             │
 ┌───────────┼───────────┐
 │           │           │
 ▼           ▼           ▼
┌───────┐ ┌───────┐ ┌─────────┐
│ Solo  │ │Clima  │ │Culturas │
└───┬───┘ └───┬───┘ └────┬────┘
    │         │           │
    └─────────┼───────────┘
              ▼
┌─────────────────────────┐
│ Motor de Análise        │
│ Agronômica              │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│ Relatórios e            │
│ Recomendações           │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│ LocalStorage            │
│ (Banco Local)           │
└─────────────────────────┘

situação do projeto :concluida.

link video de apresentação:
https://youtube.com/shorts/oqLXrRnB4tc
