# Dashboard Movimenta Sebrae Macaé 2026

## Arquivos para publicação
Publique somente:
- index.html
- 404.html
- robots.txt

NÃO publique `SENHA_ADMINISTRADOR.txt`.

## GitHub Pages
1. Crie um repositório privado ou público conforme a política institucional.
2. Envie index.html, 404.html e robots.txt para a raiz.
3. Em Settings > Pages, escolha Deploy from a branch e a pasta /root.
4. Compartilhe a senha da área protegida por um canal separado.

## Azure Static Web Apps
Envie os mesmos três arquivos à raiz do aplicativo estático. Não é necessário processo de build.

## Proteção aplicada
- A página pública contém somente dados agregados.
- Dados pessoais ficam criptografados com AES-GCM.
- A chave é derivada por PBKDF2-SHA-256 com 310.000 iterações.
- A senha não está incorporada no HTML.
- A descriptografia acontece localmente no navegador.

## Limitação importante
Como é um site estático, não há log de acesso, revogação individual ou autenticação corporativa. Para controles mais fortes, hospede a área nominal atrás de Microsoft Entra ID/Azure Static Web Apps Authentication e mantenha somente os agregados públicos.

## Dados processados
- Registros de acesso únicos: 9622
- Acessos distintos por dia/código: 94
- Espaços: 14

## Identidade visual
A interface utiliza paleta azul institucional inspirada no Sebrae, marca textual no cabeçalho, cards executivos, hierarquia visual responsiva e rodapé institucional. Para usar o arquivo oficial de marca, substitua o bloco textual do cabeçalho por um ativo aprovado pela área de Comunicação.

## Versão 2.0
Inclui destaques automáticos, gráfico de tendência diária, gráfico de composição, ranking Top 10 e mapa de intensidade por espaço e dia. Todos os gráficos são nativos no HTML e não dependem de bibliotecas externas.
