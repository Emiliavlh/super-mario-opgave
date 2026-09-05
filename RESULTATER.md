# Dokumentér dine resultater

Notér resultaterne før og efter optimering.

Du kan eksempelvis bruge denne tabel:

| Side | Performance før | Performance efter | Accessibility før | Accessibility efter 
|---|---:|---:|---:|---:|
| `index.html`| 89 | 100 | 85 | 100 |
| `news.html`| ! | 100 | 85 | 100 |
| `games.html`| 75 | 99 | 85 | 100 |
| `contact.html`| ! | 100 | 77 | 100 |

Skriv derefter kort:

1. Hvilke ændringer gav den største performanceforbedring? 
    - Ændre billedeformat til webp, og tilføje attributten loading="lazy"
2. Hvilke accessibility-problemer fandt du?
    - Manglede alt-tekster, og for lav farvekontrast - og manglende lang="en" attribut i head.
3. Hvilke problemer kunne Lighthouse finde?
    - Den kunne overall fortælle hvad der manglede, men ikke altid helt nøjagtigt hvor jeg kan forbredre det.
4. Hvilke problemer fandt WAVE?
    - Wave var et godt tool, der kunne vise hvor selve problemet var, og kunne hjælpe med hvornår farvekontrasten var god nok, inde på selve plug-in'et
5. Hvilke problemer krævede HeadingsMap eller manuel kontrol?
    - Det her plugin brugte jeg ikke så meget. Den kunne vise HTML strukturen inde på siden, men jeg fik mere hjælp af Lighhouse og WAVE.
6. Hvad har du lært om sammenhængen mellem performance og accessibility?
    - F.eks. en synshandicappet person, skal have samme mulighed for hurtig betjening af en side, som et normalt-fungerende menneske kan. Derfor skal performance være næsten ligeså skarp som tilgængeligheden. Hvis performance er god, så er færre forhindringer, for f.eks. screenreaders, eller andre hjælpemidler.