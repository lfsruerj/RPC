<h1>This is an RPC algorithm for spatial intersection of photogrammetric satellite images</h1>

<h2>Part of the e-foto 2.0 project, aiming to integrate Rational Polynomial Coefficients processing to the e-foto free photogrammetric suite.</h2>

<h2>Source</h2>
<p>
Sponsored by Fundação Carlos Chagas Filho de Amparo à Pesquisa do Estado do Rio de Janeiro
</p>

Coordinator: Prof. Dr. Luiz Carlos Teixeira Coelho (UERJ)
Students: Paulo Vitor Oliveira Vieira (1st year), Giovanna Rocha da Silva Ferreira Coutinho (2nd year) and Arthur Henrique de Souza Fernandes (both years).

<h2>Executing with CMAKE</h2>
<p>
1. Install CMAKE <br>
2. Create a build folder in the RPC_MARCEL_CODE root <br>
3. Enter in build folder <br>
4. start the cmake build,COMMAND: $ cmake .. <br>
5. build the program: $ cmake --build . <br>
</p>

<h2>Example how to compile the tests using g++</h2>
<p>
 g++ -g -Wall -I ..\includes\Eigen\Eigen -I ..\headers\ -I ..\headers\utils\ .\mainWork.cpp .\utils\RandPerm.cpp -o teste

</p>
