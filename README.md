# task

Biblioteci utilizate:
 - pandas
 - csv
   
Avem 3 datasets: 
  facebook_dataset.csv
  website_dataset.csv
  google_dataset.csv

Urmam urmatorii pasi:
  - Vizualizarea datelor daca sunt aranjate corect (exista probleme la citirea datelor din website_dataset. Folosim un delimitator pentru a citi datele corect.
  - Verificam valorile unice din csv-uri
  - ![image](https://github.com/user-attachments/assets/d825a906-c51e-4a2d-896a-80636fb46cbf)
  - ![image](https://github.com/user-attachments/assets/b09022b1-8830-4d5d-8334-5e0e93e5dd06)
  - ![image](https://github.com/user-attachments/assets/248db470-c79e-4fbd-a466-39528af9bcf6)

    Coloana phone este prezenta in cele 3 csv-uri cu un volum mare de date.
    Realizam o filtrare pe coloana phone deoarece exista mai multe formate de telefon sau caractere speciale.

    Operatia de unire este realizata in bucati (chunks) pentru a economisi memoria iar numerele de telefon sunt curatate pentru a pastra doar cifrele.

    Actiuni necesare:
       - eliminarea duplicatelor;
       - eliminarea caracterelor speciale;
       - eliminarea cuvinteler precum 'ltd';
       - analiza datelor cat % din date se regasesc si in celelalte datasets;
       - pentru a verifica prezenta datelor in celelalte datasets putem folosi - Fuzzy matching(best_match_score)
         

    
  Raspunsuri la intrebari:
  Q: What column will you use to join?
    - Imbinarea se poate face dupa coloana phone
  Q: If you have data conflicts once you join, which one do you believe?
    - Se aleg datele din csv care contin cat mai multe informatii 
  Q: If you have very similar data, what information will you keep? 
    - Cand avem date similare verficam: 
        - daca datele sunt complete;
        - eliminare duplicate;
        
    

#PythonBeginner

  
