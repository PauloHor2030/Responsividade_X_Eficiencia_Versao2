# Responsividade_X_Eficiência

Como equilibrar Responsividade e Eficiência na carga de imagens.

  Quando queremos ter imagens com resolução adequada aos equipamentos que estaremos trabalhando,   
temos que fazer com que a programação se adeque ao equipamento que irá abrir o site.

  Se o Browser utilizado suportar a propriedade srcset, podemos configurar o tamanho da imagem de acordo com a 
resolução do equipamento (ie, celular, desktop, laptop, monitor 4k):

* Se for um celular, poderá ser uma resolução menor,
  no nosso por exemplo, width= 200w.
* Quando for uma tela mediana, teremos que usar uma resolução
  igualmente mediana, no nosso por exemplo, width= 400w.
* Entretanto, quando a tela tiver uma resolução 4K ou mais, deveremos trabalhar
  com uma resolução superior, no nosso por exemplo, width= 600w.

  **** Atenção ****
  Cabe ressaltar que em caso do browser nao suportar a propriedade srcset, 
nós já prevemos com o uso da imagem no tamanho de 200 x 100.
