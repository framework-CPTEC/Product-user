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
com topografia mais acentuada. Mais detalhes em este link (https://ftp.cptec.inpe.br/modelos/tempo/SAMeT/rozante_et_al_2021.pdf


previsão sazonal do CPTEC/INPE  produzidos com o modelo BAM-1.2. Os arquivos de dados contêm a média do conjunto (de 15 membros) para todos os produtos e variáveis mostradas no site https://sazonal.cptec.inpe.br/.

Esses arquivos estão disponíveis como anomalias computadas referentes à climatologia 1981-2010.

.. note::

   support Python >= 3.10.

Contents
--------

.. toctree::
   /install
   /usage
   /examplesPython
   /grads


   
