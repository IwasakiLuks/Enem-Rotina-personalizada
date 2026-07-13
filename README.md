# ENEM Study Planner

Sistema de planejamento de estudos focado no ENEM, desenvolvido inteiramente com HTML, CSS e JavaScript puro. Sem frameworks, sem backend, sem dependências externas.

## 🚀 Funcionalidades

- **Dashboard principal**: contagem regressiva para o ENEM, meta de pontuação, média atual, fase da jornada (Base → Consolidação → Aprofundamento → Guerra) e progresso do checklist.
- **Cronograma semanal intercalado**: semanas A (imersão) e B (intercalação), com blocos de teoria, questões, aprofundamento, revisão, erros e simulado.
- **Checklist completo da matriz ENEM**: todas as áreas (Matemática, Biologia, Física, Química, Linguagens, Humanas) com seus respectivos tópicos.
- **Timer Pomodoro**: ciclo 45/10 minutos com contagem de ciclos completos.
- **Corretor de redação**: interface para inserir tema e texto, autoavaliação nas 5 competências (C1 a C5), histórico de notas e campo para chave de API (pronto para integração futura).
- **Plano de redação**: lista de 100 temas e competências com meta semanal.
- **Design responsivo e foco em usabilidade**: pensado para uma experiência limpa e objetiva.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3 (puro, sem pré-processadores)
- JavaScript (vanilla, sem bibliotecas)

A escolha por tecnologia pura foi intencional: validar o conceito rapidamente, manter portabilidade e testar habilidades de manipulação de DOM, gerenciamento de estado e lógica de dados sem camadas de abstração.

## 📁 Estrutura do projeto

O projeto é composto por um único arquivo HTML (ou estrutura estática) com CSS e JS embutidos ou em arquivos separados — fica a seu critério. Por enquanto, tudo roda localmente, sem necessidade de servidor.

## 🧩 Organização do código

Para facilitar a leitura e manutenção, o código está separado visualmente por blocos lógicos usando comentários HTML, como:

```html
<!-- SIDE BAR -->
<!-- DASHBOARD -->
<!-- CRONOGRAMA -->
<!-- CHECKLIST -->
<!-- TIMER POMODORO -->
<!-- CORRETOR DE REDAÇÃO -->
<!-- PLANO DE REDAÇÃO -->
