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