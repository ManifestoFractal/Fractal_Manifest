# Manifesto da Educação Corporativa Fractal

### O novo letramento da era da IA

> Alfabetizar não é letrar. A fluência em IA não se entrega, se replica.

*Versão atual: **1.6.0** · junho de 2026.*

---

## Sobre

Este repositório abriga o **Manifesto da Educação Corporativa Fractal**, um convite e uma
provocação sobre como empresas e trabalhadores brasileiros devem repensar sua relação com o
saber na era das máquinas que pensam.

Contra a corrida do *"IA first"*, o manifesto propõe o oposto: organizações **saúde mental
first**, com as tecnologias jogando a nosso favor. A tese central é que o aprendizado em IA
**não pode ser entregue por decreto — ele precisa se replicar**, de baixo para cima, de nó em
nó, como um fractal.

O documento não é escrito de fora: nasce da experiência de quem constrói e adota essas
máquinas no dia a dia, validada ao longo de um ciclo de 12 meses na INOV.AI.

## A tese em uma frase

A IA redefiniu o letramento mais uma vez, e a maioria das empresas confunde a nova
**alfabetização** (saber clicar, saber digitar um prompt) com o novo **letramento** (ler
criticamente a relação entre humano e máquina e reescrevê-la a seu favor).

O novo letramento se sustenta sobre três camadas que se aprofundam:

1. **Conversar com as máquinas** — estruturar intenção, contexto e formato; iterar e depurar
   um prompt como se depura um código (*brainstorm com a máquina* como engenharia, não brincadeira).
2. **Compreender o que está por baixo** — a proximidade do cru: o ambiente aberto e a
   lógica da máquina. Quem entende a camada de baixo deixa de ser refém da camada de cima.
3. **Discernir com consciência crítica** — saber quando *não* confiar na máquina, reconhecer
   alucinação e delegação indevida de julgamento. A vigilância epistemológica que protege a
   qualidade do trabalho e a saúde mental de quem trabalha.

## Estrutura do documento

- **Preâmbulo** — escrevemos de dentro, não de fora.
- **Parte I — A tese**
  1. A crise: confundimos alfabetização com letramento
  2. O Novo Letramento: ler o mundo para reescrevê-lo com as máquinas
  3. A proximidade do cru: autonomia para a pessoa, soberania para a empresa
- **Parte II — O mecanismo**
  4. A geometria fractal: como o letramento se replica
  5. O Primeiro Nó: o protocolo de propagação
  6. A objeção honesta: por que o fractal não abole a governança
- **Parte III — A condição**
  7. Saúde mental first: segurança cognitiva como alicerce
  8. Da invasão cultural à comunicação emancipadora
- **Parte IV — A evidência**
  9. 12 meses na INOV.AI: o fractal em produção
  10. O referencial MIT Sloan CISR: do Estágio 2 ao Estágio 3
- **Parte V — Os compromissos**
  11. Valores e princípios fundamentais
  12. Protocolo de ação para a liderança (a partir de segunda-feira)
  13. Diálogos pedagógicos

📄 Documento completo (versão atual): [`manifesto_v1.6.0.pdf`](manifesto_v1.6.0.pdf)

## A evidência: 12 meses na INOV.AI

O manifesto não nasceu apenas de livros. O padrão fractal foi vivido em produção, propagando-se
por quatro escalas a partir de um grupo inicial de 10 pessoas:

| Escala | Participantes | Dinâmica prática | Impacto emergente |
| --- | --- | --- | --- |
| 1. O indivíduo | Cientista de dados sênior | Especialização em LLMs via linha de comando no terminal Linux | Salto de produtividade e precisão de rotinas |
| 2. O time técnico | 2 cientistas de dados + 4 de infraestrutura | Adoção de CLIs e ambientes de desenvolvimento assistidos | Colaboração ágil em sessões conjuntas de terminal |
| 3. O interfuncional | 4 advogadas | Transição do Jupyter ao terminal; uso ativo de LLMs via CLI | Construção autônoma de bases de conhecimento em Markdown |
| 4. A cultura | A empresa de forma integrada | Sessões conjuntas de engenharia de prompt entre jurídico e tecnologia | Forte redução de silos e maior coesão de linguagem |

Resultados práticos: precisão do classificador LAIS subiu de ~80% para ~96%; ciclos de sprint
encurtaram entre 25% e 50%; e o comportamento virou um **padrão autorreplicante**, sem mandato
de RH.

## Princípios fundamentais

- **Empoderar e não substituir** — a IA amplifica as faculdades humanas, nunca as substitui.
- **Saúde mental first** — a integridade mental e emocional é o ponto de partida, não o preço.
- **Incluir e não isolar** — tirar o debate dos comitês fechados e levá-lo a empresas de todos os portes.
- **Colaborar e não centralizar** — colaboração horizontal, par a par, livre de silos.
- **Autonomia e facilitação, não controle** — substituir o "comando e controle" pelo diálogo.
- **Maturidade por replicação fractal** — o letramento replica-se organicamente, a partir do Primeiro Nó.

## Como o manifesto evolui

Este manifesto é um **documento vivo** e evolui como um projeto de código aberto — não por
decreto de um autor, mas de baixo para cima, por contágio e em rede, exatamente como a tese
que ele defende. A mecânica é a do próprio Git:

1. **Discordar de um princípio → abra uma _issue_.** Toda objeção, dúvida ou crítica vira uma
   discussão pública e rastreável.
2. **Propor uma emenda → abra um _pull request_.** Mudanças concretas no texto entram como PR,
   com o *diff* à vista e abertas à revisão.
3. **Deliberar em aberto.** O debate acontece na própria issue ou PR, à vista de todos, sem
   comitê fechado.
4. **Consolidar.** Uma emenda aceita é incorporada (*merge*) ao `manifesto.md`, a fonte do
   documento.

O fluxo, em uma linha: **discordar → emendar → deliberar → consolidar.**

### Versões e releases

Cada conjunto de emendas aceitas gera uma nova versão, seguindo o
[Versionamento Semântico](https://semver.org/lang/pt-BR/):

- **MAJOR** (ex.: `2.0.0`) — mudança que altera a tese ou um princípio central.
- **MINOR** (ex.: `1.1.0`) — conteúdo novo e compatível: uma seção, um tema, um exemplo.
- **PATCH** (ex.: `1.0.1`) — correções de redação, dados ou links, sem mudança de sentido.

O histórico de cada versão é mantido em um changelog versionado, e toda versão
publicada gera um PDF nomeado por ela (`manifesto_v<versão>.pdf`). A versão vigente é sempre o
PDF de maior número na raiz do repositório.

## Autoria (a duas vozes)

- **Jane Ilha** — economista (bacharel pela UFPR, MBA pela FGV), especialista em educação
  corporativa e facilitação de grupos, com 17 anos de trajetória no setor bancário e
  financeiro e atuação estratégica na Unibrad (Universidade Corporativa Bradesco).
- **Fabrício Amaral** — físico (doutor em Física Teórica e Computacional, com tese em sistemas
  complexos), ex-professor de Caos e Fractais na UERJ, cientista de dados e sócio e diretor de
  inovação e IA da INOV.AI.

## Referências de apoio

**Sistemas complexos, fractais e redes**

- **Everett Rogers** — *Diffusion of Innovations* (Free Press, 1962).
- **Mark Granovetter** — *Threshold Models of Collective Behavior* (*American Journal of Sociology*, 1978).
- **Benoît Mandelbrot** — *The Fractal Geometry of Nature* (W. H. Freeman, 1982).

**Amplificação do intelecto: mente e máquina**

- **J.C.R. Licklider** — *Man-Computer Symbiosis* (*IRE Transactions on Human Factors in Electronics*, 1960).
- **Douglas Engelbart** — *Augmenting Human Intellect* (relatório técnico, Stanford Research Institute, 1962).
- **Edwin Hutchins** — *Cognition in the Wild* (MIT Press, 1995).
- **Andy Clark & David Chalmers** — *The Extended Mind* (periódico *Analysis*, 1998).

**Aprendizagem, letramento e educação corporativa**

- **Lev Vygotsky** — *Pensamento e Linguagem* (orig. 1934; ed. bras. Martins Fontes).
- **Benjamin Bloom** — *Taxonomy of Educational Objectives* (David McKay, 1956).
- **Paulo Freire** — *Pedagogia do Oprimido* (orig. 1968; ed. bras. Paz e Terra, 1974) e *Extensão ou Comunicação?* (Paz e Terra, 1969).
- **Brian Street** — *Literacy in Theory and Practice* (Cambridge University Press, 1984).
- **Edgar Morin** — *Introdução ao Pensamento Complexo* (orig. 1990; ed. bras. Sulina).
- **Jean Lave & Etienne Wenger** — *Situated Learning* (Cambridge University Press, 1991).
- **Magda Soares** — *Letramento: um tema em três gêneros* (Autêntica, 1998).
- **Hugo Assmann** — *Reencantar a Educação* (Vozes, 1998).
- **Marisa Eboli** — *Educação Corporativa no Brasil: Mitos e Verdades* (Editora Gente, 2004).
- **Clara Cecchini e Alexandre Teixeira** — *Aprendiz Ágil* (Arquipélago, 2020).
- **Conrado Schlochauer** — *Lifelong Learners: o poder do aprendizado contínuo* (Editora Gente, 2021).

**Unix e software livre**

- **Dennis Ritchie & Ken Thompson** — *The UNIX Time-Sharing System* (*Communications of the ACM*, 1974).
- **Doug McIlroy** — a filosofia Unix e o *pipe* (*Bell System Technical Journal*, AT&T Bell Labs, 1978).
- **Richard Stallman** — *GNU Manifesto* (*Dr. Dobb's Journal*, 1985); *Free Software, Free Society* (GNU Press, 2002).
- **Eric Raymond** — *The Cathedral and the Bazaar* (O'Reilly, 1999).

**Trabalho, saúde mental e organização**

- **Christina Maslach** — *Burnout: The Cost of Caring* (Prentice-Hall, 1982).
- **Shoshana Zuboff** — *In the Age of the Smart Machine* (Basic Books, 1988).
- **Arie de Geus** — *The Living Company* (Harvard Business School Press, 1997).
- **Technostress e fadiga de mudança** — Ragu-Nathan, Tarafdar et al., *Information Systems Research* (INFORMS, 2008).
- **Frederic Laloux** — *Reinventing Organizations* (Nelson Parker, 2014).
- **Edward Deci & Richard Ryan** — *Self-Determination Theory* (Guilford Press, 2017).
- **Amy Edmondson** — *The Fearless Organization* (Wiley, 2018).
- **Adam Grant** — *Think Again* (Viking, 2021).

**Evidência: maturidade de IA**

- **MIT Sloan CISR** — Enterprise AI Maturity Framework (pesquisa CISR 2024–2025).
