body{
    font-family:'Poppins',sans-serif;
    margin:0;
    background:#111111;
    color:white;
}

header{
    background:linear-gradient(90deg,#ff7b00,#ffb700);
    text-align:center;
    padding:50px 20px;
}

.logo{
    width:120px;
    border-radius:20px;
}

header h1{
    margin-top:15px;
    font-size:3rem;
}

header p{
    font-size:1.2rem;
}

nav{
    background:black;
    padding:15px;
    text-align:center;
}

nav a{
    color:#ffb700;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
    transition:0.3s;
}

nav a:hover{
    color:white;
}

.hero{
    height:80vh;
    background:url('./images/escuela1.jpg') center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero-text{
    background:rgba(0,0,0,0.7);
    padding:40px;
    border-radius:20px;
    width:80%;
}

.hero-text h2{
    color:#ffb700;
    font-size:3rem;
}

.container{
    max-width:1100px;
    margin:auto;
    padding:40px 20px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1c1c1c;
    padding:25px;
    border-radius:20px;
    border:2px solid #ff7b00;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    color:#ffb700;
}

.card a{
    color:white;
    text-decoration:none;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    margin-top:30px;
}

.gallery img{
    width:100%;
    border-radius:15px;
    height:250px;
    object-fit:cover;
}

footer{
    background:black;
    text-align:center;
    padding:20px;
    color:#aaa;
    margin-top:50px;
}
