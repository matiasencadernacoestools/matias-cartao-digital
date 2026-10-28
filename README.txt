CARTÃO DIGITAL MATIAS — implantação

1. Faça upload de index.html, logo.png e matias.vcf na raiz de um repositório público do GitHub.
2. Em Settings > Pages, selecione Deploy from a branch, branch main e pasta /(root).
3. Acesse o endereço github.io exibido pelo GitHub Pages e teste todos os botões.
4. Se tiver um domínio próprio, configure Custom domain no GitHub Pages e os registros DNS no provedor.
5. Somente depois de confirmar o endereço definitivo, grave a URL HTTPS na etiqueta NFC.
6. Não bloqueie a tag durante os testes.

Observações: o botão Salvar Contato baixa/abre um arquivo vCard. O fluxo de importação varia conforme o sistema do celular. O endereço e contatos foram informados pelo solicitante.

ATUALIZAÇÃO 02: botão "Gerar QR Code do Cartão" ao lado de Compartilhar.
O QR Code aponta automaticamente para a URL pública da página (GitHub Pages ou domínio próprio).
A geração usa biblioteca QRCode.js via CDN; exige internet na hora de gerar.
Ao abrir index.html localmente (file://), publique primeiro para criar um QR Code utilizável em outros celulares.
