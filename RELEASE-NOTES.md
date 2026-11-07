# Concórdia 1.0.12

- Novo botão “Ampliar na janela” para aproveitar a altura disponível da sala sem entrar em tela cheia. As outras transmissões ficam em miniaturas.
- Som e volume são preservados ao alternar entre grade e destaque.
- O nome da fonte/jogo compartilhado aparece para os espectadores nos cartões, no vídeo e em tela cheia. Renomeações são atualizadas para todos, inclusive quem entra depois.
- Quando o sistema não informa o nome do jogo, quem transmite pode renomear a live.
- Busca de transmissões por pessoa ou nome da fonte/jogo e ajustes dos controles em janelas estreitas.

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
