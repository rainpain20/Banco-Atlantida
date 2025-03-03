<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Banco Atlántida - Simulación Educativa</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f5f5f5;
        }

        .header {
            background-color: #E30613; /* Rojo corporativo */
            color: white;
            padding: 1rem;
            text-align: center;
            border-bottom: 4px solid #002366; /* Detalle azul original */
        }

        .logo {
            max-width: 300px;
            margin: 0 auto;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo-simbolo {
            width: 40px;
            height: 40px;
            background-color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #E30613;
            font-weight: bold;
        }

        .main-content {
            max-width: 800px;
            margin: 2rem auto;
            padding: 2rem;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .login-form {
            max-width: 400px;
            margin: 0 auto;
        }

        .form-group {
            margin-bottom: 1rem;
        }

        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 0.5rem;
            margin-top: 0.3rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        .btn-login {
            background-color: #E30613; /* Rojo corporativo */
            color: white;
            padding: 0.7rem 2rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            transition: background-color 0.3s;
        }

        .btn-login:hover {
            background-color: #C20510; /* Rojo más oscuro al hover */
        }

        .security-message {
            text-align: center;
            margin-top: 1rem;
            color: #666;
            font-size: 0.9rem;
        }

        .footer {
            background-color: #002366; /* Azul original */
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .disclaimer {
            color: #ffcccc;
            font-size: 0.8rem;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="logo">
            <div class="logo-simbolo">BA</div>
            <h1>Banco Atlántida</h1>
        </div>
    </header>

    <main class="main-content">
        <h2>Bienvenido a Banca en Línea</h2>
        <form class="login-form" method="POST" action="/login">
            <div class="form-group">
                <label for="usuario">Usuario:</label>
                <input type="text" id="usuario" name="usuario" required>
            </div>

            <div class="form-group">
                <label for="password">Contraseña:</label>
                <input type="password" id="password" name="password" required>
            </div>

            <button type="submit" class="btn-login">Ingresar</button>
        </form>

        <div class="security-message">
            <p>ⓘ Recuerde nunca compartir sus credenciales de acceso</p>
            <p>Verifique siempre su correo electronico://</p>
        </div>
    </main>

    <footer class="footer">
        <p>Banco Atlántida S.A. - Todos los derechos reservados © 2024</p>
        <p class="disclaimer">Atención al cliente: +504 2216-5000 | Servicio las 24 horas</p>
        <nav>
            <a href="#" style="color: white;">Políticas de seguridad</a> | 
            <a href="#" style="color: white;">Términos y condiciones</a>
        </nav>
    </footer>
</body>
</html>
