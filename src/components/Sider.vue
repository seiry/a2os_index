<template>
  <div id="sidebar">
    <div class="inner">
      <!-- Menu -->
      <nav id="menu">
        <header class="major">
          <h2>目录</h2>
        </header>
        <ul>
          <li>
            <!-- <a href="index.html"></a> -->
            <router-link to="/">主页</router-link>
          </li>
        </ul>
      </nav>

      <!-- Section -->

      <!-- Section -->
      <section>
        <header class="major">
          <h2>加入我们</h2>
        </header>
        <ul class="contact">
          <li class="fa-qq">
            <a class="hover-image">
              A2OS-Beta QQ群
              <img src="@/assets/images/qq_group.jpg" style="width: 90%" />
            </a>
          </li>
          <li class="fa-telegram">
            <a href="https://t.me/NUAAOpenSource">NUAAOpenSource</a>
          </li>
          <li class="fa-envelope">
            <a href="mailto:a2os-general@googlegroups.com">a2os-general@googlegroups.com</a>
          </li>
          <li class="fa-home">南京航空航天大学将军路校区</li>
        </ul>
      </section>

      <!-- Footer -->
      <footer id="footer">
        <p class="copyright">@a2os.club 2018-2019 All rights reserved.</p>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sider",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#sidebar .inner{
  position: fixed;
}

.hover-image img {
  display: none;
}

.hover-image:hover img {
  display: block;
}


</style>
