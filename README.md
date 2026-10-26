# QR Code Turbo

Gerador de QR Codes estáticos, gratuito e personalizável, feito com HTML, CSS e JavaScript. O conteúdo é processado no navegador.

## Recursos da versão 1

- QR Codes para links, WhatsApp, Wi-Fi, texto e e-mail
- Prévia ao vivo
- Cores, estilos dos pontos e molduras
- Logotipo opcional no centro
- Exportação em PNG e SVG
- Sem cadastro, marca-d'água ou limite artificial de downloads
- Layout responsivo para celular e computador

## Publicação no GitHub Pages

1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment → Source**, selecione **GitHub Actions**.
3. Salve a configuração.
4. Abra **Actions** e acompanhe o workflow **Deploy QR Code Turbo to GitHub Pages**. Ele também roda automaticamente quando houver novos commits na branch `main`.

Após o primeiro deploy, o site ficará em:

https://matheusxxgamer2099.github.io/QrCode-Turbo/

## Observações

- A biblioteca QR Code Styling é carregada pela CDN jsDelivr; portanto, a geração requer conexão para carregar a biblioteca na primeira visita.
- O QR Code é estático: o conteúdo fica codificado na imagem e não expira por causa deste site. O destino precisa continuar ativo.
- Sempre teste a leitura antes de imprimir ou distribuir.
- O espaço publicitário é apenas reservado visualmente. Nenhuma rede de anúncios está conectada nesta versão.
- Antes de ativar anúncios, publique uma política de privacidade adequada e revise os requisitos e políticas do provedor escolhido.
