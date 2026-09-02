
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Informática Básica | Cândido Machive</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f4f6f9;
            color: #333;
        }

        /* MENU */
        header {
            background: #0d47a1;
            color: white;
            padding: 15px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 18px;
            font-size: 15px;
        }

        nav a:hover {
            color: #90caf9;
        }

        /* CAPA */
        .hero {
            background: linear-gradient(135deg, #0d47a1, #1976d2);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        .hero h1 {
            font-size: 40px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 18px;
            max-width: 700px;
            margin: auto;
            line-height: 1.6;
        }

        .btn {
            display: inline-block;
            margin-top: 25px;
            padding: 14px 28px;
            background: white;
            color: #0d47a1;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
        }

        .btn:hover {
            background: #e3f2fd;
        }

        /* SECÇÕES */
        section {
            padding: 60px 8%;
        }

        .titulo {
            text-align: center;
            margin-bottom: 40px;
            color: #0d47a1;
            font-size: 30px;
        }

        /* CARTÕES */
        .modulos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            text-align: center;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        .card h3 {
            margin: 15px 0;
            color: #0d47a1;
        }

        .card p {
            line-height: 1.6;
            color: #666;
        }

        .icone {
            font-size: 45px;
        }

        /* SOBRE */
        .sobre {
            background: white;
            text-align: center;
        }

        .sobre p {
            max-width: 800px;
            margin: auto;
            line-height: 1.8;
            font-size: 17px;
        }

        /* FORMADOR */
        .formador {
            background: #e3f2fd;
            text-align: center;
        }

        .formador h3 {
            color: #0d47a1;
            font-size: 24px;
            margin-bottom: 15px;
        }

        /* CONTACTO */
        .contacto {
            text-align: center;
            background: white;
        }

        .contacto p {
            margin: 10px;
            font-size: 17px;
        }

        /* RODAPÉ */
        footer {
            background: #0d47a1;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* TELEMÓVEL */
        @media(max-width: 600px) {

            header {
                flex-direction: column;
                text-align: center;
            }

            nav {
                margin-top: 15px;
            }

            nav a {
                margin: 8px;
                display: inline-block;
            }

            .hero h1 {
                font-size: 28px;
            }

            .hero {
                padding: 60px 15px;
            }

        }

    </style>
</head>

<body>

<header>

    <div class="logo">
        💻 Informática Básica
    </div>

    <nav>
        <a href="#inicio">Início</a>
        <a href="#modulos">Módulos</a>
        <a href="#sobre">Sobre</a>
        <a href="#contacto">Contacto</a>
    </nav>

</header>


<!-- CAPA -->

<section class="hero" id="inicio">

    <h1>Curso de Informática Básica</h1>

    <p>
        Plataforma oficial de aprendizagem criada para ajudar os alunos
        a desenvolver competências fundamentais no uso do computador
        e das tecnologias digitais.
    </p>

    <a href="#modulos" class="btn">
        Começar a Estudar
    </a>

</section>


<!-- MÓDULOS -->

<section id="modulos">

    <h2 class="titulo">Módulos do Curso</h2>

    <div class="modulos">


        <div class="card">

            <div class="icone">💻</div>

            <h3>Módulo 1</h3>

            <p>
                Introdução à Informática,
                Hardware e Software.
            </p>

        </div>


        <div class="card">

            <div class="icone">🖥️</div>

            <h3>Módulo 2</h3>

            <p>
                Sistema Operativo Windows,
                ficheiros e pastas.
            </p>

        </div>


        <div class="card">

            <div class="icone">📝</div>

            <h3>Microsoft Word</h3>

            <p>
                Criar documentos,
                formatar textos e inserir imagens.
            </p>

        </div>


        <div class="card">

            <div class="icone">📊</div>

            <h3>Microsoft Excel</h3>

            <p>
                Tabelas, fórmulas,
                cálculos e gráficos.
            </p>

        </div>


        <div class="card">

            <div class="icone">🎞️</div>

            <h3>PowerPoint</h3>

            <p>
                Criar apresentações
                profissionais e educativas.
            </p>

        </div>


        <div class="card">

            <div class="icone">🌐</div>

            <h3>Internet</h3>

            <p>
                Navegação, pesquisas,
                e-mail e segurança digital.
            </p>

        </div>


        <div class="card">

            <div class="icone">📝</div>

            <h3>Exercícios</h3>

            <p>
                Atividades práticas
                para testar os conhecimentos.
            </p>

        </div>


        <div class="card">

            <div class="icone">🎓</div>

            <h3>Avaliação</h3>

            <p>
                Testes e avaliações
                dos conteúdos estudados.
            </p>

        </div>


    </div>

</section>


<!-- SOBRE -->

<section class="sobre" id="sobre">

    <h2 class="titulo">Sobre o Curso</h2>

    <p>
        Este curso de Informática Básica foi desenvolvido para proporcionar
        conhecimentos fundamentais sobre computadores, programas,
        internet e ferramentas digitais.
    </p>

    <br>

    <p>
        O objetivo é preparar os alunos para utilizarem a tecnologia
        com confiança tanto na vida pessoal como profissional.
    </p>

</section>


<!-- FORMADOR -->

<section class="formador">

    <h2 class="titulo">Formador</h2>

    <h3>Cândido Machive</h3>

    <p>
        Formador de Informática Básica e Tecnologias de Informação.
    </p>

</section>


<!-- CONTACTO -->

<section class="contacto" id="contacto">

    <h2 class="titulo">Contacto</h2>

    <p>📧 Email: seuemail@email.com</p>

    <p>📱 Telefone: +258 XXX XXX XXX</p>

</section>


<!-- RODAPÉ -->

<footer>

    <p>
        © 2026 Curso de Informática Básica |
        Cândido Machive
    </p>

    <p>
        Plataforma de aprendizagem online.
    </p>

</footer>

</body>
</html>
