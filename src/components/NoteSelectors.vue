<template>
  <div class="note-selectors">
    <NoteSelector1 />
    <NoteSelector2 />
    <NoteSelector3 />

  </div>
</template>

<script>
import NoteSelector1 from "./NoteSelector1.vue";
import NoteSelector2 from "./NoteSelector2.vue";
import NoteSelector3 from "./NoteSelector3.vue";
export default {
  components: {
    NoteSelector1,
    NoteSelector2,
    NoteSelector3,
  },
};
</script>

