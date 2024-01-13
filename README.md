### Klipper-Artillery-X1
## Fichier configuration Sidewinder X1

# Slicer
Pour une expérience optimal de klipper je vous conseille [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer/releases)

# gcode de démarrage dans OrcaSlicer
```
START_PRINT BED_TEMP=[bed_temperature_initial_layer_single] EXTRUDER_TEMP=[nozzle_temperature_initial_layer]
```
# gcode de fin dans OrcaSlicer
```
END_PRINT
```

Pensez bien à personnaliser le printer.cfg au minimum pour le type de sonde et l'adresse USB de l'imprimante.

Ainsi que le Macro/PIS/PIS.cfg pour l'adresse USB (si vous avez un portable input shaper 😉)

12/01/2024 : Ajout du support pilote TMC2204 (pour le moment non testé)

13/01/2024 : Ajout support Z End Stop
