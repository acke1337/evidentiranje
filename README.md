# Evidentiranje uplata :Serbian Language:
Softver za evidenciju uplata <br>
Zdravo! Softver kreiran za vođenje evidencije koje uplate su proknjižene. <br>
Softver sam prvenstveno kreirao zbog sebe jer radim sa uplatama za račune kod ISP. <br>
Softver može dosta da pomogne ukoliko neka uplata nije evidentirana u "kasi". <br>
Prilikom evidencije uplate u "kasi", evidentirate i u softveru, tako da imate dokaz da je uplata prošla. <br>
Softver je jednostavan za upotrebu, izrađen je u RAD Studio 11, baza podataka je SQLite3. <br>
Nema nikakav "backdoor", sve se čuva na vašem računaru.<br>
# Registration of payments :English Language:
Software for records of payments <br>
Hello! Software created to keep track of which payments have been posted. <br>
I created the software primarily for myself because I work with ISP bill payments. <br>
The software can help a lot if a payment is not recorded in the "cash register". <br>
When recording a payment in the "cash register", you also record it in the software, so you have proof that the payment went through. <br>
The software is easy to use, it is made in RAD Studio 11, the database is SQLite3. <br>
There is no backdoor, everything is stored on your computer. <br>

# Instalacija / Installation
1. Preuzmite softver odavde / Download software
2. Postavite ga na željeno mesto / Put it somewhere in your PC.
3. Zatim iz foldera `Embarcadero/Studio/FireDAC` izvadite `FDConnections.ini` i nalepite ga u folder gde vam je `Evidentiranje.exe` i podesite lokaciju baze podataka / Then from folders `Embarcadero/Studio/FireDAC` cut `FDConnections.ini` and paste it to the folder where is `Evidentiranje.exe` and then configure path to your databse location.
4. `[evidencija_konekcija]
Database=Mesto vase baze podataka (npr. E:\Evidencija\bin\data\evidencija.db) / Path to your database (eg. E:\Evidencija\bin\data\evidencija.db)
User_Name=root LockingMode=Normal 
DriverID=SQLite`
5. Korisnicko ime i lozinka su `admin` / Username and password are `admin`
# Napomena / Caution
Trentno je softver ovako urađen, u sledećem update vam neće trebati deo iz "Instalacije 3. i 4."
Currenty software is created by this way, in the next update part of "Instalation 3. and 4." will be removed.
# Slike softvera / Images of the software

![prijava_prozor](https://github.com/acke1337/evidentiranje/assets/121731494/86cce97c-a1c6-4d3e-a413-e11da09c68ec) <br>
![sistem2](https://github.com/acke1337/evidentiranje/assets/121731494/b28aeccc-aaaf-473a-af5c-6073d4857b10) <br>
![sistem](https://github.com/acke1337/evidentiranje/assets/121731494/a0d30bc8-883d-4bef-b3ba-01629427c8af) <br>
![Dodavanje operatera](https://github.com/acke1337/evidentiranje/assets/121731494/76169f4c-efcc-466c-8bfe-b07083d96512) <br>
![oapk](https://github.com/acke1337/evidentiranje/assets/121731494/01b7d616-4615-4390-905b-af87d07c8ec0) <br>

# Vazno
Ukoliko budete imali nekih problema prilikom instalacije, slobodno me kontaktirajte na instagramu, facebooku, discordu ili otvorite issue ticket.
