Le code contenu dans ce repository est le code d'un proscreener basé sur la Moyenne mobile 20. Il utilise également d'autres indicateurs comme la Moyenne mobile 50 et les volumes. C'est une variante pour investisseur long terme du projet "Trading-proscreener-swing-trading-3-sma100" : https://github.com/SydneyJezequel/Trading-proscreener-swing-trading-3-sma100/blob/main/ProscreenerConditions

Il détecte les actif :

1- Dont l'une des conditions d'entrées suivantes est valide :

La dernière bougie croise à la hausse la moyenne mobile 20.
Le cours de clôture clôture de la dernière bougie est égal à la moyenne mobile 20.
Le plus bas de la dernière bougie est égal ou croise la moyenne mobile 20.
Le cours de clôture de la dernière bougie est proche (4% ou moins)et supérieur à la moyenne mobile 20.
Et on a une reprise potentielle de la tendance (dernière bougie haussière suite à une baisse).

2- Dont la tendance de fond répond aux conditions suivantes :

La moyenne mobile 20 est supérieure à la moyenne mobile 50.
La moyenne mobile 20 est haussière.
Le volume minimum est de 10 000.
Les moyennes mobiles 20 et 50 sont alignées à la hausse.
Le langage utilisé est ProRealcode, un langage propre à la plateforme de Trading Prorealtime. Ci-dessous des exemples d'actions détectées par le screener.


Exemple sur l’action Euronext au 30/01/2025 :
![Capture d’écran 2025-01-30 à 20 52 45](https://github.com/user-attachments/assets/fda7a2a0-9b39-4a80-aafc-33ca526b867e)


Exemple sur l’action TUBIZE-FIN au 30/01/2025 :
![Capture d’écran 2025-01-30 à 20 57 50](https://github.com/user-attachments/assets/3e1d8e88-2b87-49a5-afcc-74c632b00ae6)


Exemple sur l’ETF AMUNDI ETF MSCI WR au 30/01/2025 :
![Capture d’écran 2025-01-30 à 20 54 44](https://github.com/user-attachments/assets/d25749a8-72f9-4c7d-ba9d-49d5be55b326)


Exemple sur l’ETF AMUNDI PHYS GOLD au 30/01/2025 :
![Capture d’écran 2025-01-30 à 20 56 29](https://github.com/user-attachments/assets/8a8a9001-a50b-4614-a3a0-97ef4c539831)
