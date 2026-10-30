# AgendAI

Assistente de rotina com inteligência artificial que agenda, planeja e se adapta ao estudante.

**Disciplina** Engenharia de Software (EEL873)
**Professor(a)** Geraldo Xexéo
**Período** 2026.2

**Integrantes**
- Fernando Bruzzi
- Giovanni Almeida
- Raphaela Barbosa
- Pedro Ivo Pinheiro

## Links

- Página do projeto (GitHub Pages) https://fernandobruzzi.github.io/Engenharia-de-Software/
- Repositório https://github.com/fernandobruzzi/Engenharia-de-Software

## Sobre este repositório

Este repositório reúne os artefatos do Trabalho 1 da disciplina. Nesta primeira entrega, ele contém a proposta inicial informal do sistema e a análise do valor entregue segundo as pirâmides de valor B2C e B2B (Bain & Company). Ao longo do curso, novos artefatos serão acrescentados, como as histórias de usuário.

## Estrutura

| Caminho | Conteúdo |
|---|---|
| `README.md` | Este arquivo, com a explicação do projeto e os links |
| `docs/index.html` | Página publicada no GitHub Pages com a proposta e a análise de valor |

## Proposta inicial informal

É normal, para alunos da UFRJ, não encontrar uma rotina facilmente e, quando a encontram, não conseguir segui-la. Por isso, idealizamos um serviço menos focado nas tarefas e mais focado no usuário.

A ideia é desenvolver um sistema capaz de realizar duas funções, agendar e planejar, com uma IA integrada que pode gerir a rotina do usuário de forma ativa, sugerir tópicos de estudo e interagir com o usuário como um chatbot. O usuário pode inserir as datas de seus compromissos e as tarefas semanais manualmente ou por meio da conversa com o bot. As tarefas são adicionadas a uma lista de afazeres diários e organizadas por prioridade, de acordo com critérios como data limite de entrega, urgência e tempo estimado de conclusão.

A IA, com base nas informações capturadas na interação com o usuário e no reforço (tarefa bem-sucedida, compromisso bem cumprido), é capaz de mudar a abordagem e as técnicas de aprendizado (a técnica Pomodoro, por exemplo) para atingir o objetivo. Assim, otimiza a execução das tarefas de acordo com o tempo disponível em cada dia e acompanha as sessões que compõem cada tarefa, interrompendo e retomando com base nas técnicas adotadas e no comportamento do usuário.

Quando o usuário informa a data de suas avaliações, o sistema pode gerar um cronograma de estudos que distribui os conteúdos a serem revisados ao longo das semanas anteriores à prova, de modo que o usuário não precise lembrar a todo momento o que tem de estudar.

Dessa maneira, o usuário gasta menos tempo pensando no que fazer e passa a ter mais tempo para executar suas tarefas de forma otimizada e se desenvolver como profissional.

## Análise de valor

### Pirâmide B2C (cliente é o estudante)

| Nível | Elementos escolhidos | Justificativa resumida |
|---|---|---|
| Funcional | Economiza tempo, Simplifica, Organiza, Integra, Reduz esforço, Evita aborrecimentos, Informa | O sistema prioriza tarefas, centraliza agenda e estudos, distribui revisões e sugere tópicos |
| Emocional | Reduz a ansiedade, Bem-estar | Ter um plano alivia a sobrecarga, e o uso de técnicas com pausas favorece uma rotina equilibrada |
| Mudança de vida | Motivação, Autorrealização | A IA adapta a abordagem com base no reforço e o objetivo final é o desenvolvimento profissional do usuário |
| Impacto social | Nenhum | A proposta não descreve impacto direto para além do usuário individual |

### Pirâmide B2B (cliente hipotético é uma instituição de ensino)

| Nível | Elementos escolhidos | Justificativa resumida |
|---|---|---|
| Requisitos básicos | Atende às especificações, Preço aceitável, Conformidade regulatória, Padrões éticos | Funções entregues conforme a proposta, custo viável, adequação à LGPD e uso transparente dos dados |
| Funcional | Inovação, Escalabilidade | Combina chatbot, priorização e técnicas adaptativas, e atende muitos alunos sem equipe proporcional |
| Facilidade de fazer negócios | Economia de tempo, Redução de esforço, Informação, Organização, Integração, Disponibilidade, Configurabilidade | Automatiza parte do acompanhamento de estudos, funciona a qualquer hora e se ajusta a cada aluno |
| Individual | Redução de ansiedade, Crescimento e desenvolvimento | Segurança para o gestor que contrata e alinhamento ao desenvolvimento dos estudantes |
| Inspiracional | Visão, Responsabilidade social | Apoio ao estudante centrado na pessoa, que pode favorecer desempenho e permanência no curso |

A justificativa completa de cada elemento, inclusive dos que não foram escolhidos, está na [página do projeto](https://fernandobruzzi.github.io/Engenharia-de-Software/).

## Como publicar a página

1. Envie os arquivos para o repositório mantendo a pasta `docs/`.
2. No GitHub, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/docs`, e clique em **Save**.
4. Após alguns minutos, a página estará disponível em `https://fernandobruzzi.github.io/Engenharia-de-Software/`.

## Referências

- ALMQUIST, E.; SENIOR, J.; BLOCH, N. The Elements of Value. *Harvard Business Review*, set. 2016.
- ALMQUIST, E.; CLEGHORN, J.; SHERER, L. The B2B Elements of Value. *Harvard Business Review*, mar./abr. 2018.
