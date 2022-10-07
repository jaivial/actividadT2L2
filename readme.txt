Actividad 1
mkdir “T2L2”

Actividad 2
cd T2L2
touch demo.txt

Actividad 3
nano demo.txt
ESTA ÉS LA PRIMERA LÍNIA EN MAJÚSCULES EN ESTE FITXER
esta és la primera línia en minúscules en este fitxer
Esta Línia Té Totes Les Primeres Lletres De Cada Paraula En Majúscules

La línia de dalt està en blanc
Esta és l’ última línia

Actividad 4
grep “esta” demo.txt

Actividad 5
grep -i “línia” demo.txt

Actividad 6
mkidr prova | mv demo.txt prova
cd prova
cp demo.txt demo2.txt
grep -r “línia” 

Actividad 7
grep -Er “línia|blanc” 