<template>
<nav class="navbar navbar-expand-lg navbar-primary fixed-top py-3 " data-navbar-on-scroll="data-navbar-on-scroll">
    <div class="container"><a class="navbar-brand d-flex align-items-center fw-bold fs-2" href="index.html">
            <div class="text-warning">TRAMO</div>
            <div class="text-1000">S.A.S</div>
        </a>
        <button class="navbar-toggler collapsed" type="button" data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
            aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
        <div class="collapse navbar-collapse border-top border-lg-0 mt-4 mt-lg-0" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto pt-2 pt-lg-0">
                <li class="nav-item"><a class="nav-link fw-medium active" aria-current="page" href="#home">Inicio</a>
                </li>
                <li class="nav-item"><a class="nav-link fw-medium active" aria-current="page" href="./about.html">Acerca
                        de
                        nosotros</a></li>
                <li class="nav-item"><a class="nav-link fw-medium" href="#pricing">Testimonios</a>
                </li>
                <li class="nav-item"><a class="nav-link fw-medium" href="./contactos.html">Contactos</a>
                </li>

            </ul>
            <form class="ps-lg-5">
                <button class="btn btn-lg btn-primary rounded-pill order-0" type="submit">Inicio Sesion</button>
            </form>
        </div>
    </div>
</nav>
</template>
<script>
export default {
    name: 'NavComponent',
    
}
</script>