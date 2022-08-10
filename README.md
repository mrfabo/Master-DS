# Master-DS

# Zoo Animal Classification
Classificazione degli animali in base alle loro caratteristiche

Il set di dati è composto da 101 animali provenienti da uno zoo.
Ci sono 16 variabili con diversi tratti per descrivere gli animali.
I 7 tipi di classe sono: Mammifero, Uccello, Rettile, Pesce, Anfibio, Insetto e Invertebrato.

Lo scopo di questo set di dati è quello di poter prevedere la classificazione degli animali in base alle variabili.

## Dataset zoo.csv
Informazioni sugli attributi: (nome dell'attributo e tipo di dominio del valore)

  animal_name: Unico per ogni istanza
  hair Boolean
  feathers Boolean
  eggs Boolean
  milk Boolean
  airborne Boolean
  aquatic Boolean
  predator Boolean
  toothed Boolean
  backbone Boolean
  breathes Boolean
  venomous Boolean
  fins Boolean
  legs Numeric (Valori: {0,2,4,5,6,8})
  tail Boolean
  domestic Boolean
  catsize Boolean
  class_type Numeric (Interi nel range 1-7)




## Dataset class.csv
Questo csv descrive il set di dati

  Class_Number Numerico (valori interi nell'intervallo 1-7)
  NumberOfAnimalSpeciesIn_Class Numerico
  Class_Type carattere -- La descrizione in parole reali della classe
  Animal_Names carattere -- L'elenco degli animali che rientrano nella categoria della classe
