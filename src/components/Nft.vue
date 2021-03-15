<template>
  <div class="nft is-bold">
    <div class="nft-body">
      <div class="cointainer has-text-centered">
        <h1>{{ title }}</h1>
        <h2> {{ msg}} </h2>
        <p>
          First Test Project to Create AI based NFTs
          
        </p>
        <h3>Links</h3>
        <ul>
          <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">Telegram</a></li>
          <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">Medium</a></li>
        </ul>
        
        <input type='file' accept=".mp4, .mkv .ogg .wmv"/>
        <button> Upload </button>
      </div>
     </div> 
  </div>
</template>

<script>
export default {
  name: 'Nft',
  props: {
    msg: String,
    title: String
  }
}
</script>

