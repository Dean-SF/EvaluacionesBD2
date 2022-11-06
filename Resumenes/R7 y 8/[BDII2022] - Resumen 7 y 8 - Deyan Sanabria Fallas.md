<p style="text-align:center;height:150px"> <br><br><br><br><br><img src="../logo-TEC/logo-tec.png" width= "250" class="center"> </p>

<p style="text-align:center;font-size:18px"> <br><br><br>Instituto Tecnologico de Costa Rica </p>

<p style="text-align:center;font-size:18px"> <br>Sede Central de Cartago </p>

<p style="text-align:center;font-size:18px"> <br>Escuela de Computación </p>


<hr style="color:#4472C4">
<p style="text-align:center;font-size:40px;color:#4472C4"> Resumen 7 y 8 (R7 y R8) </p>
<hr style="color:#4472C4">

<p style="text-align:center;font-size:18px"> <br>IC-4302 Bases De Datos II GR 1 </p>

<p style="text-align:center;font-size:18px"> <br>Estudiantes: Deyan Sanabria Fallas #2021046131 </p>

<p style="text-align:center;font-size:18px"> <br>Profesor: Gerardo Nereo Campos Araya </p>

<p style="text-align:center;font-size:18px"> <br>Fecha de Entrega: 08/11/2022 </p>

<p style="text-align:center;font-size:18px"> <br>Segundo Semestre 2022 </p>

<div style="page-break-after: always"></div>

# Indice
1. [The Return on Connected Data](#the-return-on-connected-data)

    1.1. [Connections Unlock the Value of Data](#connections-unlock-the-value-of-data)

    1.2. [Data, Data Everywhere, Nor any Drop to Drink](#data-data-everywhere-nor-any-drop-to-drink)

    1.3. [The Power of Connected Data](#the-power-of-connected-data)

    1.4. [Quench Your Thirst for Insights with Connected Data](#quench-your-thirst-for-insights-with-connected-data)

    1.5. [Neo4j: Your Path to Connected Data](#neo4j-your-path-to-connected-data)

2. [A Brief Introduction to Graph Data Platforms](#a-brief-introduction-to-graph-data-platforms)

    2.1 [What Are Graph Databases Good for?](#what-are-graph-databases-good-for)

    2.2. [Traditional Technology Choices Do Not Consider How Data Is Interrelated](#traditional-technology-choices-do-not-consider-how-data-is-interrelated)

    2.3. [Collections vs. Connections](#collections-vs-connections)


      2.3.1. [SQL & NoSQL Systems Focus on Data Aggregation & Collection](#sql--nosql-systems-focus-on-data-aggregation--collection)


      2.3.2. [Graph Systems Focus on Data Connections](#graph-systems-focus-on-data-connections)


    2.4. [Property Graphs Are Intentionally Simple](#property-graphs-are-intentionally-simple)

    2.5. [Benefits of Graph Databases](#benefits-of-graph-databases)

3. [Use Cases for Graph Technology](#use-cases-for-graph-technology)

    3.1. [Fraud Detection](#fraud-detection)

    3.2. [Real-Time Recommendations](#real-time-recommendations)

    3.3. [Bill of Materials](#bill-of-materials)

    3.4. [Track & Trace](#track--trace)

    3.5. [Network & IT Ops](#network--it-ops)


<div style="page-break-after: always"></div>

# The Return on Connected Data

## Connections Unlock the Value of Data
The value of data comes from the ability to relate it with other data. Is diferent to say "a customer bought a child’s winter coat" than "a customer bought a child’s winter coat for the last three years, all in the color blue, in successive sizes", there is more data when connected.

Metcalf's Law of Network says: network value increases
exponentially as you add users or nodes to the network.

Relationship information is not a first-class entity in relational nor other types of databases. Relational databases don't persis relationship information.

## Data, Data Everywhere, Nor any Drop to Drink
Organizations fail to realize Big Data's value, because the value isn't in disparate data but in the relationships between the data.

Data becomes connected when treating relationships as a first-class entity persisting it, assigning properties to it, and using it as a means to develop context for applications.

## The Power of Connected Data
The biggest benefit of connected data is the ability to provide a connected view of the data to your analytic and operational applications. You also contextualize more deeply the pieces of information you collected 

Connected data is most powerful when it provides operational, real-time insights and not just after-the-fact analytics.

## Quench Your Thirst for Insights with Connected Data
How does data become connected? A graph database makes it easy to express and persist relationships across many types of data elements. 

A graph database is a highly scalable transactional and analytic database that stores data relationships as first-class entities. A graph data model is like a mind map composed of two elements: A node and a relationship.

Structural overhead of traditional database schema is eliminated, so graphs can be easily changed or updated. You can put data into a graph simply by reading in a table, and if you want to add another column or attribute to that data element, you simply add the attribute.

## Neo4j: Your Path to Connected Data
Neo4j offers an innovative, reliable native graph platform that reveals and maintains the integrity of connected data from the moment it’s conceived through each stage of design, development, analysis, implementation, and operation.

# A Brief Introduction to Graph Data Platforms
Relational databases dominates the market but fails to adapt easily to the complexity of data, its context and its interconnections, they are the wrong tool for many business challenges.

## What Are Graph Databases Good for?
* Fraud Detection & Analytics
* Artificial Intelligence & Machine Learning
* Real-Time Recommendation Engines
* Knowledge Graphs
* Network & Database Infrastructure Monitoring
* Master Data Management (MDM)

## Traditional Technology Choices Do Not Consider How Data Is Interrelated
Data and applications today require elasticity, agility, speed and interconnectivity but relational databases are not well-suited for modeling and storing today’s highly connected and agile datasets. It has a difficult time expressing and revealing how real and
virtual entities are related.

## Collections vs. Connections

### SQL & NoSQL Systems Focus on Data Aggregation & Collection

SQL and NoSQL are collection-centric storages designed to efficiently divide and store data.

SQL databases were designed to minimize storage of duplicative data because disk space was costly

NoSQL databases lack relationships (lack data structure). Data is easily storage and retrieve without the need to mantain integrity and without the concern of distributed JOINs.

### Graph Systems Focus on Data Connections
Graph databases technologies focus on how data elements are interrelated and contextualized as connected data.

Connected data is the materialization and harnessing of relationships between data elements, which is modeled as a property graph. A property graph is a data model designed to express data connectedness as nodes
connected via relationships to other nodes.

## Property Graphs Are Intentionally Simple
* You can change or update a property graph easily, because its agile design eliminates most of the structural overhead of traditional database schemas.
* You can quickly program property graphs because their query language expresses and follows relationships
* You can rapidly determine data context when property graph queries are executed in hyper-fast native graph platforms built on reliable, scalable database architectures.

## Benefits of Graph Databases
* Simple and natural data modeling
* Flexibility for evolving data structures
* Simultaneous support for real-time updates and queries
* Better, faster and more powerful querying and analytics 

# Use Cases for Graph Technology
Five of the top use cases for graph technology

## Fraud detection
Data is ripe by graph-native machine learning techniques to find fraud. It usses Neo4j to power a proprietary fraud detection application.

## Real-Time Recommendations
Contextual and instantaneous recommendations. Running Neo4j makes possible a recommentation system that generates a detailed model of all the actions a customer makes.

## Bill of Materials
Neo4j rapidly collect and combine massive bill of materials information to answer immediately. It can forecast the need for replacement parts by accurately calculating mean time to failure.

## Track & Trace
Graph data models enables traceability for things like routing, logistics, supply, chain management, and compliance.

## Network & IT Ops
A network is a graph. It enables to conduct sophisticated impact analyses. Graph query determines which applications, services, and customers will be affected if a particular network element fails.