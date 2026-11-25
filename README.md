# ui-dialogs

Modais de confirm/prompt/alert para views embedadas em iframe, onde os nativos do navegador são bloqueados silenciosamente

Repositório: https://github.com/ThinkIac/ui-dialogs.

## Uso no ThinkIac

Este pacote foi extraído de `packages/ui-dialogs`. Preserve a identidade `ui-dialogs` do manifest ao instalá-lo em um workspace Lógos. Views, rotas, ferramentas e hooks são descobertos pelo runtime e dependem dos provedores correspondentes. Esta extração publica o código atual; não converte JavaScript para LógosType nem implementa instalação por perfil.

## Dependências e validação

Consulte `package.json` e os imports para as capacidades exigidas do host.

O pacote não declara scripts npm de build/teste. Os testes existentes acompanham o fonte; a composição completa requer o host ThinkIac.

## Segurança e dados locais

Credenciais devem ser configuradas no ambiente de destino. Não acompanham esta extração bancos, sessões, uploads, perfis pessoais, arquivos `.env`, caches ou backups. As exclusões foram registradas em relatório externo à publicação. Configure segredos pelo host, sem incluí-los em commits.


## Registros encontrados no código

Não foram encontrados registros declarativos nesse formato; consulte a entrada e os exports do pacote.

A lista é um inventário estático e pode incluir registros em testes; não garante disponibilidade sem os provedores do host.

