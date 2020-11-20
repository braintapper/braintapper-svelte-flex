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



  /* ---- */



  [flex-order] {
    order: 0; }

  [flex-order--20] {
    order: -20; }

  [flex-order--19] {
    order: -19; }

  [flex-order--18] {
    order: -18; }

  [flex-order--17] {
    order: -17; }

  [flex-order--16] {
    order: -16; }

  [flex-order--15] {
    order: -15; }

  [flex-order--14] {
    order: -14; }

  [flex-order--13] {
    order: -13; }

  [flex-order--12] {
    order: -12; }

  [flex-order--11] {
    order: -11; }

  [flex-order--10] {
    order: -10; }

  [flex-order--9] {
    order: -9; }

  [flex-order--8] {
    order: -8; }

  [flex-order--7] {
    order: -7; }

  [flex-order--6] {
    order: -6; }

  [flex-order--5] {
    order: -5; }

  [flex-order--4] {
    order: -4; }

  [flex-order--3] {
    order: -3; }

  [flex-order--2] {
    order: -2; }

  [flex-order--1] {
    order: -1; }

  [flex-order-0] {
    order: 0; }

  [flex-order-1] {
    order: 1; }

  [flex-order-2] {
    order: 2; }

  [flex-order-3] {
    order: 3; }

  [flex-order-4] {
    order: 4; }

  [flex-order-5] {
    order: 5; }

  [flex-order-6] {
    order: 6; }

  [flex-order-7] {
    order: 7; }

  [flex-order-8] {
    order: 8; }

  [flex-order-9] {
    order: 9; }

  [flex-order-10] {
    order: 10; }

  [flex-order-11] {
    order: 11; }

  [flex-order-12] {
    order: 12; }

  [flex-order-13] {
    order: 13; }

  [flex-order-14] {
    order: 14; }

  [flex-order-15] {
    order: 15; }

  [flex-order-16] {
    order: 16; }

  [flex-order-17] {
    order: 17; }

  [flex-order-18] {
    order: 18; }

  [flex-order-19] {
    order: 19; }

  [flex-order-20] {
    order: 20; }
    
</style>
