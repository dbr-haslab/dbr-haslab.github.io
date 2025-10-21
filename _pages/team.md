---
title: "People"
layout: base
permalink: /people
classes: wide
sitemap: false
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
---

<script
      src="https://code.jquery.com/jquery-3.4.1.min.js"
      integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
      crossorigin="anonymous"
    ></script>
<script src="https://unpkg.com/magic-grid/dist/magic-grid.min.js"></script>

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp" crossorigin="anonymous">

<!-- # People -->

We are looking for new Postdocs, PhD students and Master/Bachelor students to join HASLab and work on distributed data management. If you are interested in working with us, contact us.

<!-- HASLab members involved in distributed storage research: -->
<div class="row">
        <div class="col-sm-12 rel pb80 tit">
          <h3 style="text-align: center;"><span>Meet the team</span></h3>
        </div>
      </div>

<div class="people" id="people_section">
  {% for member in site.data.team_members %}
  <div class="container-fluid rel icons team pt50 pb0">
          <div class="col-sm-12 text-center contIt rel shSec it5">
            <div class="item pb50">
              <div class="lineBox pb10">
                <div class="img bgi lazyload" data-src="{{ site.url }}{{ site.baseurl }}/assets/images/teampic/{{ member.photo }}" style="background-image: url(&quot;{{ site.url }}{{ site.baseurl }}/assets/images/teampic/{{ member.photo }}&quot;);"></div>
                <div class="cont sh" style="height: 118px;">
                  <div class="int">
                    <h5>{{ member.name }}</h5>
                    <p>{{ member.info }}</p>
                    <div class="social-links">
                      <a href="mailto:{{ member.email }}"><i class="fas fa-envelope"></i></a>
                      {% if member.git %} <a href="{{ member.git }}"><i class="fab fa-github"></i></a>{% endif %}
                      {% if member.ldin %} <a href="{{ member.ldin }}"><i class="fab fa-linkedin"></i></a>{% endif %}
                    </div>
                  </div>
                </div>
              </div>
      </div>
    </div>
  </div>
  {% endfor %}
</div>


<hr>


## Alumni

### Researchers
 - [Ricardo Vilaça](https://rmpvilaca.github.io/), Now at [Critical Techworks](https://www.criticaltechworks.com/) 
 - Nuno Machado, Now at [Amazon](https://amazon.com/)
 - Rui Gonçalves, Now at [Zalando](https://www.zalando.com/)

---

### PhD
 - Francisco Neves, Francisco Neves, Holistic performance and scalability analysis for large scale distributed systems, 2021, Now at [Nutrium](https://nutrium.com/)
 - Rogério Pontes, Secure multi party Computation Trade-offs in distributed Databases, 2020, Now at [AutoScout24](https://www.autoscout24.de)
 - Ricardo Gonçalves, Multi-Value Distributed Key-Value Stores, 2018, Now at [UpHold](https://www.uphold.com)
 - Fábio Coelho, Towards a Transactional and Analytical Data Management System for Big Data, 2018
 - Ana Nunes Alonso, Database Replication for Enterprise Applications, 2017
 - Clayton Costa, Efficient adaptive query processing on large database systems available in the cloud environment, 2017, Now faculty at [UFRN](https://www.ufrn.br/)
 - Francisco Cruz, Towards autonomic workload aware NoSQL databases, 2016, Now at [InvisibleLabs](https://invisiblelab.dev/)
 - Francisco Maia, Epidemic Store for Massive Scale Systems, 2015, Now faculty at [FEUP](https://www.up.pt/feup/en//)
 - Miguel Matos, Epidemic algorithms for large scale data dissemination, 2013, Now faculty at [IST](https://tecnico.ulisboa.pt)
 - Ricardo Vilaça, Clouder: a flexible large scale decentralized object store, 2012, [Critical Techworks](https://www.criticaltechworks.com/)
 - Alfranio Correia, Practical database replication, 2010, Now at [Oracle-MySQL](https://www.mysql.com)
 - Filipe Campos, Fault Tolerant Service Integration, 2017, Now at [Oracle-MySQL](https://www.mysql.com)
 - Paulo Jesus, Robust Distributed Data Aggregation, 2012, Now at [Oracle-MySQL](https://www.mysql.com)
 - Nuno Castro, Timeseries motif discovery, 2012, Now at [Expedia](https://www.lifeatexpedia.com)

---
### MSc
- Pedro Sousa, Distributed transaction optimization, 2025.
- Luís Silva, Update processing in polystores, 2025.
- Rui Souto, Query Optimizers Based on Machine Learning Techniques, 2021,  Now at [TalkDesk](https://www.talkdesk.com/)
- Luis Meruje, Automatic Parameter Tuning Using Reinforcement Learning, 2020
- Nuno Faria, High performance data processing, 2020
- Hugo Alves Carvalho, SafeSpark: Processamento Analítico de Dados Seguro, 2019, Now at [Bosch](https://www.bosch.pt)
- Hugo Abreu, High Availability Architecture for Cloud Based Databases, 2019, Now at [Feedzai](https://www.feedzai.com)
- Diogo Couto, Aplicações web com requisitos de armazenamento e processamento privados, 2018, Now at [Keyruptive](https://www.keyruptive.com)
- Cláudia Vanessa Brito, Cloud-based Analytics for Monitoring and Classification of Arrhythmias, 2018
- Daniel Cruz, SafeAnalytics: Plataforma para analítico seguro de dados, 2018
- Daniel Tavares, Armazenamento de Dados Colunar para Processamento Analítico, 2018, Now at [XPandIT](https://www.xpand-it.com)
- José Carlos Morais, Escalonamento de transações em bases de dados não-relacionais, 2018, Now at [Farfetch](https://www.farfetch.com)
- Ricardo Gonçalves Macedo, Computação Segura em Bases de Dados NoSQL (Secure Computation on NoSQL Databases),2017
- Cláudia Fernandes Ribeiro, Escalonamento de pedidos para um serviço de bases de dados relacional externo, 2017, Now at [VISA](https://www.visa.com/)
- José Pedro Pereira, Towards Building Partial Memberships with Network Sampling, 2017
- José Luís Ribeiro, Níveis de Coerência de Dados em Sistemas de Muito Larga Escala (Consistency Criterions in Very Large Scale Database Systems), 2017, Now at [XPandIT](https://www.xpand-it.com)
- Diana Martins, Safe storage of medical images in NoSQL databases, 2016, Now at [EuroTux](https://eurotux.com/)
- Pedro Ferreira, AIoTA: an IoT Platform on MonetDB, 2016, Now at [MonetDB Solutions](https://monetdbsolutions.com/)
- Pedro Guimarães, Monitoring and analysis of queries in distributed databases, 2015, Now at [OutSystems](https://www.outsystems.com/)
- João Miranda, Replicação de Bases de Dados Baseada em Comunicação em Grupo (database replication based on group communication), 2015, Now at [Vilt]( https://www.vilt-group.com/)
- André Costa. Gestão de Bases de Dados Relacionais em Cloud Computing (Relational Databases Management for Cloud Computing), 2015, Now at [Vilt]( https://www.vilt-group.com/)
- Francisco Neves, On efficient support for relational data in Apache HBase, 2015
- Mário Pinto, Secure computation of SQL, 2014, Now at [Etamax](http://www.etamax.de/)
- Fábio Coelho, Implementation and test of transactional primitives over Cassandra, 2013
- Luís Zamith, Bridging the Gap Between SQL and NoSQL, 2012, Now at [SubVisual](https://subvisual.co/)
- Pedro Gomes, Migração de aplicações legadas para bases de dados NOSQL, 2011, Now at [Oracle-MySQL](https://www.mysql.com)
- Nelson Gonçalves, Large-scale privacy-preserving Bluethooth sensing, 2013, Now at [Oracle-MySQL](https://www.mysql.com) 



<!--
## Previous Members
<table align="center" style="width:100%">
<tr><th>Visitors</th>
    <th>Master Students</th>
    <th>Bachelor Students</th>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Pedro Reis, 2012/2013</td>
  </tr>
</table>

-->





<script>

    const magicProjectsGrid = new MagicGrid({
      container: "#people_section",
      animate: false,
      gutter: 50, // default gutter size
      static: true,
      useMin: false,
      maxColumns: 5,
      useTransform: true
    });

    $("document").ready(() => {
      magicProjectsGrid.listen();
    });



</script>