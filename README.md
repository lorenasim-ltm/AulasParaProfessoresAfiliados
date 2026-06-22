<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Materiais Educativos Prontos - Alinhados à BNCC 2026</title>
    <style>
        /* --- Configurações Gerais & Reset --- */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        body {
            margin: 0;
            padding: 0;
            font-family: 'Montserrat', 'Helvetica Neue', Arial, sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            line-height: 1.6;
        }
        h1, h2, h3, h4 {
            margin: 0;
            font-weight: 700;
        }
        p {
            margin: 0 0 15px 0;
        }
        a {
            text-decoration: none;
        }

        /* --- Cores e Variáveis --- */
        :root {
            --primary-color: #1b4d61; 
            --accent-color: #f97316;  
            --accent-hover: #ea580c;
            --text-dark: #0f172a;
            --text-muted: #64748b;
            --bg-light: #ffffff;
            --bg-neutral: #f1f5f9;
            --success: #16a34a;
        }

        /* --- Barra de Topo --- */
        .top-bar {
            background-color: var(--text-dark);
            color: #ffffff;
            text-align: center;
            padding: 10px 15px;
            font-size: 11pt;
            font-weight: 600;
            letter-spacing: 0.5px;
        }

        /* --- Cabeçalho --- */
        .main-header {
            background-color: var(--bg-light);
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            padding: 10px 5%;
            display: table;
            width: 100%;
        }
        .header-container {
            display: table-cell;
            vertical-align: middle;
        }
        .logo-img {
            max-height: 55px;
            float: left;
            display: block;
        }
        .nav-menu {
            float: right;
            margin: 15px 0 0 0;
            padding: 0;
            list-style: none;
        }
        .nav-menu li {
            display: inline-block;
            margin-left: 20px;
        }
        .nav-menu a {
            color: var(--text-dark);
            font-weight: 600;
            font-size: 11pt;
        }
        .nav-menu a
