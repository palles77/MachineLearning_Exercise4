# Wskazówka 
Dla zadań na oceny od 3.0 do 3.5 użyć przykładu z pliku 'agglomerative_clustering.ipynb'

# Zadania na ocenę 3.0
Pomoc https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html
1. Przeprowadzić klasteryzację dla par kolumn 'Total Salary', 'Retirement'
2. Pokazać wynik klasteryzacji w postaci dendrogramów dla poniższych typów linkage: 'ward', 'complete', 'average', 'single'.
     Jako dendrogramu użyć przykładu z komórki 18 (Drawing Dendrogram)
3. Dla każdego z dendrogramów wybrać wizualnie liczbę klastrów i pokazać ich ułożenie w sposób podobny 
     jak w komórce  nr 21 (Drawing Clusters). Dopasować odpowiednio kod do wybranej liczby klastrów
4.  Która z klasteryzacji jest najlepsza? Podać przyczyny decyzji.
5. Dla wybranej z pkt 1.3 klasteryzacji użyć różnych rodzajów parametru 'affinity' w funkcji AglomerativeClustering. Przeprowadzić eksperymenty dla metod 'euclidean', 'l1', 'l2', 'manhattan', 'cosine', 'precomputed'.
6. Który z wybranych dystansów daje najlepsze wyniki i dlaczego?

# Zadania na ocenę 3.5 (wykonać zadania na ocenę 3.0)
7. Wykonać te same eksperymenty co w pkt 1 do 5 dla par 'Total Benefits', 'Total Compensation'
8. Wykonać te same eksperymenty co w pkt 1 do 5 dla par 'Health/Dental', 'Other Benefits'

# Zadanie na ocenę 4.0 (wykonać zadania na ocenę 3.5)
9. Na podstawie przykładu https://realpython.com/k-means-clustering-python/ Wygenerować zbiór złożony z 1000 przykładów, 5 centrów, standardowym odchyleniem 2.5
10. Wyskalować dane używając StandardScaler()
11. Zainicjiować klasteryzację KMeans dla 5 klastrów
12. Wykonać wykres współczynnika SSE (Sekcja 'Choosing the Appropriate Number of Clusters')
13. Wykonać wykres współczynnik Silhouette Coefficient.
14. Przeprowadzić dyskusję odnośnie optymalnej ilości klastrów

# Zadanie na ocenę 4.5 (wykonać zadania na ocenę 4.0)
15. Przeprowadzić dyskusję odnośnie porównania klasteryzacji 'KMeans' oraz 'DBSCAN'.
    Więcej w sekcji 'Evaluating Clustering Performance Using Advanced Techniques' z adresu https://realpython.com/k-means-clustering-python/

# Zadanie na ocenę 5.0 (wykonać zadania na ocenę 4.5)

16. Na podstawie danych z https://raw.githubusercontent.com/palles77/MachineLearning_Exercise4/main/Employee_Compensation_SF.csv
wybrać losowo 10000 rekordów. 
17. Przeprowadzić minimalizację SVD dla klas zdefiniowanych w kolumnie 'Job'. 
18. Przeprowadzić minimalizację CUR dla klas zdefiniowanych w kolumnie 'Job'. 
19. Pokazać wykres dla pierwszych dwóch najważniejszych par cech dla SVD. Jakie to cechy?
20. Pokazać wykres dla pierwszych dwóch najważniejszych par cech dla CUR. Jakie to cechy?
21. Pokazać wykres dla drugiej pary najważniejszych par cech dla SVD. Jakie to cechy?
22. Pokazać wykres dla drugiej pary najważniejszych par cech dla CUR. Jakie to cechy?

Wskazówka: Przykład przeprowadzenia prowadzenia minimalizacji SVD oraz CUR jest w pliku 'dimensionality_reduction.ipynb'

# Ostatnie zmiany
2022/01/30
