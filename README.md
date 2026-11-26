## Sobre o Projeto

Este repositório reúne os códigos, notebooks do Google Colab e materiais de apoio do Trabalho de Conclusão de Curso (TCC) focado na **detecção automática do uso de capacete por motociclistas** por meio de redes neurais convolucionais leves.

A proposta nasce da relevância social da segurança viária e da necessidade de tornar a fiscalização e o videomonitoramento urbano mais eficientes sem exigir infraestruturas computacionais de alto custo.

### Objetivo Geral
Avaliar e comparar o desempenho quantitativo, a estabilidade entre inicializações, a eficiência computacional e a aplicabilidade prática dos modelos **YOLOv8n**, **YOLOv9t** e **YOLOv10n** frente a **Faster R-CNN MobileNetV2**, **Faster R-CNN MobileNetV3** e **SSDLite MobileNetV3** na detecção das classes *With Helmet* e *Without Helmet*.

### Objetivos Específicos
- Estruturar e curar o conjunto de dados **Helmet Detection – v6 Balanced dataset** (753 imagens divididas entre treino, validação e teste, sem *data augmentation*).
- Treinar e avaliar os seis modelos no **Google Colab** sob cinco sementes aleatórias (`7`, `21`, `42`, `123` e `2025`), totalizando 30 execuções.
- Mensurar métricas de detecção (*Precision*, *Recall*, *F1-score*, *mAP@0,5* e *mAP@0,5:0,95*), custo computacional, velocidade de inferência e significância estatística (ANOVA e Tukey).
- Consolidar as matrizes de confusão das cinco sementes e realizar testes de inferência qualitativa com amostras do conjunto de dados e imagens externas.
