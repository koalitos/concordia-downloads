# Concórdia 1.0.9

- Sua própria câmera volta à grade, espelhada e muda, incluindo os fundos e efeitos escolhidos.
- Sua própria live de tela continua oculta. Um aviso permanente “Você está ao vivo” mostra a sala e permite parar a transmissão, mesmo ao visualizar outra sala.
- Aviso de nova versão no topo do app, com progresso e “Reiniciar e atualizar”, sem cobrir os controles no desktop ou celular.
- Fundos da câmera: desfoque leve/médio/forte, fundos prontos, foto personalizada e prévia local. Preferência e foto salvas por conta neste dispositivo.
- Seis sons complementares para entrada/saída da sala, início/fim de live e câmera ligada/desligada. Volume, mute e prévias em Preferências → Sons.
- Avisos sem duplicação nos snapshots e reconexões; sair da sala não gera uma cascata de sons de fim de transmissão.

## Instalação

Windows e AppImage Linux recebem a atualização pelo aplicativo instalado.
No macOS, atualização automática exige um app assinado com Developer ID;
pacotes sem esse certificado devem ser substituídos manualmente pelo novo
DMG. Fechar pelo X apenas esconde o aplicativo; use Sair na bandeja para
aplicar uma atualização adiada. Os pacotes Mac incluem Apple Silicon e Intel.

Para compartilhar no Mac, autorize o Concórdia em Ajustes do Sistema → Privacidade e Segurança → Gravação de Tela. Pacotes sem certificado podem exigir liberação em Privacidade e Segurança → Abrir Mesmo Assim. Se continuar bloqueado após mover para Aplicativos:

```
xattr -dr com.apple.quarantine /Applications/Concordia.app
```
