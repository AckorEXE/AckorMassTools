# AckorMassTools
Ackor Mass Tools es un plugin para TeamSpeak 3 que proporciona comandos administrativos
para mover, expulsar y enviar poke masivo a los usuarios de un servidor.
El plugin funciona mediante comandos de chat y no requiere interfaz gráfica.


## 🔧 Requisitos

- TeamSpeak 3 Client
- API 26 o superior (TeamSpeak 3.5.x o superior)
- Microsoft Visual C++ Redistributable 2015–2022 (x64) https://aka.ms/vc14/vc_redist.x64.exe

---

## 📥 Instalación

1. Descarga el archivo `AckorMassTools.dll`
2. Copia el archivo en la carpeta de plugins de TeamSpeak
3. ¿Cómo llegar a esta ruta?, presiona Windows + R e intruduce:
4. `%appdata%\TS3Client\plugins`
5. Reinicia TeamSpeak
6. Activa el plugin en:
   **Tools → Options → Addons → Plugins**
---

## 🚀 Comandos
Mass Move
- !mm - Mueve a todos a tu canal actual.
- !mm <id|nombre> - Mueve a todos a un canal específico por ID o nombre.
  - Ejemplo: !mm Canal 1
- !ma - Mueve solo AFK/muteados a tu canal.
- !ma <id|nombre>  -> Mueve solo AFK/muteados a otro canal.
  -  Ejemplo: !ma AFK

Mass Poke
- !mp <mensaje> - Envía un poke masivo a todos los usuarios conectados.
  - Ejemplo: !mp Reunion en 5 minutos

Mass Kick
- !mk - Kick a todos los usuarios del canal actual.
- !mk <id|nombre> - Kick masivo por canal específico.
  - Ejemplo: !mk AFK
- !mka - Kick masivo solo a AFK/muteados.

Help
- !help - Muestra la lista de comandos disponibles dentro del cliente.
---

## ⚠️ Notas importantes

- El plugin no fuerza permisos.
- *Si no tienes permisos suficientes, el propio servidor TeamSpeak rechazará la acción*.
- El plugin solo responde a comandos escritos por el propio usuario.
---

