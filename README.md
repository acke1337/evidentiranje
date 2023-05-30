# Evidentiranje uplata
Softver za evidenciju uplata <br>
Zdravo! Softver kreiran za vođenje evidencije koje uplate su proknjižene. <br>
Softver sam prvenstveno kreirao zbog sebe jer radim sa uplatama za račune kod ISP. <br>
Softver može dosta da pomogne ukoliko neka uplata nije evidentirana u "kasi". <br>
Prilikom evidencije uplate u "kasi", evidentirate i u softveru, tako da imate dokaz da je uplata prošla. <br>
Softver je jednostavan za upotrebu, izrađen je u RAD Studio 11, baza podataka je SQLite3. <br>
Nema nikakav "backdoor", sve se čuva na vašem računaru.<br>

# Instalacija
1. Preuzmite softver odavde
2. Postavite ga na željeno mesto
3. Zatim u `C:\Users\Public\Public Documents` nalepite folder `Embarcadero` ( ako nemate RAD Studio ) a ako imate, dodajte sledeće u `FDConnections.ini` 
4. `[evidencija_konekcija]
Database=Mesto vase baze podataka (npr. E:\Evidencija\bin\data\evidencija.db) 
User_Name=root LockingMode=Normal 
DriverID=SQLite`
# Napomena
Trentno je softver ovako urađen, u sledećem update vam neće trebati deo iz "Instalacije 3. i 4."
# Slike softvera

![prijava_prozor](https://github.com/acke1337/evidentiranje/assets/121731494/86cce97c-a1c6-4d3e-a413-e11da09c68ec) <br>
![sistem2](https://github.com/acke1337/evidentiranje/assets/121731494/b28aeccc-aaaf-473a-af5c-6073d4857b10) <br>
![sistem](https://github.com/acke1337/evidentiranje/assets/121731494/a0d30bc8-883d-4bef-b3ba-01629427c8af) <br>
![Dodavanje operatera](https://github.com/acke1337/evidentiranje/assets/121731494/76169f4c-efcc-466c-8bfe-b07083d96512) <br>
![oapk](https://github.com/acke1337/evidentiranje/assets/121731494/01b7d616-4615-4390-905b-af87d07c8ec0) <br>

# Vazno
Ukoliko budete imali nekih problema prilikom instalacije, slobodno me kontaktirajte na instagramu, facebooku, discordu ili otvorite issue ticket.
