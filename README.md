<h1 align="center">Monitoramento com Grafana</h1>
<p align="center">Aplicação da ferramenta Grafana para monitoramento de desempenho do Hardware e Sistema :computer:</p>

<b>Objetivo:</b> Oferecer um modelo de dashboard que apresente em gráficos, altamente intuitivos, as métricas de desempenho do hardware. Considere que o "hardware" pode ser o servidor da empresa, um microcontrolador em campo ou a própria máquina pessoal. :bar_chart:

:white_check_mark: Criei um script em PHP que armazenasse no meu BD local os valores do consumo de memória, consumo de armazenamento e um inteiro randômico entre 0 e 15 para representar o número de requisições a um sistema (login). O armazenamento foi feito com MySQL e, assim que conectei o Grafana ao banco, gerei os gráficos.

<div align="center">
  <img src="https://github.com/guilhermedonizetti/Monitoramento_Grafana/blob/master/grafana_guilhermedonizetti.jpeg?raw=true" width="700" height="400" alt="Grafana">
</div>

Dessa forma, fica compartilhado nesse repositório o Json do dashboard apresentado que pode ser importado ao seu Grafana como base para receber os incrementos necessários e atender às suas ideias/necessidades (modelo.json).

<b>Vantagens:</b> Das vantagens do Grafana destaco:
<ul>
  <li>Interface intuitiva: os recursos visuais da ferramenta são de fácil interpretação</li>
  <li>Várias fontes de dados: o Grafana se conecata com BDs estruturados e NoSQL, além de outra gama de possíveis fontes de dados para coletar as métricas.</li>
  <li>Adaptável: todo visual da ferramenta pode ser customizado, se adaptando a diferentes necessidades de gráficos e negócios.</li>
</u>


<br><br><br>

<p align="center"><b>Grafana, PHP, MySQL, Monitoramento.</b><br>Guilherme Donizetti - 2022.</p>


