# Documentación Detallada del Navbar

## 1. Estructura del Navbar

```html
<div class="header">
    <div class="container-fluid">
        <div class="row d_flex">

## 2. Sección del Logotipo

```html
    <div class="col-md-2 col-sm-3 col logo_section">
        <div class="full">
            <div class="center-desk">
                <div class="logo">
                    <a href="index.html"><img src="images/logo.png" alt="#" /></a>
                </div>
            </div>
        </div>
    </div>

## 3. Sección de Navegación

```html
    <div class="col-md-8 col-sm-12">
        <nav class="navigation navbar navbar-expand-md navbar-dark">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample04" aria-controls="navbarsExample04" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarsExample04">
                <ul class="navbar-nav mr-auto">
                    <!-- Enlaces de navegación -->
                </ul>
            </div>
        </nav>
    </div>

## 4. Enlaces de Navegación

```html
<ul class="navbar-nav mr-auto">
    <li class="nav-item active">
        <a class="nav-link" href="index.html">Inicio</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" href="about.html">Acerca de</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" href="skating.html">Proyectos</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" href="shop.html">Cómo usar</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" href="contact.html">Contáctenos</a>
    </li>
</ul>

