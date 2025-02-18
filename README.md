# Práctica 2 - Inteligencia Computacional
## Implementación de algoritmos genéticos (QAP)

### Algoritmos genéticos estándares
El algoritmo genético constituye una metodología metaheurística basada en la biología evolutiva, que utiliza técnicas como selección, cruce y mutación para generar soluciones aproximadas a problemas complejos. En este informe se describen detalladamente los componentes fundamentales del algoritmo genético diseñado, los resultados obtenidos durante las ejecuciones, y los parámetros configurados para lograr un balance adecuado entre exploración y explotación en el espacio de búsqueda.

### Algoritmos genéticos con variante baldwiniana
La variante baldwiniana del algoritmo genético incorpora técnicas de optimización local, como heurísticas greedy o búsqueda local mediante ascensión de colinas, para dotar a los individuos de la población de capacidad de aprendizaje. En esta estrategia, la evaluación del fitness de cada individuo se realiza después de aplicar una búsqueda local, pero las mejoras obtenidas no alteran el material genético original empleado para generar descendencia. Este enfoque permite mejorar la calidad de las soluciones evaluadas sin comprometer la diversidad genética de la población.

### Algoritmos genéticos con variante lamarckiana
Esta variante lamarckiana combina los principios evolutivos de los algoritmos genéticos con técnicas de optimización local, permitiendo que las mejoras logradas mediante un procedimiento de Hill Climbing optimizado se integren directamente en el material genético de los individuos. Esto significa que las adaptaciones obtenidas durante el proceso de optimización local son transmitidas a las siguientes generaciones, en línea con el principio lamarckiano de herencia de características adquiridas.
