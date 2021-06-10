<html>
    <body>
        <h1>Hai Guys</h1>
        <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2Foriginals%2Fda%2Faf%2Fc0%2Fdaafc09740dd5c9c232242ea89485fbf.gif&f=1&nofb=1">
        <h1>Yuk, kenalan sama aku?</h1>
        <button id='btn_mau' onclick='alert("I <3 U")'>Mau</button>&nbsp;
        <button id='btn_gamau' onclick='gamau(this)' style='position:absolute'>Gamau</button>
    </body>
    <script>
        function gamau(id){
            var mau = document.getElementById('btn_mau');
            var i = Math.floor(Math.random()*300)+1;
            var j = Math.floor(Math.random()*100)+mau.offsetTop;
            id.style.left = i+'px';
            id.style.top = j+'px';
        }
    </script>
</html>

