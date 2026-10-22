# Organização do Lab Técnico ETEC

## Objetivo

Manter uma estrutura pequena, clara e preparada para receber projetos acadêmicos e tecnológicos sem duplicar código nem impor burocracia excessiva.

## Repositórios atuais e suas funções

| Repositório | Função | Visibilidade observada |
|---|---|---|
| [`.github`](https://github.com/Lab-Tecnico-Etec/.github) | Perfil institucional e padrões compartilhados | Público |
| [`lab-central`](https://github.com/Lab-Tecnico-Etec/lab-central) | Governança, documentação, catálogo e modelos | Público |
| [`Web-Site-Sorveteria`](https://github.com/Lab-Tecnico-Etec/Web-Site-Sorveteria) | Projeto coletivo de Programação Web | Confirmar nas configurações do GitHub |
| [`Projetos-Java`](https://github.com/Lab-Tecnico-Etec/Projetos-Java) | Exercícios acadêmicos Java | Confirmar nas configurações do GitHub |
| [`Lab-Tecnico-Etec`](https://github.com/Lab-Tecnico-Etec/Lab-Tecnico-Etec) | Repositório institucional legado/privado | Privado; revisar antes de decidir seu destino |

A lista acima é a estrutura funcional recomendada. A visibilidade dos repositórios de projeto deve ser confirmada no GitHub antes de divulgar links publicamente.

## Regras estruturais

1. Cada projeto real possui um único repositório canônico.
2. O catálogo fica em `lab-central/catalogo/PROJETOS.md`; não criar um repositório separado só para o catálogo enquanto ele couber na central.
3. Projetos pessoais continuam nos perfis pessoais, salvo acordo explícito dos autores.
4. Para consolidar apenas uma subpasta de um repositório pessoal, copie somente o escopo autorizado e mantenha o original até validar a migração.
5. Não criar `lab-portfolio-coletivo` antes de existirem projetos revisados e autorizados para divulgação.
6. Não renomear, arquivar, excluir, transferir ou alterar a visibilidade sem avaliar links, deploys, workflows, permissões, autoria e integrações.

## Categorias para classificar projetos

As categorias são metadados do catálogo, não motivo para criar repositórios duplicados:

- **Aplicação:** sistema web, mobile ou desktop.
- **Projeto acadêmico:** atividade de disciplina ou exercício.
- **Experimento/protótipo:** prova de conceito ou estudo.
- **Biblioteca/ferramenta:** componente reutilizável.
- **Documentação/recurso:** material de apoio com origem e licença registradas.

Um projeto pode ter múltiplas tags de área (por exemplo, web + dados) e ainda assim manter um único repositório canônico.

## Padrão mínimo por repositório

Quando aplicável, incluir:

- README com objetivo, estado, tecnologias, requisitos e instruções de execução.
- Créditos e licença definidos explicitamente.
- Guia de contribuição ou link para o padrão da organização.
- Política de segurança ou referência à política comum.
- Arquivo de exemplo de configuração sem segredos, se necessário.
- Testes e automações proporcionais à maturidade do projeto.

## Convenções

- Prefira nomes curtos e descritivos; use kebab-case para novos repositórios quando possível.
- Mantenha idioma e convenções consistentes dentro de cada projeto.
- Separe código, documentação, testes e recursos estáticos quando fizer sentido.
- Não adicione licença por padrão: a decisão deve ser tomada pelos responsáveis.
- Não declare um projeto testado, implantado ou pronto para produção sem validação.

## Catálogo e revisão

O catálogo oficial fica em [`catalogo/PROJETOS.md`](../catalogo/PROJETOS.md). Registre nome, link canônico, objetivo, categoria, tecnologias, origem, estado de consolidação e responsável quando conhecido.

Revise periodicamente permissões, dependências, issues, instruções de execução, possíveis segredos e links quebrados.
