<script>
    let m = { x: 0, y: 0 };

    function handleMousemove(event) {
        m.x = event.clientX;
        m.y = event.clientY;
    }
</script>

<main>

    <div on:mousemove={handleMousemove}>
        The mouse position is {m.x} x {m.y}
    </div>

</main>


<style>
    div{
        width: 300px;
        height: 300px;
        color: rgb(90, 21, 82);
        background: lightsalmon;
    }
</style>