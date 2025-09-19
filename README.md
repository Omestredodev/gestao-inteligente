# Sistema de Gestão de Manutenção de Veículos

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Guilherme Gomes dos Santos
- Gabriel Isai Soliz Choque

## Resumo

Sistema web para gestão e manutenção de veículos, voltado para proprietários e mecânicos. A aplicação permite o cadastro de veículos, registro de manutenções, controle de custos e emissão de alertas para revisões futuras, facilitando o planejamento e o histórico de serviços realizados.

## Introdução

A manutenção de veículos é essencial para garantir segurança, desempenho e economia a longo prazo. No entanto, muitos proprietários e até mesmo mecânicos enfrentam dificuldades em manter um controle eficaz sobre revisões, custos e históricos de serviços. Esse sistema surge como uma solução prática e acessível para organizar todas essas informações de forma centralizada.

Objetivo resumido: Oferecer uma ferramenta digital para facilitar o controle de manutenções e custos de veículos, tanto para proprietários quanto para mecânicos.

Experiência esperada pelo usuário: A aplicação deve proporcionar uma navegação simples, com dados visuais claros (dashboards), funcionalidades intuitivas e lembretes automáticos — promovendo praticidade e confiabilidade no controle de veículos.

## Publico Alvo

- Proprietários de veículos que desejam controlar os gastos e histórico de manutenção dos seus automóveis.
- Donos de oficina mecânica, centros automotivos ou mecânicos independentes que desejam registrar seus serviços prestados aos seus clientes.

### Personas

 - Persona primária - Cesar, Proprietário de oficina.

    - Idade: 35 anos.

    - Profissão: Mecânico e dono de um centro automotivo.

    - Contexto: Atende clientes da região e quer melhorar o acompanhamento dos serviços realizados.

    - Nivel de Renda: Média-Alta.

    - Comportamento digital: Usa redes sociais para divulgar a oficina, mas ainda anota os serviços realizados no papel.

    - O que espera do sistema: Um painel simples para registrar os serviços por cliente e enviar lembrentes recorrentes para revisões:

    - Informações que o sistema deve guardar: Dados dos clientes, veículos atendidos, serviços realizados, datas e valores cobrados.
     

- Persona primária - Neide, Proprietária Organizada.

     - Idade: 45 anos.

     - Profissão: Engenheira Civil.

     - Contexto: Usa o carro diariamente para trabalhar e viajar com a família. Preza por economia e manutenção preventiva.

     - Nível de renda: Média.

     - Comportamento digital: Acostumada a usar aplicativos de controle financeiro e produtividade.

     - O que espera do sistema: Facilidade para cadastrar manutenções, receber lembretes e ter uma visão claro dos gastos com seu veículo.

     - Informações que o sistema deve guardar: Nome, e-mail, dados do veículo (modelo,placa,ano), histórico de manutenções, custos e datas de revisão.


---
      
## 📌 Mapa de empatia

![Mapa de empatia](empatia.png)

Mapa de empatia de duas personas definidas para o sistema de **gestão e manutenção de veículos**:  
- **Persona Primária:** Neide, proprietária organizada (muito chata, exigente, detalhista).  
- **Persona Secundária:** Cesar, mecânico e dono de oficina (muito tranquilo, prático, objetivo).  

---
## 👨 Persona primária — Cesar, Mecânico e dono de oficina

### O que vê
- Oficina movimentada, carros chegando, clientes pedindo serviços.  
- Post-its e anotações antigas grudadas na parede.  
- Redes sociais usadas para divulgar promoções.  

### O que ouve
- Clientes pedindo prazos e explicações simples.  
- Sons típicos da oficina: ferramentas, motores, telefone tocando.  
- Conversas informais com outros mecânicos.  

### O que diz e faz
- Prefere resolver rápido sem burocracia.  
- Anota no papel ou celular de forma simples.  
- Gosta de tratar clientes de forma amigável e prática.  
- Diz que “não tem tempo para complicação”.  

### O que pensa e sente
- Quer manter os clientes satisfeitos sem gastar muito tempo em organização.  
- Acredita que um sistema pode ajudá-lo a reter clientes.  
- Sente tranquilidade quando acompanha tudo de forma simples.  
- Não gosta de excesso de detalhes.  

### Dores
- Perder anotações importantes feitas em papel.  
- Esquecer revisões e datas de retorno de clientes.  
- Sistemas muito complexos que exigem treinamento.  
- Dificuldade em manter contato recorrente com clientes.  

### Ganhos
- Painel prático para registrar serviços.  
- Lembretes automáticos para clientes retornarem.  
- Economia de tempo e fidelização de clientes.  
- Maior confiança dos clientes pela organização.  

---

## 👩 Persona primária — Neide, Proprietária Organizada

### O que vê
- Aplicativos de organização financeira, lembretes no celular, planilhas e dashboards coloridos.  
- Comerciais de revisão preventiva e propagandas de concessionárias.  
- Pessoas comentando sobre gastos altos com manutenção.  

### O que ouve
- Conselhos de amigos e familiares sobre economia com carro.  
- Mecânicos recomendando revisões frequentes.  
- Alertas de aplicativos que usa no dia a dia (banco, saúde, produtividade).  

### O que diz e faz
- Reclama quando não encontra informações claras.  
- Exige detalhamento e quer tudo documentado.  
- Gosta de comparar preços e registrar cada gasto.  
- Cobra respostas rápidas e suporte eficiente.  

### O que pensa e sente
- Quer segurança e organização absoluta no histórico do veículo.  
- Sente ansiedade quando não tem controle dos custos.  
- Tem medo de gastar mais do que deveria por falta de planejamento.  
- Espera que o sistema funcione como um “assistente pessoal”.  

### Dores
- Sistemas confusos ou desorganizados.  
- Falta de relatórios detalhados.  
- Lembretes genéricos e pouco personalizados.  
- Ter que depender da memória ou anotações em papel.  

### Ganhos
- Controle total sobre custos e manutenções.  
- Relatórios visuais e alertas bem configurados.  
- Economia de tempo e dinheiro.  
- Tranquilidade em saber que está prevenindo problemas futuros.  

---

### Conclusão

- **Cesar (primária):** Busca **simplicidade, praticidade e agilidade**.  
- **Neide (primária):** Exige **detalhes, controle e relatórios completos**.  

O sistema deve equilibrar essas necessidades, oferecendo **recursos avançados para usuários exigentes** e, ao mesmo tempo, **uma interface simples e direta para quem busca praticidade**.

## 🌍 Contexto de Uso

### Ambiente de utilização
O serviço será utilizado em dois cenários principais:  
1. **Ambiente pessoal/doméstico** – onde proprietários de veículos (como Neide) acessam a aplicação em casa, no trabalho ou em mobilidade, usando computador ou smartphone.
   Acessa o sistema em seu celular sempre que recebe uma notificação relacionado a revisões que necessitam ser feitas periodicamente em seu automóvel, ja aproveitando para prever dispesas futuras e manter um controle financeiro adequada ao seu orçamento.    


2. **Ambiente profissional/oficina** – onde mecânicos e donos de oficina (como Cesar) utilizam o sistema em meio à rotina de atendimento, registrando informações rapidamente entre um serviço e outro.
   Mecânicos geralmente lidam com orçamentos de mão de obra, orçamentos de peças, horários/prazos de entrega de veículos, enquanto precisam diagnosticar os problemas dos veículos e buscam os meios para solucionar os mesmos.
   Por estarem ocupados diariamente com todos esses afazeres, falta tempo e recurso para manter organizado os históricos de serviços prestados aos clientes, e recordar valores cobrados anteriormente.  

---

### Contextos sociais, econômicos e culturais
- **Sociais:**  
  - Proprietários de veículos preocupados com segurança, organização e economia.  
  - Oficinas e mecânicos buscando fidelizar clientes e manter histórico de serviços.  

- **Econômicos:**  
  - Aumento dos custos de manutenção e peças automotivas.  
  - Necessidade de controlar gastos para evitar surpresas financeiras.  
  - Mecânicos em busca de competitividade no mercado local, utilizando tecnologia como diferencial.  

- **Culturais:**  
  - Uso crescente de aplicativos para organizar finanças, agendas e serviços.  
  - Preferência por soluções digitais que sejam **simples, rápidas e confiáveis**.  
  - Expectativa de receber lembretes automáticos e relatórios visuais claros.  

---

### Informações que o sistema deve guardar antes da interação
- **Para proprietários (Neide):**  
  - Dados pessoais (nome, e-mail).  
  - Informações detalhadas do veículo (modelo, ano, placa, quilometragem).  
  - Histórico de manutenções anteriores.  
  - Preferências de notificação e periodicidade de lembretes.  

- **Para mecânicos (Cesar):**  
  - Dados da oficina e do cliente.  
  - Registro dos serviços já realizados.  
  - Valores cobrados e datas de revisões.  
  - Informações de contato para lembretes automáticos.  

---

### Situação típica durante a interação
- **Proprietário (Neide):**  
  - Está em casa ou no trabalho, analisando custos do veículo.  
  - Pode estar recebendo um lembrete de revisão ou planejando despesas futuras.  
  - Busca praticidade e relatórios detalhados para comparar gastos.  

- **Mecânico (Cesar):**  
  - Está na oficina, com o ambiente movimentado e barulhento.  
  - Pode estar registrando rapidamente um serviço entre atendimentos.  
  - Busca rapidez, simplicidade e lembretes automáticos para manter contato com clientes.  


## Jornada do usuário

## Jornada do Cesar(Mecãnico e dono de oficina)

### 1 - Primeira interação
- Acessa o sistema interessado em obter um atendimento organizado, personalizado e fidelizar seus clientes. Como uma forma de otimizar seu tempo.
- Cadastrar sua oficina (Nome, telefone, email, endereço, CNPJ, CPF, serviços oferecidos e tabela de preço).
- Cadastrar seus clientes (nome, veículo, telefone, email, CPF/CNPJ e endereço).

### 2 - Organização
- Agenda serviços e registra ordem de serviços que estão em andamentos.
- Controla o historico de cada atendimento feito e quando foi realizado, proporcionando uma melhor organização.
- associa os clientes ao veiculos e serviços solicitados.

### 3 - Gestão financeira
- Consulta os relatórios financeiros dos faturamentos e os serviços que foram mais vendidos
- anota o fluxo de clientes semanais e identifica os periodos aonde ocorre o maior movimento.
- transfere os dados para criar relatórios contábeis e fazer planejamentos.

### 4 - Fidelização de clientes
- faz envio automático de lembretes de revisão e troca de óleo.
- analisa quais clientes retornam e quais pararam de vir.
- cria campanhas de promoções sazonais e envia aos clientes.


## Jornada da Neide(Proprietária organizada)

### 1 - Primeira interação
- Acessa o sistema buscando praticidade, organização e segurança para não esquecer revisões importantes.
- Cria uma conta informando os dados pessoais(Nome, telefone, e-mail, CPF, data de nascimento e endereço).
- Cadastra o veículo (Modelo, marca, ano, placa e histórico de manutenções).

### 2 - Registro inicial
- Adiciona as últimas manutenções que foram feitas no veículo
- Indica valores que foram gastos nos serviços ja realizados para gerar relatórios.

### 3 - Relatorio dos custos
- Acessa todos os relatórios anuais e mensais do veículo.
- Cria e visualiza gráficos por categoria de serviços ja feito no automóvel.

### 4 - Controle do histórico
- Visualiza todo o histórico dos serviços ja feitos no veículo, incluindo as datas e custos
- Adiciona observações pessoais relacionado aos serviços.
- Adiciona lembretes de revisões futuras e vencimentos de garantia.

## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados

## 1 - Tipo de coleta:
https://docs.google.com/forms/d/e/1FAIpQLScHyF849OKczKYEathKvsZlWT-veXDk2LvuifYBDKcSblhHfg/viewform?usp=dialog

## 2 - Tipo de coleta:
Roteiro de entrevista: 

## -- Perguntas para os proprietários de veículos:

° Quando você está pensando em levar seu carro para a manutenção, o que causa essa decisão?

° Você já passou por alguma situação ruim em alguma oficina? O que aconteceu?

° O que te deixa mais tranquilo no processo de manutenção do seu veículo?

° Se você pudesse ter um recurso extra no celular para conseguir cuidar do seu carro, o que  mais seria útil para você?

## -- Perguntas para mecânicos/donos de oficina:

° No seu dia a dia, qual tarefa administrativa usa a maior parte do seu tempo?

° Quando um cliente deixa de voltar na sua oficina, qual você acha que é o principal motivo?

° Se existisse uma ferramenta que pode resolver apenas um problema da sua oficina, qual problema você escolheria para resolver primeiro?

° Quais recursos você considera indispensável em um sistema de gestão de oficina?

## 3 - Tipo de coleta:
Classificação de cartões: 
## -- Gestão da Oficina (mecânico/dono):

° Tabela de preços dos serviços oferecidos

° Agenda de serviços

° Notificação de agendamentos

° Relatórios financeiros

° Controle de estoque de peças

° Histórico de atendimento

° Comunicação com o clientes (WhatsApp, e-mail, ligação)

° Lembretes de revisão para os clientes

° Controle de pagamentos (recebidos e os pendente)

° Cadastro da oficina

° Cadastro de clientes

° Cadastro de veículos dos clientes

—--------------------------------------

## -- Proprietário de Veículo: 

° Cadastrar o veículo próprio

° Histórico de manutenções do veículo

° Lembretes de troca de óleo

° Lembretes de revisão periódica

° Comparação de custos de todos os serviços usados

° Relatórios de gastos com o carro

° Agendamento online dos serviços

° Receber o orçamento digital

° Consultar os status de serviço

° Avaliar a oficina após atendimento

### Modelo de tarefas

1 -- Modelo:
## -- Cadastrar Oficina (César):  // Usar esse objetivo principal para fazer os outros 3 metodos(GOMS, CTT e diagramas/tabela).

  Objetivos/Operações               |               Problemas e recomendações
                                    |
  0. Cadastrar a oficina            |       
  1. Informar dados da oficina      | Plano: informar nome, telefone, e-mail, endereço e i
  
  
  
  
  /* Tarefa:                            Subtarefas:                                               Descrição/Detalhamento:
  0. Cadastrar a oficina       0.1 Acessar o sistema                                    O dono faz login ou cria uma cont
                               0.2 Selecionar a opção “Cadastrar a Oficina”             Entra na seção de cadastro
                               0.3 Preencher os dados principais da oficina             Nome, telefone, e-mail, endereço
                               0.4 Inserir os dados fiscais da oficina                  CNPJ/ CPF
                               0.5 Cadastrar os serviços oferecidos                     os tipos de serviços e preços oferecidos
                               0.6 Salvar os cadastros feitos                           os dados ficam disponíveis no sistema
                               0.7 Receber a confirmação do sistema                     Mensagem dizendo “Cadastro foi concluído com sucesso” */

### Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->









