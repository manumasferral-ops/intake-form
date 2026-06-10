# V1/V2 accident description examples

Reference pairs from the staff's Claude chat ("i want to use chat for the acc…",
https://claude.ai/chat/aeadbfd1-fed6-4f31-a7f2-cf9228e1d073). These define the target
style for the in-form converter (`v12Convert` in `form.html`). **V1 = at-fault vehicle,
V2 = our client.** One sentence, past tense, factual, no names.

Use these to tune `v12Convert` patterns in future passes. When the converter misses a
pattern the staff uses often, add it here and extend the rules.

| Spanish input | English output |
|---|---|
| estaba parado en un semaforo y v1 lo impacta por atras | V2 was stopped at a red light when V1 rear-ended V2. |
| V2 estaba parado y V1 lo impacta por atrás | V2 was stopped when V1 rear-ended V2. |
| Esperando la luz y v1 lo impacta por atrás | V2 was waiting at a red light when V1 rear-ended V2. |
| v2 estaba parada esperando que la luz cambie a verde, v1 lo impacta por atras | V2 was stopped waiting for the light to turn green when V1 rear-ended V2. |
| la luz se puso en verde y nuestro cliente empieza a avanzar y v1 lo impacta por atras | V2 proceeded forward on a green light when V1 rear-ended V2. |
| v2 estaba esperando que un peaton cruzara para poder hacer derecha, v1 lo impacta por la parte de atras | V2 was stopped waiting for a pedestrian to cross before making a right turn when V1 rear-ended V2. |
| v2 estaba en una señal yield y estaba completamente parado y v1 lo impacta por atras | V2 was completely stopped at a yield sign when V1 rear-ended V2. |
| Iba por su vía, había solamente una vía y v1 impacta a V2 por la parte de atras | V2 was traveling in a single lane road when V1 rear-ended V2. |
| V2 iba por vía y v1 lo impacta por atrás | V2 was traveling in his lane when V1 rear-ended V2. |
| habia mucho trafico, v2 estaba en movimiento y v1 lo impacta por la parte de atras | V2 was moving in heavy traffic when V1 rear-ended V2. |
| v2 iba por su via y empezo a bajar la velocidad y v1 lo impacta por atras | V2 was traveling in his lane and began slowing down when V1 rear-ended V2. |
| Saliendo de la autopista estaba haciendo una derecha, lo chocaron por detrás | V2 was exiting the highway making a right turn when V1 rear-ended V2. |
| v2 estaba haciendo una derecha para entrar a un shopping, v1 lo impacta por atras | V2 was making a right turn to enter a shopping center when V1 rear-ended V2. |
| Va por su vía, otro auto se salta el semáforo y lo choca por el lado del copiloto. | V2 was traveling in his lane when V1 ran a red light and impacted the passenger side of V2's vehicle. |
| Iba pasando su semáforo en verde cuando otro conductor se salta la luz en rojo para el y la impacta por el costado del conductor | V2 was traveling through a green light when V1 ran a red light and impacted the driver side of V2's vehicle. |
| No hizo un stop y choca a otro vehiculo | V1 failed to stop and impacted V2's vehicle. |
| un auto se salta su stop y la impacta por las puertas del pasajero | V1 ran a stop sign and impacted the passenger side doors of V2's vehicle. |
| Va por su vía, el otro vehículo no se detiene en su stop, se atraviesa en la vía y lo choca en el bumper de adelante | V2 was traveling in her lane when V1 failed to stop at a stop sign, crossed into V2's path, and impacted the front bumper of V2's vehicle. |
| nuestro cliente no hizo un stop y otro vehículo la impacta | V2 failed to stop and V1 impacted V2's vehicle. |
| Un vehiculo invadio su canal y lo choca por la parte del conductor | V1 invaded V2's lane and impacted the driver side of V2's vehicle. |
| iba por su via cuando un carro invade su canal y choca a nuestro cliente en la parte del chofer | V1 invaded V2's lane and impacted the driver side of V2's vehicle. |
| Cliente iba en su via y culpable le obstruyó la vía al intentar cambiar de carril y le impactó en puerta trasera del auto. | V1 attempted to change lanes, obstructing V2's path, and impacted the rear door of V2's vehicle. |
| V2 iba por su vía, cuando v1 estaba intentando hacer una izquierda y impacta a v2 en la parte derecha del carro | V2 was traveling in his lane when V1 attempted to make a left turn and impacted the right side of V2's vehicle. |
| Un carro intentó hacer un giro a la derecha desde la linea del medio y los chocó por el bumper delantero. | V1 attempted to make a right turn from the middle lane and impacted V2's front bumper. |
| v2 estaba saliendo de wawa cuando v1 haciendo una derecha lo impacta en la parte del conductor | V2 was exiting a Wawa when V1, making a right turn, impacted the driver side of V2's vehicle. |
| un vehiculo que salía de un centro comercial le invdió el carril y lo chocó por delante | V1 was exiting a shopping center, invaded V2's lane, and impacted V2's vehicle from the front. |
| v2 estaba parqueado y v1 no calculo bien y impacto a v2 por la parte de atras | V2 was parked when V1 misjudged the space and impacted the rear of V2's vehicle. |
| Estaba estacionado en un Walmart cuando una conductora dio un cruce indevido a la derecha y no lo ve y lo choca en la parte de adelante | V2 was parked at a Walmart when V1 made an improper right turn, failed to see V2, and impacted the front of V2's vehicle. |
| Estaba en un parking lot cuando otro vehículo comenzó a retroceder a gran velocidad y le llegó por la puerta del conductor | V2 was in a parking lot when V1 reversed at high speed and impacted the driver side door of V2's vehicle. |
| Iba manejando y la chica del otro vehículo iba con el teléfono en la mano. | V1 was driving while distracted on the phone and gradually drifted toward V2's vehicle, ultimately impacting it. |
| El cliente estaba en la vía esperando para doblar a la derecha y fue impactado por detrás por un conductor que venía con su teléfono. | V2 was stopped in the lane waiting to make a right turn when V1, driving while on the phone, rear-ended V2. |
| v2 estaba reduciendo la velocidad porque habian unos bumps adelante de el, v1 estaba distraido y impacto a v2 por la parte de atras | V2 was slowing down due to speed bumps ahead when V1, distracted, rear-ended V2. |
| Va por su vía, el vehículo que viene delante de él frena de repente y él lo choca por detrás | V2 was traveling in his lane when the vehicle ahead braked suddenly, causing V2 to rear-end V1. |
| el vehiculo de adelante freno repentinamente, nuestro cliente freno a tiempo pero v1 impacto a nuestro cliente por atras | The vehicle ahead braked suddenly and V2 stopped in time, but V1 rear-ended V2 from behind. |
| v3 estaba detenida, v1 impacta a v2 en la parte de atras causando que v2 impactara a v3 | V1 rear-ended V2, causing V2 to be pushed forward and rear-end V3, who was stopped ahead. |
| Detenido en el semáforo, chocan al carro que está detrás de él y este carro lo choca | V2 was stopped at a red light when a vehicle behind V2 was rear-ended and pushed forward, impacting V2. |
| iba en un uber de pasajero cuando un camion que iba adelante de ellos dio marcha atras y los choca por la parte de adelante | V2 was a passenger in an Uber when a truck ahead reversed and impacted the front of their vehicle. |
| v1 estaba rebasando a v2 en una zona que no podia, y impacta a v2 en la puerta del conductor | V1 was passing V2 in a no-passing zone and impacted the driver side door of V2's vehicle. |
| v2 iba por su via en un scooter cuando v1 le invade el carril causando que v2 lo impactara por la parte de adelante | V2 was traveling in his lane on a scooter when V1 invaded V2's lane, causing V2 to impact the front of V1's vehicle. |

## Style rules

- One sentence (two max for chain collisions), past tense, no client names.
- Default roles: client = V2, at-fault = V1; flip only when the note says the client caused it.
- "lo impacta por atrás / choca por detrás" → "rear-ended".
- Sides: conductor/chofer → driver side · copiloto/pasajero → passenger side · adelante/bumper delantero → front.
- Corrections from staff ("the other way around", "switch v1 for v2") flip the roles in the previous sentence.
