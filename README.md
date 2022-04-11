# Driloefeningen
Zie opgave in het script bestand

# Oefening 1: FizzBuzz

Het FizzBuzz-probleem is een klassieke test die wordt gegeven in coderingsinterviews. Het gaat als volgt:  
vraag de gebruiker om een geheel getal. Log "Fizz" in de console als het getal deelbaar is door 3, "Buzz" als het getal deelbaar is door 5 en "FizzBuzz" als het getal deelbaar is door zowel 3 als 5. Als het getal niet deelbaar is door 3 en/of 5 log dan het getal naar de console. Als de gebruiker geen getal heeft ingegeven, maar wel bvb een string of een boolean, log dan "is not a number" naar de console

Merk op: Met de functie [prompt](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt) kan je invoer van de gebruiker vragen via een dialoogvenster. De functie retourneert de waarde die de gebruiker heeft opgegeven, nadat de gebruiker op de OK knop geklikt heeft. De geretourneerde waarde is steeds een string. Als de geretourneerde waarde een getal is, dien je dit steeds te casten naar een Number. Als de gebruiker op Cancel klikt wordt null geretourneerd.

De constructor [Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number) kan je gebruiken om een waarde van een ander type om te zetten naar een getal
```
const input = Number(prompt("Enter a number"));
```


# Oefening 2: Drivers license

Bereken het aantal strafpunten gegeven een snelheidslimiet van 70km/uur. Per 5 km boven de snelheidslimiet wordt 1 strafpunt gegeven.
1. Definieer een variabele speedLimit die de waarde 70 bevat
2. Definieer een variabele kmPerPoint die de waarde 5 bevat
3. Vraag de huidige snelheid van de gebruiker op
2. Schrijf onderstaand resultaat naar de console
    - Als de gebruiker niet meer dan de opgegeven speedLimit rijdt dan log je "OK" naar de console</p>
    - Als de gebruiker meer dan de speedLimit rijdt dan krijgt de gebruiker voor elke 5km (= de variabele kmPerPoint) boven de speedLimit 1 strafpunt. Log naar de console "points: number of points". Maak hiervoor gebruik van een templated string. Stel de gebruiker rijdt 82km/u, op de console verschijnt "points:2".
    - Als de gebruiker 12 of meer strafpunten heeft (vanaf 130km/u), log dan naar de console "drivers license is suspended"

# Oefening 3: Sum of multiples of 3 and 5

Vraag de gebruiker naar een getal. Bereken de som van alle veelvouden van 3 en 5 gaande van 0 tot en met het getal. Log naar de console "the sum of multiples of 3 and 5 is ...". Maak hiervoor gebruik van een templated string. 
Merk op: en veelvoud wordt maar 1 keer meegeteld.

Voorbeeld. Stel het getal is 10. De veelvouden van 3 zijn 3, 6, 9; de veelvouden van 5 zijn 5 en 10. De som van deze veelvouden is 33.


# Oefening 4: Palindrome

Vraag de gebruiker naar een palindroom. Enkele voorbeelden : eye, hannah, reinier,....

Ga na of het opgegeven woord een palindroom is. Log het resultaat naar de console '... is (not) a palindrome'. Maak hiervoor gebruik van een templated string.

# Oefening 5: Reverse words

Vraag de gebruiker naar een zin.
Log de woorden uit de zin in omgekeerde volgorde naar de console.
Voorbeeld: een zin: "de woorden moeten in omgekeerde volgorde geplaatst worden".
In de console komt  
worden  
geplaatst  
volgorde  
omgekeerde  
in  
moeten  
woorden  
de  

# Oefening 6: Prime numbers

Vraag de gebruiker naar een getal.
Print alle priemgetallen naar de console die tussen 1 en het getal gelegen zijn. Een priemgetal is een getal dat enkel deelbaar is door 1 en zichzelf
