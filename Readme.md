# Wskazówka 
Dla zadań na oceny od 3.0 do 3.5 użyć przykładu z pliku 'agglomerative_clustering.ipynb'

# Zadania na ocenę 3.0
Pomoc https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html
1. Przeprowadzić klasteryzację dla par kolumn 'Total Salary', 'Retirement'
1.1 Pokazać wynik klasteryzacji w postaci dendrogramów dla poniższych typów linkage: 'ward', 'complete', 'average', 'single'.
     Jako dendrogramu użyć przykładu z komórki 18 (Drawing Dendrogram)
1.2 Dla każdego z dendrogramów wybrać wizualnie liczbę klastrów i pokazać ich ułożenie w sposób podobny 
     jak w komórce  nr 21 (Drawing Clusters). Dopasować odpowiednio kod do wybranej liczby klastrów
1.3 Która z klasteryzacji jest najlepsza? Podać przyczyny decyzji.
1.4 Dla wybranej z pkt 1.3 klasteryzacji użyć różnych rodzajów parametru 'affinity' w funkcji AglomerativeClustering. Przeprowadzić eksperymenty dla metod 'euclidean', 'l1', 'l2', 'manhattan', 'cosine', 'precomputed'.
1.5 Który z wybranych dystansów daje najlepsze wyniki i dlaczego?

# Zadania na ocenę 3.5 (wykonać zadania na ocenę 3.0)
2.0 Wykonać te same eksperymenty co w pkt 1.1 do 1.5 dla par 'Total Benefits', 'Total Compensation'
3.0 Wykonać te same eksperymenty co w pkt 1.1 do 1.5 dla par 'Health/Dental', 'Other Benefits'

# Zadanie na ocenę 4.0 (wykonać zadania na ocenę 3.5)
Na podstawie przykładu https://realpython.com/k-means-clustering-python/
4.1 Wygenerować zbiór złożony z 1000 przykładów, 5 centrów, standardowym odchyleniem 2.5
4.2 Wyskalować dane używając StandardScaler()
4.3 Zainicjiować klasteryzację KMeans dla 5 klastrów
4.4 Wykonać wykres współczynnika SSE (Sekcja 'Choosing the Appropriate Number of Clusters')
4.5 Wykonać wykres współczynnik Silhouette Coefficient.
4.6 Przeprowadzić dyskusję odnośnie optymalnej ilości klastrów

# Zadanie na ocenę 4.5 (wykonać zadania na ocenę 4.0)
4.7 Przeprowadzić dyskusję odnośnie porównania klasteryzacji 'KMeans' oraz 'DBSCAN'.
    Więcej w sekcji 'Evaluating Clustering Performance Using Advanced Techniques' z adresu https://realpython.com/k-means-clustering-python/

# Zadanie na ocenę 5.0 (wykonać zadania na ocenę 4.5)

Na podstawie danych z https://raw.githubusercontent.com/palles77/MachineLearning_Exercise4/main/Employee_Compensation_SF.cs
wybrać losowo 10000. Jako klasy badanej użyć kolumny 'O
5.1 Przeprowadzić minimalizację SVD dla klas zdefiniowanych w kolumnie 'Job'. 
5.2 Przeprowadzić minimalizację CUR dla klas zdefiniowanych w kolumnie 'Job'. 
5.3 Pokazać wykres dla pierwszych dwóch najważniejszych par cech dla SVD. Jakie to cechy?
5.4 Pokazać wykres dla pierwszych dwóch najważniejszych par cech dla CUR. Jakie to cechy?
5.5 Pokazać wykres dla drugiej pary najważniejszych par cech dla SVD. Jakie to cechy?
5.6 Pokazać wykres dla drugiej pary najważniejszych par cech dla CUR. Jakie to cechy?

Wskazówka: Przykład przeprowadzenia prowadzenia minimalizacji SVD oraz CUR jest w pliku 'dimensionality_reduction.ipynb'

# Ostatnie zmiany
2022/01/30
