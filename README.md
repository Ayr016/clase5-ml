Clase 5 - KNN vs Arbol 

Dataset: Iris (sepal length, sepal width)  
Modelos: KNN k=15 (uniform y distance) · Árbol max_depth=4  

Probé K-NN (k=15, con uniform y distance) y un Árbol de Decisión (max_depth=4) sobre Iris usando las dos variables. En el conjunto de test todos quedaron bastante parejos en accuracy (porcentaje de aciertos). En mis corridas, K-NN con distance rindió un poquito mejor cuando las clases se mezclan, porque da más peso a los vecinos cercanos. El Árbol me sirve para explicar (reglas e importancias), pero sus fronteras son más rígidas. Si priorizo interpretacion, elijo Árbol, si quiero exprimir un poquito más los aciertos y no necesito tantas explicaciones, voy con K-NN



