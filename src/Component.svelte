<script>
  import { getContext } from "svelte"

  export let text

  const { styleable } = getContext("sdk")
  const component = getContext("component")
</script>

<div use:styleable={$component.styles}>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/8OOYueXQ8c8" 
    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
    </iframe>
</div>
