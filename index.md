---

copyright:
  years: 2017, 2018
lastupdated: "2018-02-26"

---

<!-- Attribute definitions -->
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# Getting started with Analytics for Apache Spark

Apache Spark is a distributed data processing analytics engine that
makes available new capabilities to data scientists, business analysts,
and application developers. Analytics for Apache Spark provides fast
in-memory analytics processing of large data sets.


By using Analytics for Apache Spark, you can quickly start tapping into
the power of Apache Spark. The service offering includes the following:

  - **Apache Spark** for data processing at scale

    **Note:** If you want to migrate to Spark 2.1 and learn what you need to update in your Spark applications, see:
    - [Migrating from Spark 1.6 to Spark 2.1](./migrating_to_spark21.html)
    - [Migrating from Spark 2.0 to Spark 2.1.2](./migrating_2.0_to2.1.2.html)
  - **spark-submit** for batch processing with your own applications
  - **Spark Interactive API** for creating non-notebook web clients that
    can provision and use Jupyter kernels


1.  Create a new instance of the Apache Spark service from the {{site.data.keyword.Bluemix_notm}} dashboard by clicking **Create Service**, and then **Data & Analytics \>
    Apache Spark**.

    Note: Each Spark instance that you create has one set of credentials which cannot be changed. If you need to change the credentials, for example, for security reasons if your credentials were leaked, you
    must create a new instance, move your workload over to the new instance, and then delete the old instance.
2.  To start running your applications with Spark, choose one of the following options:
      - [Run Spark applications by using
        spark-submit](./using_spark-submit.html).
      - [Run Spark applications by using the Spark Interactive
        API](./spark_interactive_api.html).
