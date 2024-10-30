# TuotekuvastoApp

ProductController.cs käsittelee tuotteisiin liittyviä pyyntöjä. Se hakee tuotetiedot products.json-tiedostosta ja lähettää ne Product.cshtml-näkymälle.
products.json on tietolähde, jossa tuotetiedot ovat JSON-muodossa. Kontrolleri lukee ja deserialisoi tiedot C#-olioiksi.
Product.cshtml Razor-näkymä, joka vastaanottaa kontrollerilta tuotetiedot ja luo HTML-sivun käyttäjän nähtäväksi.

Käyttäjä tekee pyynnön tuotteista.
ProductController.cs lukee products.json-tiedoston ja muuntaa sen tiedot C#-objekteiksi.
ProductController.cs välittää tiedot Product.cshtml-näkymälle.
Product.cshtml luo HTML-sivun tiedoista ja näyttää sen käyttäjälle.
