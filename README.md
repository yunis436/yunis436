
<html>
    <body>
        <h1>Hai Masku ganteng bontot kesayangan</h1>
        <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fhdsmileys.com%2Fwp-content%2Fuploads%2F2017%2F10%2Fcony-saying-sorry-by-holding-browns-leg.gif&f=1&nofb=1">
        <h1>Maafiin aku ya sayang?</h1>
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
