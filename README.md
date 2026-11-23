# Web-Development-Project
INDIAN FLAG PROJECT

style.css for flag

h1{
    font-size: 28px;
    margin-bottom: 20px;
    color: rgba(13, 6, 0, 0.948);
}
**---**

body{
    background-color: aliceblue ;
    display:flex;
    /* align-items:center;
    justify-content: center; */

}
div{
    /* align-items:center;
    justify-content: center; */
    /* display:flex; */
    /* text-align: center; */
    height:100px;
    width:600px;
    font-size: xx-large;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

#box1{
    background-color: orange;
    text-align:center;
    /* border-style:solid; */
    /* border-width: 5px;
    border-radius : 10px; */
    
}

#box2{
    background-color:white;
     display: flex;
    justify-content: center;
    align-items: center;
}
#box3{
    background-color:rgb(43, 230, 43);
    text-align:center;
    /* border-style:solid; */
    /* border-width: 5px;
    border-radius : 10px */
}

#chakra {
    width: 80px;
    height: 80px;
    border: 3px solid navy;
    border-radius: 50%;
    position: relative;
    box-sizing: border-box;
    overflow: hidden;
}

.line {
    width: 2px;
    height: 38px;
    background-color: navy;
    position: absolute;
    left: 50%;
    top: 50%;
    transform-origin: top center;
}

.line:nth-child(1)  { transform: rotate(0deg); }
.line:nth-child(2)  { transform: rotate(30deg); }
.line:nth-child(3)  { transform: rotate(60deg); }
.line:nth-child(4)  { transform: rotate(90deg); }
.line:nth-child(5)  { transform: rotate(120deg); }
.line:nth-child(6)  { transform: rotate(150deg); }
.line:nth-child(7)  { transform: rotate(180deg); }
.line:nth-child(8)  { transform: rotate(210deg); }
.line:nth-child(9)  { transform: rotate(240deg); }
.line:nth-child(10) { transform: rotate(270deg); }
.line:nth-child(11) { transform: rotate(300deg); }
.line:nth-child(12) { transform: rotate(330deg); }
