<script setup lang="ts"></script>

<template>
  <div class="uk-container uk-margin-large-top">
    <div class="uk-grid uk-grid-collapse" uk-grid>
      <div class="uk-width-expand">
        <input type="text" class="uk-input" placeholder="Type todo and press enter">
      </div>
      <div class="uk-width-small">
        <button type="button" class="uk-button uk-button-primary">+</button>
      </div>

      <div class="uk-width-1-1 uk-margin-top">

        <div class="">
          <label for="id-1">
            <input type="checkbox" class="uk-checkbox" id="id-1">
            Test Todo
          </label>
        </div>

        <div class="">
          <label for="id-2">
            <input type="checkbox" class="uk-checkbox" id="id-2">
            Test Todo 2
          </label>
        </div>

      </div>
    </div>
  </div>
</template>



<style>
  @import 'https://cdnjs.cloudflare.com/ajax/libs/uikit/3.13.7/css/uikit.min.css';
</style>
