# Lab Técnico ETEC — Central

Ponto de entrada para organização, documentação, catálogo de projetos e recursos compartilhados do Lab Técnico ETEC.

## Navegação

- [Plano inicial](docs/PLANO-INICIAL.md)
- [Governança](docs/GOVERNANCA.md)
- [Fluxo de trabalho](docs/FLUXO-DE-TRABALHO.md)
- [Classificação de projetos](docs/CLASSIFICACAO.md)
- [Organização e padrões dos repositórios](docs/ORGANIZATION.md)
- [Catálogo de projetos](catalogo/PROJETOS.md)
- [Biblioteca de recursos](catalogo/BIBLIOTECA.md)
- [Modelo de README de projeto](templates/README-PROJETO.md)
- [Modelo de documentação de projeto](docs/PROJECT_TEMPLATE.md)
- [Guia de contribuição](CONTRIBUTING.md)
- [Código de conduta](CODE_OF_CONDUCT.md)
- [Política de segurança](SECURITY.md)
- [Perfil público e padrões globais](https://github.com/Lab-Tecnico-Etec/.github)

## Repositórios essenciais

| Repositório | Finalidade | Decisão |
|---|---|---|
| [.github](https://github.com/Lab-Tecnico-Etec/.github) | Perfil público, modelos e diretrizes padrão | Manter |
| [lab-central](https://github.com/Lab-Tecnico-Etec/lab-central) | Governança e documentação central | Manter |
| [Lab-Tecnico-Etec](https://github.com/Lab-Tecnico-Etec/Lab-Tecnico-Etec) | Apresentação institucional separada | Avaliar redundância |
| [demo-repository](https://github.com/Lab-Tecnico-Etec/demo-repository) | Demonstração genérica do GitHub | Não usar como projeto oficial |
| [fuzzy-succotash-demo-repository](https://github.com/Lab-Tecnico-Etec/fuzzy-succotash-demo-repository) | Segunda demonstração genérica do GitHub | Provável redundância |

## Padrões de colaboração

- Use branches com nomes descritivos, como `feat/nova-funcionalidade`, `fix/correcao` e `docs/atualizacao`.
- Prefira mudanças pequenas, revisáveis e documentadas; use Pull Requests sempre que possível.
- Execute os testes e builds disponíveis e informe o que realmente foi validado.
- Nunca envie credenciais, tokens, chaves privadas, dados pessoais ou arquivos `.env` reais.
- Defina a licença de cada projeto com seus responsáveis; não presuma que o código está liberado para reutilização.
- Preserve autoria, histórico e código existente. Não mova, renomeie, arquive ou exclua projetos sem autorização explícita.

## Adicionar um projeto ao catálogo

Abra uma issue ou Pull Request para registrar nome/link, objetivo, categoria, tecnologias, estado confirmado e responsável (se definido). Use "a confirmar" para informações desconhecidas; não invente metadados.

## Limites da central

Esta central documenta padrões recomendados. Ela não configura automaticamente equipes, permissões, visibilidade, regras de branch, segredos, proteções ou deploy da organização. Essas opções precisam ser revisadas e aplicadas por um administrador com permissões adequadas.
