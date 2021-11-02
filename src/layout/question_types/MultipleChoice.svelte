<script>
  export let question;
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
    <p class="question-title">{question}</p>
    <div class="choices">
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
    </div>
  </form>
</div>

<style>
</style>
