<script>

export let style = 'rounded';
export let image = 'https://placeimg.com/192/192/people';
export let size = '16';
export let mask = '';
export let presence = ''; // valid options are 'online' or 'offline'



</script>

<div class="avatar {presence}">
  {#if mask}
    <div class="w-{size} {style} mask {mask}">
      <img src={image} />
    </div>
  {:else}
    <div class="w-{size} {style}">
      <img src={image} />
    </div>
  {/if}
</div>

<style>

div.avatar {
  margin-bottom: 1em;
}

</style>