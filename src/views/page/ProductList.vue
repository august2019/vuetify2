<template>
  <v-container fluid>
    <v-row>
      <v-col
        v-for="i in 10"
        :key="i"
        cols="12"
        sm="6"
        md="4"
        lg="3"
      >
        <product-item />
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
import ProductItem from '@/components/product/ProductItem';
export default {
  components: {
    ProductItem
  }
}
</script>
