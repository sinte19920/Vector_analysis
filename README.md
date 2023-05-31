# Vector_analysis

# Eksperimentiniai Vector tyrimai

Atlikti trys tyrimai su nauja vector kalse.

1. main_speed.cpp: kodas, skirtas parodyti spartos palyginimus tarp vector class ir std::vector.
2. funciontality.cpp: kodas, skirtas parodyti, kad Vektorius ir std::vector veikia taip pat
3. source (aplankas): čia yra patobulinta V2.0 versija, realizuota su nauja Vektorius klase vietoje std::vector.

## Spartos palyginimas tarp Vector class ir std::vector su push_back:

| Įrašų skaičius  | std::vector   | Vector class    |
|-----------------|---------------|-----------------|
| 10 000          | 0.00001s      | 0.00099s        |
| 100 000         | 0.00799s      | 0.00599s        |
| 1 000 000       | 0.04048s      | 0.03497s        |
| 10 000 000      | 0.32930s      | 0.26021s        |
| 100 000 000     | 3.63974s      | 3.38305s        |
