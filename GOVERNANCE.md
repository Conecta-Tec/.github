# Governança de engenharia

## Responsabilidades

### Proprietários da organização

- Administram identidade, faturamento, integrações e políticas globais.
- Mantêm pelo menos dois proprietários ativos com 2FA.
- Revisam acessos, apps e tokens periodicamente.
- Coordenam incidentes de segurança.

### Engenharia

- Mantém padrões técnicos, automações e componentes compartilhados.
- Revisa mudanças de plataforma, arquitetura e segurança.
- Cuida do repositório `.github` e dos templates oficiais.

### Times de produto

- **Conecta:** produtos e serviços do ecossistema Conecta.
- **PlenaMente:** produto PlenaMente e serviços relacionados.
- Cada time é responsável pelo ciclo completo de seus sistemas: entrega, operação, documentação e evolução.

## Decisões

Decisões reversíveis ficam no pull request. Decisões com impacto estrutural, alto custo de reversão ou efeito em múltiplos produtos usam o [template de decisão](docs/DECISION_TEMPLATE.md).

## Acesso

- Permissão-base da organização: nenhuma.
- Acesso concedido por time e pelo menor privilégio necessário.
- Contas compartilhadas são proibidas.
- Acessos são removidos imediatamente quando deixam de ser necessários.
- Revisão de membros, times e integrações: trimestral.

## Ciclo de vida de repositórios

Todo repositório possui responsável, propósito, classificação, documentação operacional e política de arquivamento. Projetos sem manutenção ativa devem ser arquivados, nunca abandonados silenciosamente.
