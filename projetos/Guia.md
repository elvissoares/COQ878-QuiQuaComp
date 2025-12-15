# Guia para o Trabalho da disciplina COQ878

**AIMD com MACE e Validação Ab Initio com VASP**

### 1. Relatório escrito

O relatório deve ter caráter científico, com estrutura próxima à de um artigo (de 3 a 5 páginas), enfatizando **formulação de perguntas**, **rigor metodológico** e **validação cruzada**.

#### 1.1 Introdução

- Descrição clara do sistema físico-químico estudado (composição, fase, condições termodinâmicas).
- Motivação científica: relevância do sistema e do fenômeno investigado.
- Perguntas científicas principais do trabalho e possíveis desdobramentos futuros.
- Revisão sucinta da literatura: artigos-chave que fundamentam as perguntas e a metodologia adotada.

#### 1.2 Metodologia

- Justificativa do uso de AIMD e do papel do MACE no contexto do problema.
- Descrição do fluxo de trabalho: geração de dados _ab initio_, treinamento/uso do MACE e validação.
- Estratégia de validação do MACE frente ao VASP (energias, forças, estruturas, propriedades estatísticas).
- Detalhamento dos parâmetros:
    - **VASP**: funcional, pseudopotenciais, cutoff, k-points (se aplicável), critérios de convergência.
    - **AIMD**: ensemble, termostato/barostato, passo de tempo, tempo total de simulação.
    - **MACE**: foundation model utilizado, fine-tuning (se houver), parâmetros relevantes.
- Geometria e topologia do sistema inicial, incluindo referências utilizadas para sua construção.

#### 1.3 Resultados e Discussão

- Análise de estabilidade e qualidade das simulações:
    - Evolução temporal da energia potencial, temperatura e demais grandezas relevantes.
- Resultados da validação do MACE:
    - Comparações quantitativas com VASP (ex.: erros de energia e força, correlações).
- Visualização das trajetórias:
    - Imagens representativas, quando pertinentes.
- Discussão física e química:
    - Interações intermoleculares, rearranjos estruturais, ligações químicas e possíveis reações.
    - Limitações observadas do modelo e da abordagem.

#### 1.4 Conclusões e Perspectivas

- Síntese crítica dos resultados obtidos.
- Comparação com trabalhos existentes: o que foi reproduzido, melhorado ou permanece em aberto.
- Próximos passos científicos e metodológicos.

---

### 2. Apresentação oral

- **20 minutos**: exposição concisa do problema, metodologia, principais resultados, vídeos representativos, e conclusões.
- **5-10 minutos**: arguição, com foco em decisões metodológicas, validação e interpretação física.
