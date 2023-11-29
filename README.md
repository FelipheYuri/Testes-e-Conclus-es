 <!DOCTYPE html>
 <html lang="pt-BR">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <link rel="stylesheet" href="site.css">
            <script src="site.js"> </script>
            <title>
                Site aleatorio
            </title>
          <link href="/interrogation/favicon.ico" rel="icon" type="image/x-icon">
          <style>
            body{
    text-align: center;
    border: 2px solid black;
    border-radius: 10px;
    background-color: hsla(0, 0%, 0%, 0.15)
}


.p1{
    color:blue;
    font-size: 20px;
    text-align: center;
    border: 1px solid black;
}
.img1, .img2{
    height: 150px;
    width: 300px;
    border: 1px solid black;
    padding: 15px;
    
}
.a1{
  			 color: green;		
}
.ol1, .ul1{
    color: blueviolet;
    font-size: 20px;
    font-family: serif;
}
table, caption, th, td{
    border: 1px dotted black;
    border-collapse: collapse;
    border-radius: 5px;
}
.div1{
    background-color: greenyellow;
    border: 2px solid green;
    border-radius: 10px;
}
.div2{
    background-color: aqua;
    border: 2px solid blue
}
.div3{
    padding: 10px;
    background-color: aliceblue;
    border-collapse: collapse;
}
.p2{
    font-size: 20px;
}
iframe{
    border: 2px dashed
}
.img3, .img4{
  height: 40px;
  width: 40px;
  
}
          </style>
        </head>
            <body>
            <script>
            let x = 0;
function botao1() {
    x += 1;
    document.getElementById("bt1").innerText = `+${x} Wood`;
}
function botao2() { 
document.getElementById("bt2").innerHTML = "Gomu Gomu No Pistol!";
}
{
  window.alert('Olá, seja bem-vindo(a) ao meu site!')
}
            </script>
                <p class="p1"> Olá, mundo! Mas em HTML</p>
                <a class="a1"href="https://www.youtube.com/@yygames304" target="_blank">Link do meu canal: </a>
                <hr>
                <div class="div1">
                    <img class="img1" title="Terraria" src="https://logos-world.net/wp-content/uploads/2023/02/Terraria-Logo-2011.png"></a>
                    <ol class="ol1"> 
                
                       <li> Instalar o jogo (cerca de 650mb)</li>
                       <li> Descompactar o arquivo</li>
                       <li> Abrir o arquivo executável</li>
                       <li> Jogar e se divertir</li>
                </ol>
              
                <button type="button" onclick="botao1()"> Terraria </button>
                <p id="bt1"> None </p> <img class="img3" title="Madeira"src="/storage/emulated/0/Download/wood.png"
                </div>
                <div class="div2">
                <img class="img2"title="One Piece"src="https://1000logos.net/wp-content/uploads/2022/08/One-Piece-Logo.png">
                <ul class="ul1">
                  <li> Anime muito bom</li>
                  <li> Lore muito massa</li>
                  <li> +1000 de episódios</li>
                  <li> Ainda tem versão live action</li>
                </ul>
                  <button type="button" onclick="botao2()"> One Piece</button>
                  <p id="bt2"> Luffy </p> <img class="img4" title="Luffy"src="https://static.wikia.nocookie.net/fiction-battlefield/images/6/6a/Macaco_luffy.png/revision/latest?cb=20190711015626&path-prefix=pt-br">
                </div>
               <div class="div3">
                <table style="width: 100%">
                  <caption> <u>Tabela Aleatória</u></caption>
                  <tr>
                    <th> Olá</th>
                    <th> Carro</th>
                    <th> De</th>
                    <th> Pular</th>
                  </tr>
                  <tr>
                    <td> Inter.</td>
                    <td> Subs.</td>
                    <td> Prep.</td>
                    <td> Verbo</td>
                  </tr>
                  <tr>
                    <td> €</td>
                    <td> £</td>
                    <td> ¥</td>
                    <td> $</td>
                  </tr>
                </table>
                 <hr>
                  <iframe src="site1ex1.html" name="iframe1">
                  </iframe>
                  <p class="p2"> 
                    <a href="site1ex1.html" target="iframe1">
                      Myself:
                    </a> <br>
                    <a href="site1.html" target="iframe1">
                      Yourself:
                    </a>
                  </p>
                  
                  
                  
                </div>
                </body>
 </html>

