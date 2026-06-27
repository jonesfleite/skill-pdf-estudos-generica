# Skill PDF de Estudos Genérica

Skill modular para orientar uma IA a planejar e criar materiais de estudo em PDF sobre qualquer assunto.

O objetivo desta skill é transformar um tema amplo em um material didático, organizado, progressivo e confortável para leitura. Ela foi criada para funcionar de forma genérica, sem depender de uma empresa, projeto, área específica ou tecnologia específica.

A skill pode ser usada para conteúdos introdutórios, intermediários, avançados ou completos. Antes de gerar o PDF final, a IA deve levantar o escopo, sugerir subassuntos, organizar os volumes, perguntar sobre formatação e confirmar se o usuário deseja relacionar o conteúdo com algum projeto próprio.

## Finalidade

Esta skill serve para criar materiais de estudo com qualidade de livro, evitando respostas rasas, conteúdos soltos e PDFs pequenos demais para aprendizado real.

Ela orienta a IA a atuar como especialista no assunto solicitado, com capacidade de escrita pedagógica, organização editorial, comunicação clara, revisão textual e planejamento didático.

O foco é criar um conteúdo que ajude o leitor a estudar com profundidade, compreender os conceitos, praticar com exemplos e evoluir até um domínio sólido do assunto.

## Como a skill funciona

A skill trabalha em duas grandes fases.

Na primeira fase, a IA não deve gerar o PDF imediatamente. Ela deve entender o pedido, identificar o tipo de assunto, sugerir os subassuntos importantes, propor a quantidade de volumes, indicar o tamanho aproximado de cada volume e fazer perguntas de confirmação.

Na segunda fase, depois da aprovação do usuário, a IA deve criar o conteúdo final seguindo o plano aprovado. O PDF deve conter apenas o conteúdo de estudo, sem comentários sobre a conversa, sobre a skill ou sobre a formatação utilizada.

## Estrutura dos arquivos

```text
skill-pdf-estudos-generica/
├── SKILL.md
├── 00_papel_da_ia.md
├── 01_fluxo_de_trabalho.md
├── 02_perguntas_obrigatorias.md
├── 03_taxonomia_de_assuntos.md
├── 04_estrutura_do_pdf.md
├── 05_estilo_de_escrita.md
├── 06_exemplos_e_codigo.md
├── 07_volumes_e_tamanho.md
├── 08_formatacao_livro.md
├── 09_relacao_com_projeto_do_usuario.md
├── 10_regras_de_limpeza_e_revisao.md
└── 11_fontes_pesquisa_e_atualizacao.md
```

## Função de cada arquivo

`SKILL.md` é o arquivo principal. Ele coordena o uso da skill e aponta para os demais módulos.

`00_papel_da_ia.md` define o papel da IA como especialista pedagógica no assunto solicitado.

`01_fluxo_de_trabalho.md` define o processo geral de planejamento, confirmação e geração do material.

`02_perguntas_obrigatorias.md` define as perguntas que a IA deve fazer antes de finalizar o PDF.

`03_taxonomia_de_assuntos.md` ajuda a IA a quebrar o tema em subassuntos conforme o tipo de conteúdo.

`04_estrutura_do_pdf.md` define a estrutura padrão do PDF e dos capítulos.

`05_estilo_de_escrita.md` define o padrão de linguagem, clareza, didática e progressão textual.

`06_exemplos_e_codigo.md` define como exemplos, códigos, comandos, funções e explicações práticas devem ser apresentados.

`07_volumes_e_tamanho.md` define a regra de volumes variáveis e o tamanho recomendado de cada volume.

`08_formatacao_livro.md` define as opções de formatação que devem ser perguntadas ao usuário.

`09_relacao_com_projeto_do_usuario.md` define como a IA deve perguntar se o usuário deseja relacionar o assunto com algum projeto próprio.

`10_regras_de_limpeza_e_revisao.md` define as regras de revisão para evitar repetição, conteúdo fraco e comentários fora do assunto.

`11_fontes_pesquisa_e_atualizacao.md` define quando a IA deve buscar informações atualizadas ou consultar fontes confiáveis.

## Uso básico

No uso básico, o usuário informa apenas o tema e pede um PDF de estudo.

A IA deve responder com um planejamento simples, perguntando nível, escopo, tamanho, formatação e subassuntos principais.

Indicado para:

- introdução a um tema;
- visão geral;
- revisão organizada;
- primeiro contato com uma tecnologia;
- material curto ou médio.

Fluxo esperado:

1. O usuário informa o assunto.
2. A IA propõe um plano.
3. O usuário aprova ou ajusta.
4. A IA gera o PDF.

## Uso intermediário

No uso intermediário, o usuário informa o tema e também algumas preferências de estudo.

A IA deve montar uma estrutura mais detalhada, sugerindo capítulos, subassuntos, exemplos, exercícios e possíveis volumes.

Indicado para:

- estudar um assunto com mais profundidade;
- criar uma apostila técnica;
- aprender uma ferramenta ou biblioteca;
- gerar conteúdo com exemplos práticos;
- preparar material para uso recorrente.

Fluxo esperado:

1. O usuário informa o assunto e o objetivo.
2. A IA identifica os subassuntos relevantes.
3. A IA pergunta o que deve entrar e sair.
4. A IA propõe volumes ou um PDF único.
5. O usuário aprova o plano.
6. A IA gera o material final.

## Uso avançado

No uso avançado, o usuário pede um material completo, profundo ou voltado à formação de especialista.

A IA deve tratar o tema com mais rigor, mapear os recursos principais e avançados, organizar os conteúdos por categorias, propor uma coleção em volumes quando necessário e revisar o material antes da entrega.

Indicado para:

- dominar um assunto;
- estudar uma tecnologia com profundidade;
- cobrir recursos essenciais e avançados;
- criar uma coleção de volumes;
- construir material de referência;
- gerar um conteúdo próximo de um livro técnico.

Fluxo esperado:

1. O usuário informa o tema e pede profundidade.
2. A IA propõe a quantidade de volumes conforme a complexidade do assunto.
3. A IA separa fundamentos, prática, recursos avançados, erros comuns, boas práticas e exercícios.
4. A IA pergunta sobre formatação, nível, relação com projeto próprio e abrangência.
5. O usuário aprova o plano da coleção.
6. A IA gera o volume ou coleção conforme aprovado.
7. A IA revisa o conteúdo para remover repetições e melhorar a clareza.

## Formatação

Antes de gerar o PDF, a IA deve perguntar qual formato de leitura o usuário prefere.

As opções principais são:

- livro didático confortável;
- apostila técnica;
- leitura em tablet;
- impressão econômica.

Se o usuário não escolher, a IA deve usar o padrão de livro didático confortável.

A formatação deve ser aplicada silenciosamente. O conteúdo final não deve explicar fonte, margem, tamanho de letra ou diagramação.

## Volumes

A quantidade de volumes deve variar conforme o assunto.

Cada volume deve ter, como referência, um tamanho razoável em torno de 50 páginas. Esse valor não é uma regra rígida, mas serve como padrão de conforto para estudo.

A IA deve evitar volumes artificiais, repetitivos ou grandes demais. Cada volume precisa ter uma função clara dentro da coleção.

## Relação com projeto do usuário

Durante o planejamento, a IA deve perguntar se o usuário deseja relacionar o assunto com algum projeto próprio.

Se o usuário informar um projeto, a IA deve adaptar exemplos, aplicações e exercícios ao contexto fornecido.

Se o usuário não quiser relacionar com projeto, o material deve permanecer genérico.

## Revisão obrigatória

Antes de finalizar o PDF, a IA deve revisar o conteúdo para remover:

- repetições desnecessárias;
- explicações duplicadas;
- comentários sobre a conversa;
- comentários sobre a formatação;
- texto fora do assunto;
- exemplos redundantes;
- capítulos com sobreposição excessiva.

O resultado final deve parecer um material de estudo bem editado, e não uma resposta de chat convertida em PDF.

## Como instalar ou usar no ChatGPT

Coloque a pasta da skill em um local onde a IA possa consultar os arquivos.

Use o `SKILL.md` como arquivo principal e mantenha os arquivos auxiliares na mesma pasta.

Em um projeto ou assistente personalizado, envie todos os arquivos da pasta e instrua a IA a seguir o `SKILL.md` como regra principal.

## Comando de uso sugerido

```text
Use a Skill PDF de Estudos Genérica para planejar um material de estudo sobre o assunto que vou informar. Primeiro monte o escopo, os subassuntos, os volumes e as perguntas necessárias. Não gere o PDF final antes da minha aprovação.
```

## Regras para usar o GitHub como link da skill

Instruções para ser lido pela IA:

## Comando de uso sugerido

```text

Use a Skill PDF de Estudos Genérica do link do GitHub para planejar um material de estudo sobre o assunto que vou informar. Leia todos os arquivos do repositório e responda somente o resumo e o status de leitura de cada arquivos em uma mensagem breve. Monte o escopo, os subassuntos, os volumes e as perguntas necessárias. Não gere o PDF final antes da minha aprovação. Link: https://github.com/jonesfleite/skill-pdf-estudos-generica

```

## Manutenção

Para mudar o comportamento geral da skill, edite `SKILL.md`.

Para mudar o perfil da IA, edite `00_papel_da_ia.md`.

Para mudar as perguntas, edite `02_perguntas_obrigatorias.md`.

Para mudar a organização dos volumes, edite `07_volumes_e_tamanho.md`.

Para mudar a formatação, edite `08_formatacao_livro.md`.

Para melhorar a revisão final, edite `10_regras_de_limpeza_e_revisao.md`.
