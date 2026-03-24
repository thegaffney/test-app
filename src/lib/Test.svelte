<script lang="ts">
    let {children} = $props()
</script>
<button onclick={(e: MouseEvent)=>{e.stopPropagation();}}>{@render children()}</button>