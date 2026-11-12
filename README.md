# Meu Financeiro — V3

## O que mudou
- Mantidas as funcionalidades da V2: dashboard, despesas do mês na tela inicial, contas fixas, parcelamentos, cartões e paleta individual de cores.
- Entrega limpa: sem despesas, contas fixas, parcelamentos, cartões ou salários de teste. Categorias padrão e tema claro permanecem.
- Backup JSON com data no nome e atalho específico para backup antes de atualizações.
- Restauração com validação; antes de substituir os dados, o app baixa uma cópia do estado atual.
- Revisão de contraste dos temas claro/escuro, campos, textos auxiliares, menus e foco de teclado.
- Manifesto PWA com ícones PNG 192x192 e 512x512 e metadados de instalação.
- Service Worker com cache V3.

## Instalação no Android
A instalação PWA exige publicar os arquivos em HTTPS (ou executar em localhost). Abra o endereço HTTPS no Chrome do Android, abra o menu ⋮ e escolha **Instalar app** ou **Adicionar à tela inicial**. Se o Chrome oferecer o convite de instalação, use também o botão exibido no aplicativo.

## Publicação e atualizações
Publique todos os arquivos mantendo a mesma origem HTTPS. Antes de substituir arquivos, exporte um backup JSON. A chave de armazenamento local foi preservada para compatibilidade com V1/V2. Não limpe os dados do site. Se mudar de domínio ou navegador, restaure o backup no novo endereço.

## Privacidade
Os dados permanecem no armazenamento local do navegador; o aplicativo não envia dados financeiros para servidores.
