<template>
  <div>
    <b-row>
      <b-col class="d-flex justify-content-center mt-3">
        <b-img :src="pictureUrl" alt="picture" />
      </b-col>
    </b-row>

    <b-row>
      <b-col>
        <h3 class="headlines">{{ title }}</h3>
        <p>{{ body }}</p>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: "RightMenuContent",
  components: {},
  props: {
    // TODO: vedere se è meglio passare un oggetto
    pictureUrl: String,
    title: String,
    body: String,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.headlines {
  font-size: 20px;
}
</style>

