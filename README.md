# Ekaterina Rubanskaja. Banko klientų kaita

## Užduotis:

	 Šiuo darbo tikslas sukurti projektą su Power BI, kuriame reikia išanalizuoti pasirinktą duomenų rinkinį.

	Duomenis galima pasiimti iš bet kur ir bet kokius. Pavyzdžiui, iš Lietuvos atvirų duomenų (https://data.gov.lt/), ar kitų pasaulio šalių. Būtų labai gerai jei jūsų gautuose duomenyse būtų bent 5 tūkst. eilučių, tačiau jeigu duomenys nėra tvarkingi ir reikės daug laiko suinvestuoti į jų susitvarkymą, įrašų gali būti ir mažiau. Duomenys gali būti tiek iš failo (json, csv, ...), tiek iš duomenų bazės, galima naudoti kombinaciją iš kelių failų, gali viskas būti iš vieno.

	Pasistenkite išsikelti bent 5 klausimus, kuriuos atsakytumėte per įvairius skaičiavimus ir/ar diagramas. Pavyzdžiui, jeigu jūsų duomenų šaltinis yra avarijų statistika Lietuvoje, tuomet vienas iš klausimų galėtų būti "ar girti vairuotojai sukelia daugiau avarijų kur miršta žmonės?". Arba pavyzdžiui, jeigu jūsų duomenų šaltinis yra mokyklų ir mokytojų duomenys, tai vienas iš klausimų galėtų būti "kiek moksleivių tenka vienam mokytojui, priklausomai nuo to ar mokykla randasi miesto teritorijoje ar miestelyje?".

## Darbas:

  Šią darbą pavadinau „Banko klientų kaita“ ir atlikimui panaudojau duomenis iš Maven Analytics (https://mavenanalytics.io/data-playground/bank-customer-churn). Pirmiausia duomenys buvo nuvalyti, sutaisyti duomenų tipai ir nustatytas ryšys tarp lentelių. Klientai buvo suskirstyti į grupes pagal amžius ir sudaryti: 

- „Klientų skaičius pagal grupės pagal amžius“ diagrama, 
- „Numatomų atlyginimų suma pagal grupės pagal amžius“ žiedinė diagrama, 
- žemėlapis su burbuliukais, kuriuose atsispindi klientų depazitinę sumą, 
- tris kortelės: 
  1. „Bendras naudotojų kiekis“, 
  2. „Išėjusių naudotojų kiekis“, 
  3. „Likusiųjų naudotojų kiekis“,
- tris pjūviai: 
  1. pagal lytį, 
  2. „Ar aktyvus naudotojas?“, 
  3. „Geography“

	Naudojant pjūvius galima pakeisti diagramas ir kortelių turinius. Diagramose galime matyti kokių amžiaus grupių klientai aktyvesni.

## Išvados:

- Iš 9997 nauduotojų baigia bendradarbiauti su bankais 2038, pasilieka 7959. Galima išskirti, kiek iš jų moterų (atitinkamai 4541, 1140 ir 3401), kiek vyrų (atitinkamai 5456, 898 ir 4558), kiek iš jų buvo aktyvų nauduotojų. Galima išskirti pagal geografiją.
- Grafikų pagalba galima matyti, daugiausia naudotuojų tarp 30-mečių ir didžiausia numatomų atlyginimų suma irgi tarp 30-mečių.
- Žemėlapyje matom, kad didžiausias burbulas Vokietijoje, reiškia ten turtingiausi bankai pagal nauduotojų numatomus atlyginimus.
