<template>
  <v-card>
    <v-system-bar></v-system-bar>
    <v-toolbar flat class="color12">
      <v-toolbar-title>My Document</v-toolbar-title>
      <v-spacer></v-spacer>
      <div>
        <v-switch v-model="sticky" label="Sticky Banner" hide-details></v-switch>
      </div>
    </v-toolbar>
    <v-banner single-line :sticky="sticky" class="color13">
      We can't save your edits while you are in offline mode.

      <template v-slot:actions>
        <v-btn text color="color14"> Get Online </v-btn>
      </template>
    </v-banner>
    <v-card-text class="color15">
      <v-sheet max-width="800" height="300" class="color16 mx-auto">
      <br/><br/>
        <v-card class="mx-auto color22" max-width="344" outlined>
          <v-list-item three-line>
            <v-list-item-content>
              <div class="text-overline mb-4">OVERLINE</div>
              <v-list-item-title class="text-h5 mb-1"> Headline 5 </v-list-item-title>
              <v-list-item-subtitle
                >Greyhound divisely hello coldly fonwderfully</v-list-item-subtitle
              >
            </v-list-item-content>

            <v-list-item-avatar tile size="80" color="color23"></v-list-item-avatar>
          </v-list-item>

          <v-card-actions>
            <v-btn outlined rounded text> Button </v-btn>
          </v-card-actions>
        </v-card>
      </v-sheet>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  data: () => ({
    sticky: false,
  }),
};
</script>

<style></style>
