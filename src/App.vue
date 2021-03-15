<template>
  <div id="app">
    <nft msg="Create Your First NFT" title="NFT Maker" />
    <contract msg="Upload to Contract" title="NFT Maker" />
  </div>
</template>

<script>
import Nft from './components/Nft.vue'
import Contract from './components/Contract.vue'

export default {
  name: 'App',
  components: {
    Nft,
    Contract
  }
}
</script>

