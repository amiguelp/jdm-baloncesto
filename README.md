# 🏀 JDM Baloncesto

App para Android que sigue los partidos de un equipo de baloncesto de los **Juegos Deportivos
Municipales (JDM) de Madrid**. Es una app personal hecha por un padre: no es oficial ni del
Ayuntamiento ni de la Federación de Baloncesto de Madrid.

**[⬇️ Descargar la última versión](https://github.com/amiguelp/jdm-baloncesto/releases/latest)**:
en esa página, en *Assets*, el archivo `jdm-baloncesto-vX.Y.Z.apk`.

## Qué hace

- **Próximos partidos y resultados** del equipo: fecha, hora, pabellón y botón «Cómo llegar».
- **Avisos** cuando cambia la hora o el pabellón de un partido, cuando se anula o cuando hay resultado,
  y un resumen los viernes de los partidos del fin de semana.
- **Marcador en directo** durante el partido: tanteo, cuarto, tiempo, jugadas, puntos de cada jugador,
  faltas (con aviso de jugadores con 4 o 5 faltas y de bonus) y tiros libres.
- **Retransmisión** del partido y grabación, cuando el Ayuntamiento lo emite (pabellón de Las Cruces).
- **🎙️ Crónica** de cada partido poco después de terminar: para leer, escuchar con la voz del móvil y
  compartir por WhatsApp.
- **Clasificación** al día (con los resultados de la Federación) y la oficial del Ayuntamiento.
- **Calendario** opcional: puede crear un evento por partido en un calendario del móvil.
- **Se actualiza sola**: cuando hay versión nueva, la app lo avisa y se instala con dos toques.

| Inicio | Marcador en directo | Crónica | Clasificación |
|---|---|---|---|
| <img src="capturas/2_inicio.png" width="200"> | <img src="capturas/12_marcador_directo.png" width="200"> | <img src="capturas/11_cronica.png" width="200"> | <img src="capturas/3_clasificacion.png" width="200"> |

## Cómo instalarla

La app no está en Google Play: se instala con el archivo APK.

1. En el móvil, abre el enlace **[Descargar la última versión](https://github.com/amiguelp/jdm-baloncesto/releases/latest)**
   y toca `jdm-baloncesto-vX.Y.Z.apk` en *Assets*.
2. Abre el archivo descargado (desde la notificación de descarga o desde *Archivos → Descargas*).
3. Si Android pide permiso para **instalar aplicaciones desconocidas** desde el navegador o desde
   *Archivos*, actívalo y vuelve atrás.
4. Si **Google Play Protect** avisa de que es una app desconocida, toca **Más detalles → Instalar de
   todos modos**. Sale porque la app no viene de Google Play y la usan pocas personas.
5. Abre la app y sigue los pasos de bienvenida.

**Móviles con Family Link (control parental):** el padre o la madre tiene que permitir la instalación
desde la app Family Link de su móvil (*Controles → Apps*), o instalarla desde el móvil del menor con
el permiso del adulto.

## El calendario

Si ya estás suscrito al **calendario compartido del equipo** (te lo habrá pasado otro padre por enlace),
no necesitas que la app escriba en ningún calendario: en la bienvenida, o en *Ajustes → Calendario*,
marca **«No usar calendario»**. Seguirás recibiendo los avisos, el marcador y las crónicas.

Si la app escribe en un calendario, que sea solo **un móvil por calendario**: si dos móviles con la app
escriben en el mismo calendario compartido, se pisan los eventos.

## Batería

Para que los avisos lleguen a su hora, en *Ajustes → Batería* de la app toca **«Permitir en segundo plano»**
(o en los ajustes del móvil: *Aplicaciones → JDM Baloncesto → Batería → Sin restricciones*). La app solo
se despierta unos segundos al día; no gasta batería apreciable.

## Privacidad

- La app **no tiene cuentas ni recoge datos**: no envía nada sobre ti ni sobre tu móvil a nadie.
- Lee datos públicos: el calendario y la clasificación de los JDM (datos abiertos del Ayuntamiento de
  Madrid), el marcador y las estadísticas de la Federación de Baloncesto de Madrid (los mismos que la app
  oficial «Afición FBM») y las retransmisiones del portal del Ayuntamiento.
- Los **nombres de los jugadores** vienen de la Federación y solo se ven dentro de la app.
- Las **crónicas** se escriben con inteligencia artificial a partir de las estadísticas y se publican
  en este repositorio **sin nombres**, solo con dorsales; cada móvil pone los nombres al mostrarla.
- Si das permiso de calendario, la app solo crea y cambia los eventos que crea ella.

## Preguntas frecuentes

**¿Qué equipo sigue?** El que elijas en *Ajustes → Equipo* (por defecto, BJC cadete masculino de Latina).
Las crónicas solo se escriben para los equipos que tiene configurados el autor: si quieres la de otro
equipo, pídeselo.

**No me llega la crónica.** Se escribe en cuanto la Federación da el partido por terminado y la app la
busca cada 10 minutos después del partido. En *Resultados*, el botón 🎙️ del partido y *Buscar ahora*.

**La clasificación «Oficial» no tiene el último partido.** El Ayuntamiento la publica una vez por semana.
Usa «Al día (FBM)».

**¿Cómo la desinstalo?** Como cualquier app. Si escribía en un calendario, antes puedes usar
*Ajustes → Calendario → Borrar calendario y regenerar* o borrar el calendario.

---

Las versiones nuevas y las crónicas se generan automáticamente con GitHub Actions en este repositorio.
El código de la app está en un repositorio privado.
