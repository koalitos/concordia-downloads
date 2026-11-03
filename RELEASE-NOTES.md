# Concórdia 1.0.8

- Login automático ao completar os seis dígitos do código de dois fatores, inclusive colando o código.
- Lives com som do sistema/aba quando disponível, inicialmente mutadas. Mute e volume são salvos por conta e por pessoa transmitindo.
- Captura do som no Windows e macOS pelo sistema; Linux desktop usa a saída PulseAudio/PipeWire com `parec`, sem ativar microfone.
- Correções na negociação de câmera e tela, fila de candidates ICE e recuperação automática de conexão. A interface oferece reconectar se a imagem não chegar.
- Seletor de captura com telas e janelas disponíveis e aba inicial correta.
- Nítida com resolução nativa e bitrate maior; ajustes reaplicados depois da negociação. Perfil Leve sem dupla redução de resolução.
- A própria tela/câmera deixa de aparecer na grade; as transmissões de outras pessoas continuam disponíveis.
- Atualizador verifica novas versões ao abrir e a cada 15 minutos, mostra progresso e permite reiniciar com confirmação. Verificação manual na bandeja e download manual para pacotes sem suporte.

Conexões entre redes com CGNAT/firewall dependem de um relay TURN configurado no servidor.

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
