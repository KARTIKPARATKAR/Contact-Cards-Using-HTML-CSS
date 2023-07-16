# Contact-Cards-Using-HTML-CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cards</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .container{
            
            width: 100vw;
            height: 100vh;
            /* min-height: 980px; */
            background-color: #8BC6EC;
            background-image: linear-gradient(135deg, #8BC6EC 0%, #9599E2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 35px;
            padding-left: 10px;
            padding-right: 10px;
        }
        .card{
            width: 360px;
            height: 500px;
            background-color: white;
            border-radius: 25px;
            border: 3px solid rgb(43, 0, 255);
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
            padding: 20px;
            box-shadow: 5px 5px;
        }

        .card img{
            height: 57%;
            border-radius: 10px;
        }

        .card h2{
            font-weight: bold;
            font-size: 1.5rem;
        }

        .card p{
            font-size: 1.2em;
        }
        .logoes{
            height: 15px;
            width: 40px;
        }
        #gmail-logo{
            height: 40px;
            width: 45px;
        }
       /* #instagramqr #mailqr #whatsappqr #linkedinqr:hover{
        border: 4px solid green;
       } */
       .card:hover{
        cursor: pointer;
        border: 3px solid green;
        color: #04b9f6;
        background-color: #eadde9;
       }
       .FOOTER{
        background-color: #8BC6EC;
        text-align: center;
        position: relative;
        bottom: 40px;
       }
       .header{
        background-color:#8BC6EC ;
        text-align: center;
        position: relative;
        top: 70px;
        border: 1px solid rgb(0, 255, 0);
        font-size: 30px;
       }
    </style>
</head>
<body>
    <div class="header">
       <h2>CONTACT ME HERE BY SCANNING QR CODE ON GOOGLE LENS</h2>
    </div>
    <div class="container">
        
        <div class="card" id="mailqr">
            <img src="mail.png" alt="Mail Qr code">
            <img src="Gmail-Logo.jpg" alt="." class="logoes" id="gmail-logo">

            <h2>This is an Mail-id QR code</h2>

            <p>
                Scan this QR code to contact on Mail-id
            </p>
        </div>
        <div class="card" id="instagramqr">
            <img src="instagram qr.png" alt="Instagram Qr code">
            <img src="2048px-Instagram_icon.png" alt="." class="logoes">

            <h2>This is an Instagram QR code</h2>

            <p>
                Scan this QR code to contact on INSTAGRAM
            </p>
        </div>
        <div class="card" id="linkedinqr">
            <img src="linkedinqr.png" alt="Linkedin Qr code">
            <img src="702300.png" alt="." class="logoes">

            <h2>This is an Linkedin QR code</h2>

            <p>
                Scan this QR code to contact on Linkedin
            </p>
        </div>
        <div class="card" id="whatsappqr">
            <img src="whats app qr.jpeg" alt="Whasapp Qr code">
            <img src="png-transparent-iphone-whatsapp-logo-whatsapp-call-icon-grass-mobile-phones-instant-messaging.png" alt="." class="logoes">

            <h2>This is an Whatsapp QR code</h2>

            <p>
                Scan this QR code to contact on Whatsapp
            </p>
        </div>

    </div>
    <footer class="FOOTER">All Rights Reserved @KSP1</footer>

</body>
</html>
