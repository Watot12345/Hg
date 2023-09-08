div {
    width: 340px;
    height: 490px;
    background-color: red;
     animation-iteration-count: infinite;  
    animation-name: colorchange;
    animation-duration: 2s;
    -webkit-animation-name: colorchange;
    -webkit-animation-duration: 2s;
    -ms-animation-name: colorchange;
    -ms-animation-duration: 2s;
}
}
@keyframes colorchange {
    0% {background-color: red; }
    12% {background-color: voilet; }
    25% {background-color: pink; }
    50% {background-color: green; }
    62% {background-color: black; }
     75% {background-color: yellow; }  
    100% {background-color: blue; }
}
@-webkit-keyframes colorchange {
    0% {background-color: red; }
    50% {background-color: green; }
    100% {background-color: blue; }
}
@-ms-keyframes colorchange {
    0% {background-color: red; }
    50% {background-color: green; }
    100% {background-color: blue; }
}
