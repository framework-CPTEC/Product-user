CPTEC-Products Documentação
========================

É um pacote in Python para a distribuição de dados brutos do Produtos:

MERGE
O produto MERGE (Rozante et al.,2010) consiste em combinar a precipitação
observada com estimativa de precipitação por satélite. Mais detalhes sobre a técnica
podem ser encontrados em:
http://ftp.cptec.inpe.br/modelos/tempo/MERGE/rozante_et.al.2010.pdf
Este produto é gerado e disponibilizado operacionalmente pelo CPTEC/INPE utilizando
a estimativa de precipitação por satélite.

SAMeT
O produto SAMeT (South American Mapping of Temperature) é um produto desenvolvido e 
está disponível operacionalmente para a América do Sul. Este produto combina dados 
observados com a reanálise ERA5, fazendo uma correção do campo de temperatura usando 
uma taxa de lapso estimada. A taxa de lapso foi estimada para quatro regiões localizadas 
na América do Sul e para as quatro estações do ano. Os valores estimados para a taxa de 
lapso foram, em todas as situações, inferiores à taxa de lapso padrão (-6,5 °C·km⁻¹). 
A combinação de reanálise e observações, juntamente com a correção da taxa de lapso, produziu
campos de temperatura mais precisos do que os fornecidos pelo ERA5, especialmente em regiões 
com topografia mais acentuada. Mais detalhes em este link (https://ftp.cptec.inpe.br/modelos/tempo/SAMeT/rozante_et_al_2021.pdf)

SMEC
O produtos SMEC consiste em um método de previsão numérica do tempo por conjunto para a região da América do Sul. 
Este método leva em consideração combinações das previsões numéricas de vários modelos, atribuindo
maior peso aos modelos que apresentam o melhor desempenho. Nove modelos numéricos operacionais
foram utilizados para realizar este estudo. O objetivo principal do estudo é obter um produto 
de previsão do tempo (curto a médio prazo) que combine o melhor de cada um dos nove modelos 
utilizados no estudo, produzindo assim previsões mais confiáveis. 
O método proposto foi avaliado durante o verão austral (dezembro de 2012, e janeiro e fevereiro de 2013) 
e o inverno (junho, julho e agosto de 2013). Os resultados mostram que o método proposto pode melhorar
significativamente os resultados fornecidos pelos modelos numéricos e, consequentemente, 
tem potencial promissor para aplicações operacionais em qualquer centro de previsão do tempo.
Mais detalhes em este link (https://ftp.cptec.inpe.br/modelos/tempo/SMEC/rozante_et_al_2014.pdf)

.. note::

   support Python >= 3.10.

Contents
--------

.. toctree::
   /install
   /usage
   /examplesPython
   /grads


   
