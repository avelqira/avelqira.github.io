# AVELQIRA MAKE & BEAUTY

Site estático para GitHub Pages, com catálogo de produtos e pedidos por WhatsApp.

## Editar produtos e preços
Abra assets/js/products.js. Procure pelo código do produto e atualize nome, marca, categoria ou preço sugerido. Os valores devem ser números (ex.: 10 ou 15.5). O campo description pode ser preenchido para aparecer no cartão do produto. Não inclua custos, fornecedor ou estoque interno.

## Trocar fotos
Envie uma foto para assets/images/products/ e informe o caminho no campo image, por exemplo: assets/images/products/GA033.jpg. Na vitrine aparecem os produtos marcados como status ativo; use available:false para ocultar temporariamente um item.

## Contato
Os canais oficiais ficam em assets/js/config.js. WhatsApp usa o formato DDI+DDD+número, somente dígitos; Instagram é opcional.

## Publicar atualizações
No GitHub, edite o arquivo ou envie a foto, depois clique em Commit changes na branch main. O Pages republica as alterações automaticamente; pode levar alguns minutos.

Este site funciona como catálogo e solicitação pelo WhatsApp. Não processa pagamento, frete, reserva ou estoque em tempo real.
