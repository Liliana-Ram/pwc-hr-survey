<template>
  <div>
    <p>Encuesta</p>
  </div>
</template>

<script>
import { db } from '../firebase';

console.log(db);
export default {
  name: 'Companies',
  props: {
    // msg: String,
  },
  data() {
    return {
    };
  },
  // firestore: {
  //   collectionCompanies: db.collection('clientes'),
  // },
};
</script>
