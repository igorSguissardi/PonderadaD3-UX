# Visualizações de gráficos com D3.js

Ponderada de UX: **Exercício 1 de Visualização de Grafos**

Grupo 3

Participantes:

Lucas Ramenzoni Jorge <br>
Pedro Auler <br>
Igor Sguissardi de Oliveira <br>
Pedro Rodrigues<br>
Vinicius Testa Passos<br>

## Mapa de São Paulo mostrando homebases

Criadores:
Igor Sguissardi de Oliveira
Pedro Auler

### Rascunho
&emsp;O rascunho desenhado durante o momento de brainstorm, no início da dinâmica, foi imaginado da seguinte forma: o contorno externo representa a cidade de São Paulo, as linhas internas são as delimitações dos distritos da cidade ou de possíveis zonas de atendimento e os pontilhados no mapa são as home bases dos gasista que foram alocadas.
<style>
.img-responsive {
    max-width: 70%; /* Reduz para 50% da largura do contêiner pai */
    height: auto; /* Mantém a proporção da imagem */
}
</style>
</div>
<br>

<div align="center">

<sub>Figura 1 - Rascunho Gráfico SP</sub>

<img src="assets\imagemRascunho.jpg" class="img-responsive" alt="Rascunho Grafico SP">

<sup>Fonte: Material produzido por Pedro e Igor</sup>
</div>


&emsp;Escolhemos esse desenho para reproduzir utilizando a biblioteca D3.js pois acreditávamos que seria possível conseguir um resultado satisfatório no desenvolvimento desse mapa, e seria possível desnvolvê-lo durante o resto da instrução.

### Processo de desenvolvimento

&emsp;Inicialmente, procuramos na internet por aquele arquivo .csv que foi mostrado nos slides durante a instrução, o qual delimitava as arestas dos distritos da cidade de São Paulo. Transformamos esse arquivo para o formato GeoJason e plotamos utilizando o D3.js.
Adicionamos também um efeito de peso entre os distritos que simula uma possível maior e menor quantidade de chamados de atendimento em diferentes áreas.<br>
&emsp;Por último adicionamos alguns pontinhos em vermelho que simulam onde estariam alocadas as homebases.

### Versão Final do Gráfico

&emsp;Assim ficou a versão final do gráfico plotada utilizanado a biblioteca D3.js:

<sub>Figura 2 - Versão Final Gráfico SP</sub>
<div align="center">
<img src="assets\graficoVersaoFinal.png" class="img-responsive" alt="rafico SP">

<sup>Fonte: Material produzido por Pedro e Igor</sup>
</div>


&emsp;Caso você queira acessar o código desenvolvido e os dados utilizados, eles estão armazenados na pasta "atividadeD3", que está localizada na raiz do projeto.

