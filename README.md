
# Teste para a produção de conteúdo - TRYBE

Olá produtor! Abaixo estão especificadas algumas orientações gerais sobre o conteúdo que você deve desenvolver.

Lembre-se que é importante demonstrar a sua criatividade, didática e organização ao longo de todo o conteúdo.

---

## O que deve ser desenvolvido

Você deve desenvolver uma página de conteúdo que ensine os estudantes como instalar e configurar um _linter_  de JavaScript no seu editor de código, mais especificamente o [ESLint](https://eslint.org/).

A página deve ser produzida no formato Markdown, seguindo as [guidelines do GitHub](https://guides.github.com/features/mastering-markdown/).

### Cenário

* Os estudantes são orientados a utilizar Linux ([Elementary OS](https://elementary.io/), [Ubuntu](https://ubuntu.com/) ou alguma outra distro _debian based_);

* Os estudantes são orientados a utilizar o [VSCode](https://code.visualstudio.com/) como editor de texto;

* ESLint é uma das [engines](https://docs.codeclimate.com/docs/eslint) utilizados pelo Code Climate para a análise estática de código;

### Requisitos obrigatórios

* Seu conteúdo deve considerar todos os pré-requisitos para a configuração do _linter_, como instalação do NodeJS, instalação do npm/npx, pacotes, etc;

* Incluir referências à artigos/videos externos, desde que estes estejam disponibilizados de forma gratuita na internet;

* Incluir um vídeo próprio, no formato de _screen recording_ exemplificando partes do processo de instalação e/ou configuração do _linter_;

* Após cada passo necessário para a instalação/configuração, você deve guiar o estudante sobre como confirmar que este foi executado corretamente.


### Contexto

Nosso curso utiliza **projetos práticos** para avaliar os estudantes nas _habilidades_ desenvolvidas ao longo dos blocos de conteúdo que são disponibilizados diariamente.

Os projetos são disponibilizados em _repositórios abertos no GitHub_, onde cada aluno deve **submeter um _Pull Request_** com o código desenvolvido para o projeto até a data limite de entrega do mesmo.

Para que os estudantes tenham uma experiência o mais próxima possível da realidade de times de desenvolvimento de ponta, algumas regras têm de ser seguidas por eles para que seus projetos sejam avaliados.

Dentre elas, está a **obrigatoriedade** de o código do estudante estar em conformidade com a análise estática do [Code Climate](https://codeclimate.com/). As regras/configurações das ferramentas que irão fazer a análise do código no Code Climate são disponibilizadas de antemão para os estudantes no repositório do projeto.

Orientamos aos estudantes para que não modifiquem essas configurações, já que isso pode alterar a análise da ferramenta no momento da avaliação, resultando em uma entrega não válida.

Dessa forma, é sugerido ao estudante que instale e configure ferramentas de análise estática de código no seu editor de texto local, para que possa corrigir quaisquer erros de _linting_ (estilo de código, complexidade, etc) antes de submeter o código, resultando em um ciclo mais rápido de _refactoring_ e consequente ganho na produtividade.

#### TL;DR

1. Estudantes são avaliados por projetos;

2. Projetos têm que passar nos checks do _Code Climate_ para serem avaliados;

3. Estudantes não devem alterar a configuração base do CodeClimate/ESLint/etc no código base do projeto;

4. Estudantes têm o feedback da análise do CodeClimate apenas após fazer o `push` de seus `commits` para o repositório do projeto;

5. Se os estudantes estiverem com uma ferramenta de _lint_ configurada em seus editores, poderiam ter esse feedback ao digitar o código, ou salvar o arquivo, etc resultando em um ciclo mais rápido de feedback e aumento de produtividade.

---

## Prazos

Você terá 7 dias corridos a partir do recebimento do teste para nos apresentar o conteúdo desenvolvido.

A partir daí, iremos disponibilizar o resultado da sua avaliação em até 30 horas contadas após o término do prazo de entrega (em dias úteis).

---

## Apresentação e Avaliação

Você deve submeter um Pull Request para esse repositório com o conteúdo produzido até a data limite.

O Pull Request deverá conter o arquivo Markdown com o conteúdo, formatado conforme as guidelines do GitHub, além de links para vídeos/referências externas e imagens/Gifs produzidos.

Seu conteúdo será revisado por dois membros do nosso time, no formato de _Code Review_.

Iremos avaliar critérios como:

* Aderência do conteúdo produzido com a especificação;

* Organização do conteúdo conforme o formato dos demais conteúdos existentes disponibilizados como exemplo;

* Planejamento adequado do tempo necessário para o estudante consumir o conteúdo;

* Didática, tom de voz e qualidade de vídeos/imagens/gifs apresentados;

* Disponibilização de recursos adicionais, exercícios bônus e/ou requisitos extras para os estudantes;


##### Dica: crie o Pull Request em modo `draft` e vá adicionando os `commits` conforme for evoluindo no conteúdo.

---

## Acesso às plataformas de conteúdos dos alunos

1. Peça ao recrutador que faça seu cadastro na [plataforma de conteúdo para os alunos](https://course.betrybe.com/) para você ter acesso à exemplos de conteúdo.

2. Além disso, caso julgue necessário você pode requisitar o acesso ao Slack dos alunos para obter mais contexto sobre como a dinâmica das aulas é conduzida por essa ferramenta.

---

## Dicas gerais

Abaixo estão algumas guidelines que o time de produção de conteúdo se baseia para a criação das aulas.

Leia-as atentamente, e sinta-se à vontade para sugerir melhorias e dar seu feedback (PR's são bem-vindos)! 👨‍🏫

* [General Guidelines](/docs/general_guidelines.md)
