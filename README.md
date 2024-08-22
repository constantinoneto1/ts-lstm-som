# TimeSeries_SOM_LSTM  

## EN (PTBR logo abaixo)  
### What is this project about?
This is an implementation of local learning for time series forecasting using self-organizing maps (SOMs) for determining time-window similarity and specialized long short-term memory recurrent neural networks (LSTM-RNNs) for prediction. This project has been developed by [Eduardo Ximenes](https://github.com/diest), [Constantino Neto](https://github.com/constantinoneto1) and Gabriel Gonçalves.
  
### What did we find out?  
* Cosine distance tends to work better than euclidean distance for calculating similarities between time windows due to it considering the angle among two vectors, which preserves tendencies and variations.  
* RNNs are not quite optimal for local learning due to their long-term dependencies, so they perform better with longer series.

### What could be improved?
* Combining SOM with other less long-term dependant models, such as enhanced multilayer perceptrons, could prove to be more adequate for local learning applications.  
* Comparison with other local learning applications could clarify the validity of this technique.  


  
## PTBR  
### Sobre o que é esse projeto?
Uma implementação de aprendizado local para previsão de séries temporais usando mapas auto-organizáveis (SOMs) para determinar similaridade de janelas temporais e redes neurais recorrentes especializadas do tipo memória longa de curto-prazo para previsão. O projeto foi desenvolvido por [Eduardo Ximenes](https://github.com/diest), [Constantino Neto](https://github.com/constantinoneto1) e Gabriel Gonçalves.

### O que pudemos perceber?
* Distância de cosseno tende a funcionar melhor do que euclideana para calcular similaridade entre janelas temporais devido a ela considerar o ângulo entre dois vetores, o que preserva tendências e variações.
* RNNs não são ótimas para aprendizado local devido a suas dependências de longo prazo, então elas desempenham melhor com séries longas.

### O que poderia ser aprimorado?  
* Combinar SOM com outros modelos menos dependentes de longo prazo, como perceptrons multicamada aprimorados, pode se mostrar mais adequado para aplicações de aprendizado local.
* Comparar com outras aplicações de aprendizado local pode esclarecer o quão válida é essa técnica.
