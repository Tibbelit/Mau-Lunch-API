# MAH-Lunch-API

Ett enkelt API för att hämta ut dagens eller veckans lunch från några restauranger när Malmö Högskola (Niagara). Följande restauranger finns just nu med:

- [Restaurang Niagara](http://restaurangniagara.se/)
- [La Bonne Vie](http://labonnevie.se/)
- [MiaMarias](http://restaurangniagara.se/)
- [Välfärden](http://valfarden.nu/)
- [Lilla Köket](http://lillakoket.com/)

## Anrop

Följande GET-anrop kan göras:

#### Hämta ut veckans meny för restaurangerna ovan

`/`

#### Hämta ut dagens meny för restaturangerna ovan

`/today`

#### Hämta ut veckans meny för angiven restaurang

`/:restaurant`

#### Hämta ut dagens meny för angiven restaurang

`/:restaurant/today`

#### Hämta ut restaurangerna som finns tillgängliga

`/restaurants`

### Exemepelanrop

På URL: [http://mahlunch.antontibblin.se/](http://mahlunch.antontibblin.se/) finns API:t upplagt.

#### Hämta ut veckans meny för restaurangerna ovan

- [http://mahlunch.antontibblin.se/](http://mahlunch.antontibblin.se/)

#### Hämta ut dagens meny för restaturangerna ovan

- [http://mahlunch.antontibblin.se/today](http://mahlunch.antontibblin.se/today)

#### Hämta ut veckans meny för angiven restaurang

- [http://mahlunch.antontibblin.se/Niagara](http://mahlunch.antontibblin.se/Niagara)
- [http://mahlunch.antontibblin.se/Labonnevie](http://mahlunch.antontibblin.se/Labonnevie)
- [http://mahlunch.antontibblin.se/Miamaria](http://mahlunch.antontibblin.se/Miamaria)
- [http://mahlunch.antontibblin.se/Lillakoket](http://mahlunch.antontibblin.se/Lillakoket)
- [http://mahlunch.antontibblin.se/Valfarden](http://mahlunch.antontibblin.se/Valfarden)

#### Hämta ut dagens meny för angiven restaurang

- [http://mahlunch.antontibblin.se/Niagara/today](http://mahlunch.antontibblin.se/Niagara/today)
- [http://mahlunch.antontibblin.se/Labonnevie/today](http://mahlunch.antontibblin.se/Labonnevie/today)
- [http://mahlunch.antontibblin.se/Miamaria/today](http://mahlunch.antontibblin.se/Miamaria/today)
- [http://mahlunch.antontibblin.se/Lillakoket/today](http://mahlunch.antontibblin.se/Lillakoket/today)
- [http://mahlunch.antontibblin.se/Valfarden/today](http://mahlunch.antontibblin.se/Valfarden/today)

#### Hämta ut de tillgänglia restaurangerna

- [http://mahlunch.antontibblin.se/restaurants](http://mahlunch.antontibblin.se/restaurants)
