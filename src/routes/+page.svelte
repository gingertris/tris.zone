<script>
    // @ts-nocheck
    import projects from "$lib/data/projects.json"
</script>

<div id="content" class="text-normal content">
    <div id="introduction">
        <h2 class="text-blue">hello! i am <a href="https://blog.tris.zone/name"><span class="text-pink">june</span></a>, but you may know me as tris -</h2>
        <ul>
            <li>22 years old</li>
            <li>british</li>
            <li>non binary (they/she)</li>
            <li>software developer</li>
            <li>guitarist</li>
            <li>tetr.io and rocket league enjoyer</li>
        </ul>

    </div>

    <div id="projects">
        <h2 class="text-blue">projects</h2>
        {#each projects as project}
            {#if !project.hidden}
                <h4 class="text-pink">
                {#if project.link}
                    <a class="text-pink" href={project.link}>{project.name}</a>
                {:else}
                    {project.name}
                {/if}
                
                </h4>
                <p>{project.description}</p>
                <p><i>{project.timeframe}</i></p>
            {/if}

        {/each}
    </div>
    <div id="links" class="text-normal">
        <h2 class="text-blue">links</h2>
        <p>
            <a href="https://blog.tris.zone">blog</a>
            <a href="https://www.twitter.comJuneRL_">twitter</a>
            <a href="https://www.github.com/gingertris">github</a>
            <a href="https://ch.tetr.io/u/june">tetr.io</a> 
            <a href="https://www.last.fm/user/gingertris">last.fm</a>
        </p>
        
        <span>discord - gingertris</span>

    </div>
</div>
