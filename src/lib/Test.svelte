<script lang="ts">
    let {children} = $props()

    const normalJS: string = ''
</script>
<button onclick={(e: MouseEvent)=>{e.stopPropagation();}}>{@render children()}</button>