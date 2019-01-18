<template>
  <div id="login">
      <Head></Head>
      <Table></Table>
        <div class="test">123</div>
      <Footer></Footer>
  </div>
</template>
<script>
import axios from "vue-axios";
import Head from "./subcpnent/header.vue";
import Table from "./subcpnent/tables.vue";
import Alert from "./subcpnent/alert.vue";
import Footer from "./subcpnent/footer.vue";
export default {
  components: {
    Head,
    Table,
    Alert,
    Footer
  },
  data() {
    return {
      userId:""
    };
  },
  created() {
    document.body.style.cssText = "background:#f5f5f5";
  },
  mounted(){
//    axios.get(`https://api.imjad.cn/cloudmusic/?type=song&id=123456`).then((response) => {
//             // if (typeof callback === 'function') {
//             //     callback(response.data.data[0].url);
//             // }
//             console.log(response)
//         });
  }
};
</script>

<style scoped>


</style>
