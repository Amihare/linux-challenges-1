## Challenge 1

- Mettre à jour ubuntu :

```sudo apt update -y && sudo apt upgrade -y```

- En ligne de commande, télécharger l’image : https://promo-159.codeur.online/photo/surprise.jpg et la nommer image.jpg

```wget --output-document=image.jpg https://promo-159.codeur.online/photo/surprise.jpg```

- En ligne de commande réduire sa qualité de 50% et nommer cette nouvelle image image_converted.jpg

```
sudo apt install imagemagick
convert -resize 50% image.jpg image_converted.jpg
```

- [X] Rendu : toutes les lignes de commandes que vous avez tapées et l’image finale.
