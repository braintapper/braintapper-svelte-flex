<script>

  export let flex = undefined;
  export let style = undefined;
  export let id = undefined;
  export let classes = undefined;

</script>

<div layout="row" {style} {id} class={classes} {flex}>
  <slot/>
</div>

<style>

  div {
    box-sizing: border-box;
    display: -webkit-box;
    display: -webkit-flex;
    display: -moz-box;
    display: -ms-flexbox;
    display: flex; 
    flex-direction: row; 
    max-width: 100%;
  }
  
</style>
