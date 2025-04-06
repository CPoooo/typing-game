<template>
  <div>
    <h1>Choose CPU Typing Speed:</h1>
    <input id="wpm" type="text" value="50"/>
  </div>
    <textarea name="typing-area" id="typing-area" autofocus spellcheck="false"></textarea>
  </template>

<script></script>

<style scoped>
div {
  display: flex;
}

#wpm {
  background: none;
  border: none;
  outline: none;
  color: white;
  font-size: 2rem;
  width: 100px;
  text-align: center;
  caret-color: white; /* optional: matches the text color */
}

h1 {
  font-size: 1.5rem;
  font-family: monospace;
}

#typing-area {
  width: 500px;
  height: 150px; /* or adjust based on your layout */
  font-size: 1.5rem;
  font-family: monospace;
  background: none;
  border: none;
  outline: none;
  color: white;
  resize: none;
  caret-color: white;
  line-height: 1.6;
  padding: 10px;
}
</style>
