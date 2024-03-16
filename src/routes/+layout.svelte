<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Кордюков Александр</a>
        <div class="nav-links">
            <a href="/about" class="link">Обо мне</a>
            <a href="/blog" class="link">блог</a>
            <a href="/project" class="link">Проекты</a>
            <a href="contact" class="link">Контаткы</a>
        </div>
    </div>
</nav>

<div class="container">
    <!--Проекты будут ниже-->
    <slot></slot>
</div>

<style>
    .container{
        max-width: 1400px;
        margin: 50px auto;
    }
</style>