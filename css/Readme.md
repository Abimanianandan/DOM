
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: pink; 
    font-family: sans-serif;
} 
h1{
    display: flex;
    justify-content: center;
    color: red;
}
p{
    
        display: flex;
        justify-content: center;
        color: blueviolet;
    
}
#container{
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
#calculator{
   display: grid;
   grid-template-columns: repeat(4,68px);
   box-shadow: inset 5px 5px 12px #ffffff,
   5px 5px 12px rgba(0,0,0,.16);
   border-radius: 30px;
   padding: 15px;
   background: #ffffff;
}
input{
    grid-column: span 4;
    height: 70px;
    width: 260px;
    background-color: #ecf0f3;
    box-shadow: inset -5px -5px 12px rgba(0, 0, 0, .16);
    
    border-radius: 30px;
    color: rgb(70, 70, 70);
    font-size: 50px;
    text-align: end;
    margin: auto;
    margin-top: 40px;
    margin-bottom: 30px;
    padding: 20px;    
}

button{
    border: none;
    width: 48px;
    height: 48px;
    margin: 8px;
    border-radius: 50%;
    background-color: #ecf0f3;
    color: black;
    font-size: 16px;
    box-shadow: -5px -5px 12px #ffffff,
                 5px 5px 12px rgba(0,0,0,16);
    cursor: pointer;
}

#equal{
    background-color: #ecf0f3;
    width: 115px;
    border-radius: 40px;
    box-shadow: -5px -5px 12px #ffffff,
             5px 5px 12px rgba(0,0,0,16);
}
