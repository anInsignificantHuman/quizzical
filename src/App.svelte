<script>
  import Navbar from "./layout/Navbar.svelte";
  import MultipleChoice from "./layout/question_types/MultipleChoice.svelte";
</script>

<main>
  <Navbar active="home" />
  <MultipleChoice
    choices={[
      { text: "george washington" },
      { text: "abraham lincoln" },
      { text: "andrew jackson" },
      { text: "la madre" },
    ]}
  />
</main>


