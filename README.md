<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style media="screen">

    body{
    font-family: tahoma, Arial,  sans-serif;
    margin: 0;
    padding: 0;
    }

    #principal{
        width: 1024px;
        margin: 20px auto;
    }
    .header-top{
        height: 120px;
        background-color: chocolate;
        position: relative;
        border-radius: 5px;
    }

    .logotipo{
        height: 100%;
        margin: 0px 0 0 0 ;
    }

    .header-nav{
        position: absolute;
        top: 0;
        right: 0;
        height: 100%;
    }

    .header-nav ul{
        margin: 0;
        padding: 0;
    }

    .header-nav li{
        list-style: none;
        display: inline-block;
        margin: 0 15px 0 0;
        padding: 15px;
    }

    .header-nav a{
        color: white;
        text-decoration: none;
        text-transform: uppercase;
        font-size: 15px;
        font-weight: bold;
    }

    .header-nav a:hover{
        color:gray;
    }

    .portifolio{
        padding: 50px 100px;
        text-align: center;
    }

    .portifolio h1{
        font-size: 36px;
        color: chocolate;
    }

    .portifolio p{
        font-size: 16px;
        line-height: 2;
    }
    .gallery{
        color: darkgoldenrod;
        padding: 0 100px 50px 100px;
        overflow: auto;
    }

    .gallery-card{
        width: 32%;
        float: left;
        text-align: center;
    }

    .imgmenu{
    width: 200px;
    }

    .imgmain{
    width: 1024px;
    }

    .gallery-text{
        font-size: 15px;
        font-weight: bold;
        text-transform: uppercase;
    }

    .about{
        background-color: saddlebrown;
        padding: 100px;
        color: white;
        background-repeat: no-repeat;
    }

    .about h2{
        text-transform: uppercase;
        font-size: 30px;
        text-shadow: 5px 5px 5px rgb(12, 11, 11);
     }

     .about p{
        line-height: 1.5;
        width: 70%;
        text-shadow: 5px 5px 5px rgb(12, 11, 11);
     }

     #contact{
        margin: 50px 0;
     }

     #contact address{
        font-size: 26px;
        text-transform: uppercase;
        font-style: normal;
        text-align: center;
        color: sienna;
        font-weight: bold;
     }
       .maps{
        width: 100%;
        height: 450px;
        margin-top: 25px;
        text-align: center;
     }
     .maps iframe{
            width: 100%;
     }
     footer{
        background-color: peru;
        padding: 25px;
        font-size: 12px;
        color: black;
        text-align: center;
        font-size: 20px;
        border-radius: 5px;
     }

    </style>
    <title>p??es</title>
</head>
<body>
    <div id= "principal">

        <header class="header-top">
            <img class="logotipo"
            src="https://blog.novasafra.com.br/wp-content/uploads/2015/07/fotooooo.jpg" alt="Logotipo p??es">
            <nav class="header-nav">
          <ul>
              <li><a href="https://github.com/CleberPrestes">Portifolio</a></li>
              <li><a href="sobre.html">Sobre n??s</a></li>
              <li><a href="contato.html">Contato</a></li>
          </ul>
          </nav>
        </header>

        <img class="imgmain" src="https://thumbs.dreamstime.com/z/muitos-p%C3%A3es-e-rolos-misturados-53734988.jpg" alt="p??es gostosos">
        <article class="portifolio">
            <h1>P??es</h1>
            <h2>Historia dos p??es</h2>
            <p>A hist??ria do p??o ?? antiga. Ele teria surgido h?? mais de 6 mil anos, quando os eg??pcios descobriram a fermenta????o do trigo. Ali ele era considerado um alimento b??sico e era um s??mbolo de poder. Os p??es preparados com trigo de qualidade superior eram destinados apenas aos ricos.</p>
            <p>Os eg??pcios se dedicavam tanto ao p??o que se tornaram conhecidos como ???comedores de p??o???.</p>
            <h2>Tipos de P??es</h2>
            <p>P??o de centeio. A massa de p??o, fermentada naturalmente ou n??o, pode ser enriquecida com os mais diversos insumos, como sementes, cereais e gr??os, Marraqueta, Hallula, Tipos de p??es com sementes, P??o alentejano, P??o preto, P??o australiano, Ciabatta.</p>
            <p>A uma grande varia????o de p??es e muitos sabores com isso n??o da para sitar todos os p??es,ent??o esses s??o os mais famosos e gostosos p??es, com essa grande variedade nos podemos nos deliciar ainda mais</p>
        </article>
        <section class="gallery">
            <article class="gallery-card">
                <img class="imgmenu" src="https://img.itdg.com.br/tdg/images/recipes/000/061/546/102979/102979_original.jpg" alt="">
                <p class="gallery-title"></p>
                <p class="gallery-text">
                    croissant gostoso e fofinho
              </p>
            </article>
            <article class="gallery-card">
                <img class="imgmenu" src="https://cdn.panelinha.com.br/receita/1560954924818-baguete-receita.jpg" alt="">
                <p class="gallery-title"></p>
                <p class="gallery-text">
                    baguette gostoso e fofinho
                </p>
            </article>
            <article class="gallery-card">
                <img class="imgmenu" src="https://s2.glbimg.com/-V4nFrbjz9JMuWJnvQxl2NEplg8=/0x0:1280x922/924x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_e84042ef78cb4708aeebdf1c68c6cbd6/internal_photos/bs/2020/U/q/B5doHYQcKDxm0YsOynPA/pao-frances.jpeg" alt="">
                <p class="gallery-title"></p>
                <p class="gallery-text">
                    p??o fraces gostoso e crocant
                </p>
            </article>
        </section>
        <article class="about">
            <h2>Tudo sobre p??es</h2>
            <p>?? estimado que o p??o tenha surgido h?? 12 mil anos, na Mesopot??mia, juntamente com o cultivo do trigo. Os p??es eram feitos de farinha misturada com o fruto do carvalho. Os primeiros p??es eram achatados, duros, secos e muitos amargos. </p>
            <p>O p??o ?? um alimento rico em carboidratos, portanto significa que ?? uma ??tima fonte de energia para realizar as suas tarefas di??rias. Isso porque o carboidrato tamb??m contribui para a forma????o da serotonina - neurotransmissor respons??vel pela sensa????o de bom humor e bem-estar.</p>
            <p>O p??o ?? uma fonte importante de carboidrato. ?? respons??vel por fornecer energia necess??ria para desenvolver todas as atividades do nosso dia, dessa forma devemos consumi-lo em todas as fases da nossa vida.</p>
            <p>De t??o importante o alimento ganhou um dia s?? para ele: 16 de outubro, quando comemora-se o Dia Mundial do P??o. A data foi institu??da em 2000, em Nova York, pela Uni??o dos Padeiros e Confeiteiros.</p>
        </article>
        <div id="contact">
            <address>
                Ligue me para fazer sites
                <br>
                987654321
            </address>
            <div class="maps">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d28878.127840569763!2d-49.134934015860715!3d-25.21111332319534!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94dcc153d5264611%3A0xdd193cb59e9f8561!2sBocai%C3%BAva%20do%20Sul%2C%20PR%2C%2083450-000!5e0!3m2!1spt-BR!2sbr!4v1622641309172!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
        <footer>
            Autor:
            <br>
            Alexandre Cesar - N?? 2 - 1E
        </footer>
    </div>
</body>
</html>
