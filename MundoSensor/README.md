# Mundo Sensorial — V6

Ajuste de instalação:
- **Salvar App** fica sempre visível.
- Se o app estiver aberto em modo instalado/standalone, o botão fica desabilitado e mostra **✓ App instalado**.
- Após o evento `appinstalled`, o botão também muda para o estado desabilitado.
- Android/Chromium usa o prompt nativo quando ele estiver disponível.
- iPhone/iPad mostra as instruções de **Compartilhar > Adicionar à Tela de Início**.

Observação: navegadores não oferecem uma API universal para detectar uma instalação feita por outro navegador. O estado é confiável quando o app está sendo executado em modo standalone e quando a instalação ocorre na sessão pelo evento `appinstalled`.
