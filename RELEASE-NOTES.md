## Concórdia 1.0.5

- Visual azul unificado no navegador e no aplicativo, com nova identidade e novo ícone.
- Institucional redesenhado com apresentação das salas e downloads para Mac Apple Silicon, Mac Intel e Windows.
- Telas e câmeras em grade, destaque e tela cheia. A experiência é exclusivamente visual, sem áudio.
- Aplicativo usa o acesso HTTPS direto ao site e conserva o armazenamento de login existente.
- Falhas temporárias ao carregar o perfil oferecem uma nova tentativa, sem voltar ao cadastro de nickname.
- Atualização no Windows com instalador e metadados; pacotes ZIP incluídos para o mecanismo de atualização do macOS.

### Instalação

**Mac:** baixe o DMG correspondente ao processador e arraste para Aplicativos. Autorize o Concórdia em Ajustes do Sistema → Privacidade e Segurança → Gravação de Tela para compartilhar.

Pacotes sem certificado Apple podem exigir liberação em Privacidade e Segurança → Abrir Mesmo Assim. Se o app continuar bloqueado após mover para Aplicativos, execute uma vez no Terminal:

```
xattr -dr com.apple.quarantine /Applications/Concordia.app
```

O macOS exige assinatura Developer ID para atualizar automaticamente. Instalações antigas sem assinatura precisam baixar e substituir o aplicativo manualmente. A sessão é preservada.

**Windows:** execute Concordia-Setup.exe. O aplicativo instalado verifica novas versões automaticamente. Se o sistema exibir um aviso sobre o editor, confirme a origem oficial do arquivo antes de continuar.

Esta versão inclui aplicativos de desktop. Não inclui um aplicativo nativo de iPhone/iPad.
