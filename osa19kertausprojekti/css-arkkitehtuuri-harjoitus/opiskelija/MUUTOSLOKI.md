# Muutosloki

| Ennen (ongelma) | Jälkeen (ratkaisu) | Miksi? | Testaus |
|---|---|---|---|
| 1. ID-valitsimet, !important sekä tarpeettomat class-valitsimet | @layer ja :root | helpompilukuinen CSS koodinlukijalle ja selaimelle, kun spesifisyys ollaan luotu huolella | dev-tools, testattu live serverillä opera selaimessa |
| 2. turhat hex-värikoodit ja toistuvat fontti-koot | :root desing-tokenit | tärkeät ja toistuvat värit ja koot on hyvä pitää samassa paikassa | testattu live serverissä opera selaimella |
| 3. heikko kontrasti| muutettu sivun väripaletti ja korjattu kontrasti | sisällön luettavuus paranee ja sisällön rakenne on luontevampi | testattu live serverillä opera selaimessa |
| 4. toistoa .course-card ja .card-title tyyleissä | säännöt esiintyvät vain kerran .course-card ja .card-title classeissa | vähemmän toistoa ja kuollutta CSS:sää | .--. |
| 5. .button:focus { outline:none; }| focus:visible | näppäimistökohdistusta ei voi lykätä | .--. |
| 6. .button text-decoration:none | .button text-decoration:underline, text-underline-offset ja button:hover lisätty | nappejen linkit ovat huomattavampia ja saavutettavampia |
| 7. .layout ja .course-grid kiinteät sarakkeet | minmax | näytön kapeutuessa kortin sisältö pysyy luettavana |
| 8. h1 ylivuoto pienemmällä näytöllä | media query overflow-wrap:anywhere | näytön kapeutuessa suuri teksti ei ylivuoda |

## Container queryn toiminta sivupalkissa ja pääsisällössä

## Saavutettavuus ja 200 % zoom

skaalautuvuus, testattu 320-1920px -leveydellä.
saavutettavuus, huomioitu selkeä css, 200% zoom ja näppäimistökäyttäjät




