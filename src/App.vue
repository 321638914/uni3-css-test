<script setup lang="ts">
  import { onLaunch, onShow, onHide } from '@dcloudio/uni-app';
  onLaunch(() => {
    console.log('App Launch');
  });
  onShow(() => {
    console.log('App Show');
  });
  onHide(() => {
    console.log('App Hide');
  });
</script>
<style>
  view,
  text,
  image {
    box-sizing: border-box;
  }

  image {
    width: 100%;
    height: 100%;
  }
</style>
