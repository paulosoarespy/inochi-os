# InochiOS — 01 · Requisitos

## Objetivo

O InochiOS nasce com dois propósitos que caminham juntos. O primeiro é pessoal: quero ter um único lugar que, ao ser aberto, me responda de forma imediata a pergunta "o que eu faço agora?". Hoje minha rotina se divide entre trabalho, faculdade e estudos, e chego em casa tarde, com pouco tempo e pouca energia para decidir por onde começar. Preciso de um sistema que pense a organização por mim e me mostre com clareza o que é prioridade.

O segundo propósito é profissional. Este projeto será um case do meu portfólio, construído do zero e documentado em cada etapa. Hoje o uso do Claude Code nas empresas é praticamente indispensável, e quero demonstrar na prática que sei projetar e orquestrar o desenvolvimento de um produto real com ele. Por isso, mais do que o app pronto, o processo importa: as fases, as decisões tomadas, os checkpoints e as verificações ficam registrados para mostrar como eu penso e trabalho.

## Nome

O nome une duas ideias. **命 (inochi)** significa "vida" em japonês, mas não a vida como simples rotina. É a vida no sentido de essência, aquilo que é precioso e merece cuidado. Já **OS (Operating System)** remete ao sistema operacional, que coordena tudo o que roda em um computador. Juntos, formam o conceito do projeto: um sistema operacional para aquilo que é precioso na minha vida, que coordena faculdade, tarefas, compromissos e ideias para que eu consiga cuidar do essencial.

## Problema

Meu maior problema hoje não é a falta de tempo, e sim a falta de um lugar de controle. Tarefas, prazos da faculdade, compromissos e ideias ficam espalhados entre aplicativos, anotações e memória. O resultado é que, nos poucos momentos livres que tenho, gasto energia tentando lembrar e decidir o que fazer, em vez de simplesmente fazer. Prazos escapam, ideias se perdem e a sensação constante é de estar sempre atrasado sem saber exatamente com o quê.

## Formato

O InochiOS será um app web progressivo (PWA), que pode ser instalado na tela inicial do celular e funciona como um aplicativo comum. Ele será pensado primeiro para o celular, já que é onde vou usá-lo na maior parte do tempo, mas também precisa funcionar bem no computador. Os dados serão sincronizados entre os dispositivos, e o acesso será feito com login pela conta Google, para que entrar no app seja rápido e simples.

## Escopo do MVP

A primeira versão vai se concentrar no que resolve o problema central. O coração do app será a tela **Hoje**, a primeira coisa que vejo ao abrir o InochiOS, reunindo as tarefas do dia, os prazos que se aproximam e os compromissos marcados. Ela é alimentada pelo módulo de **Tarefas**, onde posso criar, concluir e organizar atividades com data, prioridade e vínculo a uma matéria.

Logo em seguida vem o módulo **Faculdade**, que organiza minhas matérias, trabalhos e provas com seus respectivos prazos, já que é aí que mora a maior parte das datas que não posso perder. Por fim, a **Captura rápida** permite anotar uma ideia ou tarefa em até dois toques, sem precisar pensar em onde ela se encaixa naquele momento. A organização fica para depois.

## O que fica para depois

Algumas funcionalidades são importantes, mas não essenciais para a primeira versão. Entre elas estão a agenda completa com calendário, o planejamento de estudos e revisões, um espaço mais elaborado para organizar ideias, a integração com o Google Agenda para enviar compromissos a partir do app, as notificações e o funcionamento offline. Elas entram nas fases seguintes, depois que o MVP estiver sendo usado de verdade no dia a dia.

## Tecnologias

Escolhi tecnologias que são padrão de mercado, porque além de construir o app quero aprender ferramentas que vou encontrar em empresas. O front-end será feito com **React**, **TypeScript** e **Vite**. Para banco de dados, login com Google e sincronização, vou usar o **Supabase**, que oferece tudo isso em um plano gratuito. O deploy será feito na **Vercel**, que também é gratuita e gera uma URL pública para o portfólio. Todo o código e a documentação ficarão no **GitHub**.

Hoje tenho apenas o conhecimento básico dessas ferramentas. Isso faz parte do projeto: o aprendizado vai acontecer durante o processo e também será registrado aqui.

## Critério de sucesso

Vou considerar o MVP um sucesso quando abrir o InochiOS todos os dias e souber o que fazer sem precisar consultar nenhum outro lugar.

## Checkpoint da Fase 0

- [x] Objetivo definido
- [x] Nome definido
- [x] Problema definido
- [x] Escopo do MVP fechado
- [x] Tecnologias escolhidas
- [x] Requisitos aprovados

**Próxima fase:** 1 — Arquitetura
