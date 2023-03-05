# patika.dev-SQL-Practice04
patika.dev-SQL-Practice04

🔸film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.

``` sql
SELECT DISTINCT REPLACEMENT_COST
FROM FILM

```
🔸film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
✅21 adet değer vardır
``` sql
SELECT COUNT(DISTINCT REPLACEMENT_COST)
FROM FILM;

```

🔸film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?

``` sql
SELECT COUNT(*)
FROM FILM
WHERE TITLE LIKE 'T%'
	AND RATING = 'G'

```
🔸country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
✅13 adet değer vardır
``` sql
SELECT COUNT(*) FROM country
WHERE COUNTRY LIKE '_____'

```
🔸city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?

``` sql
SELECT COUNT(*)
FROM CITY
WHERE CITY ILIKE '%R'

```
https://app.patika.dev/emintunahan
