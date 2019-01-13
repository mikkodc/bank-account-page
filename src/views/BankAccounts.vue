<template>
  <div>
    <AltHeader page-title="Bank Accounts"></AltHeader>
    <BankDetails></BankDetails>
  </div>
</template>

<script>
// @ is an alias to /src
import AltHeader from "@/components/AltHeader.vue";
import BankDetails from "@/components/BankDetails.vue";

export default {
  name: "home",
  components: {
    AltHeader,
    BankDetails
  }
};
</script>
