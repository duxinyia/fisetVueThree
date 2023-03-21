<template>
  <div class="about">
    <h1>This is an about</h1>
  </div>
</template>
<script lang="ts" setup>
// import { defineComponent } from "vue";

// export default defineComponent({
//   name: "AboutView",
//   setup() {
//     return {};
//   },
// });
interface PerIts {
  readonly name: string;
  age?: number;
  getName: () => void;
}
class M implements PerIts {
  name = "杜";
  age = 89;
  getName() {
    return;
  }
}
let m = new M();
m.name = "sdjijdis";
m.age = 22;
</script>
