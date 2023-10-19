<!DOCTYPE html>
<html lang="it">
<head>
    <link rel="icon" href="logo3.ico.ico" type="image/x-icon">

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biscotteria Pinocchio</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">
    <style>
        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #fffdfd;
            color: #000000;
            padding: 10px;
            text-align: left;
            font-size: 12px;
        }
        main {
            padding: 20px;
            margin-left: 50px; 
            color: #911515;

        }
        .background-image {
            position: fixed;
    top: 10px; 
    left: 10px;
    width: 90%; 
    height: 90%;
    background-size: cover;
    pointer-events: none;
    opacity: 0.12;
        }
        .carousel-item img {
            width: 100%;
            height: 70%; 
            object-fit: cover; 
        }
        .carousel-caption {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px;
            color: #fff;
        }

        .carousel-caption h3 {
            font-size: 2em; 
        }

        .carousel-caption p {
            font-size: 1.2em;
        }
        .carousel-inner {
    margin-top: 45px; 
}
    </style>
    
</head>
<body>
    
    
    <header>
        
        
        <div id="myCarousel" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
            </ol>
            
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="preferiti.jpg" alt="biscotti confezionati">
                    <div class="carousel-caption">
                        <h3>Biscotti Confezionati</h3>
                        <p>Descrizione dei biscotti confezionati</p>
                    </div>
                </div>
        
                <div class="carousel-item">
                    <img src="Biscotti meringati al cioccolato.jpg" alt="biscotti artigianali">
                    <div class="carousel-caption">
                        <h3>Biscotti Artigianali</h3>
                        <p>Descrizione dei biscotti artigianali</p>
                    </div>
                </div>
        
                <div class="carousel-item">
                    <img src="sfondo.jpg" alt="biscotti fuori produzione">
                    <div class="carousel-caption">
                        <h3>Biscotti Fuori Produzione</h3>
                        <p>Descrizione dei biscotti fuori produzione</p>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </header>    
    <main>
        
        <h2>come mangiare i biscotti</h2>
        <p>salve qui vi spiegherò come si mangiano i biscotti</p>
    </main>
    <footer>
        <p>Biscotteria Pinocchio - miglior biscotteria al mondo </p>
       <p> Via San Lorenzo 120 Mantova</p> 
        <p>Telefono: xxx-xxx-xxxx</p>
        <p>Mail XXXXXXXXX.com</p>
        <p>Fax XXX-XXX-XXXX</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script>
        $(document).ready(function(){
            $('#myCarousel').carousel({
                interval: 5000
            });
        });
    </script>
</body>
</html>
