# JavaProiectJocFotbal
Aplicatie care sa gestioneze meciurile de fotbal.

#Datele
--Posibilitatea ca importul echipelor sa se faca printr-un api de import din csv si excel sau si prin apelare de webservice(Json)
--
Liste de jucatori. 
Atributele jucatorilor
--Nume
--Pozitie
--Echipa
--Varsta
--Coeficient


Lista de echipe.
--Nume echipa
--Numar jucatori
--Componenta echipa 
--Numar de puncte
--Culoare echipament


metoda  finalmeci (echipa1, echipa2, scor1, scor2)
{
--afli castigatoare
--memorezi meciul in baza
--incrementezi punctele echipei

}

Metode Echipa:
--Creat echipa
--inserezi o lista de jucatori 



finaletapa (echipa1,echipa2,echipa3)
{
sortare pe ele dupa numarul de pct. Daca numarul de pct e egal bagi golaverajul
}

Repository
metoda Totalul punctelor pe echipa  interval
metoda Totalul golurilor date pe echipa pe interval
metoda Totalul golurilor primite pe echipa
metoda Totalul golurilor primite de la cine 



--UI
Trebuie sa gestionam adaugare de jucatori si de echipe
Echipele din etapa respectiva


#Cookies 
 


clasa echipa {
String nume;
int  nrJucatori;
componenta List<jucatori>;
in numarpct
}

--##de aratat Bogdan  jucatorul sa deriveze din echipa 
Clasa jucatori
{
echipa ;
}


clasa jucator extends echipa 
{
};
