# anime-list-organizer

Este projeto tem como objetivo implementar progressivamente e de forma didática uma aplicação web inspirada em operações comuns de instituições financeiras (ex: saque, depósito, extrato, saldo, cadastro), sendo o diferencial, a cobrança de taxas de forma abusiva para cada operação realizada pelo cliente.

O frontend da aplicação foi desenvolvido com HTML, CSS e JavaScript e o backend foi simulado pela implementação de uma API Fake, usando o JSON Server.

## Endereço de Deploy - GitHub Pages

    https://github.com/yuutokolanz/anime-list-organizer

## Protótipo

https://www.figma.com/file/caKBY1FshNOfM1NtFnuHD2/projeto-anime-list-organizer?type=design&node-id=0%3A1&mode=design&t=3Ae2PrpIllAQadFJ-1

## Checklist | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

#### RA1 - Utilizar Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos.
- [x] ID 01 - Implementa um layout responsivo de uma página web utilizando um Framework CSS, como Bootstrap ou Tailwind, que se adapta adequadamente a diferentes tamanhos de tela e dispositivos.
- [x] ID 02 - Utiliza técnicas avançadas de CSS, como Flexbox ou Grid Layout, para criar layouts responsivos e fluidos em diferentes resoluções de tela.
- [x] ID 03 - Utiliza os componentes CSS e JavaScript oferecidos por um Framework CSS, como cards, modais ou carrosséis, aplicando estilos personalizados conforme o necessário.
- [ ] ID 04 - Implementa um layout fluido e responsivo utilizando unidades de viewport relativas (vw, vh) em vez de unidades fixas (px) para criar uma experiência de usuário consistente em diferentes dispositivos e tamanhos de tela.
- [x] ID 05 - Implementa animações em elementos da página, como hover, fadeIn/fadeOut, slideIn/slideOut, utilizando CSS Animations ou bibliotecas de animação, como o Animate.css, para fornecer feedback visual ao usuário e criar uma experiência interativa.
~~ - [ ] ID 06 - Cria transições personalizadas entre diferentes estados da página ou elementos, como mudanças de layout, alterações de cor ou exibição/hide de elementos, usando CSS Transitions ou CSS Animation, para melhorar a usabilidade e a aparência da aplicação.~~
- [x] ID 07 - Aplica um Design System consistente, definindo diretrizes de estilo, cores, tipografia e padrões de componentes que são seguidos em toda a aplicação, garantindo uma experiência de usuário uniforme e atraente.

#### RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente, utilizando a API do HTML e expressões regulares (REGEX).
- [x] ID 08 - Implementa tratamento de formulários no lado cliente com apresentação de mensagens de erro ou sucesso, utilizando os recursos da API do HTML, como validação de campos obrigatórios, tipo de entrada e limites de caracteres, garantindo que os dados inseridos sejam válidos antes de serem enviados para o servidor.
- [x] ID 09 - Aplica expressões regulares (REGEX) de forma eficiente para realizar validações customizadas nos campos de formulários, como formatos específicos de e-mail, telefone, data ou outros padrões personalizados definidos pelos requisitos do projeto.
- [ ] ID 10 - Incorpora elementos de listagem, como checkbox, radio ou select, de maneira eficiente em formulários web, possibilitando a seleção e coleta precisa de dados pelos usuários.
- [x] ID 11 - Realiza a escrita e leitura de dados no Web Storage, permitindo a persistência de informações entre sessões de usuário e fornecendo uma maneira eficaz de armazenar dados localmente no navegador.

#### RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web, incluindo Node.js, NPM e linters para garantir a qualidade do código, juntamento com boas práticas de versionamento e organização de projetos.
- [x] ID 12 - Configura adequadamente um ambiente de desenvolvimento usando Node.js e NPM para gerenciar pacotes e dependências do projeto, facilitando a instalação e o uso de bibliotecas e ferramentas de terceiros.
~~- [ ] ID 13 - Utiliza linters, como ESLint ou Stylelint, para analisar e corrigir automaticamente problemas de código, incluindo erros de sintaxe, estilo e boas práticas, garantindo a qualidade e consistência do código do projeto.~~
- [x] ID 14 - Adota boas práticas de versionamento utilizando sistemas como Git, criando e gerenciando repositórios com branches adequados.
~~- [ ] ID 15 - Utiliza técnicas de minificação e otimização de recursos, como minificação de CSS e JavaScript e otimização de imagens, para melhorar o desempenho e o tempo de carregamento do site ou aplicação.~~
- [x] ID 16 - Organiza os arquivos do projeto em uma estrutura coerente, lógica e modular, facilitando a localização, manutenção e escalabilidade.
~~- [ ] ID 17 - Utiliza as metodologias BEM (Block Element Modifier) ou SMACSS (Scalable and Modular Architecture for CSS) para organizar e estruturar os estilos CSS de forma eficiente, garantindo a reutilização de estilos, a legibilidade do código e a manutenção sustentável do projeto.~~

#### RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web.
- [x] ID 18 - Utiliza a biblioteca jQuery para manipular o DOM e aprimorar a interatividade das páginas web, implementando funcionalidades como eventos, animações e manipulação de elementos HTML de forma eficiente. 
- [x] ID 19 - Seleciona e integra com sucesso um plugin jQuery, como o jQuery Mask Plugin ou outro plugin relevante para o projeto, a fim de melhorar a funcionalidade ou a aparência de elementos específicos em uma página web. 
~~- [ ] ID 20 - Utiliza bibliotecas de web components, como Lit, para criar componentes reutilizáveis e encapsulados, melhorando a modularidade e a manutenibilidade das páginas web. ~~
~~- [ ] ID 21 - Utiliza uma biblioteca de componentes prontos, como Material Web Components ou outra de escolha, ou então, algum componente independente (standalone) a fim de oferecer funcionalidades específicas sem a necessidade de estar integrado a uma biblioteca completa.~~

#### RA5 - Efetuar requisições assíncronas para uma API fake e APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente.
- [x] ID 22 - Realiza requisições assíncronas para uma API fake e APIs públicas, utilizando adequadamente conceitos como AJAX, Fetch API ou bibliotecas, para obter dados dinâmicos e realizar a manipulação e exibição dos resultados na página web.