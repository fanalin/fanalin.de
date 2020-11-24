---
title: "Kritik an der Coronakritik"
date: 2020-11-24T12:02:27+01:00
draft: false
images: ["/img/backgrounds/20190713_200304.jpg"]
---

Bei Twitter lese ich, teils aus beruflichem Interesse, wie das Intensivregister "draußen" ankommt, teils aus Neugier an der Diskussion, regelmäßig Tweets zum Intensivregister.

Dabei fällt mir auf, wie einige der Graphen, die im Intensivregister angezeigt werden, fehlinterpretiert werden - siehe z.B. [dieser Tweet von Prof. Dr. Stefan Homburg](https://twitter.com/SHomburg/status/1331130326115037184).
Das Hauptargument der Kritiker an den Kontaktbeschränkungen ist, dass diese nicht notwendig wären, da die Intensivstationen nicht ausgelastet sind. Als Beleg für die Nicht-Auslastung wird dieser Graph gezeigt und der Hinweis darauf, dass die Belegung der Intensivstationen weitgehend konstant ist (wenn man die wochenweisen Schwankungen ignoriert).

![Intensivregister-Zeitreihe: Anteil der Covid-19-PatientInnen an der Gesamtbelegung der Betten vom 24.11.](/img/posts/kritik-an-der-coronakritik/Intensivregister-Zeitreihen-Belegte-Betten.png)

Der letzte Punkt (konstante Belegungsrate der Intensivstationen) ist durchaus korrekt. Was aber bereits in eben diesem Chart zu sehen ist, ist, dass sich die PatientInnenmenge an den Intensivstationen durchaus geändert hat. Der orangefarbene Bereich war zu unterschiedlichen Zeiten in diesem Jahr unterschiedlich hoch. Derzeit sind knapp 17% (3.768 von 21.927) der Betten durch COVID-19-PatientInnen belegt, im August waren es kaum 1%.

Mir fehlt die direkte Einsicht in die Intensivstationen um herauszufinden, warum nicht-COVID-19-PatientInnen verschwinden. Häufig genannte Gründe sind:
* Durch vermehrte Tests auf den Intensivstationen werden PatientInnnen, die wegen anderer Leiden auf ICU sind und keine COVID-19-Symptome haben, als COVID-19-PatientInnen in der Statistik geführt ("mit COVID-19, nicht wegen COVID-19").
* Die Krankenhäuser verschieben nicht notwendige Operationen und Krankenhaus-Aufenthalte, und die Betten werden durch "neue" COVID-19-PatientInnen belegt. Anmerkung: dies und eventuelle Folgen nachzuhören z.B. im [hr-Info-Podcast Dr. Arunagirinathan][1]
* Durch die Kontaktbeschränkungen verletzen sich weniger Menschen bei Aktivitäten, die sie nun weglassen - dadurch fallen diese PatientInnen auf den ICUs weg. Die dadurch freigewordenen Betten werden durch "neue" COVID-19-PatientInnen belegt.

Die Wahrheit ist sicherlich ein Sammelsurium aus diesen und anderen Effekten, die ich gar nicht im Einzelnen bewerten will.

Wir können allerdings anhand der Statistik feststellen, dass die Gesamtbelegung bisher nicht wesentlich durch die Corona-Epidemie betroffen war.
Der naive Ansatz wäre nun, die Untersuchung abzubrechen und zu schlußfolgern, dass die Epidemie "ja gar nicht so schlimm sei". Hier setzt meine Kritik an, denn in der Grafik direkt über der Gezeigten zeigt sich, dass sich doch einiges änderte im Laufe der letzten Monate. Insbesondere scheint die Gesamtbelegung ein schlechtes Maß dafür zu sein, wie es um die Krankenhäuser steht, wenn trotz des Fortschreitens einer Epidemie sich diese Kenngröße kaum ändert.

![Intensivregister-Zeitreihe: Belegte und freie belegbare Betten sowie Notfallreserve vom 24.11.](/img/posts/kritik-an-der-coronakritik/Intensivregister-Zeitreihen-Belegte-und-freie-Betten.png)

Hier ist relativ einfach ersichtlich, wie die Zahl der freien belegbaren Betten im Laufe der Zeit sinkt. Zur Übersichtlichkeit (um die Schwankungen der unteren Hälfte herauszunehmen) hier einmal die Grafik, welche nur die aktuell belegbaren Betten anzeigt (die Daten sind über den Knopf "Daten herunterladen" auf der Intensivregister-Seite herunterladbar):

![Freie belegbare Betten aus Daten des Intensivregisters vom 24.11.](/img/posts/kritik-an-der-coronakritik/freie-belegbare-betten.png)

Hier nochmals die Daten, aber für jeden Tag wurde der Durchschnitt der letzten 7 Tage genommen (um die Wochenschwankungen auszugleichen). Hinweis: in der Worst-Case-Betrachtung wäre es sinnvoller, das Minimum der letzten 7 Tage zu nutzen. Da wir zum Glück nicht in der Verlegenheit sind, dass wir deutschlandweit bei 0 freien Betten wären (selbst nicht an einzelnen Tagen) reicht der Durchschnitt aber zunächst mal aus.

![Freie belegbare Betten mit 7-Tage-Durchschnitt aus Daten des Intensivregisters vom 24.11.](/img/posts/kritik-an-der-coronakritik/freie-belegbare-betten-7-tage-schnitt.png)

Wesentliche "Meilensteine": 
* 11.09.: weniger als 9.000 freie Betten. Dies war bis zum 21.10. einigermaßen stabil zwischen 8.900 und 9.000 Betten.
* 22.10. bis 28.10.: erstmals weniger als 8.000 Betten. Insbesondere sind in dieser Woche knapp 900 belegbare Betten verloren gegangen.
* 12.11.: erstmals weniger als 7.000 belegbare Betten.
* Bis heute (24.11.) sind nochmals fast 800 belegbare Betten verloren gegangen.

Dazu muss man anmerken, dass aus mehreren Gründen die angegebenen Zahlen zu optimistisch (d.h. in Realität geringer) sind:
* Einige Krankenhäuser haben, entgegen der Definition eines "belegbaren" Bettes, nur die freien Betten (unabhängig von der Belegbarkeit, was u.a. Personal mit einschließt) gemeldet. Die tatsächliche Belegbarkeit war dadurch geringer. DIVI und RKI haben im Oktober auf diese Definition verstärkt hingewiesen.
* An einigen Krankenhäusern werden die Meldungen entgegen des Konzeptes der DIVI von zentraler Stelle aus der Verwaltung (statt von Ärzten direkt von der Station) vorgenommen. Dies sorgt ebenfalls dazu, dass zu viele belegbare Betten gemeldet werden, da die Verwaltungen teils die Situation vor Ort (z.B. Personalsituation) weniger gut kennen und/oder finanzielle/Marketing-Interessen daran hatten, zuviele Betten zu melden (z.B. für die Freihaltepauschale, die bis September galt).
* Die Daten aus den Zeitreihen beziehen sich auf Erwachsenen- und Kinderintensivstationen, sowie auf alle Versorgungsgerade (hier sind also Daten von sehr kleinen Krankenhäusern enthalten, die zwar eine kleine Intensivstation besitzen, aber kein Fachwissen bzgl. COVID-19). Im Reiter "Ländertabelle" sind die entsprechenden Filter setzbar, für die Zeitreihen wurde dies noch nicht implementiert. Aus aktuell 5.955 belegbaren Betten sind so nach Abzug von Kinderbetten und Filter auf Schwerpunkt-Krankenhäuser nur noch gut 2.310 übrig. Einige, auch große, Bundesländer, haben weniger als 100 belegbare Betten für COVID-19-PatientInnen. Beispiel Hessen: 71 belegbare Betten bei derzeit 185 COVID-19-PatientInnen.

Der letzte große Kritikpunkt ist, dass sich die Corona-Politik ja an den Trends der Erkrankungen richten muss. Nun habenn wir zum Glück derzeit eine Abschwächung der Zuwächse an Patienten. Zum Zeitpunkt, als die Kontaktbeschränkungen beschlossen wurde, waren die Zuwachsraten täglich bei rund 7% (siehe z.B. [dieser Tweet](https://twitter.com/KonProg/status/1323208279024087041)), was einer Verdoppelungszeit von knapp 10 Tagen entspricht (1,07^10=1,97 - btw: dies war ein exponentielles Wachstum, was tlw. auch negiert wurde). 

Zum Glück sind diese extremen Wachstumsraten vorbei. Wir können nur Mutmaßungen anstellen, warum dieses Wachstum in der Form nicht mehr da ist - die naheliegende Antwort lautet, dass die Kontaktbeschränkunngen hier zumindest beigetragen haben. 

Wie notwendig es war, dieses Wachstum zu stoppen, zeigt folgende Rechnung:
* Bei aktuell 2.310 freien Erwachsenen-Intensivbetten in Schwerpunkt- und Maximalversorgungseinrichtungen und 2.240 COVID-19-PatientInnen hätte es nur knapp 10 Tage mit dem beschriebenen Wachstum gebraucht, bis diese Betten belegt wären. Selbst bei weiterer Verdrängung von Nicht-COVID-19-PatientInnnen wären diese Ressourcen bald ausgeschöpft gewesen. Die Folgen wären, dass entweder eine noch krassere Verdrängung stattfindet (mit allen im Interview von Dr. Arunagirinathan besprochenen Folgen) oder die PatientInnen auf kleinere Krankenhäuser mit weniger/keinem Fachwissen verteilt werden (mit anzunehmenden Folgen für eine höhere Sterblichkeit). Als letzte Alternative wäre noch das "Anzapfen" der Notfallreserve zu nennen (aber wenn man dies tut, hat man keine Notfallreserve mehr - also ist ein früheres Gegensteuern hier m.E. der korrekte Ansatz).
* Lokal sind die Zahlen noch krasser: im Beispiel Hessen wäre bereits nach 5 Tagen die rechnerische Kapazität aufgebraucht gewesen.

Diese positive Darstellung (Abschwächung der Wachstumsraten) soll keinesfalls davon ablenken, dass die Anzahl der COVID-19-PatientInnen auf den Intensivstationen weiterhin wächst.

![Intensivregisters-Zeitreihen: Anzahl der COVID-19-PatientInnen vom 24.11.](/img/posts/kritik-an-der-coronakritik/Anzahl-COVID-19-PatientInnen.png)

Wir sollten als Gesellschaft also weiterhin daran arbeiten, die Epidemie in den Griff zu bekommen. Aus meiner Sicht sind die Kontaktbeschränkungen ein schmerzhaftes, aber notwendiges Mittel, da die allgemeinen Regeln (AHA-*, ...), die im Sommer gereicht haben, derzeit wohl nicht mehr ausreichend sind.
Ärgerlich ist es m.E., dass sich der Begriff "Lockdown" eingebürgert hat. Was wir in Deutschland haben, ist kein Lockdown. Menschen dürfen das Haus verlassen, viele Geschäfte haben offen, die meisten von uns können arbeiten, .... Ein wirklicher Lockdown, wie wir ihn z.B. im Frühjahr in Wuhan gesehen haben oder in Frankreich, sieht ganz anders aus. 

Disclaimer: seit März 2020 arbeite ich beruflich an der Entwicklung des [Intensivregisters](https://www.intensivregister.de). Die hier dargestellten Gedanken, Interpretationen und Thesen sind meine eigenen und nicht mit RKI, DIVI oder meinem Arbeitgeber abgestimmt.

[1]: https://www.hr-inforadio.de/programm/das-interview/das-interview-mit-dr-umes-arunagirinathan-herzchirurg-und-autor,das-interview-mit-umes-arunagirinathan-herzchirurg-autor-100.html