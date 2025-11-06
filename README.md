# Deteccão de Anomalias

**Área de atuação**: Aprendizado não supervisionado / semi-supervisionado (Anomaly
Detection)

**Descrição**: Desenvolvimento de modelos para detecção de anomalias em conjuntos de
dados com taxas de ocorrência extremamente baixas, como casos de fraudes, ataques
cibernéticos e falhas em máquinas. 

O foco do projeto é avaliar a capacidade dos modelosde identificarem padrões atípicos em contextos de aprendizado não supervisionado e/ou semi-supervisionado e sua robustez em cenários de desbalanceamento extremo entre as classes.

**Requisitos específicos**

* Exploração e pré-processamento de dados, com foco em balanceamento de classes extremamente desbalanceadas (anomalias representam casos raros). Utilização de pelo menos 3 algoritmos diferentes, incluindo pelo menos um baseado em:
    *  Modelos probabilísticos (ex: Gaussian Mixture Models, Isolation Forest).
    * Modelos baseados em distância ou densidade (ex: kNN, DBSCAN, LOF).
    * Modelos de Deep Learning (ex: Autoencoders para detecção de outliers).
* Testar diferentes hiperparâmetros para avaliar a robustez dos métodos.
* Comparação de desempenho usando métricas adequadas para classes desbalanceadas (AUC-ROC, Precision, Recall, F1-score).
* Avaliação estatística de significância para validar diferenças de performance.
* Discussão sobre aplicabilidade real (fraude, segurança, manutenção preditiva).

