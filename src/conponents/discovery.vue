<template>
  <div id="home">
      <Head></Head>
      <Table ></Table>
      <Swiper></Swiper>
      <Footer></Footer>
  </div>
</template>
<script>
import Head from "./subcpnent/header.vue";
import Table from "./subcpnent/tables.vue";
import Footer from "./subcpnent/footer.vue";
import Swiper from "./subcpnent/swiper.vue";
export default {
  components: {
    Head,
    Table,
    Footer,
    Swiper
  },
  data() {
    return {
      txt: "",
      Investment: {},
      common: {}
    };
  },
  created() {
    function A() {
      var count = 0;
      function B() {
        count++;
        console.log(count);
      }
      return B;
    }
    var c = A();
        console.log(
            C(),C(),C(),C(),C(),C()
        )
  },
  mounted() {
    var _this = this;
    var carlist = $("#carList");
    var tops = 0;
    var carinx = this.carouselList.length;
    var clearTime;
    var animateTime = 2000;
    carouseTime();
    carlist.hover(
      function() {
        clearInterval(clearTime);
      },
      function() {
        carouseTime();
      }
    );
  },
  filters: {
    focus: function(value) {
      console.log(val);
    }
  }
};
</script>
<style scoped>
</style> 
