# GABiSOU: inventário de manutenção

Piloto de detecção de atualizações do whoami com Renovate.

## Autoridade

Este repositório registra referências para análise. Não é origem de implantação.
O whoami continua gerenciado pelo Editor Portainer no Raspberry.
Alterações e merges aqui não atualizam o ambiente.

Não adicionar segredos, arquivos .env, credenciais, dados de aplicações ou
workflows de deploy neste piloto.

## Base observada

A última evidência aceita do whoami é o canário C05, encerrado em 14/10/2026:
imagem identificada pela label 1.12.0 e pelo digest de índice abaixo.

traefik/whoami:v1.12.0@sha256:c4717a8d1f0134a7444e24f881160e033991f23027c6c5a9a3f8fd22e70d1d44

A tag v1.12.0 foi associada ao mesmo índice em consulta pública.
Adicionar a tag a este registro não altera a imagem implantada.

inventory/whoami/compose.yaml é somente entrada de detecção para Renovate.
Não aplicar esse arquivo com Docker Compose ou Portainer.

## Atualizações

Renovate propõe alterações por pull request, sem automerge.
PR de imagem é uma candidata para avaliação, não evidência de implantação.
Durante este piloto, somente o onboarding será integrado; PRs de imagem
permanecem para avaliação posterior.

O registro da versão realmente implantada será atualizado somente com
evidência de execução. Um merge no inventário não substitui essa evidência.
