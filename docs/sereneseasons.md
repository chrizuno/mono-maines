# Serene Seasons

## seasons.toml

### Duração das Subestações
Cada subestação foi configurada para durar **15 dias**, resultando em:

- 3 subestações por estação
- 45 dias por estação
- Um ano sendo 180 dias

```
sub_season_duration = 15
```
### Ajuste de Derretimento de Neve
Os valores de melt_percent foram ajustados para evitar o acúmulo infinito de neve causado pelo mod Snow! Real Magic

```
[[season_properties]]
	season = "EARLY_SPRING"
	melt_percent = 25.0

[[season_properties]]
	season = "MID_SPRING"
	melt_percent = 30.0

[[season_properties]]
	season = "LATE_SPRING"
	melt_percent = 35.0

[[season_properties]]
	season = "EARLY_SUMMER"
	melt_percent = 40.0

[[season_properties]]
	season = "MID_SUMMER"
	melt_percent = 55.0

[[season_properties]]
	season = "LATE_SUMMER"
	melt_percent = 40.0

[[season_properties]]
	season = "EARLY_AUTUMN"
	melt_percent = 18.0

[[season_properties]]
	season = "MID_AUTUMN"
	melt_percent = 10.0

[[season_properties]]
	season = "LATE_AUTUMN"
	melt_percent = 8.0
```

## fertility.toml

### Crescimento das Plantações
Muda o comportamento das plantações fora da estação correta de cultivo de `0` para `1`.

- 0: Plantas crescem devagar
- 1: Plantas não crescem

```
[general]
	out_of_season_crop_behavior = 1
```
