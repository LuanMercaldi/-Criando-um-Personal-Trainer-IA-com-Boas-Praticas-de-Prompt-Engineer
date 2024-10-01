<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://www.dio.me/users/luanwp" title="Curriculum"><img src="https://img.shields.io/badge/DIO-Curriculum-FED564"></a>
<a href="https://www.linkedin.com/in/luan-mercaldi-88080890/" title="Profile"><img src="https://img.shields.io/badge/LinkedIn-Profile-FED564?"></a>
<a href="https://chatgpt.com/" title="Powered by ChatGpt">
  <img src="https://img.shields.io/badge/Powered%20by-ChatGPT-FED564?">
</a>
</p>

<p align="center">
  <h3 align="center">🤖 Personal Trainer Virtual</h3>
    
Bem-vindo ao **Personal Trainer Virtual!** Esse bot foi desenvolvido como parte de um **desafio de Prompt Engineer** e vai ajudar você a criar treinos personalizados com base nas suas respostas a algumas perguntas rápidas e simples. Vamos nessa? 💪
</p>

---

## 📋 Índice

- [📋 Índice](#-índice)
- [🚀 O que o Bot Faz?](#-O-que-o-Bot-Faz)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 🚀 O que o Bot Faz?

O **Personal Trainer Virtual** gera um plano de treino totalmente customizado para você, considerando seu biotipo, preferências de exercício e quantos dias por semana você pode treinar. Tudo isso em poucos passos! 🏋️‍♂️

Este projeto tem como objetivo criar um **prompt que auxilia a montar o treino ideal** para cada combinação de fatores, como:

- **Biotipo Corporal**: Ectomorfo, Mesomorfo, Endomorfo, ou indefinido.
- **Disponibilidade de Tempo**: Quantos dias por semana você pode treinar.
- **Tipo de Exercícios Preferidos**: Funcional, Maquinário, Peso Livre, Cardio, HIIT.

O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário, utilizando as **melhores práticas de Prompt Engineering**.


Combinando tecnologia e conhecimento em fitness, esse bot vai facilitar a criação do **treino ideal** para cada usuário, ajudando-o a atingir seus objetivos de forma eficaz e personalizada.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/Interrogacao.png" width="50%" height="50%">
    </td>
    <td><strong>Não sei, me ajude!</strong></td>
    <td>Não tem problema, dá uma olhada neste vídeo [aqui](www.youtube.com/watch?v=UTHHEOqJIaU) que vai te ajudar a entender melhor. 🎥
</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 🏋️ Tipos de Exercícios

A Segunda regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Treinos com movimentos naturais, que trabalham o corpo todo de forma equilibrada.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Você curte aparelhos de academia? Então essa é a opção ideal.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Se você prefere treinar com halteres e barras, essa é a escolha. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Gosta de correr, pedalar ou fazer exercícios de resistência? Cardio é para você!                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Quer treinos curtos e intensos para queimar gordura? O HIIT vai te desafiar! 🔥                                      |

---

## 📅 Dias Disponíveis para Treino

A Terceira regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: O bot vai sugerir um treino Full Body, ou seja, para o corpo inteiro em uma única sessão.
- **ABC**: Você vai receber um treino ABC, que divide os grupos musculares em três dias.
- **ABCDE**: Aqui o treino é mais avançado, com um plano ABCDE, onde cada dia tem um foco específico.

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
