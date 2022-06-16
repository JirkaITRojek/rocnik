<!DOCTYPE html>
<html lang="cs">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <title>Úvodní stránka</title>
</head>

<body>
    <header>
        <ul class="nav nav-tabs" id="navId" role="tablist">
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button"
                    aria-haspopup="true" aria-expanded="false">Suroviny</a>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="./g/index.html#iron">Železná ruda</a>
                    <a class="dropdown-item" href="./g/index.html#med">Měděná ruda</a>
                    <a class="dropdown-item" href="./g/index.html#coal">Uhlí</a>
                    <a class="dropdown-item" href="./g/index.html#stone">Kámen</a>
                    <a class="dropdown-item" href="./g/index.html#wood">Dřevo</a>
                    <a class="dropdown-item" href="./g/index.html#steel">Ocel</a>
                    <a class="dropdown-item" href="./g/index.html#oil">Ropa</a>
                    <a class="dropdown-item" href="./g/index.html#oilp">Ropné produkty</a>
                    <a class="dropdown-item" href="./g/index.html#uranium">Uranová ruda</a>
                    <a class="dropdown-item" href="./g/index.html#energy">Elektřina</a>
                </div>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button"
                    aria-haspopup="true" aria-expanded="false">Vědecké balíčky</a>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="./a/index.html#automatizacni">Automatizační</a>
                    <a class="dropdown-item" href="./a/index.html#logisticni">Logistický</a>
                    <a class="dropdown-item" href="./b/index.html#vojensky">Vojenský</a>
                    <a class="dropdown-item" href="./c/index.html#chemicky">Chemický</a>
                    <a class="dropdown-item" href="./d/index.html#vyrobni">Výrobní</a>
                    <a class="dropdown-item" href="./e/index.html#uzitek">Užitkový</a>
                    <a class="dropdown-item" href="./f/index.html#space">Vesmírný</a>
                </div>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button"
                    aria-haspopup="true" aria-expanded="false">Odkazy</a>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="https://www.factorio.com/">Oficiální strana Factoria</a>
                    <a class="dropdown-item" href="https://www.youtube.com/watch?v=J8SBp4SyvLc">Trailer 2020</a>
                    <a class="dropdown-item" href="https://www.youtube.com/watch?v=KVvXv1Z6EY8">Trailer 2016</a>
                    <a class="dropdown-item" href="https://store.steampowered.com/app/427520/Factorio/">Steam</a>
                    <a class="dropdown-item" href="https://www.youtube.com/c/Nilaus">Youtube EN Nilaus</a>
                    <a class="dropdown-item" href="https://www.youtube.com/c/Trupen">Youtube EN Trupen</a>
                    <a class="dropdown-item" href="https://www.youtube.com/c/TenSterakdary/featured">Youtube CZ
                        Sterakdary</a>
                </div>
            </li>
            <li class="nav-item ">
                <a class="nav-link " href="./uvod.html" role="button" aria-haspopup="true" aria-expanded="false">Úvodní
                    strana</a>
            </li>
            <li class="nav-item ">
                <a class="nav-link " href="./h/index.html" role="button" aria-haspopup="true"
                    aria-expanded="false">Test</a>
            </li>


        </ul>
        <div class="tab-content" id="myTabContent">
            <div class="tab-pane fade show active" id="tab1Id" role="tabpanel"></div>
            <div class="tab-pane fade" id="tab2Id" role="tabpanel"></div>
            <div class="tab-pane fade" id="tab3Id" role="tabpanel"></div>
            <div class="tab-pane fade" id="tab4Id" role="tabpanel"></div>
            <div class="tab-pane fade" id="tab5Id" role="tabpanel"></div>
        </div>
        <script>
            var triggerEl = document.querySelector('#navId a')
            bootstrap.Tab.getInstance(triggerEl).show()
        </script>
        <h1>Factorio</h1>
    </header>
    <main class="container">

        <div class="okolo">
            <div>
                <h2>Příběh Factoria</h2>
                <p>Ztroskotali jste na planetě a abyste se mohli dostat zpátky na Zemi musíte vyzkoumat raketu a
                    postavit si ji, ale vyzkoumat a postavit raketu není jenom tak budete k tomu potřebovat hromady
                    surovin které budete muset vytěžit samozřemně nebude těžit všechno ručně účelem hry je automatizace
                    na začátku máte těžící zařízení které poháníte uhlím nebo dřeven ale postupně se dostáváte do fází
                    kde je všechno na elektřinu kterou musí někde vyrábět. Každým rozšířením svojí továrny za účelem
                    výzkumu rakety se vám někde objeví nedostatek o který se musíte postarat může vám dojít železo nebo
                    ropa či elektřina. Nemyslete si však že jste na planetě sami znečištění které vaše továrna produkuje
                    např. těžením surovin se nelíbí místním obivatelům se kterými budou stále problémy a bude je muset
                    ve své cestě za větší továrnou přátelsky vyhladit. </p>
                <p>Factorio je singleplayer hra která se dá hrát i v multiplayer módu s přáteli.</p>
                <p>Cílem hry je stavět, udržovat a rozšiřovat továrny.</p>

            </div>
            <div>
                <h2>Účel stránky</h2>
                <p>Účelem této stránky je dát základní informace o vědeckých balíčcích ve hře a suroviny potřebné k
                    jejich výrobě. Plus nějaké tipy a odkazy na videa která mohou usnadnit postup ve hře.</p>
            </div>
            <div class="row">
                <div id="carouselId" class="carousel slide" data-bs-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-bs-target="#carouselId" data-bs-slide-to="0" class="active"></li>
                        <li data-bs-target="#carouselId" data-bs-slide-to="1"></li>
                        <li data-bs-target="#carouselId" data-bs-slide-to="2"></li>
                        <li data-bs-target="#carouselId" data-bs-slide-to="3"></li>
                        <li data-bs-target="#carouselId" data-bs-slide-to="4"></li>


                    </ol>
                    <div class="carousel-inner" role="listbox">
                        <div class="carousel-item active">
                            <img src="./img/trosky.png" alt="Trosky rakety"
                                style="width:700px;height: 500px; text-align: center;">
                        </div>
                        <div class="carousel-item">
                            <img src="./img/firstmine.png" alt="První těžení" style="width:700px;height: 500px;">
                        </div>
                        <div class="carousel-item">
                            <img src="./img/automatizace.png" alt="Začátek automatizace"
                                style="width:700px;height: 500px;">
                        </div>
                        <div class="carousel-item">
                            <img src="./img/firstfight.png" alt="Prní boj s nepřítelem"
                                style="width:700px;height: 500px;">
                        </div>
                        <div class="carousel-item">
                            <img src="./img/rocket.png" alt="Odlet rakety" style="width:700px;height: 500px;">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselId"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselId"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
            <div class="container mt-3">
                <h2>Statisktiky</h2>
                <p>Tahle tabulka ukazuje odehraný čas a počty obětovaných věcí k dokončení hry.</p>
                <table class="table table-dark">
                    <thead>
                        <tr>
                            <th>Názvy</th>
                            <th>Počty</th>
                            <th>Vysvětlení</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Odehraný čas</td>
                            <td>71:28:02</td>
                            <td>Čas potřebný k nasbírání všech fotek použitých na těchto stránkách</td>
                        </tr>
                        <tr>
                            <td>Velký plivač</td>
                            <td>88 544</td>
                            <td>Počet zabitých nepřátelských plivačů</td>
                        </tr>
                        <tr>
                            <td>Velký kousač</td>
                            <td>60 485</td>
                            <td>Počet zabitých nepřátelských kousačů</td>
                        </tr>
                        <tr>
                            <td>Střední plivač</td>
                            <td>49 573</td>
                            <td>Počet zabitých nepřátelských plivačů</td>
                        </tr>
                        <tr>
                            <td>Střední kousač</td>
                            <td>22 737</td>
                            <td>Počet zabitých nepřátelských kousačů</td>
                        </tr>
                        <tr>
                            <td>Obří plivač</td>
                            <td>7 451</td>
                            <td>Počet zabitých nepřátelských plivačů</td>
                        </tr>
                        <tr>
                            <td>Obří kousač</td>
                            <td>6 512</td>
                            <td>Počet zabitých nepřátelských kousačů</td>
                        </tr>
                        <tr>
                            <td>Malý plivač</td>
                            <td>3 562</td>
                            <td>Počet zabitých nepřátelských plivačů</td>
                        </tr>
                        <tr>
                        <td>Malý kousač</td>
                        <td>3 255</td>
                        <td>Počet zabitých nepřátelských kousačů</td>
                        </tr>
                        <tr>
                        <td>Strom</td>
                        <td>2090</td>
                        <td>Počet brutálně zničených stromů</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div>
                <h2>Co jsi vzít z těchto stránek?</h2>
                <ul style="list-style-type:circle">
                    <li>Výroby vědeckých balíčků</li>
                    <li>Výroby základních surovin</li>
                    <li>Že hru trvající přes 70 hodin nechcete hrát</li>
                    <li>Pobavení a možné pochopení účelu stránek</li>
                </ul>
                <h2>Údaje</h2>
                <ul style="list-style-type:circle">
                    <li>Email - it2120@sspu-opava.cz</li>
                    <li>Jméno pachatele - Jiří Rojek</li>
                    <li>&copy; Jiří Rojek IT1 , 2022</li>
                    <li>Tyhle stránky jsou jenom ročníkový projek</li>
                </ul>
            </div>
        </div>   
    </main>
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"
        integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js"
        integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/holder/2.9.8/holder.min.js"
        integrity="sha512-O6R6IBONpEcZVYJAmSC+20vdsM07uFuGjFf0n/Zthm8sOFW+lAq/OK1WOL8vk93GBDxtMIy6ocbj6lduyeLuqQ=="
        crossorigin="anonymous" referrerpolicy="no-referrer"></script>
</body>

</html>
