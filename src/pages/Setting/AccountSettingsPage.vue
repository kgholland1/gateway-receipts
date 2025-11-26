<template>
  <div class="container-fluid">
    <div class="inner-main-content">
      <div class="card-title d-flex justify-content-between align-items-center mb-3">
        <h3 class="fw-medium fs-18 mb-0">Agency Details</h3>
      </div>
      <FieldSettings />

      <MainFooter />
    </div>
  </div>
</template>

<script setup lang="ts">
import FieldSettings from "../../components/Settings/AccountSettings/FieldSettings.vue";
import MainFooter from "../../components/Layouts/MainFooter.vue";
</script>
