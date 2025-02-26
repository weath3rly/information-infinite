<!DOCTYPE html>
<html>
<head>
    <title>Joshua Unraveled Lite</title>
    <style>
        body { background: #D2B48C; margin: 
0; display: flex; justify-content: center; 
align-items: center; height: 100vh; }
        #tree { width: 100px; height: 
200px; background: green; transition: all 
0.5s; }
        #tree.glow { background: blue; }
    </style>
</head>
<body>
    <div id="tree"></div>
    <script>
        const tree = 
document.getElementById('tree');
        tree.addEventListener('touchstart', 
() => {
            tree.classList.toggle('glow');
        });
    </script>
</body>
</html>