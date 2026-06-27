# Skill: PDF de Estudos Genérica

# Regras para usar o GitHub como link da skill

## Mapa de leitura obrigatório para IA

Ao usar esta skill a partir de um link do GitHub, a IA não deve considerar que leu a skill apenas por abrir o `README.md`.

Antes de aplicar a skill, a IA deve ler os arquivos nesta ordem:

1. `README.md`, para entender a finalidade geral da skill.
2. `SKILL.md`, que é o arquivo principal e coordena o comportamento da IA.
3. Todos os arquivos numerados de `00_...md` até `11_...md`, pois eles detalham papel da IA, fluxo de trabalho, perguntas obrigatórias, estrutura do PDF, estilo de escrita, exemplos, volumes, formatação, relação com projeto do usuário, revisão e atualização.
4. Os arquivos da pasta `modelos/`, quando o assunto solicitado pertencer a uma categoria específica, como biblioteca Python, framework web, IA/dados, DevOps, matemática, protocolo, linguagem de programação ou tecnologia.
5. Os arquivos da pasta `templates/`, quando for necessário seguir um formato de saída mais padronizado.
6. Os arquivos da pasta `exemplos/`, quando houver um exemplo parecido com o pedido do usuário.

Se a IA não conseguir acessar algum arquivo, ela deve informar claramente quais arquivos foram lidos e quais não foram lidos, em vez de afirmar que leu toda a skill.

Depois da leitura, a IA deve resumir internamente a regra principal da skill: primeiro planejar o material, perguntar o que for necessário, propor escopo e volumes, aguardar aprovação quando o tema for amplo e só então gerar o conteúdo final.


## Finalidade

Esta skill orienta a IA a criar PDFs e coleções de estudo sobre qualquer assunto, com escrita pedagógica, estrutura clara, progressão didática, revisão editorial e formatação confortável para leitura.

A skill é genérica. Ela não deve mencionar projetos, empresas, produtos ou contextos pessoais específicos, a menos que o usuário informe que deseja relacionar o assunto a um projeto próprio.

## Mapa de leitura recomendado

1. 00_papel_da_ia.md
2. 01_fluxo_de_trabalho.md
3. 02_perguntas_obrigatorias.md
4. 03_taxonomia_de_assuntos.md
5. 04_estrutura_do_pdf.md
6. 05_estilo_de_escrita.md
7. 06_exemplos_e_codigo.md
8. 07_volumes_e_tamanho.md
9. 08_formatacao_livro.md
10. 09_relacao_com_projeto_do_usuario.md
11. 10_regras_de_limpeza_e_revisao.md
12. 11_fontes_pesquisa_e_atualizacao.md
13. modelos/[modelo correspondente ao tema]
14. templates/[template necessário]
15. exemplos/[exemplo compatível]

Quando o tema pertencer a uma categoria específica, usar também o modelo correspondente da pasta `modelos`.

Quando houver um exemplo compatível na pasta `exemplos`, usar o exemplo como referência de comportamento, especialmente para diferenciar pedidos introdutórios, avançados e de formação completa de especialista.

## Regra principal

Nunca gerar o PDF final imediatamente quando o tema ainda estiver amplo, incompleto ou sem escopo aprovado.

A IA deve primeiro criar um plano do material, perguntar ao usuário sobre subassuntos, nível, profundidade, volumes, formatação e relação com projeto próprio. Depois deve aguardar a aprovação do plano.

## Fases obrigatórias

### Fase 1 — Entendimento

Identificar o assunto central, o tipo de conteúdo, o público provável, o nível pretendido e o objetivo do estudo.

### Fase 2 — Planejamento

Propor:

1. objetivo do material;
2. subassuntos principais;
3. quantidade sugerida de volumes;
4. estimativa de páginas por volume;
5. sumário preliminar;
6. estilo de escrita;
7. opções de formatação;
8. necessidade de exemplos, código, exercícios ou projeto prático;
9. pergunta sobre relação com algum projeto do usuário.

### Fase 3 — Confirmação

Perguntar se o usuário deseja:

- incluir subassuntos;
- remover subassuntos;
- alterar a ordem;
- aumentar ou reduzir profundidade;
- escolher outro padrão de formatação;
- relacionar o assunto com algum projeto pessoal, profissional, acadêmico ou técnico.

### Fase 4 — Geração

Somente após aprovação, criar o PDF ou o conteúdo do volume solicitado.

### Fase 5 — Revisão

Antes de finalizar, revisar:

- repetição;
- clareza;
- progressão;
- coesão;
- utilidade prática;
- fidelidade ao sumário aprovado;
- qualidade da formatação;
- ausência de comentários internos ou metatexto.

## Saída da primeira resposta

Na primeira resposta, a IA deve apresentar um planejamento, não o PDF final.

A resposta deve conter:

1. interpretação do tema;
2. objetivo sugerido;
3. subassuntos sugeridos;
4. quantidade sugerida de volumes;
5. estimativa aproximada de páginas por volume;
6. sumário preliminar;
7. perguntas de confirmação;
8. pergunta sobre relação com algum projeto do usuário;
9. opções de formatação.

## Saída final

O PDF final deve conter somente conteúdo de estudo sobre o assunto.

Não incluir:

- comentários sobre a skill;
- comentários sobre a conversa;
- justificativas internas;
- explicações sobre fonte, margem ou diagramação;
- frases como "conforme solicitado";
- avisos sobre o processo de criação.

## Ativação sugerida

Use esta skill quando o usuário pedir:

- PDF de estudos;
- apostila;
- livro de estudo;
- coleção em volumes;
- material didático;
- guia completo;
- explicação com exemplos;
- conteúdo para aprender um assunto;
- estudo do zero ao avançado.
