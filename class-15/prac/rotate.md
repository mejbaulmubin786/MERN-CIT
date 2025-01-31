.left-rect {
width: 220px;
height: 380px;
background-color: #e5f5d0;
position: absolute;
bottom: 0;
z-index: 1;
animation: left-rect 5s infinite;
}

.vartical {
width: 250px;
height: 480px;
position: absolute;
top: 87px;
right: 80px;
background-color: #dee9ec;
z-index: 1;
}

.horizontal {
width: 585px;
height: 183px;
position: absolute;
right: 0;
bottom: 0;
background-color: #dee9ec;
z-index: 1;
}

@keyframes left-rect {
0% {
transform: rotate(0deg);
}
25% {
transform: rotate(90deg);
}
50% {
transform: rotate(180deg);
}
75% {
transform: rotate(270deg);
}
100% {
transform: rotate(0deg);
}
}
