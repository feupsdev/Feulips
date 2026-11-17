# Arquivos do perfil feupsdev

## Estrutura

Copie a pasta `.github` para a raiz do repositório especial `feupsdev/feupsdev`.
Ela contém os três workflows:

- `arcade.yml`: gera o Pac-Man.
- `snake.yml`: gera a cobrinha com paleta roxa.
- `profile-3d.yml`: gera o gráfico 3D.

O arquivo `README-Beyond-Code.md` contém apenas a seção visual. Copie o conteúdo dele para o seu `README.md` atual; não substitua o README inteiro se já tiver seu perfil montado.

## Ativar

1. Crie o repositório público `feupsdev/feupsdev`.
2. Envie a pasta `.github` e seus arquivos para a raiz do repositório.
3. Em Settings > Actions > General > Workflow permissions, habilite `Read and write permissions`.
4. Abra a aba Actions e execute manualmente os três workflows uma vez.
5. Aguarde a conclusão. Pac-Man e Snake publicam seus SVGs na branch `output`; o gráfico 3D cria a pasta `profile-3d-contrib` na branch `main`.
6. Cole a seção de `README-Beyond-Code.md` no README principal.

Não é necessário criar Personal Access Token: os workflows usam `GITHUB_TOKEN` fornecido pelo GitHub Actions.

## Observações

- Os workflows rodam automaticamente uma vez por dia e também podem ser executados manualmente.
- O Pac-Man usa o tema escuro fornecido pelo projeto. O Snake foi configurado com tons roxos.
- O gráfico 3D usa o tema `profile-night-rainbow`, que é escuro, mas não exclusivamente roxo.
- Troféus e piada são imagens de serviços externos; podem ficar indisponíveis temporariamente.
