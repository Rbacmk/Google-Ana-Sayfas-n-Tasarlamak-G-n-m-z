# Google-Ana-Sayfas-n-Tasarlamak-G-n-m-z
Html Kodları
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google-Günümüz</title>
    <link rel="stylesheet" href="googleÖ3.css">
    <!--Html ve Css ile iletişim kuruyor.-->
</head>

<body>
    <div class="container">
        <div class="item1">

            <div class="google">
                <div class="kutu1 ">
                    <p><a href="">Gmail</a> <a href="">Görseller</a></p>
                </div>

                <div class="kutu2">
                    <img src="3.PNG" alt="resim">
                </div>
            </div>

        </div>
        <!--Gmail ve Görsel KISMI-->






        <div class="item2">
            <div class="item21">
                <img src="https://github.com/Kodluyoruz/taskforce/blob/main/css/odev2/google_homepage/assets/logo.png?raw=true"
                    alt="">
                <div class="item22">
                    <input type="text" class="inputStyle">
                   
                </div>

                <div class="item23">
                    <center><img src="7.PNG" alt=""></center>
                </div>




            </div>

            <div>

            </div>
        </div>








































    </div>

</body>

</html>
Css Kodları
*{
    margin:0px;
    padding:2px;
}
.container{ /*En büyük kutumuz*/
    display:flex;
    background-color: white;
    width:1350px;
    height:630px;
    flex-direction: column;/*Kolonlara böldük.*/
}
   

.item1{
    background-color: white;
    width:100%;
    height: 100px;
    
    }
    .google{
        width:250px;
        height:90px;
        background-color: white;
        float:right;
    }
    .kutu1{
     float:left;
    }
    .kutu2{
        float:left;
    }

.item2{
     background-color: white;
     width:100%;   
     height: 400px;
     display:flex;
     align-content: stretch;
    justify-content:center;
}
.item21{
background-color: white;
width:300px;
height: 399px;

}
.item22{
    
    width:300px;
    height: 25px;
    background-color: white;
    border-radius: 10px;
}
.item23{
    margin-top:10px;
    width:300px;
    height: 75px;
    background-color: white;
    border-radius: 10px; 
    display: flex;
    
   
    
}
.inputStyle {
    width: 299px;
    height: 25px;
    border-radius: 2px;
    border:1;
}

