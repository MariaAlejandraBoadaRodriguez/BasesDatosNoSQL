# Champions League DB Management

Este proyecto consiste en el desarrollo de un modelo de base de datos en MongoDB para la gestión de un torneo deportivo, en este caso, la Champions League. El modelo permite administrar participantes (jugadores, entrenadores, árbitros), encuentros deportivos, resultados y una tabla de posiciones.

## Descripción de Colecciones

### Players (Jugadores)
- **Campos**:
  - `name`: Nombre del jugador.
  - `team_id`: ID del equipo.
  - `position`: Posición.
  - `stats`: Estadísticas (goles, asistencias, etc.).
  - `date_of_birth`: Fecha de nacimiento.
  - `nationality`: Nacionalidad.

### Coaches (Entrenadores)
- **Campos**:
  - `name`: Nombre del entrenador.
  - `team_id`: ID del equipo.
  - `experience`: Años de experiencia y logros.
  - `strategies`: Estrategias preferidas.

### Referees (Árbitros)
- **Campos**:
  - `name`: Nombre del árbitro.
  - `experience`: Experiencia.
  - `matches`: Lista de partidos arbitrados.
  - `ratings`: Evaluaciones de desempeño.

### Matches (Encuentros)
- **Campos**:
  - `date`: Fecha y hora.
  - `teams`: IDs de los equipos (local y visitante).
  - `referee_id`: ID del árbitro.
  - `location`: Lugar del partido.
  - `score`: Resultado.

### Teams (Equipos)
- **Campos**:
  - `name`: Nombre del equipo.
  - `coach_id`: ID del entrenador.
  - `players`: Lista de IDs de jugadores.
  - `matches_played`: Partidos jugados.
  - `wins`, `losses`, `draws`: Partidos ganados, perdidos y empatados.
  - `points`: Puntos totales.
  - `goal_difference`: Diferencia de goles.

## Enlace al Video
[Video Explicativo](....)

## Enlace al Repositorio
[Repositorio en GitHub](https://github.com/MariaAlejandraBoadaRodriguez/BasesDatosNoSQL.git)