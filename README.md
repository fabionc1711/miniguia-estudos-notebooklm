## 📋 Contexto e Objetivos

### Contexto
O avanço acelerado da Inteligência Artificial generativa e dos modelos de aprendizado de máquina trouxe inovações disruptivas para o mercado de tecnologia, mas também acendeu o alerta sobre os riscos associados ao seu uso. Questões como viés algorítmico (*algorithmic bias*), falta de explicabilidade (*XAI*) e segurança de dados deixaram de ser discussões teóricas e passaram a ser desafios críticos de engenharia e negócios. 

Globalmente, movimentos como o *EU AI Act* (a Lei de IA da União Europeia) e, no Brasil, o Projeto de Lei nº 2338/2023 estão redesenhando as regras do jogo. O mercado de tecnologia agora busca profissionais que não apenas saibam construir modelos, mas que compreendam o ciclo de vida do desenvolvimento sob a ótica da governança, mitigação de riscos e conformidade (*compliance*). 

Este projeto nasce da necessidade de compreender esse cenário regulatório e ético de forma profunda e estruturada, utilizando a Inteligência Artificial do NotebookLM como uma ferramenta de aprendizagem ativa e curadoria de conhecimento.

### Objetivos de Estudo
O desenvolvimento deste Caderno Temático tem como metas principais:
1. **Compreender a Abordagem Baseada em Risco:** Mapear como as legislações nacionais e internacionais classificam os sistemas de IA (especialmente os de Alto Risco) e quais obrigações técnicas são impostas aos desenvolvedores.
2. **Estudar Frameworks Práticos de Mitigação:** Analisar guias consolidados (como o *NIST AI Risk Management Framework*) para identificar boas práticas de auditoria de dados e engenharia ética.
3. **Dominar a Engenharia de Prompts para Análise Técnica:** Desenvolver habilidades avançadas de formulação de prompts e *troubleshooting*, forçando a IA a extrair respostas com alto rigor factual e referenciado diretamente das fontes.
4. **Consolidar um Guia de Consulta Rápida:** Criar um repositório centralizado de conhecimento (resumos, glossário e prompts reutilizáveis) que sirva de apoio para futuras tomadas de decisão arquiteturais e de compliance em projetos de software.

### Fontes
A Lei de IA da União Europeia (EU AI Act - Resumo Oficial):
https://artificialintelligenceact.eu/wp-content/uploads/2024/11/Future-of-Life-InstituteAI-Act-overview-30-May-2024.pdf

Projeto de Lei nº 2338/2023 (Senado Federal do Brasil) :
https://legis.senado.leg.br/sdleg-getter/documento?dm=9347622

Guia de Avaliação de Riscos de IA da ENISA ou NIST:
https://www.nist.gov/itl/ai-risk-management-framework

Relatório Técnico sobre Ética e IA (Ex: UNESCO ou Fórum Econômico Mundial):
https://unesdoc.unesco.org/ark:/48223/pf0000381137

### Engenharia de Prompts e "Cicatrizes"

Prompt Inicial (Testado)
1) O que o projeto de lei do Brasil fala sobre os riscos da inteligência artificial?
2) Como evitar viés de IA segundo as fontes?

Resposta: 1) Um texto longo explicando que a lei divide os riscos, mas sem especificar as regras de desenvolvimento. 2) Uma resposta filosófica sobre igualdade e diversidade de dados.

Problema Encontrado (Cicatriz): 1) Ficou muito genérico. Não serve como guia prático para um time de engenharia de software. 2) Faltou a parte prática de engenharia de dados e processos de auditoria.

Prompt Refinado (Estratégico): 1) Com base estritamente no PL 2338/2023 (Fonte 2), liste quais são as obrigações técnicas e de transparência impostas aos desenvolvedores de sistemas classificados como de Alto Risco.
2) Análise comparativa: Como o framework do NIST (Fonte 3) e as diretrizes da União Europeia (Fonte 1) recomendam mitigar o viés algorítmico (bias) no ciclo de vida do software? Responda em uma tabela comparando os dois métodos.

Resultado Final: 1) O NotebookLM isolou os artigos exatos da lei, gerando um checklist objetivo de conformidade (governança). 2) Uma tabela clara dividida em: fase de design, coleta de dados e auditoria contínua pós-implementação.


### Miniguia de Estudo (Sua Entrega Final)
Esta seção deve ser o resultado consolidado que você gerou através das suas conversas com o NotebookLM. Use a estrutura abaixo para preencher o seu README.md:

## 1. Resumo Estruturado do Assunto
A regulamentação de IA não visa proibir a tecnologia, mas sim gerenciar os riscos associados a ela. Tanto a legislação europeia quanto a proposta brasileira adotam uma abordagem baseada em risco, dividindo os sistemas em categorias:

Risco Inaceitável: Práticas proibidas (ex: pontuação social baseada em comportamento, sistemas de identificação biométrica em massa em tempo real sem autorização judicial).

Alto Risco: Exigem auditoria rigorosa, governança de dados e supervisão humana (ex: IA na saúde, triagem de currículos para contratação, análise de crédito bancário).

Risco Baixo ou Mínimo: Exigem apenas transparência básica (ex: informar ao usuário que ele está conversando com um chatbot ou que uma imagem foi gerada por IA).

## 2. Glossário de Conceitos Aprendidos
Algorithmic Bias (Viés Algorítmico): Distorções sistemáticas e injustas nos resultados de uma IA, geralmente causadas por dados de treinamento históricos que refletem preconceitos humanos.

Explainability (Explicabilidade / XAI): A capacidade de um sistema de IA de explicar suas decisões em termos compreensíveis para os seres humanos. Crucial para auditorias de conformidade.

Compliance de IA: O processo de garantir que um software que utiliza aprendizado de máquina esteja em total conformidade com as leis de privacidade (como LGPD) e as regulamentações éticas.

Sandboxes Regulatórios: Ambientes controlados e testados onde empresas podem experimentar inovações de IA sob a supervisão de órgãos reguladores, mitigando riscos jurídicos antes do lançamento oficial.

### 3. Prompts Reutilizáveis para Revisão Futura

- "Atue como um analista de compliance. Revise o seguinte caso de uso [inserir ideia do seu sistema de IA] à luz das restrições de Alto Risco mapeadas no caderno."
- "Crie um roteiro de perguntas para uma entrevista de auditoria ética com a equipe de cientistas de dados antes de colocarmos um modelo de crédito em produção."
- "Quais são as principais penalidades previstas no PL 2338/2023 caso uma empresa descumpra as regras de governança de dados?"
