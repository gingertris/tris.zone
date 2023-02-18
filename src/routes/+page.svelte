<script>
    // @ts-nocheck
    import projects from "$lib/data/projects.json"
</script>

<div id="content" class="text-normal">
    <div id="introduction">
        <h2 class="text-blue">hello! i am tris -</h2>
        <p>- 21 years old</p>
        <p>- british</p>
        <p>- non binary</p>
        <p>- developer</p>
        <p>- computer science student</p>
        <p>- guitarist</p>
        <p>- tetr.io and rocket league player</p>
        <p>- toki pona learner</p>
    </div>

    <div id="projects">
        <h2 class="text-blue">projects</h2>
        {#each projects as project}
            <h4 class="text-pink">
                {project.name}
            </h4>
            <p>{project.description}</p>
            <p><i>{project.timeframe}</i></p>
        {/each}
    </div>
    <div id="links" class="text-normal">
        <h2>links</h2>

        <a href="https://www.youtube.com/@Trisxd">youtube</a>
        <a href="https://www.twitter.com/Gingertris1">twitter</a>
        <a href="https://www.github.com/gingertris">github</a>
        <a href="https://www.last.fm/user/gingertris">last.fm</a>
        <a href="https://ch.tetr.io/u/gingertris">tetr.io</a>
        <span>discord - Tris#1111</span>

    </div>
</div>
