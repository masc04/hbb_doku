---
title: Tasmota
has_children: true
parent: Smart-Home
nav_order: 1
---

## Tasmota

### Steckdose kalibrieren

#### Spannung

```VoltageSet [spannung]```

#### Stromstärke

Die Stromstärke wird in mA angegeben. Also ggf. umrechnen! __*1.5A sind 1500mA*__

```CurrentSet [milliampere]```

#### Leistung

Die Leistung kann mit Kommastelle (Achtung, Punkt als Komma) eingegeben werden.

Sie kann auch berechnet werden. Dazu `Leistung (W) = Spannung (V) * Strom (A)`, z.B. *233 * 1,5 = 349,5W*

```PowerSet [power]```


### Links

- [GitHub - Tasmota](https://tasmota.github.io/docs/Commands/)
