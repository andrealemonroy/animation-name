<div>
<h1>Tipos de animation-name</h1>
</div>
<div>
<h3>FadeIn</h3>
<br/>
.fadeIn {
    -webkit-animation-name: fadeIn;
    animation-name: fadeIn;
    -webkit-animation-duration: 1s;
    animation-duration: 1s;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
}
@-webkit-keyframes fadeIn {
    0% {opacity: 0;}
    100% {opacity: 1;}
}
@keyframes fadeIn {
    0% {opacity: 0;}
    100% {opacity: 1;}
}
</br>
<h3>FadeOut</h3>
<br/>
.fadeOut {
  -webkit-animation-name: fadeOut;
  animation-name: fadeOut;
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
}
@-webkit-keyframes fadeOut {
  0% {opacity: 1;}
  100% {opacity: 0;}
}
@keyframes fadeOut {
  0% {opacity: 1;}
  100% {opacity: 0;}
}
</div>
