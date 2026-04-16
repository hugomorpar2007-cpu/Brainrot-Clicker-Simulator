# Brainrot-Clicker-Simulator
1. Títol provisional del joc
Brainrot Clicker Simulator

2. Tipus de microvideojoc escollit
Simulator / Clicker (Roblox)

3. Objectiu del joc
L'objectiu és colpejar un personatge "Brainrot" per guanyar diners, millorar la força del jugador i acumular "Rebirths" per desbloquejar noves zones i progressar infinitament.

4. Rol del jugador
Què controla: Un avatar de Roblox en tercera persona.

Què pot fer: Fer clic a la pantalla per colpejar, interactuar amb botigues (GUIs) per comprar millores i travessar portals a noves zones.

5. Regles bàsiques
Cada clic al Brainrot atorga una quantitat de diners proporcional a la força actual.

Els diners es poden gastar en una botiga per augmentar la força permanentment.

En arribar a un límit de força i diners, el jugador pot fer un "Rebirth".

6. Condicions de victòria i derrota
Victòria: No hi ha una victòria final definitiva (joc incremental), però l'èxit es defineix per desbloquejar totes les zones disponibles.

Derrota: No hi ha derrota per mort, el repte és l'eficiència en la gestió del temps i els recursos.

7. Bucle principal del joc
Acció: El jugador fa clic al Brainrot.

Recompensa: Guanya diners.

Millora: Gasta diners en força per guanyar més diners per clic.

Hito: Fa Rebirth per multiplicar el guany i obrir noves zones.

8. Repte principal i dificultat
Repte: L'augment exponencial dels costos de les millores i els Rebirths.

Dificultat: Molt baixa tècnicament (accessible), centrada en la satisfacció del progrés visual i numèric.

9. Limitacions explícites
No hi haurà sistema de combat entre jugadors (PvP).

No hi haurà mascotes (pets) amb sistema d'inventari complex.

El joc només tindrà 2 o 3 zones com a màxim per a la versió inicial.

No hi haurà animacions personalitzades avançades (s'usaran les de Roblox).

10. Riscos tècnics
DataStore: Risc que les dades de diners i Rebirths no es guardin correctament en sortir del servidor.

Exploiting: Risc que jugadors usin auto-clickers simples si no hi ha un mínim de validació al servidor.

UI Dinàmica: Configurar els menús de botiga perquè funcionin correctament en mòbils i PC.

11. Exploració amb IA
Prompt 1: "Dona'm un script senzill de Roblox per a un sistema de Clicker on al fer clic a un objecte anomenat 'Brainrot' es sumin diners a una variable de Leaderstats."

Resposta resumida: La IA ha proporcionat un script de ClickDetector que interactua amb el DataStore i les Leaderstats.

Prompt 2: "Com puc fer un sistema de zones a Roblox que només deixi passar al jugador si té un valor de Rebirths determinat?"

Resposta resumida: Ús de TouchEvents en una paret invisible que comprova el valor de la carpeta leaderstats del jugador.

12. Proposta final escollida
Un joc de colpejar un NPC estàtic (Brainrot) amb un sistema de botiga de força simple, un botó de Rebirth i dues zones diferenciades per colors/textures.

13. Justificació de viabilitat
Roblox Studio permet crear sistemes de punts i zones molt ràpidament amb scripts de Lua senzills. Al no incloure sistemes complexos com inventaris de mascotes o animacions, el "core loop" es pot programar en poques hores.

14. Mini pla de treball
Fase 1 (1.5h): Disseny i documentació (Aquesta fase).

Fase 2 (3h): Creació de Leaderstats (Diners/Força) i script de clic al Brainrot.

Fase 3 (3h): Creació de la botiga (GUI) i el sistema de Rebirth.

Fase 4 (2.5h): Disseny de zones, portes de bloqueig per Rebirth i estètica final.

15. Eines previstes i justificació
Roblox Studio: Motor de joc que ja inclou el servidor i la base de dades.

Luau (Llenguatge): Necessari per programar la lògica a Roblox.

Roblox Toolbox: Per a models ambientals bàsics (estalvi de temps en modelatge).
