<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

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
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

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

Claro, vou te ajudar a montar um plano de treino e dieta ideal para o mês, com base nas variáveis que você forneceu. Vamos começar por definir a rotina de treinos e a alimentação apropriada para cada biotipo e tipo de treino. Vou detalhar isso conforme as regras estabelecidas.

1. Identificação do Biotipo e Tipo de Treino
Vamos usar as variáveis fornecidas para identificar o biotipo, os dias disponíveis para o treino e o tipo de treino.

Biotipo:
Ectomorfo: Corpo mais magro, dificuldade para ganhar peso e massa muscular.
Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
Endomorfo: Corpo com tendência a acumular gordura, dificuldade em perder peso.

Dias Disponíveis para o Treino:
1 dia: Treino Corpo Inteiro
3 dias: Treino ABC
5 dias: Treino ABCDE

Tipos de Treino:

Funcional: Melhora a funcionalidade do corpo, usando movimentos naturais.
Maquinário: Foco em isolar grupos musculares.
Peso Livre: Trabalha vários grupos musculares simultaneamente.
Cardio: Melhora a resistência cardiovascular.
HIIT: Treinos intervalados de alta intensidade para queima de gordura.

Tipos de Alimentos:

Ectomorfo: Alta quantidade de carboidratos.
Mesomorfo: Alta quantidade de proteínas.
Endomorfo: Equilíbrio entre carboidratos e proteínas, focando em menor quantidade de carboidratos.

2. Estrutura do Treino para 20 Dias
Treinos para um Mês de 20 Dias:

Treino Corpo Inteiro (1 dia)

Segunda-feira: Treino Corpo Inteiro
Treino ABC (3 dias)
Terça-feira: Treino A (Peito, Ombros e Tríceps)
Quinta-feira: Treino B (Costas e Bíceps)
Sábado: Treino C (Pernas e Abdômen)
Treino ABCDE (5 dias)

Segunda-feira: Treino A (Peito)
Terça-feira: Treino B (Costas)
Quarta-feira: Treino C (Pernas)
Quinta-feira: Treino D (Ombros)
Sexta-feira: Treino E (Braços e Abdômen)

Distribuição dos Dias:
Treino Corpo Inteiro: 1 dia
Treino ABC: 3 dias
Treino ABCDE: 5 dias

Dias Restantes: 11 dias podem ser usados para descanso ou treinos adicionais, dependendo da necessidade individual.

3. Plano de Treino Ideal por Biotipo e Tipo de Treino
Vamos definir um plano de treino ideal com base no biotipo e tipo de treino especificado:

1. Ectomorfo:
Objetivo: Ganho de massa muscular

Treino Ideal: Peso Livre e Maquinário

Segunda-feira: Corpo Inteiro (Peso Livre)
Terça-feira: ABC (Peso Livre)
Quinta-feira: ABC (Maquinário)
Sábado: ABCDE (Peso Livre)

Dieta:

Carboidratos: Alta quantidade, cerca de 60-70% das calorias diárias
Proteínas: Moderada, cerca de 15-20% das calorias diárias

2. Mesomorfo:
Objetivo: Manutenção e definição muscular

Treino Ideal: Peso Livre e HIIT

Segunda-feira: Corpo Inteiro (Peso Livre + HIIT)
Terça-feira: ABC (Peso Livre)
Quinta-feira: ABC (HIIT)
Sábado: ABCDE (Peso Livre)

Dieta:

Proteínas: Alta quantidade, cerca de 25-30% das calorias diárias
Carboidratos: Moderada, cerca de 40-50% das calorias diárias

3. Endomorfo:
Objetivo: Redução de gordura e ganho muscular

Treino Ideal: HIIT e Funcional

Segunda-feira: Corpo Inteiro (HIIT)
Terça-feira: ABC (Funcional)
Quinta-feira: ABC (HIIT)
Sábado: ABCDE (Funcional)

Dieta:

Carboidratos: Menor quantidade, cerca de 30-40% das calorias diárias
Proteínas: Alta quantidade, cerca de 30-35% das calorias diárias

4. Exemplo de Plano de Treino para um Ectomorfo:
Segunda-feira: Treino Corpo Inteiro

Aquecimento: 10 min de Cardio leve
Agachamento com Barra: 4x8
Supino Reto com Barra: 4x8
Remada com Halteres: 4x8
Desenvolvimento com Halteres: 4x8
Rosca Direta: 3x10
Abdominais: 3x15
Terça-feira: Treino ABC (Peso Livre)

Peito: Supino Reto, Supino Inclinado
Ombros: Desenvolvimento com Barra, Elevações Laterais
Tríceps: Mergulho, Extensão de Tríceps
Quinta-feira: Treino ABC (Maquinário)

Costas: Pulley, Remada Baixa
Bíceps: Rosca Scott, Rosca Alternada
Abdômen: Crunch, Elevação de Pernas
Sábado: Treino ABCDE (Peso Livre)

Peito: Supino Reto, Supino Inclinado
Costas: Barra Fixa, Remada com Halteres
Pernas: Agachamento, Leg Press
Ombros: Desenvolvimento com Halteres, Face Pull
Braços: Rosca Direta, Tríceps Testa

Com essas diretrizes, você pode ajustar a intensidade e a duração dos treinos conforme a necessidade e a resposta do seu corpo. A alimentação deve acompanhar o plano de treino para maximizar os resultados.





