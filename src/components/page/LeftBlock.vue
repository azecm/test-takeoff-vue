<template>
  <div class="left-block">
    <div class="logo"></div>
    <div style="height: 50px;"></div>

    <menu-button class="active">
      <svg focusable="false" data-prefix="fal" data-icon="ballot-check" xmlns="http://www.w3.org/2000/svg"
           viewBox="0 0 448 512">
        <path fill="currentColor"
              d="M112 432h32c17.7 0 32-14.4 32-32v-32c0-17.6-14.3-32-32-32h-32c-17.7 0-32 14.4-32 32v32c0 17.6 14.3 32 32 32zm0-64h32v32h-32v-32zm0-192h32c17.7 0 32-14.4 32-32v-32c0-17.6-14.3-32-32-32h-32c-17.7 0-32 14.4-32 32v32c0 17.6 14.3 32 32 32zm0-64h32v32h-32v-32zM416 0H32C14.3 0 0 14.4 0 32v448c0 17.6 14.3 32 32 32h384c17.7 0 32-14.4 32-32V32c0-17.6-14.3-32-32-32zm0 480H32V32h384v448zM216 144h128c4.4 0 8-3.6 8-8v-16c0-4.4-3.6-8-8-8H216c-4.4 0-8 3.6-8 8v16c0 4.4 3.6 8 8 8zm0 128h128c4.4 0 8-3.6 8-8v-16c0-4.4-3.6-8-8-8H216c-4.4 0-8 3.6-8 8v16c0 4.4 3.6 8 8 8zm0 128h128c4.4 0 8-3.6 8-8v-16c0-4.4-3.6-8-8-8H216c-4.4 0-8 3.6-8 8v16c0 4.4 3.6 8 8 8zm-97.4-113.6c2.1 2.1 5.5 2.1 7.6 0l64.2-63.6c2.1-2.1 2.1-5.5 0-7.6l-12.6-12.7c-2.1-2.1-5.5-2.1-7.6 0l-47.6 47.2-20.6-20.9c-2.1-2.1-5.5-2.1-7.6 0l-12.7 12.6c-2.1 2.1-2.1 5.5 0 7.6l36.9 37.4z"></path>
      </svg>
      <span>Опросы</span>
    </menu-button>

    <menu-button>
      <svg focusable="false" data-prefix="fal" data-icon="users" role="img" xmlns="http://www.w3.org/2000/svg"
           viewBox="0 0 640 512">
        <path fill="currentColor"
              d="M544 224c44.2 0 80-35.8 80-80s-35.8-80-80-80-80 35.8-80 80 35.8 80 80 80zm0-128c26.5 0 48 21.5 48 48s-21.5 48-48 48-48-21.5-48-48 21.5-48 48-48zM320 256c61.9 0 112-50.1 112-112S381.9 32 320 32 208 82.1 208 144s50.1 112 112 112zm0-192c44.1 0 80 35.9 80 80s-35.9 80-80 80-80-35.9-80-80 35.9-80 80-80zm244 192h-40c-15.2 0-29.3 4.8-41.1 12.9 9.4 6.4 17.9 13.9 25.4 22.4 4.9-2.1 10.2-3.3 15.7-3.3h40c24.2 0 44 21.5 44 48 0 8.8 7.2 16 16 16s16-7.2 16-16c0-44.1-34.1-80-76-80zM96 224c44.2 0 80-35.8 80-80s-35.8-80-80-80-80 35.8-80 80 35.8 80 80 80zm0-128c26.5 0 48 21.5 48 48s-21.5 48-48 48-48-21.5-48-48 21.5-48 48-48zm304.1 180c-33.4 0-41.7 12-80.1 12-38.4 0-46.7-12-80.1-12-36.3 0-71.6 16.2-92.3 46.9-12.4 18.4-19.6 40.5-19.6 64.3V432c0 26.5 21.5 48 48 48h288c26.5 0 48-21.5 48-48v-44.8c0-23.8-7.2-45.9-19.6-64.3-20.7-30.7-56-46.9-92.3-46.9zM480 432c0 8.8-7.2 16-16 16H176c-8.8 0-16-7.2-16-16v-44.8c0-16.6 4.9-32.7 14.1-46.4 13.8-20.5 38.4-32.8 65.7-32.8 27.4 0 37.2 12 80.2 12s52.8-12 80.1-12c27.3 0 51.9 12.3 65.7 32.8 9.2 13.7 14.1 29.8 14.1 46.4V432zM157.1 268.9c-11.9-8.1-26-12.9-41.1-12.9H76c-41.9 0-76 35.9-76 80 0 8.8 7.2 16 16 16s16-7.2 16-16c0-26.5 19.8-48 44-48h40c5.5 0 10.8 1.2 15.7 3.3 7.5-8.5 16.1-16 25.4-22.4z"></path>
      </svg>
      <span>Пользователи</span>
    </menu-button>
    <menu-button>
      <svg focusable="false" data-prefix="fal" data-icon="engine-warning" xmlns="http://www.w3.org/2000/svg"
           viewBox="0 0 640 512">
        <path fill="currentColor"
              d="M320 32C196.3 32 96 132.3 96 256c0 123.76 100.3 224 224 224s224-100.24 224-224c0-123.7-100.3-224-224-224zm0 416c-105.87 0-192-86.13-192-192S214.13 64 320 64s192 86.13 192 192-86.13 192-192 192zm18.64-320.02h-37.28c-7.9 0-14.08 6.82-13.29 14.69l10.69 149.29c.68 6.83 6.43 12.03 13.29 12.03h15.9c6.87 0 12.61-5.2 13.29-12.03l10.69-149.29c.79-7.86-5.39-14.69-13.29-14.69zM320 328c-13.26 0-24 10.74-24 24 0 13.25 10.74 24 24 24s24-10.75 24-24c0-13.26-10.74-24-24-24zM90.69 69.17l-12.4-10.11c-3.49-2.85-8.75-2.31-11.51 1.25C23.65 116.12 0 185.28 0 256c0 70.74 23.65 139.88 66.75 195.65 2.76 3.57 8.01 4.1 11.51 1.25l12.4-10.11c3.36-2.73 3.84-7.58 1.19-11.01C53.2 381.66 32 319.54 32 256c0-63.53 21.2-125.65 59.88-175.82 2.65-3.43 2.17-8.28-1.19-11.01zm482.53-8.86c-2.76-3.57-8.01-4.1-11.51-1.25l-12.4 10.11c-3.36 2.73-3.83 7.58-1.19 11.01C586.8 130.35 608 192.47 608 256c0 63.54-21.2 125.66-59.85 175.79-2.64 3.43-2.17 8.27 1.19 11.01l12.4 10.11c3.49 2.85 8.75 2.31 11.51-1.25C616.35 395.88 640 326.74 640 256c0-70.72-23.65-139.88-66.78-195.69z"></path>
      </svg>
      <span>Черные списки</span>
    </menu-button>
    <menu-button>
      <svg focusable="false" data-prefix="fal" data-icon="phone-alt" xmlns="http://www.w3.org/2000/svg"
           viewBox="0 0 512 512">
        <path fill="currentColor"
              d="M493.09 351.3L384.7 304.8a31.36 31.36 0 0 0-36.5 8.9l-44.1 53.9A350 350 0 0 1 144.5 208l53.9-44.1a31.35 31.35 0 0 0 8.9-36.49l-46.5-108.5A31.33 31.33 0 0 0 125 .81L24.2 24.11A31.05 31.05 0 0 0 0 54.51C0 307.8 205.3 512 457.49 512A31.23 31.23 0 0 0 488 487.7L511.19 387a31.21 31.21 0 0 0-18.1-35.7zM456.89 480C222.4 479.7 32.3 289.7 32.1 55.21l99.6-23 46 107.39-72.8 59.5C153.3 302.3 209.4 358.6 313 407.2l59.5-72.8 107.39 46z"></path>
      </svg>
      <span>Колл-центр</span>
    </menu-button>

    <div style="height: 400px;"></div>
    <button class="help-button">?</button>
  </div>
</template>

<script lang="ts">
  import MenuButton from '../element/MenuButton.vue';
  import {Component, Vue} from 'vue-property-decorator';

  @Component({
    components: {MenuButton},

  })
  export default class LeftBlock extends Vue {
  }
</script>


<style scoped lang="scss">
  @import "../../styles/colors";
  @import "../../styles/button-drop";

  .left-block {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 120px;
    min-height: 600px;
    border-right: 1px solid #eee;
    border-bottom: 1px solid #eee;
    padding-top: 1em;
    padding-bottom: 1em;
  }

  .help-button {
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    background-color: white;
    border-radius: 50%;
    width: 2em;
    height: 2em;
    border: 1px solid black;
    color: $add-color;
    transition-duration: 0.2s;

    &:hover {
      box-shadow: 0 0 0.5em silver;
      color: $top-color;
      border-color: silver;
    }
  }

  .logo {
    width: 2.5em;
    height: 2.5em;
    background-color: #dc3545;
    border-radius: 50%;
  }
</style>
