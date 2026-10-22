# Plano de implantação do Lab Técnico ETEC

Este documento transforma a estrutura proposta em etapas verificáveis. O plano não presume que configurações descritas aqui já estejam ativadas no GitHub.

## Estado inicial verificado

A listagem consultada em 22/10/2026 retornou três repositórios da organização:

| Repositório | Visibilidade | Papel recomendado |
|---|---|---|
| [`.github`](https://github.com/Lab-Tecnico-Etec/.github) | Público | Perfil institucional e padrões compartilhados |
| [`lab-central`](https://github.com/Lab-Tecnico-Etec/lab-central) | Público | Governança, documentação e catálogo |
| [`Lab-Tecnico-Etec`](https://github.com/Lab-Tecnico-Etec/Lab-Tecnico-Etec) | Privado | Repositório institucional a revisar antes de decidir seu destino |

O catálogo já registra Sorveteria e Java como parte do escopo do laboratório, mas seus arquivos continuam nos repositórios pessoais de origem. Registro no catálogo não significa migração física concluída.

## Fase 1 — Fundação

- [x] Manter um repositório `.github` para o perfil e padrões compartilhados.
- [x] Manter `lab-central` como central de documentação e catálogo.
- [x] Documentar o estado dos repositórios e distinguir vínculo institucional de migração concluída.
- [ ] Revisar o conteúdo completo do repositório privado `Lab-Tecnico-Etec`.
- [ ] Confirmar integrantes, responsáveis e níveis de acesso.
- [ ] Conferir se as regras de proteção da branch principal estão configuradas no GitHub.

**Conclusão:** documentos e papéis estão descritos; permissões e proteções só serão considerados concluídos após verificação nas configurações do GitHub.

## Fase 2 — Inventário e consolidação

### Sorveteria

- [x] Registrar origem, equipe identificada e estado no catálogo.
- [x] Criar o repositório canônico `Web-Site-Sorveteria` na organização.
- [x] Copiar páginas HTML, CSS, JavaScript, licenças, fontes e 56 dos 57 recursos binários identificados.
- [ ] Copiar `imgs/imgs/Logo1.png` da origem e validar todos os caminhos de recursos.
- [ ] Preservar créditos e confirmar autorização dos participantes.
- [ ] Testar caminhos relativos, responsividade e comportamento das páginas.
- [ ] Confirmar o destino da hospedagem antes de alterar qualquer publicação existente.

### Java

- [x] Registrar origem e listas conhecidas no catálogo.
- [x] Criar o repositório canônico `Projetos-Java` na organização.
- [x] Copiar somente os 42 arquivos Java identificados na pasta Java, sem transferir o repositório pessoal inteiro.
- [x] Organizar README geral e instruções básicas de execução.
- [ ] Compilar/executar amostras de cada lista e corrigir eventuais diferenças de ambiente.
- [ ] Verificar autoria, dependências, execução e ausência de dados sensíveis.

**Regra de segurança:** preservar os repositórios de origem até validar a cópia. Não apagar, arquivar ou transferir nada como parte desta etapa sem revisão e autorização.

## Fase 3 — Padronização e governança

- [x] Disponibilizar guia de contribuição, código de conduta, política de segurança e templates compartilhados no repositório `.github`.
- [x] Manter modelos e orientações centrais no `lab-central`.
- [ ] Definir um responsável por projeto e um substituto quando necessário.
- [ ] Aplicar permissões de menor privilégio, com pelo menos dois Owners de confiança se houver pessoas disponíveis e aprovadas para essa função.
- [ ] Configurar proteção da branch principal quando o plano GitHub permitir.
- [ ] Exigir revisão para mudanças coletivas relevantes, sem burocratizar exercícios individuais.
- [ ] Conferir licenças e verificar credenciais antes de qualquer publicação pública.

### Papéis recomendados

- **Owner:** administra organização, segurança, membros e configurações críticas. Manter esse papel restrito.
- **Maintainer:** cuida da manutenção e das revisões de um projeto; não precisa ser Owner da organização.
- **Contributor:** propõe código, documentação, Issues e Pull Requests.
- **Reader/Triage:** consulta projetos ou ajuda a classificar e organizar Issues, conforme as permissões reais disponíveis no GitHub.

Os papéis acima são uma proposta de governança; não significam que os acessos já foram alterados.

## Fase 4 — Portfólio coletivo

- [ ] Selecionar projetos com autorização de publicação.
- [ ] Criar demonstrações, capturas de tela e instruções reproduzíveis.
- [ ] Documentar tecnologias, objetivos, contribuições e estado do projeto.
- [ ] Criar `lab-portfolio-coletivo` apenas quando houver projetos validados suficientes para justificar outro repositório.
- [ ] Revisar todos os links públicos e a ausência de dados privados antes da divulgação.

## Critérios para considerar um projeto pronto

1. Existe um repositório canônico definido.
2. O README explica objetivo, tecnologias, instalação/execução e estado.
3. Créditos, licenças e permissões foram verificados.
4. Arquivos necessários e dependências estão presentes.
5. Testes ou validações apropriadas foram executados.
6. Não há credenciais nem dados pessoais expostos.
7. A visibilidade do repositório foi deliberadamente escolhida.

## Próximas ações prioritárias

1. Copiar o arquivo `imgs/imgs/Logo1.png` para `Web-Site-Sorveteria` e validar todas as páginas localmente.
2. Compilar/executar amostras de cada lista em `Projetos-Java`.
3. Revisar o repositório privado institucional.
4. Confirmar membros, permissões, visibilidade dos projetos e proteção de branches.
5. Só então preparar uma vitrine pública coletiva.
