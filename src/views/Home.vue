<template>
  <div class="home" id="wrapper">
    <Main />
    <Sider />
  </div>
</template>

<script>
// @ is an alias to /src

import Sider from '@/components/Sider'
import Main from '../components/Main'
export default {
  name: 'home',
  components: {
    Sider,
    Main
  }
}
</script>
