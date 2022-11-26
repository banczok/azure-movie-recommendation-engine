# Cel 
Prosta applikacja webowa do rekomendacji filmów.

# Opis działa  projektu 
Użytkownik podaje filmy, które mu się podobałają a nastepnie strona zwraca przynajmniej 10 propozycji filmów do obejrzania.


![obraz](https://user-images.githubusercontent.com/66008982/202915524-e50b310a-4e30-461d-9445-f66ef70cb3c4.png)


# Opis funkcjanalności 
- Prosta, szybka aplikacja webowa bez logowania. 
- Do rekomendacji wystarczy podać chociaż jeden film. 
- Program działający w chmurze Azura. 

?# azure-movie-recommendation-engine
# Schemat

![obraz](https://user-images.githubusercontent.com/66008982/202915524-e50b310a-4e30-461d-9445-f66ef70cb3c4.png)



# Opis projektu 
Projektu składał się z trzech cześci:
- załadowanie filmów do bazy [data_loading/README](data_loading/README.md) 
- aplikacji webowej [movie-re-app/README](movie-re-app/README.md) 
- modelu rekomendacji  [machine-learning/README](machine-learning/README.md) 


# Wybrane stos technologiczny
- Azure postgres - Baza filmów oraz oceń uzytkowników z IMD.
- Azure machine learning studio - Tworzenie endpointu z modelem rekomendacji. 
- Azure Kubernetes Service - Api modelu rekomendacji.
- Azure Web app - Aplikacja webowa. 






