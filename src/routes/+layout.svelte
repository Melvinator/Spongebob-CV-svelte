<svelte:head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spongebob CV</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400&family=Peralta&display=swap"
        rel="stylesheet">
    <script src="https://kit.fontawesome.com/01a0fd7944.js" crossorigin="anonymous"></script>
</svelte:head>

<div class="parent">
    <div class="sidebar" />
    <div class="content">
        <slot />
    </div>
</div>

<style>
    :global(html, body) {
        width: 100%;
        height: 100%;
        padding : 0;
        margin: 0;
    }
    .parent {
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: row;
    }
    .sidebar {
        background-color:blue;
        width: 200px;
        height:100%;
    }
    .content {
        display: flex;
        flex-direction: column;
    }
    
</style>