# Skill PDF de Estudos Genérica

Esta pasta contém uma skill modular para orientar uma IA a criar materiais de estudo em PDF sobre qualquer assunto.

A skill foi desenhada para ser genérica, reutilizável e adaptável. Ela não menciona empresas, marcas, projetos pessoais ou contextos específicos. Durante o planejamento, a IA deve perguntar se o usuário quer relacionar o assunto com algum projeto próprio.

## Estrutura

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
├── 11_fontes_pesquisa_e_atualizacao.md
├── modelos/
├── templates/
└── exemplos/
```

## Como usar

Use o arquivo `SKILL.md` como arquivo principal da skill. Os demais arquivos funcionam como módulos de apoio.

Exemplo de comando:

> Use a skill PDF de Estudos Genérica para criar uma coleção de estudo sobre [assunto].

A IA deve primeiro planejar o material, perguntar sobre escopo, volumes, subassuntos, formatação e possível relação com algum projeto do usuário. Depois da aprovação, a IA pode gerar o PDF.

## Exemplos incluídos

A pasta `exemplos` contém modelos de resposta para diferentes pedidos. Foram incluídos exemplos específicos para:

- biblioteca Python em nível geral;
- biblioteca Python em nível avançado, com funções avançadas;
- biblioteca Python para formação de especialista, com cobertura completa de funções e possibilidades.

