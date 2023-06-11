LAB 2 --> Am folosit Singleton pentru a menaja scaunele disponibile, se verifica daca locul este disponibil. Dupa care putem rezerva un loc.
Am folosit Prototype pentru a crea ticket-urile care obiecte, pentru a clona acest obiect de fiecare data cand avem nevoie.
Am folosit Abstract factory pentru a crea tickete si VIP tickete, builderul pentru a construi ticket-ul alegand teatrul si filmul.


LAB 3 --> Acest cod implementează șablonul de proiectare Proxy (Proxy Pattern) în contextul vânzării de bilete la teatru.
Clasa TheaterTicketSeller este clasa principală care este responsabilă de vânzarea efectivă a biletelor. Metoda sellTicket(show, row, seat) ar trebui să implementeze logica specifică pentru vânzarea unui bilet la un anumit spectacol, rând și loc.
În concluzie, utilizarea șablonului Proxy permite clasei TheaterTicketProxy să ofere o funcționalitate suplimentară de memorare cache pentru bilete, în timp ce își păstrează aceeași interfață ca și clasa TheaterTicketSeller reală. Aceasta ajută la optimizarea performanței și reduce timpul de acces la bilet în cazul în care același bilet este solicitat de mai multe ori.
La fel am folosit, Adapter, Bridge, Facade


LAB 4 --> În acest cod, sunt prezentați doi alți șabloni de proiectare: Visitor pattern și Mediator pattern.
La începutul codului, există o linie care importă clasa TicketCounter dintr-un fișier numit "TicketObserver.js". Este posibil ca implementarea clasei TicketCounter și a altor clase asociate să fie disponibilă în acel fișier.
În concluzie, acest cod utilizează Visitor pattern pentru a implementa o funcționalitate de vizitare a obiectelor și Mediator pattern pentru a facilita comunicarea între obiectele implicate în procesul de vânzare a biletelor.
