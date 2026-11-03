# Concórdia 1.0.10

- Áudio isolado do aplicativo escolhido, sem capturar a saída geral do computador. Discord, Concórdia e outros apps de chamada conhecidos são bloqueados como fontes de som.
- Janelas compartilham apenas a saída do aplicativo correspondente, quando disponível; a tela inteira começa sem som e permite escolher um único aplicativo.
- Para isolar abas de navegadores, use a captura de aba com áudio no navegador. Janelas do mesmo aplicativo podem compartilhar a mesma saída de som.
- No Linux/Wayland, confirme a saída de áudio correspondente à fonte escolhida no seletor do sistema.
- Novo aviso de live com nome da fonte, aplicativo de áudio, sala e opção de renomear.
- Recuperação de sessão e mensagens de login corrigidas.

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
