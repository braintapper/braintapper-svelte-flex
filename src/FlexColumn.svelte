<script>

  export let flex = undefined;
  export let style = undefined;
  export let id = undefined;
  export let classes = undefined;

</script>

<div layout="column" {style} {id} class={classes} {flex}>
  <slot/>
</div>

<style>

  [layout] {
    box-sizing: border-box;
    display: -webkit-box;
    display: -webkit-flex;
    display: -moz-box;
    display: -ms-flexbox;
    display: flex; 
  }

  [layout=column] {
    flex-direction: column; 
  }

</style>
