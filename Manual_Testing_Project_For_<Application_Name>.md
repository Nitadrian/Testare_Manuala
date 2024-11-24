<h1>Testing Project for BLUEGIFTS</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **BLUEGIFTS**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories were created in Jira and describe the functional specifications of the "BLUEGIFTS" module, for which the final project is performed upon.
![Captură de ecran din 2024-11-24 la 19 46 11](https://github.com/user-attachments/assets/480d8568-e7a7-4aca-b09a-f3741dd67862)
![Captură de ecran din 2024-11-24 la 19 46 24](https://github.com/user-attachments/assets/97730845-af35-4d98-94a3-abed6822f3f6)
![Captură de ecran din 2024-11-24 la 19 48 23](https://github.com/user-attachments/assets/9f358eba-fb9c-491e-bb3c-c853385eb41d)



Here you can find the release that was created for this project:
![Captură de ecran din 2024-11-24 la 19 48 23](https://github.com/user-attachments/assets/03a95638-49ab-4779-b069-ec425732cad4)



<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (https://docs.google.com/document/d/1csD214Vh7Saf7Vs0SzBFK6v9e3kx6WcA/edit?usp=sharing&ouid=115896007939005608517&rtpof=true&sd=true)![image](https://github.com/user-attachments/assets/a2ec0ff3-a529-4413-8ad2-1749c0301528)


<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<ul>
  <li>Popescu Maria</li> 
  <li>Popescu Iulia</li>
  <li>Rusu Noelia</li>
  <li>Niță Adrian</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

Specificațiile aplicației BlueGifts au fost complet finalizate și documentate.
Mediul de testare a fost configurat și este stabil.
Testele automate au fost pregătite și integrate în sistem.
Resursele necesare (testeri, medii de testare, acces la sistemul de dezvoltare) sunt disponibile.
Furnizarea accesului la aplicație pentru testare a fost realizată.
Datele de testare au fost pregătite.

<h4> 1.1.3 Exit criteria defined </h4>

Toate cazurile de testare au fost executate conform planului de testare.
Toate defectele critice au fost raportate și rezolvate sau o decizie a fost luată privind remedierea lor.
Funcționalitățile cheie au fost validate și funcționează conform cerințelor specificate.
Testele de regresie au fost efectuate și nu au apărut erori noi în zonele testate.
Rapoartele de testare au fost completate și documentate corespunzător.
Performanța aplicației a fost testată și nu există întârzieri sau probleme semnificative.
Documentația de testare a fost actualizată corespunzător cu rezultatele obținute.


<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

Testarea funcționalităților aplicației BlueGifts, inclusiv:
Funcționalitatea de căutare a produselor.
Testarea filtrării produselor după categorii, preț, rating etc.
Verificarea procesului de adăugare a produselor în coș și a modificării cantității.
Testarea procesului de checkout (finalizarea comenzilor).
Testarea afisării prețului total în coș.
Verificarea performanței (timpul de încărcare a paginii și a produselor).
Testarea compatibilității pe diferite dispozitive și browsere.


<h5>Tests not in scope: </h5>

Teste de security testing (aceasta va fi o etapă separată și nu face parte din testarea inițială).
Teste de compatibilitate cu platformele externe (ex. platforme de plată terță parte).
Teste de performanță de încărcare sub volum mare de trafic.
Teste de usability (evaluarea experienței utilizatorului nu va face parte din acest ciclu de testare).


<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

Disponibilitatea resurselor: Riscul de a nu avea suficiente resurse (testeri, echipamente de testare) în perioada stabilită.
Accesul limitat la mediu: Posibile întârzieri în obținerea accesului complet la mediile de testare sau la aplicație.
Modificări ale cerințelor pe parcursul testării, care pot duce la necesitatea refacerii unor teste.
Condițiile tehnice: Riscuri legate de performanța serverelor sau a aplicației, care pot influența timpii de testare.

<h5> Product risks: </h5>

Incoerențe în implementarea funcționalităților: Posibilitatea ca funcționalitățile să nu fie implementate conform specificațiilor.
Bugs critici care ar putea afecta experiența utilizatorilor (ex: imposibilitatea de a adăuga produse în coș sau erori în procesul de checkout).
Defecte de UI care ar putea influența utilizabilitatea aplicației (ex: elemente de design care nu se potrivesc corect pe dispozitive mobile).
Probleme de performanță legate de încărcarea paginilor sau de încărcarea lentă a produselor.


<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

Etapa de monitorizare și control a fost implementată pentru a urmări progresul testării, a verifica dacă toate testele sunt realizate conform planului și a identifica posibile riscuri sau întârzieri. De asemenea, prin această etapă s-a dorit verificarea conformității testelor cu cerințele de afaceri și cele tehnice stabilite anterior. Monitorizarea a fost realizată prin generarea de rapoarte de status în Zephyr. Aceste rapoarte au furnizat detalii despre testele executate, testele care au eșuat și starea generală a proiectului. 

![image](https://github.com/user-attachments/assets/88c4a724-8004-43b4-b2b0-ba17a02f15e9)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

**(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
