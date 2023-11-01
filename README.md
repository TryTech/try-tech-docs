# Apresentação do Projeto TryTech

## Sobre a TryTech

A TryTech é uma empresa de software focada no desenvolvimento de soluções inovadoras para auxiliar outras empresas em sua jornada rumo ao sucesso. Nossa abordagem central é a criação de software modular, baseado em microserviços, abrangendo uma ampla gama de aplicações, desde sistemas web até aplicativos móveis. Acreditamos em fornecer soluções eficazes por meio de pacotes de software interconectados em uma estrutura de árvore, onde cada pacote depende dos anteriores, criando uma experiência integrada e completa.

## Nossos Objetivos Iniciais

Estamos comprometidos em oferecer uma ampla variedade de soluções para atender às necessidades específicas de nossos clientes. Aqui estão os principais projetos em andamento, juntamente com suas regras de negócio:

1. **Sistema de Recursos Humanos (RH):** A regra de negócio principal para o sistema de RH é automatizar e simplificar o gerenciamento de recursos humanos. Isso envolve a criação de perfis de funcionários, rastreamento de horas trabalhadas, registro de férias, controle de salários e benefícios, além de fornecer ferramentas para o acompanhamento de metas e desempenho dos funcionários.

2. **Sistema Financeiro:** A regra de negócio fundamental do sistema financeiro é ajudar as empresas a controlar suas finanças de forma eficaz.

3. **Gerenciamento de Funcionários e Exames:** A regra de negócio aqui é fornecer uma plataforma para gerenciar informações de funcionários, incluindo contratação, demissão e documentação relevante.

4. **Envio de E-mails Automáticos:** Esta regra de negócio visa melhorar a comunicação automatizando o envio de e-mails para serviços específicos.

5. **Relatórios Mensais e Gráficos:** O objetivo é coletar dados relevantes de vários sistemas da empresa e gerar relatórios mensais detalhados.

6. **Módulo Ponto Hora (Pacote Adicional):** A regra de negócio para o módulo de Ponto Hora é oferecer uma solução para o registro automático das horas de trabalho dos funcionários.

## Plano de Desenvolvimento

Atualmente, estamos iniciando com um monolito, que será desenvolvido com as seguintes tecnologias:

- **FastAPI:** Nosso monolito será construído em Python, com o framework FastAPI, priorizando a agilidade e eficiência no desenvolvimento.

- **PostgreSQL:** Usaremos o PostgreSQL como nosso banco de dados, que será orquestrado pelo Alembic e gerenciado pelo SQLAlchemy nas versões 1.3/1.4 (devido à limitação da versão do PostgreSQL no Heroku).

- **Celery:** Para processamento de tarefas em segundo plano, utilizaremos o Celery com tanto o worker quanto o beat, juntamente com Redis e RabbitMQ para gerenciamento de filas.

- **Web:** Para a interface web, adotaremos o Next.js na versão 14, garantindo um desenvolvimento moderno e ágil.

- **Aplicativo Móvel:** Para a plataforma móvel, optaremos pelo React Native com Expo, proporcionando uma experiência eficiente de desenvolvimento e entrega para dispositivos móveis.

Além disso, é importante destacar que, no futuro, planejamos evoluir nossa arquitetura de monolito para micro apps, utilizando linguagens mais adequadas para cada regra de negócio, garantindo escalabilidade e eficiência.

Cada tecnologia escolhida foi cuidadosamente selecionada para atender aos nossos objetivos e garantir que nossos produtos sejam eficazes e inovadores.
