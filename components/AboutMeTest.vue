<template>
<v-card class="basil">
  <v-tabs vertical  background-color="transparent">
    
    <v-tab>
      Option 1
    </v-tab>
    <v-tab>
      Option 2
    </v-tab>
    <v-tab>
      Option 3
    </v-tab>

    <v-tab-item>
      <v-card flat>
        <v-card-text>
          <p>
            Sed aliquam ultrices mauris. Donec posuere vulputate arcu. Morbi ac
            felis. Etiam feugiat lorem non metus. Sed a libero.
          </p>

          <p>
            Nam ipsum risus, rutrum vitae, vestibulum eu, molestie vel, lacus.
            Aenean tellus metus, bibendum sed, posuere ac, mattis non, nunc.
            Aliquam lobortis. Aliquam lobortis. Suspendisse non nisl sit amet
            velit hendrerit rutrum.
          </p>

          <p class="mb-0">
            Phasellus dolor. Fusce neque. Fusce fermentum odio nec arcu.
            Pellentesque libero tortor, tincidunt et, tincidunt eget, semper
            nec, quam. Phasellus blandit leo ut odio.
          </p>
        </v-card-text>
      </v-card>
    </v-tab-item>
    
    <v-tab-item>
      <v-card flat>
        <v-card-text>
          <p>
            Morbi nec metus. Suspendisse faucibus, nunc et pellentesque egestas,
            lacus ante convallis tellus, vitae iaculis lacus elit id tortor. Sed
            mollis, eros et ultrices tempus, mauris ipsum aliquam libero, non
            adipiscing dolor urna a orci. Curabitur ligula sapien, tincidunt
            non, euismod vitae, posuere imperdiet, leo. Nunc sed turpis.
          </p>
        </v-card-text>
      </v-card>
    </v-tab-item>
    
    <v-tab-item>
      <v-card flat>
        <v-card-text>
          <p>
            Fusce a quam. Phasellus nec sem in justo pellentesque facilisis. Nam
            eget dui. Proin viverra, ligula sit amet ultrices semper, ligula
            arcu tristique sapien, a accumsan nisi mauris ac eros. In dui magna,
            posuere eget, vestibulum et, tempor auctor, justo.
          </p>

          <p class="mb-0">
            Cras sagittis. Phasellus nec sem in justo pellentesque facilisis.
            Proin sapien ipsum, porta a, auctor quis, euismod ut, mi. Donec quam
            felis, ultricies nec, pellentesque eu, pretium quis, sem. Nam at
            tortor in tellus interdum sagittis.
          </p>
        </v-card-text>
      </v-card>
    </v-tab-item>

  </v-tabs>
</v-card>
</template>

<script>
export default {
  data() {
    return {
      tab: null,
      items: [
        { tab: "One", content: "Tab 1 Content" },
        { tab: "Two", content: "Tab 2 Content" },
        { tab: "Three", content: "Tab 3 Content" },
        { tab: "Four", content: "Tab 4 Content" },
        { tab: "Five", content: "Tab 5 Content" },
        { tab: "Six", content: "Tab 6 Content" },
        { tab: "Seven", content: "Tab 7 Content" },
        { tab: "Eight", content: "Tab 8 Content" },
        { tab: "Nine", content: "Tab 9 Content" },
        { tab: "Ten", content: "Tab 10 Content" },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>

.basil {
  background-color: #30302f !important;
}
.basil--text {
  color: #77ebc8 !important;
}
</style>