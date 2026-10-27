# Publicidade no QR Code Turbo

A integração está preparada, mas DESATIVADA. Não gera receita até vincular uma conta e um site aprovados no AdSense. Não há IDs fictícios nem anúncios de demonstração.

## Dados necessários

- Identificador público `ca-pub-` com 16 dígitos.
- Códigos de dois blocos Display responsivos, incluindo `data-ad-slot`.
- Confirmar o domínio do site aprovado no AdSense.

## Ativação

1. Adicionar/verificar o site no AdSense e concluir a revisão do Google. A existência de uma conta não garante aprovação deste site.
2. Desativar anúncios automáticos para este site no painel. Manter somente os dois blocos manuais: após favoritos e antes das perguntas frequentes. Desativar otimizações que acrescentem ou expandam posições automaticamente. O JavaScript do site não pode garantir a ausência de anúncios automáticos se o painel os habilitar.
3. Configurar Privacidade e mensagens no AdSense, inclusive a CMP certificada do Google onde necessária. Revisar também as configurações aplicáveis às outras regiões. O campo `consentConfigured` é apenas uma trava de implantação: não substitui consentimento do visitante nem implementa uma CMP.
4. Atualizar `turboAdsConfig` no index.html com os IDs reais. Somente após as configurações anteriores, definir `enabled`, `consentConfigured` e `manualOnlyConfirmed` como true.
5. Verificar anúncios no domínio publicado sem clicar nos próprios anúncios. Receita depende de tráfego legítimo, inventário, aprovação e políticas; não é garantida.

Os blocos têm tamanhos responsivos fixos (300×100, 468×60, 728×90), carregamento próximo à área visível e identificação PUBLICIDADE. Não são usados pop-ups, intersticiais, bloqueio de download ou atualização periódica de anúncios. Antes da ativação, ficam ocultos e nenhum script do AdSense é carregado.

## ads.txt no GitHub Pages

O projeto está em `/QrCode-Turbo/`. Um arquivo colocado aqui seria publicado em `/QrCode-Turbo/ads.txt`, não na raiz do domínio. Se o AdSense pedir ads.txt, publicar a linha fornecida pelo painel em `https://matheusxxgamer2099.github.io/ads.txt` usando o repositório da página raiz da conta, ou configurar um domínio próprio e publicar na raiz desse domínio. Não criar uma linha com ID inventado. Confirmar a URL rastreada no painel.

## Referências oficiais

- https://support.google.com/adsense/answer/7584263?hl=pt-BR
- https://support.google.com/adsense/answer/9183363
- https://support.google.com/adsense/answer/13554116
