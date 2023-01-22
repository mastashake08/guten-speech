<template>
  <div>
    <NuxtWelcome />
  </div>
</template>
<script>
import Gutendex from 'gutendex'
const guten = new Gutendex()
console.table(await guten.getBooksByTopic('children'))
</script>
