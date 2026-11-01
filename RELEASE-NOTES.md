## Concórdia 1.0.6

- Fundo preto e superfícies neutras no navegador e no aplicativo instalado. O desktop respeita o tema do site, sem injetar o estilo azul antigo.
- Duplo clique no nome da sala entra diretamente. Enter oferece a mesma ação pelo teclado.
- Entrar novamente na sala atual mantém a câmera e a tela ativas. Ao trocar de sala, a captura anterior é encerrada e a nova sala começa com a captura desligada.
- Menu do botão direito com avatar, identificação e opções separadas para sua conta, transmissões e moderação.
- No seu menu: editar perfil, ajustar tela e câmera, iniciar/parar capturas e sair da sala.
- No menu de outra pessoa: ver perfil, assistir/parar de assistir tela e ações de moderação conforme seu cargo. Remover do espaço pede confirmação dentro do aplicativo.
- Botão direito também nos vídeos; menus acessíveis por teclado e posicionados dentro da tela.

### Instalação

Windows recebe a atualização pelo aplicativo instalado. No Mac, instalações sem assinatura Apple precisam baixar o DMG e substituir o app em Aplicativos; o login é preservado. Os pacotes Mac incluem Apple Silicon e Intel.

Para compartilhar no Mac, autorize o Concórdia em Ajustes do Sistema → Privacidade e Segurança → Gravação de Tela. Pacotes sem certificado podem exigir liberação em Privacidade e Segurança → Abrir Mesmo Assim. Se continuar bloqueado após mover para Aplicativos:

```
xattr -dr com.apple.quarantine /Applications/Concordia.app
```
