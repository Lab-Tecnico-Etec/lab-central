# Catálogo de projetos

Inventário oficial do Lab Técnico ETEC. O catálogo distingue o vínculo institucional do estado real de consolidação do código.

## Infraestrutura da organização

| Repositório | Finalidade | Estado |
|---|---|---|
| [`.github`](https://github.com/Lab-Tecnico-Etec/.github) | Perfil público e padrões compartilhados | Manter |
| [`lab-central`](https://github.com/Lab-Tecnico-Etec/lab-central) | Governança, documentação e catálogo | Manter |
| [`Lab-Tecnico-Etec`](https://github.com/Lab-Tecnico-Etec/Lab-Tecnico-Etec) | Repositório institucional privado | Revisar conteúdo antes de decidir se é necessário mantê-lo separado |

## Projetos canônicos

### Sorveteria — desenvolvimento web coletivo

- **Repositório canônico:** [Lab-Tecnico-Etec/Web-Site-Sorveteria](https://github.com/Lab-Tecnico-Etec/Web-Site-Sorveteria)
- **Origem preservada:** [Lvc4br/Projetos-PW-ETEC/tree/main/Sorveteria](https://github.com/Lvc4br/Projetos-PW-ETEC/tree/main/Sorveteria)
- **Tecnologias:** HTML, CSS e JavaScript.
- **Equipe indicada na origem:** Luca, Bianca e Fred.
- **Arquivos já copiados para o repositório canônico:** páginas HTML, folhas CSS, scripts JS e textos de licença/fontes.
- **Estado:** migração parcial. Arquivos binários de imagens e fontes ainda precisam ser transferidos e validados; até então, caminhos de recursos podem estar quebrados e o site não deve ser tratado como pronto para publicação.
- **Próximas tarefas:** copiar todos os recursos binários mantendo os caminhos relativos, verificar licenças e créditos, testar todas as páginas em servidor local e só depois considerar publicação.
- **Hospedagem:** a URL mencionada na origem não é considerada publicação oficial nem foi validada nesta etapa.

### Java — exercícios acadêmicos

- **Repositório canônico:** [Lab-Tecnico-Etec/Projetos-Java](https://github.com/Lab-Tecnico-Etec/Projetos-Java)
- **Origem preservada:** [Lvc4br/ETEC-Desenvolvimento-de-Sistemas/tree/main/java](https://github.com/Lvc4br/ETEC-Desenvolvimento-de-Sistemas/tree/main/java)
- **Conteúdo:** exercícios organizados em `listaA`, `listaAExtra2`, `listaD`, `listaExtra` e `listaF`.
- **Estado:** os 42 arquivos Java identificados na pasta de origem foram copiados para o repositório canônico; README de execução e autoria foi atualizado. A origem permanece intacta.
- **Próximas tarefas:** compilar/executar amostras de cada lista, revisar nomes de classes e pacotes, confirmar créditos e decidir a visibilidade adequada.

## Repositórios pessoais preservados

| Repositório | Uso | Decisão |
|---|---|---|
| [LV_Portfolio](https://github.com/Lvc4br/LV_Portfolio) | Portfólio pessoal | Manter pessoal |
| [nexo-analytics](https://github.com/Lvc4br/nexo-analytics) | Analytics relacionado ao portfólio | Manter pessoal enquanto iniciativa individual |
| [Projetos-PW-ETEC](https://github.com/Lvc4br/Projetos-PW-ETEC) | Coleção acadêmica de Programação Web | Preservar; contém a origem da Sorveteria |
| [ETEC-Desenvolvimento-de-Sistemas](https://github.com/Lvc4br/ETEC-Desenvolvimento-de-Sistemas) | Exercícios de Desenvolvimento de Sistemas | Preservar; contém a origem Java |

## Critérios de organização

- Um projeto real possui um único repositório canônico dentro do escopo acordado.
- Não transferir repositórios pessoais inteiros quando apenas uma pasta pertence ao laboratório.
- Preservar os repositórios de origem até concluir a validação da cópia.
- Não publicar projetos coletivos sem confirmar autoria, permissões, licenças e ausência de dados sensíveis.
- O catálogo deve refletir o estado real da migração; não confundir documentação com implementação.

## Próximas prioridades

1. Completar os recursos binários da Sorveteria e testar o site.
2. Executar validação básica dos exercícios Java.
3. Inspecionar o repositório institucional privado.
4. Confirmar integrantes, permissões e proteção da branch principal.
5. Criar uma vitrine coletiva somente quando houver projetos validados suficientes.
