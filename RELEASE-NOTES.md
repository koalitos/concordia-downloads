# Concórdia 1.0.11

- Primeiro suporte à troca automática entre o cliente de League of Legends / TFT e a partida, no desktop Windows e macOS.
- Selecione a janela do cliente ou da partida e marque “Acompanhar launcher e partida automaticamente”. A opção começa desmarcada.
- A live acompanha a partida, volta ao cliente quando ela termina e mostra uma tela de espera se nenhuma das janelas estiver disponível, sem exigir que os espectadores voltem a assistir.
- Quando selecionado, o som isolado acompanha o aplicativo. O nome personalizado da live é preservado, com indicação de Cliente, Partida ou espera.
- A captura permanece limitada à mesma instalação do jogo; outros launchers e jogos ainda usam seleção manual. No Linux e no navegador, a seleção continua manual.

Este suporte inicial passou por testes automatizados de detecção, troca de vídeo, áudio e encerramento. A validação com uma partida real no Windows/macOS ainda está pendente. Se a tela cheia exclusiva não produzir imagem, use janela ou janela sem bordas.

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
