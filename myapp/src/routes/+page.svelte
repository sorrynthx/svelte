<script>
    import Title from '$lib/title/+page.svelte'
</script>

<Title />

<div class="main">
    <h1>Main</h1>
    <a href="/about">move About</a>
    <a href="/guides">move Guides</a>
</div>

<style>
.main {
    display: block;
    margin: 20px auto;
    font-size: 20px;
}
</style>