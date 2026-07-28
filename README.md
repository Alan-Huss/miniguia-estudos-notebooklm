# Miniguia de Estudos: Projeto Educação Musical Sem Fronteiras

## 📌 Contexto e Objetivos

O presente Caderno Temático tem como foco a análise do Projeto de Extensão **Educação Musical Sem Fronteiras**, desenvolvido no âmbito do curso de Licenciatura em Música na modalidade a distância (EaD) da Universidade do Estado do Rio Grande do Norte (UERN), em parceria com a Universidade Aberta do Brasil (UAB).

A justificativa pedagógica do estudo apoia-se na necessidade de compreender como a integração entre ensino, pesquisa e extensão pode ser viabilizada em cursos de licenciatura a distância, garantindo a formação cidadã e profissional do futuro educador musical. A iniciativa fundamenta-se no princípio freireano da educação como prática da liberdade e na "ecologia de saberes", promovendo a democratização do acesso ao conhecimento musical por meio do uso de Tecnologias da Informação e Comunicação (TICs).

No contexto do Desafio de Projeto da plataforma DIO (Digital Innovation One), os objetivos deste estudo são:

- Mapear o processo de implementação da Curricularização da Extensão em um curso superior EaD;
- Documentar a curadoria de documentos institucionais, normativos federais e publicações acadêmicas;
- Demonstrar a aplicação de Engenharia de Prompts e estratégias de troubleshooting no assistente virtual NotebookLM para extração precisa de dados e síntese do conhecimento.

## 📚 Curadoria de Fontes

A construção do conhecimento deste repositório baseou-se em uma curadoria rigorosa de fontes primárias e secundárias, abrangendo quatro categorias documentais principais:

### 1. Artigos e Comunicações Científicas (ABEM)

- **Documento:** "Educação Musical Sem Fronteiras: proposta de curricularização da extensão na licenciatura em Música a distância" (Araújo & Mariano, 2025; 27º Congresso Nacional da ABEM).
- **Papel:** apresenta os dados empíricos de execução do projeto no primeiro semestre de 2025, o embasamento teórico-metodológico e os impactos quantitativos e qualitativos na formação docente e na comunidade.

### 2. Projeto Pedagógico do Curso (PPC - UERN)

- **Documento:** Projeto Pedagógico do Curso de Licenciatura em Música na Modalidade EaD (UERN/DART/UAB).
- **Papel:** define a matriz curricular do curso (3.305 horas), os objetivos da formação docente, a estrutura de apoio dos Polos UAB e a regulamentação interna das Unidades Curriculares de Extensão (UCEs).

### 3. Resoluções e Regulamentos Institucionais

- **Documentos:** Regulamento Geral da Extensão Universitária da UERN (Resolução nº 14/2017-CONSEPE/PROEX) e Resolução nº 25/2017-CONSEPE.
- **Papel:** estabelecem diretrizes operacionais para institucionalização de programas, projetos, cursos e oficinas de extensão, além de definir os critérios de avaliação e registro de UCEs na UERN.

### 4. Editais e Informativos Governamentais/Institucionais

- **Documentos:** Lei nº 13.005/2014 (Plano Nacional de Educação - PNE), Resolução CNE/CES nº 7/2018 e Editais da PROEX/UERN.
- **Papel:** fornecem o respaldo jurídico federal (exigência de 10% da carga horária para extensão) e a comprovação da aprovação e continuidade do projeto nos editais de extensão.

## 🛠️ Engenharia de Prompts e Troubleshooting

Durante a estruturação do Caderno Temático no NotebookLM, foram aplicadas técnicas iterativas de engenharia de prompts para superar limitações de ambiguidade e garantir respostas estritamente pautadas nas fontes.

### Evolução dos Prompts

- **Prompt Inicial (Genérico - Versão 1):**
  > "Resuma o projeto Educação Musical Sem Fronteiras com base nos PDFs."
  - **Limitação:** A resposta retornava dados abrangentes, genéricos e por vezes misturava iniciativas de ONGs ou orquestras do RJ e Roraima com nomes similares.

- **Prompt Refinado Final (Versão 2 - Aplicado com sucesso):**
  > "Atue como um pesquisador em educação musical. Com base exclusivamente nos documentos da UERN/ABEM anexados, elabore uma síntese do 'Projeto Educação Musical Sem Fronteiras' considerando: 1. Origem e alinhamento com a Resolução CNE/CES nº 7/2018 (Curricularização); 2. Modalidades operacionais (Cursos, Oficinas e Recitais); 3. Dados quantitativos de impacto do semestre 2025.1. Não utilize fontes externas nem generalize informações."
  - **Resultado:** A IA isolou perfeitamente o escopo do DART/UERN, eliminou alucinações e trouxe os dados exatos (26 ações, 375 concluintes).

### Troubleshooting (Desafios e Soluções)

| Desafio | Solução aplicada via prompt |
| --- | --- |
| Ambiguidade de nomenclatura: existência de outros projetos com o termo "Música Sem Fronteiras" em fontes externas (ex: orquestra indígena em Roraima ou projetos no RJ). | Restringir o contexto explicitamente via instrução de sistema: "Considere exclusivamente a iniciativa vinculada ao DART/UERN e ao componente UCE do curso de Licenciatura em Música EaD." |
| Diferenciação de formatos: dificuldade do modelo em diferenciar a dinâmica operacional entre "Cursos Presenciais" e "Oficinas Presenciais". | Solicitar uma matriz comparativa em tabela especificando duração, continuidade e exigências de carga horária para UCE. |
| Alucinação de dados quantitativos: risco de generalização de números de participantes ou ações. | Exigir a citação direta dos dados extraídos do artigo da ABEM referente ao semestre 2025.1 (ex: 26 ações, 375 concluintes, 87 discentes). |

## 📖 Miniguia de Estudo (Entrega Final)

### (a) Origem e Contexto Institucional

O projeto constitui-se como um conjunto de ações extensionistas vinculadas às Unidades Curriculares de Extensão (UCEs) do curso de Licenciatura em Música (modalidade EaD) da Universidade do Estado do Rio Grande do Norte (UERN), em parceria com a Universidade Aberta do Brasil (UAB). Foi idealizado em 2024 por docentes do Departamento de Artes (DART) do Campus Central em Mossoró/RN, tendo sua origem na expansão do projeto "Educação Musical Online", iniciado em 2021 durante a pandemia.

A iniciativa cumpre a Meta 12.7 do Plano Nacional de Educação (PNE 2014-2024 / Lei nº 13.005/2014) e a Resolução CNE/CES nº 7/2018, que determinam a obrigatoriedade de destinar no mínimo 10% da carga horária total da graduação a atividades de extensão. No PPC do curso, isso se traduz em 345 horas de formação extensionista.

### (b) Metodologia e Ações Práticas

A metodologia orienta-se pela democratização do ensino de música através das TICs e pelo protagonismo dos discentes, que atuam em equipes na concepção, mediação e execução das propostas. As atividades organizam-se em quatro modalidades operacionais:

- **Cursos Online:** formações integrais (média de 40 horas) mediadas por Moodle, Google Sala de Aula e WhatsApp, combinando atividades síncronas e assíncronas.
  - Conteúdos: iniciação ao violão, flauta doce, técnica vocal, musicalização e teoria musical.
- **Cursos Presenciais:** formações contínuas de múltiplos encontros, realizadas em escolas, igrejas e centros comunitários nos municípios polo.
  - Conteúdos: prática de conjunto, harmonia e instrumentos de sopro/cordas.
- **Oficinas Presenciais:** intervenções práticas de curta duração (2 a 4 horas), pontuais e replicáveis.
  - Conteúdos: confecção de flautas em PVC (MUSICANO), ritmo do xote na sanfona e canto popular.
- **Recitais Didáticos:** ações híbridas que integram performance artística e exposição didática acessível sobre estilos, instrumentos, gêneros e contextos históricos.

### (c) Impacto Social e Formação Docente

No primeiro semestre de 2025, o projeto registrou a execução de 26 ações pedagógicas, beneficiando diretamente 375 participantes concluintes na comunidade externa e mobilizando um total de 470 pessoas (além do público de espectadores dos recitais).

Para os 87 graduandos envolvidos, a experiência promoveu o desenvolvimento de competências essenciais, como planejamento pedagógico, autonomia digital e mediação cultural. Além disso, o projeto atuou como espaço de recomposição de aprendizagens, permitindo que os próprios licenciandos suprissem lacunas de sua formação musical inicial ao participar das formações ofertadas.

## Glossário de Conceitos-Chave

- **Curricularização da Extensão:** diretriz educacional que insere as atividades extensionistas na matriz curricular dos cursos de graduação, correspondendo a pelo menos 10% da carga horária total do curso.
- **Unidade Curricular de Extensão (UCE):** componente curricular obrigatório previsto no PPC através do qual se viabilizam as ações de extensão vinculadas a projetos institucionalizados na PROEX/UERN.
- **Recital Didático:** modalidade de ação de extensão que alia apresentação artística a explicações didáticas sobre a estrutura, história e características das obras e instrumentos apresentados.
- **Protagonismo Discente:** princípio pedagógico em que os estudantes da graduação deixam o papel de receptores e assumem a proposição, o planejamento e a regência das ações educacionais junto à comunidade.
- **Ecologia de Saberes:** conceito epistemológico (Boaventura de Sousa Santos) aplicado ao projeto para promover o diálogo e o reconhecimento mútuo entre o conhecimento científico-acadêmico e os saberes culturais populares.
- **Polos UAB (Universidade Aberta do Brasil):** unidades físicas descentralizadas localizadas em diversos municípios que fornecem a infraestrutura acadêmica e operacional para os alunos de EaD e realização de ações presenciais.
- **Interação Dialógica:** princípio da extensão universitária focado no intercâmbio bidirecional e na construção coletiva do conhecimento entre a universidade e os atores sociais comunitários.
- **Oficina Presencial:** ação pedagógica intensiva e de curta duração (2h a 4h), voltada ao ensino prático de um tópico específico e com alto potencial de replicação em diferentes contextos.

## 1. Documentos Institucionais e Publicações do Projeto

- Araújo, P. & Mariano, S. (2025). "Educação Musical Sem Fronteiras: proposta de curricularização da extensão na licenciatura em Música a distância". 27º Congresso Nacional da ABEM.
- Projeto Pedagógico do Curso de Licenciatura em Música na Modalidade EaD. UERN/DART/UAB.
- Regulamento Geral da Extensão Universitária da UERN (Resolução nº 14/2017-CONSEPE/PROEX).
- Resolução nº 25/2017-CONSEPE da UERN.
- Editais da PROEX/UERN relacionados ao projeto Educação Musical Sem Fronteiras.

## 2. Referências Bibliográficas e Legislação Citadas nos Documentos

- Brasil. Lei nº 13.005, de 25 de junho de 2014. Plano Nacional de Educação (PNE) 2014-2024.
- Conselho Nacional de Educação. Resolução CNE/CES nº 7, de 14 de dezembro de 2018.
- Freire, P. (1996). Pedagogia da autonomia: saberes necessários à prática educativa. São Paulo: Paz e Terra.
- Santos, B. S. (2008). A gramática do tempo: para uma nova cultura política. São Paulo: Cortez.
- UERN. Projeto Pedagógico do Curso de Licenciatura em Música EaD.

## 🔄 Prompts Reutilizáveis

Os prompts a seguir foram formulados para que outros estudantes ou pesquisadores possam consultar e aprofundar tópicos específicos sobre este projeto no NotebookLM:

- **Análise de Fundamentação Legal:** 
  > *"Com base no PPC e nas Resoluções do CONSEPE anexadas, explique como a carga horária de 345h de extensão do curso de Licenciatura em Música EaD da UERN atende às exigências da Lei nº 13.005/2014 (PNE)."*

- **Detalhamento das Ações Práticas e Conteúdos:** 
  > *"Crie uma tabela comparativa detalhando as 4 modalidades operacionais do projeto (Cursos Online, Cursos Presenciais, Oficinas e Recitais Didáticos), indicando público-alvo, duração média e conteúdos ensinados."*

- **Avaliação do Impacto na Formação de Professores:** 
  > *"Quais foram os principais benefícios pedagógicos e desafios relatados pelos 87 graduandos em Música que atuaram como extensionistas no projeto durante o semestre 2025.1?"*

- **Guia para Replicação em Outros Polos:** 
  > *"Extraia das fontes um passo a passo estruturado para discentes que desejam propor uma nova Oficina Presencial de Música em seu Polo UAB no âmbito do projeto."*
