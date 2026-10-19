# Essência — retorno Mercado Livre

Página estática de retorno da autorização OAuth do Mercado Livre para o aplicativo local Essência.

Depois da autorização, a página permite copiar a URL de retorno para concluir a conexão no aplicativo local. A validação de `state`, a troca do código por tokens e a renovação são realizadas pelo aplicativo no computador do usuário.

Esta página não recebe a senha da conta, a Secret Key ou access tokens. Não possui analytics nem chamadas para serviços externos. Não publique credenciais neste repositório nem compartilhe a URL temporária recebida após a autorização.

## Hospedagem

Publicar pelo GitHub Pages, branch `main`, diretório raiz `/`. Depois de confirmar a URL publicada, cadastrar exatamente esse endereço como URL de retorno da aplicação no Mercado Livre e no Essência, incluindo a barra final quando houver.
