respostas da comparação



@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap'); ->importa a fonte do google




body {
    font-family: "Quicksand", sans-serif;
    font-optical-sizing: auto;
    font-weight:400;
    font-style: normal;
    background-color: #f4f4f4;

    background-image: url('header3');
    background-repeat: no-repeat; 
    background-size: cover;      
    background-position: center; 
    background-attachment: fixed; 
    
    color: #640d31; 
    
    
}

*{
    cursor: url('https://cdn.cursors-4u.net/css-previews/shiny-magenta-spinning-heart-a44fb078-css.webp') 0 0, auto !important;
}



#topo-principal {
    background-color: #ffeb93;
    color: rgb(76, 90, 138);
    padding: 20px;
    text-align: center;
}


h1, h2{
    color: #2c3e50;
}


nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: rgb(76, 90, 138);
    text-decoration: none;
}


nav ul li:nth-child(2) {
    text-transform: uppercase;
}


.lista-animais {
    display: flex;
    gap: 20px;
    justify-content: center;
    margin-top: 40px;
}


.card {
    background-color: white;
    border-radius: 10px;
    width: 200px;
    padding: 15px;
    text-align: center;

   
    border: 2px dashed #dbb855;
}


.card.destaque {
    border: 3px solid rgb(67, 122, 185);
    transform: scale(1.05);
}


p span {
    font-weight: bold;
    color: blue;
}


button {
    background-color: #ff1493;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 8px;
    margin-top: 10px;
}


button:hover {
    background-color: #27ae60;
    cursor: pointer;
}