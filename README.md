# sptrans-projeto
#  Projeto SPTrans - Pipeline de Dados em Tempo Real

Este projeto tem como objetivo construir um **pipeline de dados em tempo (ou quase tempo) real** utilizando a **API da SPTrans**, integrando ferramentas de ingestão, tratamento, armazenamento e visualização de dados.


## 🚀 Arquitetura do Projeto

SPTrans API → Apache NiFi → MinIO (Bronze)
↓

Apache Spark → MinIO (Prata)
↓

FastAPI → Power BI 
