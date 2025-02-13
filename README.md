Análise de Imagens com Azure ML: Reconhecimento Facial e Extração de Texto
Este projeto explora as capacidades do Azure Machine Learning para análise de imagens, focando em duas tarefas principais: reconhecimento facial e extração de texto. O projeto foi desenvolvido como parte de um laboratório prático, demonstrando a aplicação de modelos de IA para processamento de imagens no Azure.

1. Reconhecimento Facial
A funcionalidade de detecção de rostos do Azure ML foi testada em diferentes cenários, incluindo fotos com óculos escuros e imagens contendo tatuagens. Os resultados foram notáveis:

Detecção Robusta: Mesmo com o uso de óculos escuros, a IA conseguiu identificar corretamente a presença de um rosto, demonstrando a robustez do modelo de detecção facial.
Reconhecimento de Tatuagem: Uma tatuagem contendo um rosto, mesmo sendo antiga e parcialmente apagada, foi identificada como um rosto pela IA, evidenciando a capacidade do modelo de reconhecer padrões complexos em imagens.
2. Extração de Texto de Imagens
O laboratório de extração de texto de imagens utilizou dois arquivos JPG com textos distintos:

Arquivo 1: Uma imagem contendo a frase "ANDAR COM FÉ a FÉ NÃO COSTUMA FALHAR" escrita em arco. O modelo não conseguiu identificar e extrair o texto em sua totalidade, possivelmente devido ao formato em arco da frase.
Arquivo 2: Uma imagem contendo o convite de casamento. O modelo extraiu todo o texto do convite com sucesso, demonstrando sua eficácia em textos estruturados.
3. Conclusões
Este projeto demonstrou o potencial do Azure ML para análise de imagens, incluindo reconhecimento facial e extração de texto. Os resultados obtidos evidenciaram a robustez do modelo de detecção facial e a capacidade do modelo de extração de texto em lidar com textos estruturados.
