---
layout: post
excerpt: Der Artikel "Beyond Agile - Antifragilität in der Softwareentwicklung" gibt auf eine belegbare Weise wieder, warum es Sinn macht Agil zu entwickeln und nur Dinge zu entwickeln, die  gebraucht werden.
---
# Warum agil entwickeln?
Der Artikel "[Beyond Agile: Antifragilität in der Softwareentwicklung](https://jaxenter.de/antifragilitaet-in-der-softwareentwicklung-19453)" gibt auf eine belegbare Weise wieder, warum es Sinn macht Agil zu entwickeln und nur Dinge zu entwickeln, die  gebraucht werden. Zudem wird anschaulich erklärt, dass es durchaus Sinn ergibt, Optionen möglichst lange offen zu lassen (z.B. "**First make it run, then make it fast**"), bis es eine Chance gibt herauszufinden (z.B. durch User-Feedback), welche der Optionen tatsächlich umgesetzt werden müssen.

Folgend versuche ich die mir besonders wichtigen Dinge aus dem Artikel zusammenzufassen.

Zum einen gibt es da die **Five Orders of Ignorance** (fünf Level der Unwissenheit) (Auszug aus dem Artikel):
> # Five Orders of Ignorance
(siehe: Armour, Phillip G.: „The Laws of Software Process“)
> * 0th Order of Ignorance (**0OI**) – **Lack of Ignorance**: Die erste Stufe von Unwissen bedeutet, dass man über sicheres Wissen verfügt. Ein typischer Fall von 0OI ist sein eigenes Geburtsdatum. Das kennen die meisten Menschen sehr genau.
* 1st Order of Ignorance (**1OI**) – **Lack of Knowledge**: Auf der zweiten Stufe des Unwissens fehlt eine Information. Man weiß aber sehr genau, wie man diese Information beschaffen kann. Als Beispiel mag die Telefonnummer eines Kollegen dienen. Wenn man sie nicht auswendig gelernt hat, kann man sie im Adressbuch der Firma nachschlagen.
* 2nd Order of Ignorance (**2OI**) – **Lack of Awareness**: Die dritte Stufe des Unwissens beschreibt das Fehlen von Wissen darüber, welche Informationen fehlen. Man weiß nicht, was man nicht weiß. Für diese Stufe ist es naturgemäß schwierig, ein gutes Beispiel zu liefern, darum stattdessen ein Zitat unbekannter Herkunft: Wenn wir wüssten, was wir nicht wissen, wüssten wir es schon.
* 3rd Order of Ignorance (**3OI**) – **Lack of Process**: Gibt es zusätzlich auch keinen bekannten Weg, über den herausgefunden werden kann, ob es etwas gibt, von dem man nicht weiß, dass man es nicht weiß, befindet man sich auf der vierten Stufe des Unwissens.
* 4th Order of Ignorance (**4OI**) – **Metaignoranz**: Die fünfte und letzte Stufe des Unwissens beschreibt letztendlich die Tatsache, dass nicht bekannt ist, dass die Five Orders of Ignorance existieren.

Dann gibt es noch das Prinzip der "**Schwarzen Schwäne**", also nicht vorhersehbare Ereignisse mit drastischen Folgen, die mindestens auf dem **2OI** angesiedelt sind.

Pläne können maximal mit dem Level **1OI** umgehen und ist dementsprechend auch von der Erfahrung der beteiligten abhängig. Je unerfahrener man in einem Gebiet ist, desto mehr Dinge sind im **2OI** angesiedelt. Darauf wird gerne mit generischen Lösungen auf einem hohen Abstraktionsgrad reagiert, um zukünftige Aufwände durch Vorausdenken einzusparen oder mögliche zukünftige Anforderungen, frühzeitig zu berücksichtigen. Dies führt aber dazu, dass die Software komplexer wird als sie sein müsste und damit schwer zu ändern ist, wenn ein "_Schwarzer Schwan_" auftritt.

Agile Entwicklung geht hier einen anderen Weg. Bei der Agilen Entwicklung geht es darum, die Dinge zuerst zu erledigen, die den größten Mehrwert bringen. Natürlich können auch hier "_Schwarze Schwäne_" auftreten, aber die Folgen sind nicht so gravierend. "Unwichtige" Dinge sind ja noch nicht umgesetzt worden. Damit ist weniger zu ändern und es ist mehr Zeit da, darauf zu reagieren.
