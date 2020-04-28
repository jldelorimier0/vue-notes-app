<template>
  <div class="note-container">
  <!-- note-selectors goes here -->
  <note-selectors />
    <div class="note-editor">
      <p class="note-editor-info">Timestamp here...</p>
      <textarea class="note-editor-input">
        First note...
        Note text here...
      </textarea>
    </div>
  </div>
</template>

<script>
import NoteSelectors from "@/components/NoteSelectors"

  export default {
    name: 'note-container',
    components: {
      NoteSelectors
    }
  }
</script>