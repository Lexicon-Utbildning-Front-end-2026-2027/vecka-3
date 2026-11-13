# 📅 Schema Vecka 3: HTML/CSS

---

## 🎯 Mål för veckan

* Arbeta med det som står under vecka 3 i övningen. Meny och sidan med flera recept

## 📚 Material

### 🛠️ Övningar
* [Receptsidan](https://github.com/Lexicon-Utbildning-Front-end-2026-2027/vecka-1/blob/main/ovning-1.md)

## 📅 Måndag: The Box Model (P)

### 🎯 Mål för dagen

* Förstå CSS Box Model och förklara hur content, padding, border och margin påverkar ett elements storlek och placering.
* Förstå och använda box-sizing, samt skillnaden mellan content-box och border-box.
* Förstå skillnaden mellan block- och inline-element, och hur deras beteende påverkas av CSS-egenskapen display.
* Använda logiska CSS-egenskaper (Logical Properties), exempelvis margin-inline, padding-block och inline-size, och förstå skillnaden mot traditionella egenskaper som margin-left och width.
* Använda webbläsarens DevTools för att undersöka och felsöka elements storlek, marginaler och utfyllnad.

### 📚 Material

#### 💻 E-Learning
* [(YT - Kevin Powell) HTML & CSS for Absolute Beginners: The box model - width, height, inline-size, block-size](https://www.youtube.com/watch?v=D_akuQHIPtg&list=PL4-IK0AVhVjOJs_UjdQeyEZ_cmEV3uJvx&index=31)
* [(YT - Kevin Powell) Write better CSS using logical properties](https://www.youtube.com/watch?v=kzvmaVik4mA)

#### 📃 Läsning
* [(MDN) - The box model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model)
* [(MDN) - Logical properties for margins, borders, and padding](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Logical_properties_and_values/Margins_borders_padding)
* [[Extra om man vill läsa mer om logical properties [(MDN) - Basic concepts of logical properties and values](](](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Logical_properties_and_values/Basic_concepts)

#### 🛠️ Övningar
* [(MDN) - Test your skills: The box model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Test_your_skills/Box_model)
* [(MDN) - Test your skills: Sizing](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Test_your_skills/Sizing)

---

## 📅 Tisdag: Flexbox (P)

### 🎯 Mål för dagen

* Förstå CSS Box Model och hur content, padding, border och margin påverkar ett elements storlek och placering.
* Förstå och använda box-sizing för att styra hur ett elements bredd och höjd beräknas.
* Förstå skillnaden mellan block- och inline-element och hur de beter sig i dokumentflödet.
* Förstå och använda logiska CSS-egenskaper och hur riktningarna inline och block används för storlek och avstånd, exempelvis inline-size, margin-inline-start och padding-block-end.
* Kunna undersöka och felsöka Box Model med hjälp av webbläsarens utvecklarverktyg.

### 📚 Material

#### 💻 E-Learning
* [(YT - Kevin Powell) Learn flexbox the easy way](https://www.youtube.com/watch?v=u044iM9xsWU)
* [(YT) - Kevin Powell - Flexbox Alignment & Justification Without the Guesswork](https://www.youtube.com/watch?v=uIzaU98Ak1k)

#### 📃 Läsning
* [(CSS-Tricks) CSS Flexbox Layout Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

#### 🛠️ Övningar
* [(MDN) Test your skills: Flexbox](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Test_your_skills/Flexbox)
* [Extra - Om ni vill och hinner inför fredag - Gör en skip link till er receptsida](https://www.accede-web.com/en/guidelines/html-css/keyboard-navigation/skip-links/)
* [Flexbox Froggy](https://flexboxfroggy.com/#sv)

---

## 📅 Onsdag: CSS Grid (R)

### 🎯 Mål för dagen

* Förstå skillnaderna mellan flex och grid när det gäller  positionering och syfte
* Kunna använda devtools för att inspektera och felsöka grid-strukturer
* När ska vi använda auto-fit vs auto-fill och vilken skillnad gör de egentligen?
* Explicit vs implicit grid - Fatta medvetna beslut kring när man ska ha en dynamisk grid vs ett statiskt grid.
* Använd grid för att ändra ordning i en layout, både för stil och för tillgänglighet
* Förstå några andra bra hacks man kan göra med grid - överlappande delar utan absolut position
* Extra - Använd grid för att skapa sidlayouter med breakouts - utan negativa marginaler

### 📚 Material

#### 💻 E-Learning
* [(YT) Coding2GO - CSS Grid Course](https://www.youtube.com/watch?v=JYfiaSKeYhE)
* [(YT) Kevin Powell - CSS Grid Alignment & Justification Without the Guesswork](https://www.youtube.com/watch?v=WvoYYok1Ddo)
* [(YT) Kevin Powell - The magic auto-fit and auto-fill (and the difference between them)](https://www.youtube.com/watch?v=OZ6qKoq7RJU)

#### 📃 Läsning
* [(MDN) CSS grid layout](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Grids)
* [Varning - innehåller även en del överkurs (css-tricks) CSS Grid Layout Guide](https://css-tricks.com/snippets/css/complete-guide-grid)

#### 🛠️ Övningar
* [(MDN) Test your skills: CSS grids](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Test_your_skills/Grid)
* [Grid Garden](https://cssgridgarden.com/#sv)
* Öva på att använda grid på lämpliga ställen på receptsiten

---

## 📅 Torsdag: Eget arbete

Repetera veckans mål, arbeta med receptsidan och öva på att göra en avvägning kring "Flexbox vs Grid". Granska din kod och identifiera de olika delarna:

* Innehållsstyrd (1D): Använd Flexbox (t.ex. knappar, taggar, menyrad).

* Rutnätsstyrd (2D): Använd Grid (t.ex. sidans övergripande sektioner, receptgalleriet).

### 🎯 Mål för dagen

* Repetera veckans mål och e-learning
* Bygga ett receptkort som demonstrerar layout-samarbete (t ex grid för layout och flex för flödande innehåll)
* Refaktorera bort fällor - Identifiera och ta bort onödiga wrapper-element (<div>) och ersätta fasta höjder (height: 400px) med säkra minimimått och flexibla enheter.
* Förbereda argument inför fredag: Välj ut 1 plats i koden där du övervägde Flexbox men valde Grid (eller tvärtom) och formulera varför.

### 📚 Material

#### 💻 E-Learning
* [(YT) Kevin Powell - Flexbox or grid - How to decide?](https://www.youtube.com/watch?v=3elGSZSWTbM)
* [Överkurs - (YT) Kevin Powell - A new approach to container and wrapper classes](https://www.youtube.com/watch?v=c13gpBrnGEw)

#### 🛠️ Övningar
* [(MDN) Challenge: Fundamental layout comprehension](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Fundamental_Layout_Comprehension)

---

## 📅 Fredag: Kodsnack (R)

### I grupp

Börja med att visa era receptsajter:

- Gissa först: Var har du använt Flexbox och Grid? Låt de andra gissa, visa sedan koden.
- Före och efter: Vad blev enklare eller bättre när du byggde om sidan?
- Veckans kluring: Vad var svårast att få på plats? Hur löste du det?

Diskutera sedan:

- Hur har ni tänkt kring mellanrum så att sidan känns sammanhängande?
- Hur fungerar era menyer och listor med recept på olika skärmstorlekar? Visa och jämför.
- Vad upptäckte ni under arbetet som fick er att ändra hur ni tänkte?

Be varandra visa exempel i koden och fråga ”Hur tänkte du där?”. Låt alla komma till tals.

### Gemensamt

- Vilka olika lösningar har ni valt för samma sak? Vad finns det för fördelar med dem?
- Varje grupp lyfter en kluring från sitt samtal.

### 🎯 Mål för dagen

* Förklara hur och när du använt Flexbox och Grid på din receptsajt.
* Jämföra olika lösningar för layout, mellanrum och skärmstorlekar.
* Lära av varandras lösningar och problem.
* Öva på att prata om kod och ställa frågor.

---
