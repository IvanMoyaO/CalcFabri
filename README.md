# Calculadora Cota Fabricación SJ11
## https://ivanmoyao.github.io/CalcFabri/

[En el Informe](https://github.com/IvanMoyaO/Fabricacion), los planos se han incluido en formato .pdf para que no pierdan calidad, y se han ajustado para que quepan correctamente en la página (la alternativa era que no se mostrara el encabezado):
```latex
\begin{figure}
    \centering
    \includegraphics[width=\linewidth]{...}
\end{figure}
```
`\linewidth` indica que ha de ser tan ancho como una línea (valor que podemos hallar usando `\the\linewidth` y ronda los 470 puntos). Es decir, estamos _escalando_ la imagen (en .pdf). Por tanto, las cotas no coincidrán con los valores que mediremos en el plano.

Esta calculadora realiza una sencilla operación que bien permite "predecir" (directo )lo que mediremos, a partir de una cota, o bien devolver el valor que indicará la cota (inverso) a partir de lo que midamos.

Se ha usado JavaScript para la funcionalidad, junto con Bootstrap para el diseño. Es extremadamente básica, limitada y muy mejorable.
