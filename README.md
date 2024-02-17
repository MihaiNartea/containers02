## Lucrare de laborator nr.2

## Nume
Prima aplicație Docker.

## Scopul
Scopul lucrarii de laborator:
+ Familiariza cu elementele de bază ale containerizării.
+ Pregătirea spațiului de lucru pentru următoarele lucrări de laborator.

## Sarcina
Instalarea Docker Desktop si verificarea acestuia.

## Pasii efectuati
Executiile efectuate.
- Prima executie `docker build -t containers02 .` - contruieste imaginea.
  - Cât timp a durat crearea imaginii? - **Building 20.8s**

- A doua executie `docker run --name=containers02 containers02` - executa imaginea creata.
  - Ce a fost afișat în consolă? -
    ```
    hello from 00b50b3da101
    ```

- A treia executie `docker rm containers02` si `docker run -ti --name containers02 containers02 bash`. - Am sters containerul cu numele **containers02**, dupa executarea repetata am accesat imaginea.
  - In fereastra deschisa am executat `cd /var/www/html/` si `ls -l`
    - Ce este afișat pe ecran? - **-rwxr-xr-x 1 root root 215 Feb 17 10:20 index.html**

## Concluzii
Cu ajutorul acestei lucrari de laborator, m-am familiarizat cu elementele de baza ale contanizarii si am pregatit spatiul de lucru pentru urmatoarele lucrari de laborator.

## Bibliografie
`https://moodle.usm.md/mod/assign/view.php?id=282515`
