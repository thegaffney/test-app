<script lang="ts">
    let {children, response} = $props()

    const normalJS: string = ''
</script>
<button onclick={(e: MouseEvent)=>{e.stopPropagation(); response()}}>{@render children()}</button>
