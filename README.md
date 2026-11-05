# Edificio PlantUML — Actividad Análisis de Sistemas

Repositorio de versionamiento de la actividad "Edificio PlantUML", aplicada al proyecto **RPG Manager**.

**Autor:** Juan Esteban Castellanos Forero
**Código:** 20232578053
**Universidad Distrital Francisco José de Caldas**

## Estructura

Cada carpeta corresponde a un piso del edificio. Cada diagrama se versiona como un archivo `.puml` individual, en su propio commit, más la imagen renderizada (`.png` o `.svg`).

```
lobby/    -> fundamentos de PlantUML
piso1/    -> requisitos (casos de uso y actividades)
piso2/    -> estructura (clases, objetos y paquetes)
piso3/    -> interacción (secuencia y estados)
piso4/    -> arquitectura y datos (componentes, despliegue, entidad-relación, C4)
azotea/   -> reto integrador
```

Cada ejemplo del edificio tiene además una variación propia aplicada al módulo del proyecto **RPG Manager** (sistema de texto para crear y gestionar personajes — Guerrero, Mago, Arquero — con combate, inventario y guardado de estado).

## Convención de commits

```
[piso-N] nombre del diagrama
```

Ejemplo: `[piso-2] diagrama de clases Personaje`

## Trabajo escrito

El registro completo de los 21 retos (sala, pregunta, respuesta explicada y código PlantUML a mano con su variación) se entrega aparte en PDF escaneado, según lo indicado en la actividad.
