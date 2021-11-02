<script>
  import Navbar from "./layout/Navbar.svelte";
  import MultipleChoice from "./layout/question_types/MultipleChoice.svelte";
</script>

<main>
  <Navbar active="home" />
  <div class="container">
    <div class="row">
      <div class="col">
        <MultipleChoice
          question="who was first president lol"
          choices={[
            { text: "george washington" },
            { text: "abraham lincoln" },
            { text: "andrew jackson" },
            { text: "la madre" },
          ]}
        />
      </div>
      <div class="col">
        <MultipleChoice
          question="who was first president lol"
          choices={[
            { text: "george washington" },
            { text: "abraham lincoln" },
            { text: "andrew jackson" },
            { text: "la madre" },
          ]}
        />
      </div>
      <div class="col">Column</div>
    </div>
  </div>
</main>