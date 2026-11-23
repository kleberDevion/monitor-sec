## Especificação do projeto. MNT-SEC

> Stack

- Linguagem: TypeScript
- FrameWork: Electron

> FrontEnd

- FrameWork: React + Next

> BackEnd

- TypeScript

> Branding

- Empresa Capixaba Megasec: IG(https://www.instagram.com/megasec.es/), WEBSITE: https://megasec.com.br/
- Logo, Tonalidade de cores da marca

Objetivos:

1 - Inicial:

``` 
Criar um painel de monitoramento que seja possivel ver informações em tempo real,
de carregadores eletricos, vc tera que usar o client "Electron", para obter da aba de "Rede - em visualização" os dados em JSON  que vem dessas urls:
1 - https://cms.spott.eco/pt/site-monitor/bf02bee2-d135-4885-af24-043c7a48eca2
2 - https://cms.spott.eco/pt/site-monitor/580d9035-92f9-41e9-af6e-bbbb3bfb43fa
3 - https://cms.spott.eco/pt/site-monitor/f929c2a7-ffd0-488c-83dc-185288de264e

 Atualmente, so tem 3 equipamentos, futuramente devera ter uma OP no painel, que ao add a url do equipamento, ele e cadastrado.

 Com bas eem somente isso, traga um MVP, 
``` 

2 - Login, com sessão cravada no servidor, nada de JWT, WebSocket que verifica se o client ta com aba aberta, se fechar o token expira na hora.
