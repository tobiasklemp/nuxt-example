<script lang="ts" setup>
  import { ITest } from './src/types'
  const bla: ITest = {
    test: '123',
    test2: 123,
  }
  console.log('test-123')
</script>

<template> 
  <div>
    {{ bla }}
  </div>
</template>
