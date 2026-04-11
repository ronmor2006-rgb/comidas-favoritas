/* Configuración General */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #2c3e50;
    color: white;
    padding: 2rem;
    text-align: center;
}

.container {
    max-width: 900px;
    margin: 2rem auto;
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

/* Imagen Responsive */
.main-img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
    margin-bottom: 2rem;
}

.content h2 {
    margin-bottom: 1rem;
    color: #e67e22;
}

/* Lista Ordenada */
.food-list {
    margin: 1.5rem 0;
    padding-left: 1.5rem;
}

.food-list li {
    margin-bottom: 1rem;
    font-size: 1.1rem;
}

/* Botón con efecto Hover */
.btn-action {
    background-color: #e67e22;
    color: white;
    border: none;
    padding: 12px 24px;
    font-size: 1rem;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease; /* Transición suave */
    display: block;
    width: fit-content;
}

.btn-action:hover {
    background-color: #d35400; /* Cambio de color al pasar el mouse */
}

/* Diseño Responsive para móviles */
@media (max-width: 600px) {
    .container {
        margin: 1rem;
        padding: 1rem;
    }

    header h1 {
        font-size: 1.5rem;
    }

    .btn-action {
        width: 100%;
        text-align: center;
    }
}

footer {
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
    color: #777;
}
