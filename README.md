# Analiza podataka iz igrice Pokemon Go

#### Projekat za predmet sistemi baza podataka

<br/>

### Korišteni podaci
U projektu su korišteni set podataka sa osobinama pokemona i set pokemona sa zabeleženim susretima. Setove podataka i informacije o njima moguće je pronaći na sledećim linkovima:
 * [Set podataka o pokemonima](https://www.kaggle.com/alopez247/pokemon "Pokémon for Data Mining and Machine Learning")
 * [Set podataka o susretima](https://www.kaggle.com/semioniy/predictemall "Predict'em All")
 
 ### Potrebno pre pokretanja
 1. *MongoDB, verzija 4.0.10*. Za više informacije [pogledati ovde](https://www.mongodb.com/download-center "MongoDB Download Center")
 2. *Python 3.6.5*
 3. *PyMongo 3.8.0*
 4. *Studio 3T 2019.3.0* ili drugi odgovarajući MongoDB GUI.
 
 ### Pokretanje
 1. Pokrenuti mongo u lokalu na portu 27017 i kreirati bazu sa nazivom sbp.
 2. Pokrenuti skriptu koja kreira kolekcije pokemon i encounters. Pozicionirati se u folder *scripts* i pokrenuti: <br/> 
	 <code>
		python fill_database.py
	 </code>
 3. Željeni upit kopirati iz fajla *upiti.md* i pokrenuti u okviru *Studio 3T*
