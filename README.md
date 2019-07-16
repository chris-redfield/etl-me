---


---

<h1 id="análise-ferramentas-etl">Análise ferramentas ETL</h1>
<p>busca por uma solução ideal para gestão dos fluxos de dados no Ministério da Economia.</p>
<h2 id="critérios-de-seleção">Critérios de seleção</h2>
<p>Obrigatórios</p>
<ul>
<li>Agendamento de jobs</li>
<li>Visualização de estado dos jobs e estatísticas de sucesso</li>
<li>Versionamento dos jobs</li>
<li>Fácil manutenção</li>
<li>Fácil configuração execução de jobs de maneira distribuída e remota</li>
<li>Trabalhar com qualquer formato de acesso e dados (ex: SFTP, mqeue etc)</li>
</ul>
<p>Desejáveis</p>
<ul>
<li>Não necessitar licença para utilização / manutenção da ferramenta</li>
<li>Visualização dos pipeline de dados com ordem de execução</li>
<li>Solução amplamente utilizada na comunidade</li>
</ul>
<h2 id="soluções-pesquisadas">Soluções pesquisadas:</h2>
<ol>
<li>SQL Server Integration Services</li>
<li>Informatica PowerCenter</li>
<li>Pentaho Data Integration</li>
<li>Apache Airflow</li>
<li>Talend Open Studio</li>
</ol>
<h3 id="sobre-os-critérios-de-seleção">Sobre os critérios de seleção</h3>
<ul>
<li>
<p>Agendamento de jobs: A ferramenta possui feature nativa, ou fácil de instalar de agendamento de jobs ?</p>
</li>
<li>
<p>Solução amplamente utilizada na comunidade: baseado em uma pesquisa no google trends em 15/07/2019.</p>
</li>
</ul>
<p><img src="https://raw.githubusercontent.com/chris-redfield/etl-me/master/img/google-trends-etl.PNG" alt="google-trends"></p>
<h2 id="resultados">Resultados</h2>

<table>
<thead>
<tr>
<th></th>
<th>SQL Server Integration Services</th>
<th>Informatica PowerCenter</th>
<th>Pentaho Data Integration</th>
<th>Apache Airflow</th>
<th>Talend Open Studio</th>
</tr>
</thead>
<tbody>
<tr>
<td>Agendamento de jobs</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td>Visualização de estado dos jobs e estatísticas de sucesso</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td>Fácil versionamento do código dos jobs / nativo</td>
<td>0</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td>Fácil manutenção</td>
<td>0</td>
<td>0</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Fácil execução de jobs de forma distribuída</td>
<td>0</td>
<td>0</td>
<td>1</td>
<td>1</td>
<td>0,5</td>
</tr>
<tr>
<td>Qualquer formato de acesso e dados</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td>Não necessitar licença</td>
<td>0</td>
<td>0</td>
<td>0,25</td>
<td>0,5</td>
<td>0,25</td>
</tr>
<tr>
<td>Visualização dos pipelines de dados com ordem de execução</td>
<td>0,5</td>
<td>0,5</td>
<td>0,5</td>
<td>0,5</td>
<td>0,5</td>
</tr>
<tr>
<td>Comunidade Grande</td>
<td>0,5</td>
<td>0</td>
<td>0,5</td>
<td>0,5</td>
<td>0</td>
</tr>
<tr>
<td>Total</td>
<td>4,00</td>
<td>4,50</td>
<td>6,25</td>
<td>6,50</td>
<td>5,25</td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table><blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

