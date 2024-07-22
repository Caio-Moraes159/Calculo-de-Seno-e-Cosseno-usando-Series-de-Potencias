<h1>Cálculo de Seno e Cosseno usando Séries de Potências</h1>

<p>Este projeto calcula o seno e o cosseno de um ângulo utilizando séries de potências e compara os resultados com as funções <code>cos()</code> e <code>sin()</code> da biblioteca <code>cmath</code>.</p>

<h2>Funcionalidades</h2>
<ul>
    <li>Calcula seno e cosseno para 3 e 40 termos das séries de potências.</li>
    <li>Compara com os valores obtidos pelas funções <code>cos()</code> e <code>sin()</code> de <code>cmath</code>.</li>
    <li>Imprime o erro absoluto e percentual.</li>
</ul>

<h2>Exemplo de Saída</h2>
<p>Para um ângulo de 45 graus:</p>
<pre>
Digite um ângulo em graus: 45

Resultados com 3 termos:
cos(45) ≈ 0.707317
sen(45) ≈ 0.707291

Resultados com 40 termos:
cos(45) ≈ 0.707106
sen(45) ≈ 0.707107

Resultados usando cmath:
cos(45) = 0.707107
sen(45) = 0.707107

Erros para 3 termos:
Erro absoluto no cosseno: 0.000211
Erro percentual no cosseno: 0.0299%
Erro absoluto no seno: 0.000184
Erro percentual no seno: 0.026%

Erros para 40 termos:
Erro absoluto no cosseno: 0.000000
Erro percentual no cosseno: 0.0000%
Erro absoluto no seno: 0.000000
Erro percentual no seno: 0.0000%
</pre>

<h2>Licença</h2>
<p>Este projeto é licenciado sob os termos da licença MIT.</p>
