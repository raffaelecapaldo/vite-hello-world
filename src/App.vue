:<template>
    <AppTitle />
    <AppHero />
    <div class="vue-logo d-flex justify-content-center w-25 mx-auto">
      <img class="img-fluid" src="src/assets/logo.svg" alt="">
    </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'
export default {
  data () {
    

    return {}
  },
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<style lang="scss" scoped>

</style>