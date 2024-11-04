# 1. Visme

Visme es una plataforma de diseño en línea que permite a los usuarios crear presentaciones, infografías, documentos y gráficos.

[https://www.visme.co/](https://www.visme.co/)

## 1.1. ¿Cómo usarla?
<button onclick="toggleFullScreen()" style="margin-top: 10px; padding: 10px; background-color: #007bff; color: white; border: none; border-radius: 5px; cursor: pointer;">Pantalla Completa</button>


<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe id="slideshow-iframe" src="https://docs.google.com/presentation/d/e/2PACX-1vQL5zGmAK5ahYBT-7SG0bwiW3U8owVPugrZL24q5DAq4LcLt6lYjG27t3zhMNvHWWmZmoC7t64phKt2/embed?start=true&loop=true&delayms=600000000" frameborder="0" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

<script>
function toggleFullScreen() {
  var iframe = document.getElementById('slideshow-iframe');
  if (!document.fullscreenElement) {
    if (iframe.requestFullscreen) {
      iframe.requestFullscreen();
    } else if (iframe.mozRequestFullScreen) { // Firefox
      iframe.mozRequestFullScreen();
    } else if (iframe.webkitRequestFullscreen) { // Chrome, Safari and Opera
      iframe.webkitRequestFullscreen();
    } else if (iframe.msRequestFullscreen) { // IE/Edge
      iframe.msRequestFullscreen();
    }
  } else {
    if (document.exitFullscreen) {
      document.exitFullscreen();
    } else if (document.mozCancelFullScreen) { // Firefox
      document.mozCancelFullScreen();
    } else if (document.webkitExitFullscreen) { // Chrome, Safari and Opera
      document.webkitExitFullscreen();
    } else if (document.msExitFullscreen) { // IE/Edge
      document.msExitFullscreen();
    }
  }
}
</script>
