# Projet_Analyse_Num2021

<h1>Sommaire:</h1>

<ul>
  <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#introduction-g%C3%A9n%C3%A9ral">Introduction Générale</a>
    </li>
  <li>
    <a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#etude-dune-fonction--">
      Etude d'une fonction</a>
    <ul>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-1but-">But</a>
        </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-2etude-de-fonction">
        Etude de fonction</a>
        </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-3etude-graphique">Etude Graphique</a>
      </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-4etude-de-primitive-">
        Etude de primitive</a>
        </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-5etude-de-d%C3%A9riv%C3%A9">
        Etude de dérivé</a>
        </li>
      <ul><li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-5aordre-de-d%C3%A9riv%C3%A9"> 
        Ordre de dérivé</a>
        </li></ul>
   </ul>
  </li>
  <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-m%C3%A9thodes-dint%C3%A9gration-num%C3%A9rique">
    Methode d'intégration numérique </a>
    <ul>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-1but">
        But</a>
        </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-2m%C3%A9thode-de-r%C3%A9ctangle">
        Méthode de Réctangle</a>
        </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-3m%C3%A9thode-des-trap%C3%A8zes">
        Méthode des Trapézes</a>
        </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-4m%C3%A9thode-de-simpson">
        Méthode de Simpson</a>
        </li>
      <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-5m%C3%A9thode-des-points-milieux">
        Méthode des Points Milieux</li>
    </ul>
  </li>
  <li><a href="https://github.com/aminkammoun/AnalyseNUMERIQUE/tree/master/projet/README.md#-conclustion-et-perspectives">
    Conclustion et perspectives </a></li>
</ul>

<h1>Introduction général:</h1>

<h1>Etude d'une fonction : </h1>

<h2> 1.But </h2>

<h2> 3.Etude graphique:</h2>

<h2> 4.Etude de primitive :</h2>

<h2 > 5.Etude de dérivé:</h2>

 <h3> 5.a.Ordre de dérivé:</h3>
<h1>Demo</h1>
<hr>
<img src="https://github.com/aminkammoun/AnalyseNUMERIQUE/blob/master/projet/Pictures/first_demo.gif" alt="Calculer le dérive et prémitive de f(x) et afficher les 3 courbes" width="800" height="400">
<img src="https://github.com/aminkammoun/AnalyseNUMERIQUE/blob/master/projet/Pictures/demo_mrthods.gif" alt="Calculer la valeur exacte d'un itégrale et calculer et afficher la valeur approché ansi que l'erreur d'une méthode d'analyse numérique" width="800" height="400">


<h1> Méthodes d'intégration numérique:</h1>

<h2> 1.But</h2>
<p>Le but  est d’aborder le calcul général de l’intégrale d’une fonction  <a href="https://www.codecogs.com/eqnedit.php?latex=C^{(n)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?C^{(n)}" title="f(x)" /></a> sur un domaine fini délimité par des bornes finies a et b.</p>

<h2> 2.Méthode de Réctangle:</h2>
<FONT FACE="Arial, Helvetica, sans-serif" size="4">Cette méthode, très élémentaire, basée sur les sommes de Cauchy-Riemann (approchant l'aire sous une courbe) et appliquée à une fonction f continue, permet le calcul approché d'intégrales en choisissant une subdivision régulière de pas </Font> <br/>
<a href="https://www.codecogs.com/eqnedit.php?latex=xi&plus;1&space;-&space;xi&space;=&space;\frac{(b-a)}{n}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?xi&plus;1&space;-&space;xi&space;=&space;\frac{(b-a)}{n}" title="xi+1 - xi = \frac{(b-a)}{n}" /></a>

<p>donc indépendant de i avec une valeur de n <i>"suffisamment grande"</i>.</p>
<FONT FACE="Arial, Helvetica, sans-serif" size="4">On obtient une succession de rectangles en rose ci-contre, d'où le nom de cette méthode, approchant l'aire sous la courbe,  où ci est choisi ici au "milieu" de </FONT> <br/>
<a href="https://www.codecogs.com/eqnedit.php?latex=[xi&space;,&space;xi&plus;1]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?[xi&space;,&space;xi&plus;1]" title="[xi , xi+1]" /></a>
<p>On calcule :</p>
<a href="https://www.codecogs.com/eqnedit.php?latex=S_{n}&space;=&space;h&space;*&space;\sum&space;f(c_{i})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{n}&space;=&space;h&space;*&space;\sum&space;f(c_{i})" title="S_{n} = h * \sum f(c_{i})" /></a>
<p><b>i variant de 0 à n - 1</b></p>
<p>Avec : </p>
<a href="https://www.codecogs.com/eqnedit.php?latex=h&space;=&space;\frac&space;{b-a}{n}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?h&space;=&space;\frac&space;{b-a}{n}" title="h = \frac {b-a}{n}" /></a> <br/>
<a href="https://www.codecogs.com/eqnedit.php?latex=x_i&space;=&space;a&space;&plus;&space;i.h" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x_i&space;=&space;a&space;&plus;&space;i.h" title="x_i = a + i.h" /></a> <br/>
<a href="https://www.codecogs.com/eqnedit.php?latex=c_i&space;=&space;(x_i&plus;1&space;&plus;&space;x_i)/2&space;=&space;a&space;&plus;&space;i.h&space;&plus;&space;\frac&space;{h}{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?c_i&space;=&space;(x_i&plus;1&space;&plus;&space;x_i)/2&space;=&space;a&space;&plus;&space;i.h&space;&plus;&space;\frac&space;{h}{2}" title="c_i = (x_i+1 + x_i)/2 = a + i.h + \frac {h}{2}" /></a>
<p>Le passage à la limite fournit l'intégrale cherchée</p>
<h2> 3.Méthode des trapèzes:</h3>

<FONT FACE="Arial, Helvetica, sans-serif" size="4">l'interpolation linéaire par intervalles.</FONT> </br>
<a href="https://www.codecogs.com/eqnedit.php?latex=\int_{a}^{b}&space;f(x)dx" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\int_{a}^{b}&space;f(x)dx" title="\int_{a}^{b} f(x)dx" /></a>

<FONT FACE="Arial, Helvetica, sans-serif" size="4">Le principe est d'assimiler la région sous la courbe représentative d'une fonction f définie sur un segment </br>
<a href="https://www.codecogs.com/eqnedit.php?latex=[a&space;,&space;b]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?[a&space;,&space;b]" title="[a , b]" /></a> à un trapèze et d'en calculer l'aire T :</FONT>
<br/><a href="https://www.codecogs.com/eqnedit.php?latex=T&space;=&space;(b-a)&space;\frac{f(a)&plus;f(b)}{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?T&space;=&space;(b-a)&space;\frac{f(a)&plus;f(b)}{2}" title="T = (b-a) \frac{f(a)+f(b)}{2}" /></a>

<h2> 4.Méthode de simpson:</h2>

<h2> 5.Méthode des points milieux:</h2>

<h1> Conclustion et perspectives</h1>
