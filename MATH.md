# Fonctions mathématiques

## Ease in out

```
1 - 1 / ( 1 + exp(11 * x - 5.5))
```

## Ease in

```
exp(5.5 * x - 5.5)
```

## Ease out

```
1 - 1 / exp(5.5 * x)
```

## Bounce out

```
exp(11 * min(0.5, max(0, x)) - 5.5) + sin(x * 62.9) * floor((x * 2) % 2) * (1 - 4 * pow(0.5 - x, 2)) / 6
```
