<script>
  import Header from "./components/Header.svelte";
  import Counter from "./lib/Counter.svelte";
  import GetStarted from "./pages/GetStarted.svelte";
</script>

<main>
  <Header />
  <GetStarted />
  <div class="mainSection noSelect" style="margin-top: 85px;">
    <div class="subSection">
      <h3 class="heading noSelect">Sample Function</h3>
      <Counter />
    </div>
  </div>
</main>
