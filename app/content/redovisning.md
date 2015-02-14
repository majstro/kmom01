Redovisning
====================================

Kmom01: PHP MVC ramverk
------------------------------------
Jag använder mig för att skapa/programmera sidorna en dator med Windows 8.1, Dreamweaver CS5.5. För att se hur det kommer att se ut använder jag Firefox, InternetExplorer och Crome.

Min utvecklingsserver är en Avdankad gammal HP server som (nu mer) kör Debian 7.8(Wheezy), Apache2, MySQL och PHP 5.4. Just denna lilla sak har ställt till med mycket problem för denna kursen. Blev tvungen att ominstallera allt då den gamla server jag hade inte gillade uppgraderingen av PHP.

Min erfarenhet av att använda ramverk i PHP sträcker sig inte längre än Anax i förra kursen (oophp). Så för min del vart detta att dyka med huvudet före i djupt vatten. Förhoppnings vis lärde jag mig lite denna gången och mer kommande kursdelar.

Min uppfattning av Anax speciellt Anax-MVC nu är: Det är omfattande. Jag har svårt att greppa allt ännu, men som jag innan sa hoppas jag att det lossnar snart.

Jag hade under detta moment riktig svårt att få till de "snygga" länkarna. Tyckte jag hade aktiverat alla overrides m.m. och hade rätt dokumentroot i .htaccess filerna. Men icke sa nicke. Visar sig att Anax verkade missa: "$app->url->setUrlType(\Anax\Url\CUrl::URL_CLEAN)". Så min lösning blev att ändra direkt CDIFactoryDefaults. Då så funkade allt som det ska.

Tycker att Git är krångligt ännu, men jag får det att fungera iallafall som det är tänkt. Är van vid FTP, och jag gillar det sättet.