<h2>1. membuat dokumen html</h2>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <header>
            <h1>CSS Internal dan <i>Inline CSS</i></h1>
        </header>
        <nav>
            <a href="lab2_css_dasar.html"></a>
            <a href="lab2_css_eksternal.html"></a>
            <a href="lab1_tag_dasar.html"></a>
        </nav>
        <!-- CSS ID Selector-->
        <div id="intro">
            <h1> Hello world</h1>
            <p> kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrogaman
                web</b> di <i>universitas pelita bangsa</i>. Pelajaran pertama yang kami dapat 
                adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar hatml                 dan css</p>
        <!-- Css class selector-->
              <a class="button btn-primary" href="#intro">Informasi selengkapnya</a>
         </div>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/6f53216c-2af0-43d4-a5b4-0b27ea941e8b)

<h2>2. mendeklarasika css internal</h2>

    <style>
        body {
            font-family: 'opem sans', sans-serif;
        }
        header {
            min-height: 80px;
            border-bottom: 1px solid #77CCEF;
        }
        h1 {
            font-size: 24px;
            color: #0F189F;
            text-align: center;
            padding: 20px 10px;
        }
        h1 i {
            color: #6d6a6b;
        }
    </style>

![image](https://github.com/user-attachments/assets/e40028ac-f027-4f1a-b073-b308aad6f44d)

<h2>3. menambahkan inline css</h2>

    <p style="text-align: center; color: #ccd8e4">

![image](https://github.com/user-attachments/assets/1bf48b76-b460-4aef-9087-e84f28532a67)

<h2>4. membuat css eksternal</h2>

    nav {
      background-color: #20A759;
      color: #FFF;
      padding: 10px;
    }
    nav a {
      color: #FFF;
      text-decoration: none;
      padding: 10px 20px;
    }
    nav .active,
    nav a:hover{
    background: #0B6B3A;
    }
Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head> 

    <link rel="stylesheet" href="style.css" type="text/css">

![image](https://github.com/user-attachments/assets/0171888a-fac1-4d36-87e5-d41528da3185)


<h2>5. menambahkan css selector</h2>

    /* ID selector */
    #intro { 
      background: #418fb1;     
      border: 1px solid #099249;     
      min-height: 100px;     
      padding: 10px; 
    } 
    #intro h1 {     
      text-align: left;     
      border: 0;     
      color: #fff; 
    } 

    /* Class Selector */ 
    .button { 
      padding: 15px 20px;     
      background: #bebcbd;    
      color: #fff;     
      display: inline-block;     
      margin: 10px; 
      text-decoration: none; 
    } 
    .btn-primary { 
      background: #E42A42; 
    } 



![image](https://github.com/user-attachments/assets/7cc3d453-62a3-40a6-b9fd-5f9fbe4818ed)

