# Sales Data Exploratory Analysis

## Objective

This project analyzes a sales dataset to understand sales performance across products, categories, and cities.

The objective is to clean the data, explore its main characteristics, visualize important patterns, and extract useful insights.

## Dataset

The dataset contains sales orders with information about products, categories, prices, quantities, customers, and cities.

## Analysis

The project includes:

* Data understanding and inspection
* Data cleaning
* Feature engineering
* Exploratory Data Analysis (EDA)
* Data visualization
* Correlation analysis
* Interpretation of the results

## Tools

* Python
* Pandas
* NumPy
* Matplotlib

## Key Insights

1. Produits — Revenue
Les Phones génèrent le revenue total le plus élevé du dataset. Cela semble notamment lié à leur prix unitaire relativement élevé et au fait que plusieurs commandes concernent ce produit.
2. Quantités achetées
Les produits les moins chers, notamment les Chargers et les Headphones, ont tendance à être achetés en plus grande quantité que les produits plus chers comme les Phones. Cela suggère une relation négative entre le prix et la quantité achetée dans ce dataset.
3. Catégories
La catégorie Electronics génère nettement plus de revenue que la catégorie Accessories. Cela semble notamment s'expliquer par les prix plus élevés des produits Electronics, qui comprennent les Phones et Tablets, alors que les Accessories contiennent des produits moins chers comme les Chargers et Headphones.
4. Villes
Lyon génère le revenue total le plus élevé. Bien que le nombre de commandes soit assez proche de celui de Paris, l'écart de revenue est important. Cela suggère que le nombre de commandes seul n'explique pas le revenue : la composition des commandes, notamment le type de produit, son prix et la quantité achetée, joue également un rôle important.
5. Relation entre le prix et la quantité achetée
Après le nettoyage des données, on observe que les produits ayant un prix élevé ont tendance à être achetés en plus petites quantités, tandis que les produits moins chers sont généralement achetés en plus grande quantité. Cette relation est visible dans le scatter plot et suggère une association négative entre le prix et la quantité. Cependant, cette observation ne permet pas de conclure à une relation de causalité.

\## Future Improvements



\- Perform deeper statistical analysis

\- Explore additional relationships between variables

\- Apply the analysis to a larger real-world dataset

