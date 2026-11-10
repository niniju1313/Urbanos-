# Panel 1: Avenida Primera / Ronda del Sinú (Montería)

Biombo de biodiversidad y conectividad urbana. Este archivo sirve para retomar el trabajo en una sesión nueva.

## Estado

- Panel 1 ilustrado (PDF, 1501×838 pt).
- La revisión del contratista dice que la imagen no es realista, que parece una recreación de los años 60 y que se ve muy pobre de gente, de basura y de ambiente urbano.
- **Siguiente paso:** bocetar las correcciones con Gemini (desde la web, con la sesión de Chrome ya iniciada y el plan Pro) en 5 pasadas. La ilustradora repinta después los cambios con su propio trazo.

## Diagnóstico: por qué parece de los años 60

1. Casi no hay gente. La plaza y el sendero de la Ronda están vacíos.
2. Hay pocas motos. En Montería el tráfico real es de motos y mototaxis.
3. No hay basura en la calle, en la orilla, en el río ni en el suelo.
4. La paleta sepia y la textura de papel envejecen la imagen.
5. Falta ruido visual actual: avisos, señales, publicidad y desgaste.
6. Falta el **perezoso**, una de las especies más emblemáticas de la Ronda.
7. No hay fuente que confirme electrocuciones de aulladores en Montería; los casos documentados son de Panamá y Costa Rica. Lo verificado en Montería es un mono en los cables que causó un apagón.

## Fotos de referencia (orden de carga en Gemini)

| # | Foto | Qué tomar de ella |
|---|------|-------------------|
| 1 | Panel 1 (la ilustración) | La base a editar |
| 2 | Tráfico en la Calle 31 | Densidad de carros y motos, semáforo con brazo amarillo, señal de 30, "Motos a la derecha", placa verde de nomenclatura, valla negra y roja con QR, estación de bicis pública, costales de basura en la esquina, mangos sobre la calle |
| 3 | Busto en la Ronda | Postes de luz **turquesa**, pedestal con musgo y placa rota, valla del parque, adoquín, setos, cordyline roja |
| 4 | Orilla del Sinú con basura | Agua **café turbio**, **bolsas negras colgando de las ramas** (marcan la creciente), icopor, vasos, botellas, tapas y escombro mezclados con hojarasca |
| 5 | Ficus de la Ronda | Raíces aéreas, poste de concreto gris con afiches, kiosco azul de lata, palma de coco, guayacán rosado |
| 6 | Mangos | **Troncos pintados de blanco con cal**, kiosco de madera, banca, río al fondo |

Notas:
- En las fotos 3, 5 y 6 casi no hay gente. Para dar densidad sin inventar, ambienta la escena **al final de la tarde**.
- Las fotos 5 y 6 tienen decoración navideña. No la dibujes, salvo que quieras fechar la escena en diciembre.
- Paleta: cielo blanco grisáceo y nublado; verdes oscuros y saturados; acentos en turquesa, amarillo y rojo y negro.

## Reglas para usar los prompts

- Una pasada por vez. Cada pasada parte de la imagen que salió de la anterior.
- Si una pasada altera algo que no se pidió, se repite desde la imagen anterior en vez de corregir encima.
- En la publicidad se usan marcas inventadas, nunca reales.
- Se pega el **bloque fijo** y después el texto de la pasada.

## Bloque fijo (va al inicio de cada pasada)

```
Image 1 is my original hand-drawn illustration: a wide panoramic cross-section of
Avenida Primera and the Ronda del Sinú riverside park in Montería, Colombia, with the
Sinú river and a floating "planchón" ferry on the left, a large tree with a howler
monkey in the center, a street with colonial and modern buildings on the right, and an
underground soil section with roots and soil fauna along the bottom.
Images 2–6 are current reference photos of this exact location.

Edit Image 1 only in the zone described below. Keep the exact same composition, camera
angle, horizon line, and the positions of the main tree, the howler monkey, the birds,
the recycler with his cart, all buildings, the power poles and the underground soil
section, except where this pass says otherwise. Do not change framing or aspect ratio.

Push the rendering toward semi-realistic illustration: more accurate proportions,
believable perspective, realistic materials (worn concrete, rusted metal, wet mud,
plastic sheen), natural light and cast shadows, and real-world detail density, while
keeping the hand-drawn ink linework and colored-pencil texture of Image 1 so it still
reads as an illustration, not a photograph.
```

## Pasada 1: luz y paleta

```
Change: re-light the whole scene as a humid, overcast late afternoon in the Colombian
Caribbean, matching Images 3, 5 and 6. Replace the clean pale-blue sky with a bright,
hazy, whitish-grey cloudy sky and soft diffused light. Make the foliage deeper and more
saturated: dark mango and ficus greens with denser shadow under the canopies. Reduce
the warm sepia cast so the image reads as present-day, with slightly higher contrast.
Do not add or remove any object in this pass.
```

## Pasada 2: río y orilla (izquierda)

```
Change only the river and riverbank on the left. Paint the Sinú river water an opaque,
muddy café-con-leche brown with small ripples, as in Image 4. Along the bank, add
realistic litter mixed with dry brown leaves and broken concrete rubble: white
styrofoam food containers, plastic cups, plastic bottles, bottle caps and crumpled
black plastic bags. Add two black plastic bags snagged on low branches hanging over
the water, marking the last flood level. Add three or four people on the planchón deck,
seated and standing. Keep the planchón, the heron, the fish and the shoreline shape.
```

## Pasada 3: parque de la Ronda (centro)

```
Change only the park area between the river and the street. Repaint every park lamp
post as a slender turquoise-teal metal pole, as in Images 3 and 5. Paint the lower
trunks of the park trees white with lime wash, as in Image 6. Add weathering to the
statue pedestals: green moss stains and one cracked plaque, as in Image 3. Add a
small blue sheet-metal kiosk and a wooden kiosk, as in Images 5 and 6.
Add people in late-afternoon park life: two joggers on the path, a family with a child
sitting on a bench, a street vendor with a fruit and juice cart under an umbrella.
Add an overflowing green public trash bin by the path with three pigeons pecking at the
spilled waste, and a three-toed sloth hanging from a high branch of the main tree.
Keep the monkey, the squirrels, the iguana and the woodpecker exactly as drawn.
```

## Pasada 4: calle (derecha)

```
Change only the street on the right, matching the dense traffic of Image 2.
Fill the road with traffic: six to eight motorcycles, some carrying a passenger
(mototaxis), riders in helmets, two or three cars and a small delivery truck with a
colorful snack-brand wrap of invented, non-real brands. Add two motorcycles parked on
the sidewalk. Add a yellow traffic-light pole with a long yellow arm over the street.
Add street signs: a round red-bordered speed-limit sign reading "30" (EXACT), a small
blue sign reading "MOTOS A LA DERECHA" (EXACT), and a green street-name plate reading
"CALLE 30" (EXACT). Add a black and red digital billboard with an invented ad and a QR
code on a building. Make the power poles grey concrete with torn paper posters stuck on
them. At the street corner, pile three white woven sacks of garbage and flattened
cardboard. Add cracks and patched sections to the sidewalk tiles. Add four or five
pedestrians, including one person looking at a phone. Keep the recycler, the buildings,
the pigeons and the birds on the wires.
```

## Pasada 5: suelo

```
Change only the underground soil section at the bottom. Add a few pieces of buried
plastic among the roots and soil layers: a plastic bottle cap, a fragment of a plastic
bag tangled in the roots, and small plastic shards, drawn subtly in the same style.
Keep the earthworms, the beetle, the tunnels, the fungi and the roots exactly as drawn.
```

## Instrucciones para la sesión local de Claude Code

1. Usar **Claude in Chrome** sobre la sesión de Gemini que ya está abierta en el navegador de la usuaria. No se escriben credenciales.
2. En gemini.google.com, cargar las 6 imágenes en el orden de la tabla.
3. Pegar el bloque fijo y la pasada 1. Mostrar el resultado y esperar aprobación antes de seguir.
4. Seguir con las pasadas 2 a 5 en el mismo orden, descargando cada resultado en la carpeta del proyecto.

## Fuentes

- [BID: Montería Pasos Seguros (conflicto entre vendedores, peatones y ciclistas en la Av. Primera)](https://blogs.iadb.org/ciudades-sostenibles/es/monteria-pasos-seguros-fortaleciendo-de-forma-colaborativa-el-tejido-urbano-y-social-con-herramientas-del-urbanismo-tactico)
- [El Tiempo: restricciones de motos en Montería](https://www.eltiempo.com/colombia/otras-ciudades/en-monteria-un-ano-mas-sin-parrilleros-en-motos-los-dias-martes-y-jueves-681726)
- [El Universal: vertimientos al Sinú y saneamiento (CVS)](https://www.eluniversal.com.co/regional/cordoba/polemica-en-monteria-por-denuncia-de-vertimiento-de-excrementos-al-rio-sinu-NH4854971)
- [Policía: jornada "Sinú Limpio"](https://www.policia.gov.co/index.php/noticia/jornada-aseo-embellecimiento-sinu-limpio-en-ronda-del-sinu)
- [106 árboles retirados de la Ronda (2025)](https://ground.news/article/106-trees-removed-from-the-sinu-round-due-to-plant-protection-problems)
- [El Heraldo: macrofiguras en la Ronda (2025)](https://www.elheraldo.co/cordoba/2025/05/21/la-ronda-del-sinu-se-llenara-de-arte-y-tradicion-durante-la-feria-nacional-de-la-ganaderia/)
- [Colombia Reports: mono en cables deja sin luz el centro](https://colombiareports.com/monkey-leaves-monteria-without-electricity/amp)
- [colombia.travel: fauna de la Ronda](https://colombia.travel/es/monteria)
