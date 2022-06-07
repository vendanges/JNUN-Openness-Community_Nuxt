<template>
  <main>
    <div class="tabs is-centered">
      <ul>
        <li v-for="(item, index) in list" :key="index" :class="active === item.id ? 'is-active is-active_this' : 'active_clicke'" id="openness_proposal_li" @click="handleClick(item.id)">
          <a style="text-align: -webkit-left;display: block;">
            <p class="active-mouse_over">
              <span :class="active === item.id ? 'tabs-title' : 'istabs'" style="display: block">{{ item.title }}</span> <!-- 我知道 block 可以换，，问题是在那个地方-->
              <span :class="active === item.id ? 'tabs-title_info' : 'istabs-info'">{{ item.titleEn }}</span>
            </p>
          </a>
        </li>
      </ul>
    </div>
    <page-openness-proposal v-if="active === 1" />
    <page-openness-council v-if="active === 2" />
    <page-openness-engineering-group v-if="active === 3" />
    <mobile-main-body />
  </main>
</template>

<script>
  export default {
    name: "Tabs",
    data() {
      return {
        active: 1,
        list: [
          { id: 1, title: '开放性提案', titleEn: 'OPENNESS PROPOSAL' },
          { id: 2, title: '开放性决策', titleEn: 'OPENNESS COUNCIL' },
          { id: 3, title: '执行的提案', titleEn: 'ENGINEERING GROUP' },
        ]
      }
    },
    methods: {
      // 点击事件
      handleClick(id) {
        this.active = id
      }
    },
  }
</script>

<style>
.tabs-body {
  display: none;
}
</style>
