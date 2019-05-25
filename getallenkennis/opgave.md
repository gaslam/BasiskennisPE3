# Zoned decimal Oefening

## Opgave

Maak van het volgende decimaal getal een zoned decimal.

**Gevraagd getal:** (845)<sub>10</sub>

## Uitwerking en oplossing

|     8     |     4     |       5      |
| :-------: | :-------: |    :-------: |
| 1111 1000 | 1111 0100 |    1111 0101 |
| 1111 1000 | 1111 0100 | (+)1100 0101 |
| 1111 1000 | 1111 0100 | (-)1101 0101 |

# Hamming-bit oefening

## Opgave

Controleer de hamming-bits:

**Hamming-bits:** 1110110

## Uitwerking

| H1 | H2 | D3 | H4 | D5 | D6 | D7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1   |1     |1     |0    |1     |1    |0     |

| Hamming-bit | Optelling   | Correctie |
| :-------------- | :-----------: | ---------: |
| H1                  | (1) 110 = 0 | Fout        |
| H2                  | (1) 110 = 0 | Fout        |
| H4                  | (0) 111 = 1 | Juist        |

# Oplossing

1110110 = 0010110
