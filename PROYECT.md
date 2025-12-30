# PROJECT

## Pitch
Plataformas 2D narrativo y atmosférico donde el jugador recorre una mazmorra
que representa un estado mental de apatía y duelo, enfrentándose a enemigos
lentos y pesados mientras aprende a avanzar pese a la desidia.

## Core Loop (3 pasos)
Explorar → superar obstáculos simples → combatir enemigos simbólicos
(apatía, duda) → avanzar a la siguiente zona.

## Pilares (3)
1. Atmósfera y simbolismo por encima de mecánicas complejas.
2. Jugabilidad sencilla, pesada y deliberada.
3. Progreso narrativo integrado en el entorno, no en cinemáticas largas.

## Plataforma
PC (Windows)

## Motor
Unity 2D

## Resolución / Escala
16:9 · 1920x1080  
PPU definido para personaje visible y animaciones simples.

## Controles
- Movimiento lateral
- Salto
- Ataque básico
- Interactuar (tecla única)

## Estilo visual (3 reglas)
1. Mazmorra / caverna en ruinas, tonos apagados, bajo contraste.
2. Fondo vacío o abstracto (nunca recargado).
3. Entornos modulares por “slices” que se puedan unir.

## Restricciones (3)
1. No cinemáticas complejas: todo in-engine y jugable.
2. Sin mecánicas de agua, gas o estados avanzados en el Capítulo 1.
3. Puzzles simples de interacción (palanca, recoger objeto, hablar).

## Capítulo 1 – Estructura Simplificada

### Inicio
- Imagen estática + música breve (sin cinemática).
- Texto narrado o en pantalla (opcional).
- Control pasa rápido al jugador.

### Zona 1: El Corredor de la Desidia
- Mazmorra tipo canal empedrado.
- Tutorial encubierto:
  - Movimiento
  - Salto
  - Ataque básico
- Encuentro con NPC (Duende):
  - Diálogo corto.
  - Introduce el concepto del lugar (apatía).
  - Sin decisiones complejas.

### Zona 2: Caminos sin recompensa
- Varias bifurcaciones.
- Algunas no llevan a nada (mensaje simbólico).
- Introducción de enemigos lentos tipo “piñata”.
- El arma básica se obtiene aquí (navaja o palo).

### Zona 3: Palanca de Progreso
- El jugador encuentra una manivela.
- Activarla desbloquea el camino principal.
- Primer punto de guardado simple.

### Zona 4: Boss 1 – Masa de Lodo
- Boss lento, fácil.
- Ataques simples.
- Más resistencia que daño.
- Simboliza el peso de la apatía.

### Zona 5: Sala del Sosiego
- Estatua / mausoleo.
- NPC Ansa aparece automáticamente (SIN puzzle musical).
- Función:
  - Guardar.
  - Recuperar vida.
  - Diálogo emocional.
- Ansa se convierte en guía narrativo a partir de aquí.

## NPCs Clave
- Duende: representa la duda y la burla interna.
- Ansa: espíritu materno, guía emocional y narrativa.

## Enemigos
- Lentos, resistentes.
- Poco daño.
- Su función es cansar al jugador, no matarlo rápido.

## Hito Actual
Vertical Slice del Capítulo 1 completo y jugable:
Inicio → Duende → combate → palanca → boss → Ansa.

## Bloqueo Actual
Ajustar historia potente sin sobrecargar mecánicas ni cinemáticas.
