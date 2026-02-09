# Ice & Fire

## O que esperar:

- Geração de dragões e estruturas perigosas beeeem reduzida
- Dragões mais resistentes
- Mobs mais raros em geral, mas um pouco mais fortes

## Dragões

### Geração

Valores  ajustados para **reduzir a frequência geral de dragões e estruturas**

```
[Generation.Dragon]
"Generate Dragon Skeleton Chance" = 900   # original: 300
"Generate Dragon Cave Chance" = 500       # original: 180
"Generate Dragon Roost Chance" = 1200     # original: 360

```

### Atributos dos Dragões

Os dragões foram configurados para serem **mais resistentes** e seus ovos **demorarem mais** para chocar

```

[Dragons.Attributes]
"Dragon Egg Hatch Time" = 336000           # original: 7200
"Dragon Flap Noise Distance" = 8           # original: 4
"Dragon Health" = 750.0                    # original: 500.0

```

### Comportamento dos Dragões

Dragões agora voam mais alto e detectam ouro a maiores distâncias.

```

[Dragons.Behaviour]
"Max Dragon Flight Height" = 300            # original: 256
"Dragon Gold Search Length" = 60            # original: 30

```

---

## Mobs

### Pixies
Vilas maiores e mais raros.

```
[Mobs.Pixies]
"Spawn Pixies Chance" = 90                  # original: 60
"Pixie Village Size" = 10                   # original: 5

```
### Cyclops
Cyclopes mais raros e levemente mais resistentes.

```
[Mobs.Cyclops]
"Spawn Cyclops Cave Chance" = 400           # original: 100
"Cyclops Max Health" = 180.0                # original: 150.0
```

### Stymphalian Birds
Redução na taxa de drop de penas.

```
[Mobs.Stymphalians]
"Stymphalian Bird Feather Drop Chance" = 15 # original: 25
```

### Sea Serpents
Sea serpents ficaram **bem mais raros**, porém mais resistentes.

```
[Mobs.SeaSerpents]
"Spawn Sea Serpent Chance" = 750            # original: 250
"Sea Serpent Base Health" = 30.0            # original: 20.0
```

