<template>
  <div class="profile">
      <div class="container">
          <div class="row justify-content-center">
              <div class="col-lg-6">
                  <div class="media text-left">
                    <img src="../assets/photo-profile.png" class="mr-3 img-profile" alt="">
                    <div class="media-body">
                        <h5 class="mt-0">Sahrial Ardians</h5>
                        <p>
                            I am a web developer based in Medan, Indonesia. And I focus on back-end developers. But I also have a passion for website design and mobile devices.
                        </p>
                    </div>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'Profile',
  components: {
    // HelloWorld
  }
}
</script>

<style scoped>
    .img-profile{
        width: 100px;
        height: 100px;
        border-radius: 200%;
    }
</style>
