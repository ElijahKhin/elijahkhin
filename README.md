## Contents

* [About Me](#about-me)
* [Expirience](#expirience)
* [Education](#education)
* [Projects](#projects)


## About Me
<img align='right' src='https://github.com/ElijahKhin/elijahkhin/blob/main/materials/guts-berserk.gif' width='200'>
I am Elijah Khin, 25 years old, living in Russia, Moscow.

<ul>
<li>Entrepreneur a.k.a. unemployed</li>
<li>Ex. data analyst at Samsung Electronics</li>
<li>Student at High School of Economics and School21 (ex. E'cole 42)</li>
</ul>


## Experience

### Liilta X (11.2022 - now)

Lilita X (my pet-project) is a technology startup specializing in digital currencies, in particular in the mining of cryptocurrencies. At the moment, the combined hashrate of all devices is ~10 PH/s. The equipment is located on 3 hosting sites in different regions of Russia.

The main technological task from the point of view of development was ** creation of a decision support system**.
The DSS includes: integration of external sources, a data warehouse, and a set of BI dashboards.
+ External sources mainly mean data from mining pools and crypto exchanges. Integration with the data warehouse is carried out through **FastAPI**. Automation via **Apache Airflow**.
+ The DBMS **PostgreSQL** is used to develop the data warehouse. The logical model was designed according to Kimball, such a choice was due to the small amount of data, as well as the simplicity of development relative to the Inmon approach.
+ **Yandex DataLens** is used as a BI-system.

**Technology stack:** Python (Pandas, Numpy, FastAPI), SQL (PostgreSQL), Apache Airflow, Linux (Ubuntu), Yandex DataLens

### Samsung Electronics / Data Analyst (11.2020 - 05.2024)

In the company held the position of data analyst of the department of monobrand retail.
The main task was to create a small **DWH** for my department.
+ Several servers were involved on the **Linux (Ubuntu)** operating system. I used **Greenplum** to process large amounts of data. Automation of ETL-processes was carried out using **Apache Airflow**. **Power BI** (for Russian users) and **Apache Superset** (for Korean users) were used as BI-systems.
In addition to designing and developing a DWH for marketing research purposes, it was necessary to process large amounts of data containing device activation geodata. In addition to **Python**, **C++** was used for acceleration.

**Technology stack:** Python (Pandas, Numpy), C++, SQL (PostgreSQL), Greenplum, Apache Airflow, Linux (Ubuntu), Power BI, DAX, Power Pivot (M), Apache Superset


## Education

### National Research University Higher School of Economics (2024 - 2026)
*Faculty of Computer Science, Data Engineering*

### School 21 / Sber (2021 - 2025)
*Corporate Programming School*

### Plekhanov Russian University of Economics (2016-2020)
*Institute of Digital Economics and Information Technology, Business Analytics*


## Projects

### Basic algorithms on graphs 
C++ programming of basic graph algorithms: 
1. Depth First Search 
2. Breadth First Search 
3. Dijkstra's algorithm 
4. The Floyd-Warshall algorithm 
5. Prim's algorithm 
6. Solving the traveling salesman problem using the "ant" algorithm.

Link to the project: https://github.com/ElijahKhin/algo_graphs

### Creating a PostgreSQL database for an educational organization

Link to the project: https://github.com/ElijahKhin/SQL2_Info21

### 

<!-- ![](https://github-readme-stats.vercel.app/api/top-langs/?username=elijahkhin&layout=compact&theme=white) -->
