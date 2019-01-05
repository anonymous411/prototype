# prototype

<html>
  <head><meta charset="utf-8"/><title>title</title></head>
<body>
    <svg width="300" height="200" xmlns="http://www.w3.org/2000/svg">
     <g>
      <title>Layer 1</title>
      <g id="svg_8">
       <rect x="-1" y="-1" width="200" height="300" id="canvas_background" fill="#fff"/>
       <g transform="translate(10.8911, -41.5841) translate(-11.8812, 42.5742) translate(-47.5247, 34.6534) translate(82, 66)" id="canvasGrid" display="none">
        <rect id="svg_3" width="100%" height="100%" x="0" y="0" stroke-width="0" fill="url(#gridpattern)"/>
       </g>
      </g>
    </g>
    <g id="Group">
<!--Home Screen-->
      <g id="Home_Screen" onclick="callUser_Input()">
      <rect id="Welcomee" height="201" width="302" y="-0.059891" x="-2.490097" stroke-width="1.5" stroke="#000" fill="#fff"/>
      <text fill="#000000" stroke="#000" stroke-width="0" stroke-opacity="null" fill-opacity="null" x="128.276304" y="50.105899" id="svg_4" font-size="5" font-family="Helvetica, Arial, sans-serif" text-anchor="start" xml:space="preserve" transform="matrix(3.59869, 0, 0, 2.67071, -446.928, -101.94)">Welcome to the Unit Converter</text>
      <text transform="matrix(2, 0, 0, 6, 264, -350)" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="10" id="svg_19" y="77" x="-90" stroke-width="0" stroke="#000" fill="#000000">click to begin</text>
      <text transform="matrix(2.08632, 0, 0, 3.08563, -241.336, -362.433)" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="5" id="svg_21" y="170" x="160" fill-opacity="null" stroke-opacity="null" stroke-width="0" stroke="#000" fill="#000000">By Graceus Schexnayder</text>
      </g>
<!--User_Input-->
      <g id="User_Input">
      <rect id="Homee" height="200.989797" width="298.019354" y="-1.039268" x="301.485147" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#00FFFF"/>

      <text transform="matrix(2.91139, 0, 0, 3.83977, -396.38, -211.185)" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="8" id="svg_24" y="80" x="245" stroke-opacity="null" stroke-width="0" stroke="#000" fill="#000000">Choose Your Conversion</text>
      <text transform="rotate(-0.0917446, 368.605, 167.766) matrix(1.57039, 0, 0, 1.74345, -204.946, -101.271)" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="10" id="Path_One" y="156.998778" x="344.138914" fill-opacity="null" stroke-width="0" stroke="#ffffff" fill="#000000" onclick="callKilom()">km to mi</text>
      <text style="cursor: move;" transform="rotate(-0.0917446, 453.317, 167.767) matrix(1.57039, 0, 0, 1.74345, -204.946, -101.271)" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="10" id="Path_Two" y="156.998778" x="398.360086" fill-opacity="null" stroke-width="0" stroke="#ffffff" fill="#000000" onclick="callMiles()">mi to km</text>
      <text transform="rotate(-0.0917446, 547.053, 167.767) matrix(1.57039, 0, 0, 1.74345, -204.946, -101.271)" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="10" id="Path_Three" y="156.998778" x="454.171461" fill-opacity="null" stroke-width="0" stroke="#ffffff" fill="#000000" onclick="callLogs()">Logs</text>
      </g>
      
      <g id="km_to_mi" onclick="callHome()">
      <rect id="Choose" height="203.999997" width="304.477608" y="200" x="300" stroke-opacity="null" stroke-width="1.5" stroke="#fff" fill="#ffff"/>
      <text fill="#000000" stroke="#000" stroke-width="0" stroke-opacity="null" fill-opacity="null" x="191.470922" y="126.281654" id="svg_5" font-size="8" font-family="Helvetica, Arial, sans-serif" text-anchor="start" xml:space="preserve" transform="matrix(4.00671, 0, 0, 2.67071, -456.072, -101.94)">Kilometres to Miles</text>

          <g id="boxes_with_info">
            <rect id="svg_2" height="38.181818" width="74.545455" y="280.795455" x="339.090909" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#3f007f"/>
            <rect id="svg_3" height="38.181818" width="74.545455" y="280.795455" x="482.727266" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#3f007f"/>
            <rect id="svg_4" height="22.471652" width="56.17913" y="288.131006" x="349.434187" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#d9bbf9"/>
            <rect id="svg_6" height="22.471652" width="56.17913" y="288.131006" x="492.129179" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#d9bbf9"/>
            <text style="cursor: move;" stroke="#000" transform="matrix(0.37285950779914856,0,0,0.37285950779914856,227.59320424776524,173.2965563214384) " xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="24" id="svg_7" y="346.457982" x="335.79639" stroke-opacity="null" stroke-width="0" fill="#ffffff">ïnsert value"</text>

  <path stroke="#000" id="svg_1" d="m431.60948,300.330895c0.035484,-3.908191 -0.022705,-7.821605 0.291801,-11.722923c7.727997,1.283363 15.364848,3.383261 22.962622,5.271682c0.407881,-1.916344 0.215902,-3.505973 0.570291,-5.277767c4.881128,3.728342 9.718242,7.509777 14.357111,11.47128c-4.450545,4.493709 -9.555481,8.396186 -14.56716,12.392363c-0.162289,-1.860961 -0.324608,-3.721909 -0.4869,-5.582871c-7.386477,1.800394 -15.197923,3.661826 -22.632157,5.307731c-0.505564,-3.797858 -0.490704,-7.933837 -0.495608,-11.859496z" stroke-width="1.5" fill="#cccc2a"/>
          </g>
      </g>
      
<!--mi to km-->
      <g id="mi_to_km" onclick="callHome()">
      <rect id="redRectangle" height="203.999995" width="302.999997" y="199.940114" x="-2.490094" stroke-width="1.5" stroke="#fff" fill="#ffff"/>
      <text fill="#000000" stroke="#ffffff" stroke-width="0" fill-opacity="null" x="125" y="126.86451" id="svg_6" font-size="8" font-family="Helvetica, Arial, sans-serif" text-anchor="start" xml:space="preserve" transform="matrix(4.3101, 0, 0, 2.67071, -536.698, -101.94)">Miles to Kilometres</text>
<path stroke="#000" id="svg_1" d="m139.477998,311.566721c0.035484,-3.908191 -0.022705,-7.821605 0.291801,-11.722923c7.727997,1.283363 15.364848,3.383261 22.962622,5.271682c0.407881,-1.916344 0.215902,-3.505973 0.570291,-5.277767c4.881128,3.728342 9.718242,7.509777 14.357111,11.47128c-4.450545,4.493709 -9.555481,8.396186 -14.56716,12.392363c-0.162289,-1.860961 -0.324608,-3.721909 -0.4869,-5.582871c-7.386477,1.800394 -15.197923,3.661826 -22.632157,5.307731c-0.505564,-3.797858 -0.490704,-7.933837 -0.495608,-11.859496z" stroke-width="1.5" fill="#cccc2a"/>

<rect id="svg_2" height="38.181818" width="74.545455" y="292.03128" x="46.959428" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#3f007f"/>
<rect id="svg_3" height="38.181818" width="74.545455" y="292.03128" x="190.595784" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#3f007f"/>
<rect id="svg_4" height="22.471652" width="56.17913" y="299.366831" x="57.302705" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#d9bbf9"/>
<rect id="svg_6" height="22.471652" width="56.17913" y="299.366831" x="199.997697" stroke-opacity="null" stroke-width="1.5" stroke="#000" fill="#d9bbf9"/>
<text stroke="#000" transform="matrix(0.37285950779914856,0,0,0.37285950779914856,227.59320424776524,173.2965563214384) " xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="24" id="svg_7" y="376.592189" x="-447.693036" stroke-opacity="null" stroke-width="0" fill="#ffffff">ïnsert value"</text>
     </g>

      <text transform="translate(10.8911, -41.5841) matrix(20.4796, 0, 0, 4.56642, -2696.58, -546.342)" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="10" id="svg_20" y="160.950012" x="138.5" fill-opacity="null" stroke-opacity="null" stroke-width="0" stroke="#000" fill="#000000"/>
    </g>
    </svg>
    
    <script>

    function callUser_Input(){
      document.getElementById('Group').setAttribute('transform', 'translate(-300,0)');
    }

    function callKilom(){
      document.getElementById('Group').setAttribute('transform', 'translate(-300,-200)');
    }

    function callMiles(){
      document.getElementById('Group').setAttribute('transform', 'translate(0,-200)');
    }


    function callHome(){
      document.getElementById('Group').setAttribute('transform', 'translate(0,0)');
    }
    </script>
</body>
</html>
