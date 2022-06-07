<template>
  <nav class="navbar navbar-style_width" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="#">
        <img src="/img/_navigation/opennesscommuni_nav.png"/>
      </a>

      <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
    <div id="navbarBasicExample" class="navbar-menu navbar-menu_logo">
      <div class="navbar-start">
        <a class="navbar-item" style="margin-left: 20px;margin-right: 20px;">
          <p><span class="navbar-title">新闻</span><br>
            <span class="navbar-title_info">阅读我们的动态</span></p>
        </a>

        <a class="navbar-item" style="margin-left: 20px;margin-right: 20px;">
          <p><span class="navbar-title">介绍</span><br>
            <span class="navbar-title_info">了解我们的理念</span></p>
        </a>

        <a class="navbar-item" style="margin-left: 20px;margin-right: 20px;">
          <p><span class="navbar-title">参与</span><br>
            <span class="navbar-title_info">加入到开放运动中</span></p>
        </a>

        <a class="navbar-item" style="margin-left: 20px;margin-right: 20px;">
          <p><span class="navbar-title">联合</span><br>
            <span class="navbar-title_info">促进更多可能的诞生</span></p>
        </a>

        <a class="navbar-item" style="margin-left: 20px;margin-right: 20px;">
          <p><span class="navbar-title">档案</span><br>
            <span class="navbar-title_info">提供资料的查询和学习</span></p>
        </a>
      </div>
      <div class="navbar-end">
        <div class="navbar-item">
          <div class="columns" style="display: block">
            <div class="column">
              <ul class="navbar-column_layout">
                <li><a class="navbar-item navbar-title_a"><img src="/img/_navigation/login_nav_icon.png" width="26.3" height="19.29" style="margin-right: 6px;vertical-align: -2px" />登录</a></li>
                <li><a class="navbar-item navbar-title_a"><img src="/img/_navigation/language_nav_icon.png" width="21" height="20" style="margin-right: 6px;vertical-align: -2px"/>
                  语言</a></li>
                <li><a class="navbar-item navbar-title_a"><img src="/img/_navigation/search_nav_icon.png" width="23" height="23" style="margin-right: 6px;vertical-align: -4px"/>
                  搜索</a></li>
                <li><a class="navbar-item navbar-title_a"><img src="/img/_navigation/accessible_nav_icon.png" width="23" height="23" style="margin-right: 6px;vertical-align: -4px;"/>
                  无障碍</a></li>
              </ul>
            </div>
            <div class="column"><a class="navbar-item navbar-back_announcement">#(P)22-0502 未来可能发生的域名争议</a></div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>
