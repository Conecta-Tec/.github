# Padrões de repositório

## Nomes

Use nomes curtos, descritivos e em `kebab-case`:

- `conecta-*` para produtos Conecta;
- `plenamente-*` para produtos PlenaMente;
- `platform-*` para capacidades compartilhadas;
- `internal-*` para ferramentas operacionais;
- `infra-*` para infraestrutura como código.

Evite nomes de pessoas, siglas obscuras e sufixos como `new`, `final` ou `v2`.

## Configuração inicial

- Visibilidade privada, salvo decisão explícita.
- Branch padrão `main`.
- Merge por squash; excluir branch após merge.
- Issues e Projects somente quando fizerem parte do fluxo do time.
- Time responsável com permissão de manutenção ou escrita.
- Descrição, site e tópicos preenchidos.

## Arquivos mínimos

- `README.md`: propósito, arquitetura, setup, operação e responsáveis.
- `.gitignore` e licença quando aplicável.
- `.env.example` sem valores reais.
- Testes e workflow de CI.
- `CODEOWNERS` para áreas críticas.
- Runbook para serviços em produção.

Os arquivos globais de contribuição, segurança, suporte, issues e pull requests são herdados deste repositório `.github`.

## Proteção da branch principal

- Pull request obrigatório.
- Pelo menos uma aprovação.
- Conversas resolvidas.
- Checks de lint, testes e build.
- Branch atualizada quando o risco justificar.
- Push forçado e exclusão bloqueados.

## Segurança e dados

- Segredos ficam no provedor apropriado, nunca no Git.
- Dados pessoais e de escolas não entram em fixtures, logs ou screenshots.
- Dependências usam lockfile e atualização automatizada.
- Ambientes possuem credenciais separadas.
- Produção exige trilha de auditoria e rollback.

## Operação

Todo serviço precisa declarar responsável, dashboards, alertas, procedimento de deploy, rollback e resposta a incidentes. Repositórios sem dono não entram em produção.
