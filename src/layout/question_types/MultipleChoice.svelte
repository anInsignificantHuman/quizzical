<script>
  export let choices;
  /*
    {
      text: string,
      correct: boolean, 
    }
  */
</script>

<div class="question">
  <form>
    {#each choices as choice, index}
      <div class="form-check">
        <input
          class="form-check-input"
          type="radio"
          name="choices"
          id="choice{index}"
        />
        <label class="form-check-label" for="choice{index}">
          {choice.text}
        </label>
      </div>
    {/each}
  </form>
</div>


<style>

</style>