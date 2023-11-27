<template>
    <div>
        <Select class="employee-select" label="Employees" name="pt" :options="options" placeholder="Select employee" />
    </div>
</template>
<script setup>

import Select from "@/components/Select";

const options = [
    { value: "1", text: "Jane Cooper" },
    { value: "2", text: "Jone Dick" },
    { value: "3", text: "Sevastian Kilvo" },
    { value: "4", text: "Valiyana Kushnova" },
];
</script>

<style lang="scss" scoped></style>
  