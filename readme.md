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


