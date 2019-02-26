<template>
  <div>
    <scroll-view scroll-y style="height:30rpx;width:100%;">
      <div>
        <p>你是傻子吧</p>
      </div>
      <div @click="new_try(1)">{{msg}}</div>
    </scroll-view>
  </div>
</template>

<script>
import { formatTime } from "@/utils/index";
import card from "@/components/card";

export default {
  components: {
    card
  },

  data() {
    return {
      msg: "yes"
    };
  },
  methods: {
    new_try(e) {
      console.log(e);
      this.msg = "不，我不是";
    }
  },
  created() {}
};
</script>

<style>
.news {
  width: 50px;
  line-height: 100px;
  background: blue;
}
</style>
