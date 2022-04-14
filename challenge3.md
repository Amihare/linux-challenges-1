# Challenge 3
- Dans le dossier « Challenges » créer un script qui prend en paramètre un chiffre et qui calcule sa table de multiplication (de 0 à 10)
- [ ] Rendu : un fichier markdown contenant  contenant votre script

```touch multiplication```

- Donner les droits sur le fichier : 

```chmod +x multiplication```

- modifier le fichier : 

```nano multiplication```

- Créer le script :

```  
#!/bin/bash
echo "Entrez un chiffre :"
read -r chiffre
echo 'Votre chiffre est :' $chiffre

for (( i=0 ; i<10 ; i++ ))
 do
  echo $((chiffre*i))
 done
 ```
 
 - Lancer le script : 

```./multiplication```
