<script>

  export let flex = "initial";
  export let style = undefined;
  export let type = undefined;
  export let id = undefined;
  export let classes = undefined;

</script>

<div {flex} {style} {id} class={classes} {type}>
  <slot/>
</div>

<style>

  [flex] {
    flex: 1;
    box-sizing: border-box;
  }

  [flex=grow] {
    flex: 1 1 100%;
  }

  [flex=initial] {
    flex: 0 1 auto;
  }

  [flex=auto] {
    flex: 1 1 auto;
  }

  [flex=none] {
    flex: 0 0 auto;
  }

  [flex=noshrink] {
    flex: 1 0 auto;
  }

  [flex=nogrow] {
    flex: 0 1 auto;
  }

  [flex='0'] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 0%
  }


  /* ---- */


  [flex='5'] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 5%;
  }

  [flex="10"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 10%;
  }

  [flex="15"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 15%;
  }

  [flex="20"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 20%;
  }

  [flex="25"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 25%;
  }

  [flex="30"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 30%;
  }

  [flex="35"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 35%;
  }

  [flex="40"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 40%;
  }

  [flex="45"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 45%;
  }

  [flex="50"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 50%;
  }

  [flex="55"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 55%;
  }

  [flex="60"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 60%;
  }

  [flex="65"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 65%;
  }

  [flex="70"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 70%;
  }

  [flex="75"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 75%;
  }

  [flex="80"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 80%;
  }

  [flex="85"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 85%;
  }

  [flex="90"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 90%;
  }

  [flex="95"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 95%;
  }

  [flex='100'] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 100%;
  }

  [flex="33"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 33.33%;
  }

  [flex="66"] {
    flex: 1 1 100%;
    max-width: 100%;
    max-height: 66.66%;
  }



    
</style>
