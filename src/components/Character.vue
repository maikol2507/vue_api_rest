 <template>
  <div class="colums is-12-mobile is-4-desktop is-4-tablet">
    <div class="card">
      <div class="card-header">
        <img v-bind:src="character.image" v-bind:alt="character.name" />
      </div>
      <div class="card-content">
        <h3 class="title is-size-4">{{ character.name }}</h3>
        <button class="button is-danger is-rounded is-small">Ver más</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ["character"],
};
</script>>
