# <!DOCTYPE html>
<html lang="es">
<head>
    <title>Framework de Estudio</title>
    <style>
        body { background: #121212; color: white; font-family: sans-serif; display: flex; justify-content: center; align-items: center; height: 100vh; }
        button { padding: 20px; font-size: 1.2rem; cursor: pointer; background: #333; color: #0f0; border: 1px solid #0f0; border-radius: 8px; }
        button:hover { background: #0f0; color: #000; }
    </style>
</head>
<body>
    <button onclick="abrirTodo()">EJECUTAR ENTORNO DE ESTUDIO</button>

    <script>
        function abrirTodo() {
            const urls = [
                'https://drive.google.com',
                'https://campus2026.unahur.edu.ar/my/courses.php',
                'https://gemini.google.com',
                'https://mail.google.com'
            ];
            urls.forEach(url => window.open(url, '_blank'));
        }
    </script>
</body>
</html>
