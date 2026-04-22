# festival

Descreva aqui as alterações/correções que fez

## url.py:
 - Adicionei um path para "dias" 

## views.py:
 - Correção do import, para usar dia e concerto para além do palco
 - Mudança no dias_view para ordenar por data
 - Adição do palcos_view
 - Mudança no conecrto_view para associar ao id

 ## Templates
 - em palcos.html o href foi igualado ao id do conecrto
 - em palcos.html foi adicionado o " date:"Y-m-d" " para ordenação
 - foi criado o dias.html pois foi pedido pelo dias_view em views.py