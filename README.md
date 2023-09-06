<!DOCTYPE html>
<html>
<head>
    <title>Página com Barra de Navegação e Campos de Login</title>
    <style>
        /* Estilo para os links de navegação */
        td.nav-links a {
            margin-right: 5cm; /* Define a margem de 5 centímetros à direita dos links */
        }
        /* Estilo para os botões de login e signup */
        td.nav-links button {
            margin-left: 10px; /* Define a margem de 10 pixels à esquerda dos botões */
        }
    </style>
</head>
<body>
    <table width="100%" cellspacing="0">
        <tr>
            <td>
                <table width="100%" cellspacing="0" cellpadding="10">
                    <tr>
                        <td>
                            <h1>Logo</h1>
                        </td>
                        <td class="nav-links" align="right">
                            <a href="#">Home</a>
                            <a href="#">About</a>
                            <a href="#">Contact</a>
                            <button>Login</button>
                            <button>Sign Up</button>
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>

    <div style="float: left; width: 50%;">
        <label for="campo1">nome:</label>
        <input type="text" id="campo1" name="campo1"><br><br>

        <label for="campo2">email:</label>
        <input type="text" id="campo2" name="campo2"><br><br>

        <label for="campo3">subject:</label>
        <input type="text" id="campo3" name="campo3"><br><br>

        <label for="campo4">message:</label>
        <input type="text" id="campo4" name="campo4"><br><br>
        
        <button>Send Message</button>
    </div>
</body>
</html>
