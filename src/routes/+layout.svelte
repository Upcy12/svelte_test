<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Кордюков Александр</a>
        <div class="nav-links">
            <h1>lol</h1>
            {#if nav.isShow=true}
                <a href={nav.href} class="link">{nav.title}</a>

            {/if}
        </div>
    </div>
</nav>

<div class="container">
    <!--Проекты будут ниже-->
    <slot></slot>
</div>

<script>
    const nav=[
        {
            title:'Обо мне',
            href:'/about',
            isShow:true,
        },
        {
            title:'Блог',
            href:'/blog',
            isShow:true,
        },
        {
            title:'Портфолио',
            href:'/project',
            isShow:true,
        },
        {
            title:'Контакты',
            href:'/contact',
            isShow:true,
        },
        {
            title:'temp',
            href:'/temp',
            isShow:false,
        }
    ];
</script>
<style>
    .container{
        max-width: 1400px;
        margin: 50px auto;
    }
</style>