# Capstone Project - Chat Export

_Export razgovora kroz 6. oktobar 2026._

## USER

Na kraju smo procesa onboardinga gde smo ucili javu, springboot, git, angular. Podeljeni smo u grupe od 4 clana, 3 developera i 1 QA, za kraj treba da napravimo neki capstone project. Ovo su ideje od ljudi prethodnih godina:

| ScholarFlow |
| ----------- |
| InkWell     |
|             |

| Personal Finance Tracker | 
| InterviewVault |
| Equipment Lending Library |
| ClariCare - Healthcare Management System |
| Restaurant management system |

Ne mogu da smislim nikakvu ideju sta mi da pravimo a da se ne ponavlja od prethodnih godina. Ne treba da bude ni prejednostavna CRUD aplikacija ali ne treba ni da bude overkill. Postavi mi dosta pitanja kako bi strukirao ideju po meni.

## ASSISTANT

Da bih ti smislio ideju koja neće biti ni „još jedan CRUD“, ni projekat koji vas pojede za tri nedelje, prvo bih je „profilisao“ prema vama četvorici i tehnologijama koje ste učili. Odgovori i kratko; ne moraš na svako pitanje savršeno.

### 1. Šta vas četvoro zapravo zanima?

1. Od ova četiri pravca, šta ti je najzanimljivije:
   **A)** business/enterprise  
   **B)** productivity  
   **C)** social/community  
   **D)** entertainment/gaming  
   **E)** finance  
   **F)** health/wellness  
   **G)** education  
   **H)** something completely different?

2. Šta bi **ti lično** najviše voleo da naučiš kroz projekat, čak i ako ostalima nije prioritet?

3. Da li znaš šta zanimaju druga dva developera i QA? Napiši makar okvirno.

4. Da li neko od vas ima neki hobi/interesovanje koje bi moglo da postane domen aplikacije? Npr. teretana, fudbal, putovanja, automobili, gaming, muzika, kuvanje, fotografija, knjige...

5. Da li želite da napravite nešto što biste **zaista koristili vi ili drugi ljudi**, ili vam je važnije da bude tehnički zanimljivo za prezentaciju?

### 2. Koliko „ozbiljan“ projekat treba da bude?

6. Koliko vremena realno imate za capstone? Npr. 2 nedelje, 4 nedelje, 6 nedelja?

7. Koliko sati nedeljno očekujete da radite na njemu?

8. Da li se projekat radi isključivo kao završni zadatak ili će neko iz kompanije gledati kod, arhitekturu, testove, Git history itd.?

9. Da li imate zadate obavezne tehnologije? Da li **morate** koristiti:
   - Java
   - Spring Boot
   - Angular
   - Git
   - neki konkretan database
   - neke vrste testiranja?

10. Da li vam je dozvoljeno da dodate nešto što niste učili? Na primer Redis, Docker, WebSocket, OAuth2, Kafka, neki javni API itd.

11. Da li želite da projekat bude nešto što izgleda dobro na **CV-u / GitHubu**, ili to nije bitno?

### 3. Koliko kompleksna aplikacija treba da bude?

Ocenjuj od **1 do 5** koliko vas privlači svaka opcija:

12. **Kompleksna business logika** — mnogo pravila i različitih scenarija.

13. **Više user rola** — npr. admin, employee, manager, customer.

14. **Real-time funkcionalnosti** — chat, live notifications, statusi, osvežavanje podataka bez refresh-a.

15. **Dashboardi i analytics** — grafikoni, statistika, trendovi, izveštaji.

16. **Workflow/state machine** — nešto prolazi kroz više stanja, npr. `CREATED → REVIEW → APPROVED → COMPLETED`.

17. **Scheduling** — kalendar, rezervacije, termini, konflikti.

18. **Search/filter/sort** — napredna pretraga sa više kriterijuma.

19. **File upload / dokumenti / slike**.

20. **Email / notifications**.

21. **External API integracije** — npr. mapa, vremenska prognoza, kurs valuta, neki AI API, payment sandbox itd.

22. **Audit/history** — ko je šta promenio i kada.

23. **Automated testing** — da QA može da napravi ozbiljan set testova, a ne samo nekoliko basic test case-ova.

### 4. Šta želite da pokažete iz tehnologija koje ste učili?

Ovo mi je posebno bitno jer capstone treba da pokaže da ste naučili više od „napravili smo tabelu i endpoint“.

24. Koliko želite da frontend bude važan?  
Da li preferirate:
**backend-heavy**, **frontend-heavy** ili približno **50/50**?

25. Da li želite da Spring Boot bude samo REST API ili želite malo ozbiljniju arhitekturu:
`Controller → Service → Repository`, DTO-i, validation, exception handling, security, itd.?

26. Da li ste učili Spring Security / JWT autentifikaciju i autorizaciju?

27. Da li ste radili JUnit / Mockito / integration testing?

28. Da li je QA član vašeg tima učio automatizaciju testova ili više manual testing?

29. Da li želite da QA ima dovoljno prostora za ozbiljan rad, odnosno da aplikacija ima mnogo različitih scenarija i edge case-ova?

30. Da li ste radili Angular dovoljno da vam je zanimljivo praviti:
   - reusable components
   - forms + validation
   - route guards
   - services
   - RxJS
   - state management?

31. Da li želite Git workflow koji liči na pravi tim — feature branches, PR-ovi, code review, issues itd.?

### 5. Kakav korisnički problem želite da rešavate?

32. Da aplikacija postoji kao pravi proizvod, **ko bi bio korisnik**?

33. Da li biste radije rešavali problem:
   **A)** zaposlenih u kompanijama  
   **B)** običnih ljudi  
   **C)** studenata  
   **D)** malih biznisa  
   **E)** neke specifične zajednice  
   **F)** potpuno izmišljene korisničke grupe?

34. Šta vam je zanimljivije:
   **„Imamo problem sa organizacijom nečega“**  
   ili  
   **„Imamo ogromnu količinu podataka i treba da ih pretvorimo u korisne informacije“**?

35. Da li želite da postoji neki „core mechanic“ koji aplikaciju čini zanimljivom, a ne samo skup funkcionalnosti?

Na primer, ne samo „korisnik kreira task“, nego sistem koji automatski **predlaže prioritete**, pravi raspored ili reaguje na određene događaje.

### 6. Šta definitivno NE želite?

36. Pored navedenih projekata, koje teme biste odmah odbacili?

37. Da li želite da izbegavate:
   - social network
   - e-commerce
   - booking/reservation
   - healthcare
   - finance
   - education
   - project/task management

38. Da li vam smeta da aplikacija ima veoma sličnu **core funkcionalnost** kao neki poznati proizvod, sve dok nije ista tema?  
Npr. workflow kao Jira, ali u potpuno drugom domenu.

39. Koliko vam je bitno da ideja bude **originalna**?  
Da li je dovoljno da bude originalna kombinacija poznatih koncepata ili želite nešto što stvarno niste videli na 100 mesta?

### 7. Jedno veoma bitno pitanje

40. Kada zamisliš završnu prezentaciju pred mentorima, šta bi ti bilo najzanimljivije da kažeš:

> „Napravili smo sistem koji rešava ovaj konkretan real-world problem.“

ili

> „Napravili smo tehnički zanimljiv sistem koji ima ove kompleksne funkcionalnosti.“

ili nešto između?

41. Da vam dam **jednu godinu više vremena**, koji bi projekat voleo da napravite? Ovo pitanje je često najbolji način da se otkrije šta vas zapravo zanima.

42. I poslednje: od **1 do 10**, koliko ste spremni da „rizikujete“ sa idejom?  
**1 = provereno, jednostavno i sigurno**  
**10 = vrlo kreativno i potencijalno komplikovano**

Odgovori mi numerisano **1–42** (slobodno preskoči pitanja na koja ne znaš odgovor). Na osnovu toga mogu da ti napravim nekoliko konkretnih ideja koje su prilagođene timu **3 developera + 1 QA**, sa jasno definisanim MVP-om, „wow“ funkcionalnostima, backend/frontend kompleksnošću i procenom koliko je svaka realna za capstone.

## USER

1. **A)** business/enterprise
   **B)** productivity
   **C)** social/community

2. Nije bitno nista da naucimo
3. Nije bitno sta nas zanima nego sta je interesantno
4. Nista specijalno
5. Nemam odgovor na ovo pitanje
6. 3 nedelje

7. Dnevno 8 sati, 5 puta nedeljno
8. Menadzer ce gledati kod i arhitekturu
9. Obavezno je da pokrijemo sve sto smo ucili znaci Java, springboot, angular baza ce vrv biti postgresql
10. Dozvoljeno je, planirao sam JWT svakako, al sve ostalo moze
11. Nije bitno

12) 3 (prosecna bussines logika, moze i malo naprednije cak)
13) 3/4 (bar 3 role, al moze i vise)
14) 1 (Nije potrebno)
15) 1 (nije neophodno)
16) 1 (nije neophodno al moze da se implementira)
17) 3/4 (okej)
18) 3/4 (moze)
19) 4 (moze)
20) 2 (moze ali nije neophodno)
21) 1 (ovo mislim da je malo previse, al mozda, videcemo)
22) 1 (ne)
23) 5 (ali ce ovo biti potpuno zadatak QA, mi developeri necemo nista raditi)

24. 50/50
25. Ozbiljnija arhitektura
26. Jesmo, moracemo implementirati
27. Jesmo, al to ostavi za QA
28. oba je ucio
29. Da
30. Da
31. Da
32. Svejedno
33. Svejedno ti predlozi
34. Svejedno ti predlozi
35. Bilo bi pozeljno
36. Nemam preferenciju
37. Ne bih nista izbegavao ako je okej ideja
38. Ne smeta, svakako je sve na isti kalup
39. Moze da bude originalnija malo, ne treba neko djubre
40. Napravili smo sistem koji rešava ovaj konkretan real-world problem
41. Ne znam
42. 6/7

## ASSISTANT

Na osnovu odgovora, ja bih vam **svesno izbegao** tipične projekte kao što su task manager, booking sistem, social network, e-commerce, help desk sa običnim ticketima itd. To možete napraviti, ali teško ćete pokazati nešto zanimljivo.

Vaš idealan projekat je:

**enterprise problem + više uloga + workflow + nekoliko business pravila + dokumenti + pretraga/filteri + JWT/RBAC + ozbiljan REST API + dovoljno edge case-ova za QA.**

Sa 3 developera × 3 nedelje × 40h imate nominalno oko **360 developerskih sati**, što je sasvim dovoljno za solidan projekat, ali samo ako vam je scope disciplinovan.

## Moja prva ideja: AccessFlow

### „Sistem za upravljanje zahtevima za pristup internim resursima“

Zamisli firmu koja ima desetine sistema:

- Git repositories
- Jira projekti
- AWS okruženja
- baze
- interne aplikacije
- VPN
- Slack/Teams grupe
- različiti nivoi pristupa

Zaposleni ne sme sam da dobije pristup svemu. On napravi zahtev:

> „Treba mi read access na Production Database zbog ovog projekta.“

Sistem onda određuje **ko treba da odobri zahtev**.

Na primer:

`Employee → Manager → Resource Owner → Security`

ali ne mora svaki zahtev kroz sve nivoe.

Za običan resurs:

`Employee → Manager → Approved`

Za osetljiv resurs:

`Employee → Manager → Resource Owner → Security → Approved`

Za privremeni pristup:

`Approved → Active → Expired`

Tu već imate ozbiljnu business logiku.

### Uloge

**Employee**
- pregleda dostupne resurse
- podnosi zahtev
- vidi svoje zahteve
- povlači zahtev
- vidi status

**Manager**
- vidi zahteve svojih zaposlenih
- approve/reject
- ostavlja komentar
- vidi istoriju svojih odluka

**Resource Owner**
- upravlja resursima za koje je odgovoran
- odobrava pristup
- definiše koji nivo pristupa postoji

**Security/Admin**
- upravlja osetljivim resursima
- odobrava high-risk zahteve
- upravlja korisnicima/ulogama

Već imate **4 role**, a svaka ima drugačiji UI i dozvole.

### Gde je zapravo zanimljivost?

Ne u CRUD-u.

Nego u pravilima.

Na primer:

```text
Resource:
    Production DB
    sensitivity = HIGH

Requested access:
    WRITE

Duration:
    30 days

=> requires:
    Manager approval
    Resource owner approval
    Security approval
```

Ali:

```text
Resource:
    Internal Wiki
    sensitivity = LOW

Requested access:
    READ

=> requires:
    Manager approval
```

Još jedna mogućnost:

```text
WRITE access
+
HIGH sensitivity
+
duration > 7 days
=
Security approval mandatory
```

To je već nešto gde možete napisati ozbiljan service layer i lepo demonstrirati Spring Boot.

## Funkcionalnosti

### MVP

**Authentication**
- login
- JWT
- password hashing
- role-based authorization

**Resource management**
- kreiranje resursa
- tip resursa
- sensitivity level
- owner
- dostupni permission level-i

**Access request**
- korisnik bira resurs
- bira nivo pristupa
- navodi razlog
- opcioni attachment
- duration

**Approval workflow**
- automatski određivanje approval chain-a
- approve/reject
- statusi
- validacija ko sme šta da odobri

**Search/filter**
- po statusu
- korisniku
- resursu
- sensitivity
- datumu

**Dashboard**
- Employee: moji zahtevi
- Manager: pending approvals
- Security: high-risk requests
- Admin: resources/users

**File upload**
- npr. justification/document

## QA bi ovde imao baš dosta posla

Ovo je jedna od stvari zbog koje mi se ideja sviđa za vaš tim.

QA može testirati matrice poput:

| Scenario | Očekivano |
|---|---|
| Employee traži LOW + READ | Manager approval |
| Employee traži HIGH + READ | Manager + Owner + Security |
| Employee traži WRITE | dodatna pravila |
| Neovlašćen korisnik pokušava approve | 403 |
| Manager pokušava da odobri zahtev drugog tima | 403 |
| Već odobren zahtev se ponovo approve-uje | greška |
| Reject bez razloga | validation error |
| User povuče request koji je već approved | nije dozvoljeno |
| Request sa isteklim datumom | neaktiviran / expired |
| Security odbije | finalni status rejected |

To znači da QA nije „testirao pet CRUD endpointa“, nego stvarno može napraviti ozbiljan test plan.

---

# Druga veoma dobra ideja: ProcureFlow

### Sistem za interne zahteve za kupovinu

Zaposleni želi da kupi nešto:

> Laptop stand – €80

ili:

> Software license – €700

Podnese purchase request.

Sistem na osnovu **cene + kategorije + departmenta** određuje ko mora da odobri.

Na primer:

```text
€0–€250
→ Manager

€250–€1000
→ Manager + Department Head

€1000+
→ Manager + Finance + Procurement
```

Nakon odobrenja:

`Requested → Approved → Ordered → Delivered`

Role:

- Employee
- Manager
- Finance
- Procurement
- Admin

Ovo je **veoma enterprise**, a opet potpuno razumljivo na prezentaciji.

Ima odličnu business logiku, file upload za quotation/invoice i odličan prostor za QA.

Meni je ovo možda čak **najbezbednija opcija**.

---

# Treća ideja: ChangeFlow

### Sistem za upravljanje IT promenama

Ovo je malo „više tech“, ali bih ga ozbiljno razmotrio.

Developer želi da napravi promenu na production sistemu.

Kreira:

> Deploy version 2.4.1 to Production

Uz zahtev navodi:

- description
- affected system
- risk
- planned date/time
- rollback plan
- testing evidence
- attachments

Na osnovu rizika sistem određuje approval.

```text
LOW RISK
→ Team Lead

MEDIUM RISK
→ Team Lead + System Owner

HIGH RISK
→ Team Lead + System Owner + Security
```

Workflow:

`Draft → Submitted → Under Review → Approved → Scheduled → Implemented → Closed`

Možete dodati konflikt:

> „Ne možeš schedule-ovati change ako drugi approved change već zauzima isti system/time window.“

E tu dobijate baš lep business rule.

Ovo bi na prezentaciji moglo da zvuči dosta ozbiljnije od tipičnog studentskog projekta.

---

# Četvrta ideja: SkillBridge

### Interna platforma za razmenu znanja među zaposlenima

Ovo je najmanje „enterprise workflow“, ali ima **social + productivity** komponentu.

Zaposleni ima:

**Skills**
- Java
- Angular
- AWS

i može da kaže:

> „I need help with Kubernetes.“

Drugi zaposleni koji zna Kubernetes može da ponudi pomoć.

Sistem pravi matching na osnovu:

- skillova
- availability
- experience level
- preference

Može postojati:

`Request → Accepted → Scheduled → Completed`

Role:

- Employee
- Mentor
- Moderator
- Admin

Možete ubaciti rating, session booking, matching logic, search/filter itd.

Ovo je kreativnije, ali je **slabije za enterprise architecture** od prve tri ideje.

---

# Peta ideja: ContractFlow

### Upravljanje internim ugovorima i njihovim odobravanjem

Firma ima ugovore sa vendorima.

Korisnik uploaduje ugovor i kreira:

> „New contract with AWS partner“

Sistem prati:

- vendor
- contract value
- start date
- expiry date
- responsible person
- status
- approval requirements

Na osnovu vrednosti ugovora:

```text
< €5k → Manager
€5k–€50k → Manager + Finance
> €50k → Manager + Finance + Legal
```

Možete imati upozorenja za expiry, search/filter, različite role, upload dokumenata i workflow.

Vrlo jednostavno za objasniti, ali dovoljno ozbiljno.

---

# Šesta ideja: Resource Allocation

### Sistem za raspoređivanje zaposlenih na projekte

Project Manager napravi:

> Project Alpha

i traži:

> Java Developer × 2  
> Angular Developer × 1

Sistem prikazuje zaposlene koji odgovaraju zahtevima.

Manager odobrava assignment.

Zaposleni može biti na:

- Project A: 60%
- Project B: 40%

I onda imate business pravilo:

> Employee ne može biti assigned na više od 100% kapaciteta.

Možete dodati početak/kraj assignmenta, skill matching, department restrictions i search.

Ovo je odličan projekat za SQL jer imate dosta relacija.

---

# Kako bih ih ja rangirao za **vas**

| Ideja | Enterprise | Business logic | QA potencijal | Frontend | Težina | Moj utisak |
|---|---:|---:|---:|---:|---:|---|
| **AccessFlow** | 5/5 | 5/5 | 5/5 | 4/5 | 4/5 | ⭐⭐⭐⭐⭐ |
| **ProcureFlow** | 5/5 | 5/5 | 5/5 | 4/5 | 3.5/5 | ⭐⭐⭐⭐⭐ |
| **ChangeFlow** | 5/5 | 5/5 | 5/5 | 4/5 | 4/5 | ⭐⭐⭐⭐⭐ |
| ContractFlow | 5/5 | 4/5 | 4/5 | 4/5 | 3/5 | ⭐⭐⭐⭐ |
| Resource Allocation | 5/5 | 4/5 | 5/5 | 5/5 | 4/5 | ⭐⭐⭐⭐ |
| SkillBridge | 3/5 | 4/5 | 4/5 | 5/5 | 3.5/5 | ⭐⭐⭐⭐ |

## Da biram umesto vašeg tima

Moj **#1 izbor bio bi AccessFlow**.

Jer imate vrlo čist domen:

**User → Resource → Access Request → Approval Rules → Approvals → Access**

To vam daje odličan model baze, Spring service layer sa pravom logikom, Angular različit za svaku rolu, JWT/RBAC, validaciju, file upload, search/filter, workflow i ogroman prostor za QA testiranje — bez potrebe za WebSocketima, Kafka-om, mikroservisima, AI-jem ili nekom drugom „tehnologijom radi tehnologije“.

Mogu ti odmah sledeće razraditi **AccessFlow do nivoa pravog project proposal-a**: kompletne funkcionalnosti, user stories za 3 developera + QA, ER model/bazu, API endpoint-e, role/permissions, Angular stranice, workflow i precizan MVP + šta da ostavite kao stretch goal za 3 nedelje.

## USER

Da li mozes ceo ovaj chat da exportujes u word/pdf/md?
