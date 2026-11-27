# Reembolso UAI

*Gastou aí? Manda a nota.*

App web (PWA) para fotografar notas fiscais de refeição, conferir os dados e baixar a planilha de reembolso no formato da tabela **NotasViagem**.

- Lê o QR code da NFC-e e o texto da nota no próprio celular (sem enviar nada para servidor).
- Aceita foto ou PDF.
- Guarda notas e fotos só no aparelho (IndexedDB).
- Exporta `.xlsx` (tabela NotasViagem) e `.zip` com a planilha + pasta `FOTOS`.
- Funciona sem internet depois da primeira abertura.

## Usar no iPhone
Abra o link no Safari → Compartilhar → **Adicionar à Tela de Início**.

## Bibliotecas incluídas (pasta `vendor/`)
jsQR 1.4.0 (Apache-2.0), Tesseract.js 5.1.1 + core + dados `por` (Apache-2.0), PDF.js 3.11.174 (Apache-2.0).
