Do obliczeń naukowych i inżynierskich przy pomocy języka python często wykorzystuje się rozszerzenie Scipy, dostępne jako oprogramowanie typu open source, zbudowane na rozszerzeniu 
NumPy Pythona. 
Pakieta zawiera procedury matematyczne i numeryczne w postaci szybkich prekompilowanych funkcji. Scipy jest pakietem zawierającym implementacje szeregu procedur numerycznych, 
takich jak całkowanie i różniczkowanie numeryczne, algorytmy rozwiązywania równań różniczkowych, algorytmy z algebry liniowej, funkcje specjalne, narzędzia do programowania 
równoległego i wiele innych. Co do zasady, Scipy powinien zawierać procedury numeryczne. 

Biblioteka Scipy udostępnia obszerny zbiór procedur matematycznych i numerycznych, podzielonych na następujące działy:
-Clustering package / Algorytmy grupowania(scipy.cluster)
-Constants /Stałe fizyczne i matematyczne (scipy.constants)
-Discrete Fourier transforms / Procedury szybkiej transformacji Fouriera (scipy.fftpack)
-Integration and ODEs / Solvery całkowania i zwykłych równań różniczkowych (scipy.integrate)
-Interpolation / Interpolacje (scipy.interpolate)
-Input and output / Wejście i wyjście (scipy.io)
-Linear algebra / Algebra liniowa (scipy.linalg)
-Miscellaneous routines (scipy.misc)
-Multi-dimensional image processing / N-wymiarowe przetwarzanie obrazu (scipy.ndimage)
-Orthogonal distance regression / Ortogonalna regresja odległości (scipy.odr)
-Optimization and root finding / Procedury optymalizacji i wyszukiwania rootów (scipy.optimize)
-Signal processing / Przetwarzanie sygnałów (scipy.signal)
-Sparse matrices / Rzadkie macierze i powiązane z nimi procedury (scipy.sparse)
-Spatial algorithms and data structures / Struktury i algotytmy danych przestrzennych (scipy.spatial)
-Special functions / Funckje specjalne (scipy.special)
-Statistical functions / Rozkłady i funckje statystyczne (scipy.stats)
-C/C++ integration (scipy.weave)

INSTALACJA PAKIETU POPRZEZ WIERSZ POLECEŃ:
python -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose

IMPORT PAKIETU: 
>>> import matplotlib as mpl

Pakiety SciPy należy importować osobno, na przykład:
>>> from scipy import linalg, optimize


Dokumentacja do SciPy: https://docs.scipy.org/doc/
