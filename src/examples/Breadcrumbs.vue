<template>
  <nav aria-label="breadcrumb">
    <ol
      class="px-0 pt-1 pb-0 mb-0 bg-transparent breadcrumb"
      :class="isRTL ? '' : ' me-sm-6'"
    >
   
   
    </ol>
    <h6 class="mb-0 font-weight-bolder" :class="color">
      {{ currentPage }}
    </h6>
  </nav>
</template>

<script>
import { mapState } from "vuex";

export default {
  name: "breadcrumbs",
  props: {
    currentPage: {
      type: String,
      required: "",
    },
    color: {
      type: String,
      default: "text-dark",
    },
  },
  computed: {
    ...mapState(["isRTL"]),
  },
};
</script>
