## Ukoly na flowcharty
Otevřete [app.diagrams.net](https://app.diagrams.net) a navrhněte vývojové diagramy pro následující programy.
Algorimus je vždy v pseudokodu a pythonu.

### Program 1
```pseudo
i = 1
opakuj 10 krat:
    vypis i
    zvys i o 1
```
```python
i = 1
while i < 10:
    print(i)
    i += 1
```
### Program 2`
```pseudo
i = 0
opakuj 11 krat:
    pokud i delitelne 2:
        vypis i
    zvys i o 1
```
```python
i = 0
while i <= 10:
    if i % 2 == 0:
        print(i)
    i += 1
    
```

### Program 3
```pseudo
i = 0
smer = 0

opakuj 360 krát:
    self.forward(100)
    pen.down()
    pen.up()
    self.backwards()
    smer += 1
    i += 1
```

### Program 4
![scratch program](ScreenshotScratch.png)

### Program 5
```pseudo
i = 420
opakuj dokud i neni 1:
    vypis i
    pokud i delitelne 2:
        i = i/2
    jinak:
        i = 3*i + 1
vypis i
```
```python
i = 420

while i != 1:
    print(i)
    if i % 2 == 0:
        i /= 2
    else:
        i = 3*i + 1
print(i)
```