<template>
  <div id="app" class="small-container">
    <h1>Transactions:</h1>
    <TransactionTable />
  </div>
</template>

<script>
import TransactionTable from './components/TransactionTable';

export default {
  name: 'App',

  components: {
    TransactionTable,
  },
}
</script>
