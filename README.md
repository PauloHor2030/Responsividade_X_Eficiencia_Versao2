# Responsividade_X_Eficiência

## Como equilibrar Responsividade e Eficiência na carga de imagens?<br>

  Quando queremos ter imagens com resolução adequada aos equipamentos que estaremos trabalhando,<br>   
teremos que fazer com que a programação se adeque ao equipamento/device que irá abrir o site.

###  Se o Browser utilizado suportar a propriedade srcset, podemos configurar o tamanho da imagem de acordo com a <br>
###  resolução do equipamento (ie, celular, desktop, laptop, monitor 4k):

* Se for um celular, poderá ser uma resolução menor,<br>
  no nosso por exemplo [até 480px de largura] , width= 200w.
* Quando for uma tela mediana, teremos que usar uma resolução<br>
  igualmente mediana, no nosso por exemplo [de 481px até 1024px de largura], width= 400w.
* Entretanto, quando a tela tiver uma resolução 4K ou mais, nos casos de ultrawide [maior que 1024px de largura], <br> 
  deveremos trabalhar com uma resolução superior, no nosso por exemplo, width= 600w.

### **** Atenção **** <br>
  Cabe ressaltar que em caso do browser nao suportar a propriedade srcset, <br>
nós já prevemos com o uso da imagem no tamanho de 200 x 100.
