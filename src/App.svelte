<script>
  import PrismCode from './component/PrismCode.svelte';
</script>

<main>
  <PrismCode lang="php">{`private $name = 'world';`}</PrismCode>
  <PrismCode lang="js">{`console.log("world");`}</PrismCode>
  <PrismCode lang="css">{`.root {color: #dedede;}`}</PrismCode>
</main>
