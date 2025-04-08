# DP-203_Lab5
# Data-analyse in een Data Lake met Apache Spark en Azure Synapse Analytics

Dit project demonstreert hoe je grote hoeveelheden gegevens kunt verkennen, verwerken en analyseren in een data lake met behulp van Apache Spark in een Azure Synapse Analytics-omgeving. Het is gebaseerd op een hands-on lab uit de Microsoft Learn DP-203 cursus.

## Inhoud

- Opzetten van een Azure Synapse Analytics werkruimte met een Apache Spark pool
- Verkennen van gegevens in een Azure Data Lake Storage Gen2
- Gebruik van PySpark DataFrames voor het laden, filteren en groeperen van gegevens
- Uitvoeren van analyses met Spark SQL
- Visualisatie van resultaten met behulp van Matplotlib en Seaborn

## Benodigdheden

- Een actieve Azure-abonnement met beheerdersrechten
- Toegang tot de Azure Portal
- Basiskennis van Python en SQL

## Stappen

1. **Provisioneren van Azure Resources**  
   Met behulp van een PowerShell-script en ARM-template wordt automatisch een Synapse werkruimte, een Data Lake en een Spark pool aangemaakt.

2. **Verkennen van Data in de Data Lake**  
   CSV-bestanden met verkooporders worden geanalyseerd in een `sales/orders` map.

3. **Laden en Verwerken van Data met PySpark**  
   Data wordt geladen in een DataFrame en gestructureerd via een schema. Vervolgens worden filters toegepast en aggregaties uitgevoerd.

4. **SQL Queries met Spark SQL**  
   Er worden tijdelijke views gecreëerd waarmee SQL-query’s kunnen worden uitgevoerd.

5. **Visualisatie**  
   Analyse resultaten worden gevisualiseerd via Matplotlib en Seaborn, inclusief staafdiagrammen en lijndiagrammen.

6. **Opruimen van Resources**  
   Na voltooiing worden alle resources verwijderd om kosten te vermijden.

## Screenshots

📊 *Voeg hier eventueel enkele screenshots toe van je Synapse Studio omgeving of gegenereerde grafieken.*

## Auteur

- **Naam:** [Zehra Okay]

## Licentie

Dit project is gebaseerd op Microsoft Learn materiaal en bedoeld voor educatieve doeleinden.

![Schermafbeelding 2025-04-08 001647](https://github.com/user-attachments/assets/32e235d5-44b8-41ca-8e46-d8701c304f64)
![Schermafbeelding 2025-04-08 003717](https://github.com/user-attachments/assets/98a5dd9a-bf87-4d23-b762-a41d1336afb1)
![Schermafbeelding 2025-04-08 003837](https://github.com/user-attachments/assets/8086ac61-df88-4363-8a52-f1e61b295354)
![Schermafbeelding 2025-04-08 005100](https://github.com/user-attachments/assets/1ea39055-333a-4c28-a596-307d821194b0)
![Schermafbeelding 2025-04-08 010811](https://github.com/user-attachments/assets/86690c14-020d-4789-8f5e-74333e1d0db9)
![Schermafbeelding 2025-04-08 011027](https://github.com/user-attachments/assets/4d2a1428-816d-45c1-a75b-7476ed9aa36a)
![Schermafbeelding 2025-04-08 011255](https://github.com/user-attachments/assets/a363dc06-56db-403a-894c-f467c7ca2f5c)
![Schermafbeelding 2025-04-08 011553](https://github.com/user-attachments/assets/7f626a02-0c57-4219-aad6-ad13683002ea)
![Schermafbeelding 2025-04-08 011641](https://github.com/user-attachments/assets/2997b8c2-f2e5-4a9b-b973-30a3cbc66bda)









