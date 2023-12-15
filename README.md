# ADB CHEATSHEET

### Comandos Comuns
- devices                   # Visualizar dispositivos conectados
- start-server              # Iniciar servidor adb
- kill-server               # Parar servidor adb
- logcat                    # Visualizar logs
- install                   # Instalar um aplicativo (APK)
- uninstall                 # Desinstalar um aplicativo (APK)
- shell                     # Acessar terminal
---
### Outros Comandos
- help                      # Visualizar informações de ajuda
- version                   # Visualizar versão
- devices                   # Visualizar dispositivos conectados
- forward                   # Encaminhar porta
- reverse                   # Encaminhar porta reversa
- bugreport                 # Gerar relatório de erro adb
- install                   # Instalar um aplicativo (APK)
- uninstall                 # Desinstalar um aplicativo (APK)
- disconnect                # Desconectar dispositivo
- tcpip                     # Ouvir porta
- connect                   # Conectar dispositivo
- start-server              # Iniciar servidor adb
- kill-server               # Parar servidor adb
- logcat                    # Visualizar logs
- reboot                    # Reiniciar
- push                      # Enviar arquivos
- pull                      # Baixar arquivos
- root                      # Reiniciar adbd com permissões de root
- disable-verity            # Desativar dm-verity para modificar a partição /system
- remount                   # Remontar a partição /system com permissões de leitura e escrita
- get-serialno              # Obter número de série
- shell                     # Acessar terminal
- shell screencap           # Capturar tela
- shell screenrecord        # Gravar vídeo da tela
- shell pm list packages    # Listar pacotes de todos os aplicativos instalados
- shell pm list packages -s # Listar pacotes de aplicativos do sistema
- shell pm list packages -3 # Listar pacotes de aplicativos de terceiros
- shell pm clear            # Limpar dados e cache de um aplicativo
- shell am start -n         # Iniciar aplicativo
- shell am force-stop       # Parar aplicativo
- shell am force-stop       # Forçar parada de aplicativo
- shell wm size             # Visualizar resolução da tela
- shell wm density          # Visualizar densidade da tela
---
#### Referências
- [ADB Command-Line](https://developer.android.google.cn/studio/command-line/adb.html)

---
