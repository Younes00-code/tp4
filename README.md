Web Service SOAP

Ce projet Java JAX-WS met en place un Web Service SOAP simple qui fournit les fonctionnalités suivantes :
-Conversion de montants de l’euro vers le dirham marocain
-Consultation d’un compte bancaire par ID
-Consultation de la liste de tous les comptes bancaires disponibles

Déploiement du Web Service avec JAX-WS
Serveur JAX-WS
Le Web Service a été exposé à l’aide d’un serveur JAX-WS simple, sans conteneur externe 
![image](https://github.com/user-attachments/assets/1dbb2347-d112-42ed-9fef-de317024821a)


L’interface WSDL est générée automatiquement et disponible via un navigateur à l’URL :
http://localhost:9090/BanqueWS?wsdl

Analyse du WSDL
Le fichier WSDL (Web Services Description Language) est accessible et lisible depuis le navigateur à l’URL :
http://localhost:9090/BanqueWS?wsdl
![image](https://github.com/user-attachments/assets/7edd850d-01ef-47ec-bbed-4e5bd0c0226c)

Il décrit les opérations exposées par le Web Service, les types de données, les ports, et les bindings SOAP.

Test avec SoapUI
Import du WSDL
Test de chaque opération (conversionEuroToDH, getCompte, getComptes)
Visualisation des requêtes/ réponses XML
![image](https://github.com/user-attachments/assets/1674b2c1-ba72-41bf-905d-37ce1bcd339c)
![image](https://github.com/user-attachments/assets/ca331274-4489-43b1-bf74-618a17a9abd2)
![image](https://github.com/user-attachments/assets/c2f95af0-0ddc-4d65-bc4d-4d69b612cc04)



