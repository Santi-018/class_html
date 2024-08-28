# class_html
classes_two

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Libros</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        form {
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
    </style>
</head>
<body>
    <form>
        <h1>Libros</h1>
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre" required><br><br>
        
        <label for="id">ID:</label><br>
        <input type="text" id="id" name="id" required><br><br>
        
        <input type="search" id="buscar" name="buscar" placeholder="Buscar..." required><br><br>
        
        <input type="submit" value="Enviar">
    </form>
</body>
</html>

