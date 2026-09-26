<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inscription</title>
        <style>
        body {background-color: #f4f4f9;}
        /*TEXTE*/
        .text-section {
            width: 50%;
            position:relative;
            padding: 40px;
        }
        .text-section h1 {
            margin-bottom: 3px;
            color: #9b2e2e;
        }
        /* inscription*/
        .form-section {
            position: absolute;
            top: 50%;
            left: 70%;
            transform: translate(-50%, -50%);  
        }
        .form-group {margin-bottom: 20px;}

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
            color: #333;
        }

        .form-group input {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 14px;
        }
        /* Inscription */
        .btn-submit {
            width: 100%;
            padding: 12px;
            background-color: #3498db;
            border: none;
            border-radius: 6px;
            font-size: 16px;
        }

        .btn-submit a{
            color: white;
            text-decoration: none;
            font-weight: 600;
        }
        .form-section p a {
            color: #3498db;
            text-decoration: none;
            font-weight: 600;
        }
    </style>
</head>
<body> 
    
    <div class="text-section">
        <h1> sur votre plateforme commerciale intégrée !</h1>
        <p>​La solution idéale pour présenter et gérer vos produits en toute simplicité.
        Notre plateforme vous permet de créer votre espace, d'ajouter vos produits, de suivre
        et modifier votre stock en temps réel, et d'exposer vos articles à vos clients de manière professionnelle.
        </p>
        <h4> ou créez un compte dès maintenant pour développer votre activité !</h4>
        <h1>مرحباً بك في منصتك التجارية الشاملة!</h1>
        <p>​​المنصة الأمثل لإدارة وعرض منتجاتك بكل سهولة وأمان.تتيح لك إمكانية إضافة منتجاتك الخاصة، مراقبة المخزون وتحديثه في الوقت الفعلي، وعرض معروضاتك للزبائن بشكل احترافي لزيادة مبيعاتك.
        </p>
        <h4>​قم بتسجيل الدخول أو إنشاء حساب جديد للبدء في إدارة متجرك الآن!</h4>
        <h1> ​Welcome to your all-in-one e-commerce platform!</h1>
        <p>
        ​The ultimate solution to showcase and manage your products with ease.<br> Our platform allows you to create your store, add your products, track and update your inventory in real time, and present your items professionally to your customers.
        </p>
        <h4>​Log in or sign up today to start growing your business!</h4>
    </div>
    <!--inscription-->
    <div class="form-section">
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="gmail">Gmail</label>
                    <input type="email" id="gmail" name="gmail" placeholder="exemple@gmail.com" required>
                </div>

                <div class="form-group">
                    <label for="code">Code</label>
                    <input type="password" id="code" name="code" placeholder="أدخل الكود الخاص بك" required>
                </div>

                <button type="submit" class="btn-submit"><a href="votre_Boutique.html">Inscription</a></button>
                <p>Vous n'avez pas de compte ? <a href="signup.html"> créer un compte</a></p>
                
            </form>
    </div>
</body>
</html>
