<template>
  <v-app>
    <v-app-bar app color="color8" dark>
      <v-toolbar-title>Vuetify Custom Theme App</v-toolbar-title>
    </v-app-bar>
    <v-main>
      <theme-component-1></theme-component-1>
      <br />
      <theme-component-2></theme-component-2>
      <br />
      <theme-component-3></theme-component-3>
      <br/>
      <theme-component-4></theme-component-4>
      <br/>
      <theme-component-5></theme-component-5>
      <br/>
      <theme-component-6></theme-component-6>
      <br/>
      <theme-component-7></theme-component-7>
      <br/>
      <theme-component-8></theme-component-8>
    </v-main>
  </v-app>
</template>

<script>
import ThemeComponent1 from "./components/ThemeComponent1.vue";
import ThemeComponent2 from "./components/ThemeComponent2.vue";
import ThemeComponent3 from "./components/ThemeComponent3.vue";
import ThemeComponent4 from './components/ThemeComponent4.vue';
import ThemeComponent5 from './components/ThemeComponent5.vue';
import ThemeComponent6 from './components/ThemeComponent6.vue';
import ThemeComponent7 from './components/ThemeComponent7.vue';
import ThemeComponent8 from './components/ThemeComponent8.vue';
export default {
  name: "App",

  components: {
    ThemeComponent1,
    ThemeComponent2,
    ThemeComponent3,
    ThemeComponent4,
    ThemeComponent5,
    ThemeComponent6,
    ThemeComponent7,
    ThemeComponent8,
  },

  data: () => ({
    //
  }),
};
</script>
