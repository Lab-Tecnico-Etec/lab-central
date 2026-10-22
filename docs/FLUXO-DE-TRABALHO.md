# Fluxo de trabalho

## Ciclo recomendado
1. Abra uma issue para descrever problema, contexto e resultado esperado.
2. Crie uma branch curta a partir da branch padrão: `feat/nome`, `fix/nome`, `docs/nome` ou `chore/nome`.
3. Faça mudanças pequenas e mantenha o escopo claro.
4. Execute testes, validações e verificações disponíveis no projeto.
5. Abra um pull request usando o template; descreva impacto, testes e limitações.
6. Solicite revisão ao mantenedor do projeto.
7. Integre somente após revisão e verificações adequadas ao risco.
8. Atualize a documentação quando comportamento, instalação ou configuração mudar.

## Commits
Use mensagens claras, por exemplo `feat: adicionar filtro de projetos`, `fix: corrigir validação` e `docs: atualizar instalação`. Não é obrigatório reescrever histórico existente.

## Segurança
- Não comitar `.env`, tokens, chaves privadas, credenciais, dados de alunos ou dumps de banco.
- Use variáveis de ambiente e exemplos como `.env.example` sem valores reais.
- Se um segredo for exposto, revogue/rotacione-o imediatamente; remover o arquivo do último commit não invalida o segredo.
- Não execute testes invasivos nem acesse sistemas sem autorização.

## Projetos escolares
Documente requisitos, dependências, versão das ferramentas, passos de execução e limitações conhecidas. Não apresente protótipos como sistemas prontos para produção.