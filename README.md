<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Bonjour</title>
    <style>
        body {
            background-color: #64CDE8;
            font-family: 'Courier New', Courier, monospace;
            text-align: center;
            padding: 50px;
        }
        .btn {
            font-size: 25px;
            padding: 15px 30px;
            margin: 20px;
            background-color: white;
            color: black;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #e0e0e0;
        }
        .btn-blue {
            color: #0C19CF;
        }
    </style>
</head>
<body>
    <h1>Bonjour</h1>
    <button class="btn" onclick="openFuze()">Ouvre Youtube Fuze</button><br>
    <button class="btn" onclick="openKSPfr()">KSP FR</button><br>
   <button class="btn" onclick="openYoutubeHome()">Ouvrir Youtube Accueil</button><br>
    <button class="btn btn-blue" onclick="openGraven()">Ouvrir Youtube KSP1080p</button>
    <script>
        function openFuze() {
            window.open("https://www.youtube.com/@FuzeIII", "_blank");
        }
        function openKSPfr() {
            window.open("https://www.youtube.com/results?search_query=ksp+fr", "_blank");
        }
        function openYoutubeHome() {
            window.open("https://www.youtube.com/", "_blank");
        }
        function openGraven() {
            window.open("https://www.youtube.com/@theo_ksp5546", "_blank");
        }
    </script>
</body>
</html>
