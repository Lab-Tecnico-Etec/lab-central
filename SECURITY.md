# Política de segurança

A segurança dos projetos do Lab Técnico ETEC é importante.

## Como reportar uma vulnerabilidade
- Não publique detalhes exploráveis de uma vulnerabilidade em uma issue pública.
- Entre em contato de forma privada com os mantenedores da organização pelo canal privado disponível na instituição ou no GitHub.
- Inclua o repositório afetado, o impacto potencial, os passos mínimos para reproduzir o problema e uma sugestão de correção, se houver.

## Boas práticas
- Nunca faça commit de senhas, tokens, chaves privadas, credenciais, arquivos `.env` reais ou dados pessoais.
- Use variáveis de ambiente e mantenha um `.env.example` apenas com nomes de variáveis e valores fictícios.
- Aplique o princípio do menor privilégio às credenciais e integrações.
- Atualize dependências vulneráveis com revisão e testes.
- Remova segredos expostos e revogue/rotacione a credencial; apagar o arquivo em um commit posterior não torna o segredo seguro.
- Não execute testes de segurança em sistemas de terceiros sem autorização explícita.

Esta política não promete um prazo de resposta específico. Os canais de contato e responsáveis devem ser definidos pelos mantenedores da organização.
