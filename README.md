# Pousada-Secreta
Projeto que fiz pelo Dev Media 
<!DOCTYPE HTML>
<html>
    <head>
        <meta lang = "pt-br">
        <meta charset = "UTF-8">
        <meta name = "descriptions" content = "Pousada Secreta">
        <meta name = "robots" content = "noindex, nofollow">
        <meta name = "viewport" content = "width=device-width, initial-scale=1.0">
        <link rel = "stylesheet" type = "text/css" href = "CSS/pousada.css"/>
        <link rel = "stylesheet" href = "https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700;1,900&display=swap"/>
        <title>Pousada Secreta</title>
    </head>
    <body>
        <!--1 - Topo-->
        <div class = "topo">
            <div class = "secao-menu">
                <a class = "nome-logo" href = "#PousadaSecreta">Pousada <span>Secreta</span></a>
                <div>
                    <a class = "menu" href = "#sobre">SOBRE</a>
                    <a class = "menu" href = "#rota">ROTA</a>
                    <a class = "menu" href = "quartos.html">QUARTOS</a>
                </div>
            </div>
        </div>

        <!--2 - Imagem do fundo-->
        <div class = "conteudo-principal">
            <div class = "PousadaSecreta">
                <div class = "pagina-inicial">
                    <h1>Pousada Secreta</h1>
                    <p>A pousada reservada em Angra dos Reis</p>
                </div>
            </div>

            <!--3 - Conteudo Bem vindo-->
            <div class = "secao-titulo">
                <div id = "pousada.html">
                    <h2>SEJA BEM VINDO (A)!</h2>
                    <p>Relaxe em nossa acomodações e curta o melhor de Angra dos Reis.</p>
                    <p>Temos quartos para solteiros, casal ou familía.</p>
                </div>
            </div>
            <!--Seção quartos-->
            <div class = "secao-tamanho secao-quartos">
                <div class = "quartos">
                    <img src = "img/quarto-solteiro1.jpg" alt = "Quarto de Solteiro" title = "Quarto de solteiro">
                    <a href = "quartos.html#solteiro" target = "_self"><p>QUARTO DE SOLTEIRO</p></a>
                </div>

                <div class = "quartos">
                    <img src = "img/quarto-casal1.jpg" alt = "Quarto de casal" title = "Quarto de casal">
                    <a href = "quartos.html#casal" target = "_self"><p>QUARTO DE CASAL</p></a>
                </div>

                <div class = "quartos">
                    <img src = "img/quarto-familia1.jpg" alt = "Quarto família" title = "Quarto família">
                    <a href = "quartos.html#familia" target = "_self"><p>QUARTO FAMÍLIA</p></a>
                </div>
            </div>

            <!--Seção ROTA-->
            <div class = "secao-titulo">
                <!--<div id = "rota">-->
                    <h2 id = "rota">ROTA</h2>
                    <p>Veja como chegar até a pousada</p>
                </div>
            </div>
            <iframe src = "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14692.471710812997!2d-43.3641911!3d-22.9826906!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x539cb07246f0e38d!2sVia%20Parque%20Shopping!5e0!3m2!1spt-BR!2sbr!4v1612707978931!5m2!1spt-BR!2sbr" width="100%" height="350" frameborder="0" style="border:0" allowfullscreen></iframe>
            
            <!--Seção SOBRE-->
            <div class = "secao-titulo">
                <div id = "sobre">
                    <h2>SOBRE A POUSADA!</h2>
                    <p>Conheça um pouco sobre nossa pousada.</p>
                </div>
            </div>

            <div class = "principal-container-sobre">
                <div class = "container-sobre">
                    <div class = "descricao-sobre">
                        <h3>A POUSADA</h3>
                        <p>A pousada Dev dispõe de estabelecimento privativo gratuita, piscina ao ar livre e bar.</p>
                    </div>
                    <div>
                        <img class = "descricao-img" src = "img/img1.jpg" alt = "Imagem da pousada">
                    </div>
                </div>

                <div class = "container-sobre">
                    <div class = "descricao-sobre">
                        <h3>Nossos quartos</h3>
                        <p>
                            Os quartos possuem TV de tela plano a cabo, cozinha compacta e área para refeição. Além disso, as unidades da Pousada Dev contam
                            com ar-condicionado.
                        </p>
                    </div>
                    <div>
                        <img class = "descricao-img" src = "img/img2.jpg" alt = "Quartos">
                    </div>
                </div>

                <div class = "container-sobre">
                    <div class = "descricao-sobre">
                        <h3>Alimentação</h3>
                        <p>A pousada serve café da manhã em estilo continental ou buffet. Nossos restaurantes funcionam 24hrs.</p>
                    </div>
                    <div>
                        <img class = "descricao-img" src = "img/img3.jpg" alt = "Buffet">
                    </div>
                </div>

                <div class = "container-sobre">
                    <div class = "descricao-sobre">
                        <h3>Recepção</h3>
                        <p>Nossa recepção fica aberta 24hrs.</p>
                    </div>
                    <div>
                        <img class = "descricao-img" src = "img/img5.jpg" alt = "Recepção">
                    </div>
                </div>
            </div>
        </div>

        <!--Seção RODAPE-->
        <div class = "container-rodape">
            <div class = "secao-rodape">
                <div class = "secao-info">
                    <h4>Entre em contato conosco:</h4>
                </div>

                <div class = "secao-info">
                    <img class = "icone-rodape" src = "img/icones/endereco.png" alt = "">
                    <a class = "link-rodape" href = "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14692.471710812997!2d-43.3641911!3d-22.9826906!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x539cb07246f0e38d!2sVia%20Parque%20Shopping!5e0!3m2!1spt-BR!2sbr!4v1612707978931!5m2!1spt-BR!2sbr" target = "_blank"><p>Endereço Av. 123,222 - Rio de Janeiro RJ</p></a>
                </div>

                <div class = "secao-info">
                    <img class = "icone-rodape" src = "img/icones/telefone.png" alt = "">
                    <p>Cel: +55 (21) 90000-0000</p>
                </div>

                <div class = "secao-info">
                    <img class = "icone-rodape" src = "img/icones/calendario.png" alt = "">
                    <a class = "link-rodape" href = "https://www.booking.com" target = "_blank"><p>Faça sua reserva pelo Booking.com</p></a>
                </div>

                <div class = "rodape-compania">
                    <p>© Copyright - PousadaDev</p>
                </div>
            </div>
        </div>
    </body>
</html>



CSS - Pousada.css
*{
    box-sizing: border-box;
}
body{
    font-family: 'Source Sans Pro', sans-serif;
    margin: 0;
    padding: 0;
    color: #3D3D3D;
    background-color: #FFFFFF;
}
img{
    width: 100%;
}

/*Estilização TOPO*/
.secao-menu{
    max-width: 1024px;
}
.topo{
    width: 100%;
    position: fixed;
    background-color: white;
    border-bottom: 1px solid #5D5D5D;
}
.topo .secao-menu{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 60px;
    padding: 0 10px;
    margin: 0 auto;
}
.nome-logo{
    margin: 0 40px 0 0;
    font-size: 24px;
    color: #3D3D3D;
    text-decoration: none;
}
.nome-logo span{
    color: #6592C9;
}
.menu{
    text-transform: uppercase;
    line-height: 18px;
    padding: 0px 15px 10px 15px;
    color: #3D3D3D;
    text-decoration: none;
}
.link:hover{
    border-bottom: 3px solid #6592C9;
}

/*Imagem do fundo*/
.PousadaSecreta{
    background-image: url(img.css/img-fundo.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
.pagina-inicial{
    color: #FFFFFF;
    background-color: #0A9077B3;
    text-align: center;
    font-size: 30px;
    padding: 0 20px;
    border: 1px solid #FFF;
    border-radius: 5px;
}
.secao-titulo{
    text-align: center;
    font-size: 20px;
    padding-top: 50px;
    padding-bottom: 20px;
}
.secao-titulo h2{
    font-weight: normal;
    font-size: 30px;
}

/*Seção Quartos*/
.secao-tamanho{
    width: 1024px;
    margin: 0 auto;
}
.secao-quartos{
    display: flex;
    justify-content: space-between;
}
.secao-quartos img{
    width: 350px;
}
.quartos{
    margin-right: 30px;
    font-size: 20px;
    border-bottom: 2px solid #00836A;
    text-decoration: none;
    color: #3D3D3D;
}
.quartos a{
    text-decoration: none;
    color: #333333;
}
.quartos a p{
    text-align: center;
    font-weight: bold;
}
.quartos:last-child{
    margin-right: 0;
}

/*Secao SOBRE*/
.principal-container-sobre{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding-bottom: 50px;
    width: 1024px;
    margin: 0 auto;
}
.container-sobre{
    display: flex;
    width: 45%;
    margin: 0 10px;
    align-items: center;
    justify-content: space-between;
}
.descricao-sobre{
    flex: 1 1 auto;
}
.descricao-img{
    width: 100px;
    height: 113px;
    object-fit: cover;
    margin-left: 10px;
}

/*Seção RODAPE*/
.container-rodape{
    width: 100%;
    background-color: #49997D;
    color: #FFFFFF;
}
.container-rodape h4{
    font-size: 22px;
}
.secao-rodape{
    width: 1024px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
.secao-info{
    width: 23%;
    display: flex;
    align-items: center;
}
.link-rodape{
    margin-right: 10px;
    color: #FFFFFF;
    text-decoration: none;
}
.icone-rodape{
    width: 40px;
    height: 40px;
    margin-right: 10px;
}
.rodape-compania{
    text-align: center;
    padding: 20px;
    border-top: 1px solid #3B7863;
    font-weight: 600px;
    width: 100%;
}
