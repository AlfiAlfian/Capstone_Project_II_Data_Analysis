# **0_BRIEF -- Chapstone Project II - Data Analysis**
Perkenalkan saya Alfian. Berikut adalah high level dari apa yang telah kerjakan Pada Chapstone Project II - Data Analysis. Pembahasan saya mulai dari : 
* Pembahasan General mengenai database
* SQL
* Data Manipulation
* Data Insight (Statistics & Data Visualization)

Untuk detail setiap bagiannya dapat melihat informasi dibawah ini. 

Bila ada masukan megenai project ini atau hal hal yang sekiranya ingin disampaikan dapat menghubungi saya di email sebagai berikut : personalalfi22@gmail.com

Terima kasih

# **1_GENERAL DATA INFORMATION**

## **1_1_CONTEXT**

Database ini menjelaskan mengenai perusahaan fiktif bernama "Northwind Traders". Perusahaan ini bergerak di bidang export dan import "speciality food" dari seluruh dunia. Perusahaan ingin mengetahui gambaran umum tentang bisnis yang sedang mereka jalankan. Apakah ada hal hal yang bisa ditingkatkan atau dinotice dari data yang ada? Dari insight yang dihasilkan diharapkan bisa membantu perusahaan dalam menentukan langkah strategis untuk mengembangkan perusahaan dan lain sebagainya.
<br>

**Fokus Analisis : Orders**

## **1_2_DATABASE INFORMATION**

Pada bagian ini saya memberikanpenjelasan mengenai data data setiap tabel pada database Northwind

## **1_3_TABLE RELATIONSHIP** 

berikut ini diberikan Entity Relationship Diagram (ERD) untuk database "Northwind"
![](image/Northwind%20ERD.png)
<br>

# **2_SQL**
**THE OBJECTIVES**
* SQL TO PYTHON CONNECTION
* USING CTE OR OTHER WINDOW FUNCTION (IF NEEDED)
* BUILT – IN FUNCTION AS NEEDED

## **2_1_CONNECTING TO DATABASE**
Membuat koneksi dari SQL ke Python agar bisa melakukan query di Jupyter Notebook
<br>

## **2_2_1_SQL - TASK (TABLE INTEPRETATION)**
Saya melakukan intepretasi dari tabel yang ada yang nantinya akan saya gabungkan menjadi sebuah dataframe
<br>

## **2_2_2_SQL - TASK (TABLE CREATION)**
Gambaran tabel tabel yang akan saya gabungkan untuk saya jadikan sebuah dataframe. Pada bagian ini saya memanfaatkan beberapa fitur built in SQL seperti LEFT JOIN dan USING.

![](image/sql%20dataframe%20composition%201.jpg)
<br>

## **2_3_SQL (CTE & WINDOW FUNCTION)**
Penerapan fungsi CTE dan Window Function dari SQL. Window function yang saya gunakan disini adalah OVER(PARTITION BY) dan ROW_NUMBER(PARTITION BY).
![](image/sql%20dataframe%20composition%202.jpg)
<br>

# **3_DATA MANIPULATION**
**THE OBJECTIVES**
* ANY ANOMALIES ? (MISSING VALUE, OUTLIER, DATA FORMATTING, DOUBLE DATA ? 
* HOW TO DEAL WITH THE ANOMALIES ? 
* IF THERE’S NO ANOMALIES, PROVE IT 
<br>

## **3_1_GENERAL INFORMATION FOR DATA**
Mengetahui informasi umum data dengan .info. melihat statistik deskriptif data dengean .describe() dan custom dataframe untuk melihat informasi general dengan lebih detail
<br>

## **3_2_CHANGING DATA TYPE, MISSING VALUE & ANOMALY**
* Mengubah tipe data menjadi tipe data yang sesuai dengan datanya. 
* Mengatasi missing value
<br>

## **3_3_DIVE THE DATA IN EACH FEATURE**
Dibantu dengan 2 buah fungsi col_info dan visualize_distribution. saya mempelajari data dari tiap feature yang tersedia. col_info untuk melihat informasi general dari data yang ada. visualize distribution saya gunakan untuk data numerikal untuk melihat distribusi data dan outliers menggunakan distplot dan boxplot.

Bagian ini juga ada penanganan anomali seperti typo dan value kategorikal formatnya saya sesuaikan dengan kebutuhan saya.
<br>

# **4_DATA INSIGHT (DATA VISUALIZATION, STATISTICS)**
**THE OBJECTIVES**
<br>
DATA VISUALIZATION
* DATA VISUALIZATION USING PYTHON & TABLEAU
* INSIGHT / STORY / ANY INFORMATION TO EXPLAIN THE GRAPH TO SOLVE THE PROBLEM

STATISTICS
* COMPARING VALUE / PROPORTION WITH SUITABLE METHOD
* RELATIONSHIP BETWEEN FOCUS ANALYSIS WITH OTHER VARIABELS
* INSIGHT FROM DESCRIPTIVE STATISTIC TEST & INFERENTIAL STATISTIC TO SOLVE THE PROBLEM
<br>

## 4_1_PRODUCT
**Product Analysis 1 -- Kategori item yang paling sering dibeli dan kenapa ?**
<br>
**Product Analysis 2 -- Correlation between n_transaction vs Qty total vs cummulative_total_sales**
<br>
**Product Analysis 3 -- Hypothesis testing antara produk kategori meat/poultry dengan confections & seafood**
<br>
**Product Analysis 4 -- Most Bought *goods*, General Information for Prospective Buyer**

Yang saya lakukan pada bagian ini : 
* Visualisasi menggunakan TABLEAU (world map, heat map with report, tree map) dan python (Lineplot)
* Uji kenormalan data
* Uji hipotesis
* Data manipulation
* Insight
* etc
<br>

## 4_2_DATE ANALYSIS
**Date Analysis 1 -- Analisis keterlambatan**
<br>
**Date Analysis 2 -- Total penjualan tiap bulannya**
<br>
**Date Analysis 3 -- Trend harga product tiap kategori**
<br>
**Date Analysis 4 -- Seafood Product**
<br>
melakukan uji hipotesis untuk membandingkan rerata total sales salah satu produk seafood dengan produk seafood lainnya


Yang saya lakukan pada bagian ini : 
* Visualisasi menggunakan TABLEAU (Lineplot dual axis) dan python (lineplot)
* Uji kenormalan data
* Uji hipotesis
* Data manipulation
* Insight
* etc
<br>

## 4_3_CUSTOMER ANALYSIS
<br>
**Customer Analysis 1 -- Loyal Customer by number of transaction & total sales**
<br>
**Customer Analysis 2 -- Komparasi rerata sales dari Perusahaan Ernst Handle dan Quick Stop**
<br>

Yang saya lakukan pada bagian ini : 
* Visualisasi menggunakan python (lineplot)
* Uji kenormalan data
* Uji hipotesis
* Data manipulation
* Insight
* etc
<br>

## 4_4_EXPEDITION SERVICES
Menginformasikan hal hal mengenai jasa expedisi yang digunakan perusahaan Northwind
