# Extension_Header_Promocao
Extension of disclosure stripe. When you need to put a disclosure banner on your Magento system, use our extension to improve your web application maintenance.

# Introdução
A extensão "Header_Promocao" utiliza da ferramenta chamada de modman.Desse modo, o desenvolvimento do sistema fica mais
pratico com o uso do modman, porêm uso do modman, em seu sistema, se torna opcional.(Caso queria aprender e utilizar em seu sistema
segue o link: https://andykdocs.de/development/Magento/2013-03-15+Deploying+Magento+Modules+with+modman)
# Introduction
The extension "Header_Promocao" uses the tool called modman. In this way, the development of the
Practice using modman, through the use of modman, in your system, making it optional (if you want to learn and use it in your system)
Follow the link:  https://andykdocs.de/development/Magento/2013-03-15+Deploying+Magento+Modules+with+modman)

# Desenvolvimento 
A implementação dessa tarja você quem escolhe.Portanto, vai ser preciso você criar um block onde pode ser interpretado em seu frontend.
Dessa forma vamos iniciar com o seguinte, Primeiro vá em busca do layoute que deseja inserir essa extensão. Com isso coloque esse trecho
do codigo para poder realizar o chamado: <block type="page/html" name="header_promocao" as="header_promocao" template="page/html/headerpromocao.phtml"/>.
Por fim insirar em seu header.phtml o :getChildHtml("hearder_promocao");

# Developer
The implementation of this stripe you choose.Therefore, you will need to create a block where it can be interpreted in your frontend.
That way we will start with the following, First go in search of the layoute that you want to insert this extension. With that put this stretch
of the code to be able to perform the call: <block type = "page / html" name = "header_promotion" as = "header_promocao" template = "page / html / headerpromocao.phtml" />.
Finally insert your header.phtml o: getChildHtml ("hearder_promotion");

# Comunicação 
Caso ainda exista Duvidas no funcionamento da extensão entre em contato com: jjortb@gmail.com. Para finalizar o tutorial de implementação
vai ser preciso você colocar suas edições no front-end para que se adeque ao seu template. ok ? bom uso do serviço.

# communication
If there is still doubt in the operation of the extension contact : jjortb@gmail.com. To complete the implementation tutorial
you'll need to put your edits on the front end to fit your template. OK ? good use of the service.
