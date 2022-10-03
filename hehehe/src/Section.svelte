<script>
    export let title;
</script>

<article>
    <hr>
    <h2>{title}</h2>
    <slot></slot>
</article>

<style>
    h2 {
        font-family: 'Comic Sans MS', 'Chalkboard', 'Zapfino', cursive;
    }
</style>