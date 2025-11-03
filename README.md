# 🔢 **VoidMathMentor**: Professor de Matemática Guiado pela API do Gemini 📐

👋 Olá, Engenheiro(a)! Este repositório é um **Showcase de Engenharia de IA** que demonstra como a **API do Google Gemini** pode ser rigorosamente controlada para atuar como um tutor de matemática de alta precisão.

O **VoidMathMentor** prova que modelos de linguagem podem ser forçados a seguir uma **metodologia de ensino estruturada**, combatendo o problema de respostas diretas e apressadas.

## ✨ **O Cérebro do Professor (Arquitetura e Instruções)**

A eficácia do **VoidMathMentor** está na sua `System Instruction`, que impõe a personalidade do tutor e uma metodologia de ensino clara.

| Componente -> Função -> Base de Conhecimento Injetada |

| **Persona** --> Tutor paciente, focado em compreensão conceitual. | `001 - Instruções_do_Gem.txt` |
| **Metodologia (Ordem Estrita)** --> LLM deve sempre seguir 5 passos: Contextualizar → Definir Conceitos → **Demonstrar Passo a Passo** → Interagir → Praticar |`001 -Instruções_do_Gem.txt`|
| **Resolução de Problemas** --> Utiliza os "5 Passos Fundamentais" (Compreensão, Definição de Variáveis, Tradução, Resolução, Verificação) | `02_Metodologia_Resolucao_Problemas.txt` |
| **Conhecimento** --> Fórmulas, definições e exemplos de Álgebra, Geometria e Cálculo Avançado. | `01_Formulas_...`, `03_Algebra_...`, etc. |

## ⚙️ **Destaques de Engenharia (*Prompting*)**

A precisão do **VoidMathMentor** é garantida por *prompts* que exigem:

1. **Rigor no Raciocínio:** Para problemas de palavra, o Gem deve mostrar como **traduzir o português para a matemática** antes de resolver, e **NUNCA pular etapas**.
2. **Referência Explícita:** O Gem deve sempre referenciar fórmulas pelo nome correto (ex: "Teorema de Pitágoras") e explicar o significado de cada variável.
3. **Estrutura Rígida de Resposta:** O formato da resposta é fixo (`📚 Conceito`, `🎯 Objetivo`, `🔍 Passo a Passo`, `✅ Verificação`), garantindo a entrega do valor educacional.

## 📚 **Conteúdo e Demonstração**

O projeto demonstra o ensino em vários níveis, usando os materiais injetados:

* **Álgebra:** Resolução de Equações de 1º e 2º Grau e Sistemas por Adição.
* **Geometria:** Classificação de Triângulos e aplicação do Teorema de Pitágoras.
* **Avançado:** Explicações sobre a Fórmula Integral de Cauchy e o Teorema do Resíduo no Cálculo Complexo.

## 🛠️ **Implementação e Teste**

Siga as instruções para configurar sua Gem no Google AI Studio e injetar a base de conhecimento.

1.  **Acesse** o Google AI Studio e crie sua Gem.
2.  **Copie e cole** o conteúdo de `001 - Instruções_do_Gem.txt` nas Instruções.
3.  **Faça upload** de todos os outros arquivos de texto na seção de Conhecimento.

## 🤝 **Colabore!**

Sua expertise em IA e matemática é bem-vinda para otimizar o *prompt* e o conteúdo.
