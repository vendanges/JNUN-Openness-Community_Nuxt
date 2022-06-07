<template>
  <main>
    <svg width="331" height="1230" viewBox="0 0 331 1230" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M35.7373 19.5H330.5V1226.74L0.5 876.801V62.6781L35.7373 19.5Z" stroke="#D9DADD"/>
      <path d="M160 20L175 70.75L160 121.5L121 160.5H1.5" stroke="#D9DADD"/>
      <path d="M331 161H120L160.5 120.5H331V161Z" fill="#006FEA" style="cursor: pointer;"/>
      <path d="M234.663 15L235.833 3.99H234.243L233.103 15H234.663ZM235.827 15H237.402L238.287 6.57L243.372 15H244.947L246.087 3.99H244.527L243.672 12.15L238.707 3.99H236.982L235.827 15ZM246.081 15H247.641L248.166 9.96H253.476L253.641 8.4H248.331L248.646 5.535H254.346L254.871 3.99H247.221L246.081 15ZM256.055 3.99L254.87 15H262.64L263.825 3.99H256.055ZM257.465 5.535H262.1L261.26 13.455H256.64L257.465 5.535ZM273.969 3.99L273.354 10.065H279.489L279.144 13.455H272.814L273.024 15H280.524L281.199 8.52H275.094L275.394 5.535H279.939L279.849 6.39H281.394L281.649 3.99H273.969ZM284.392 3.99H282.832L281.647 15H289.402L290.587 3.99H289.027L288.022 13.455H283.402L284.392 3.99ZM290.583 15H298.638L299.163 10.005L298.713 9.225L299.328 8.46L299.793 3.99H291.738L290.583 15ZM292.833 8.46L293.133 5.535H298.053L297.753 8.46H292.833ZM292.308 13.455L292.668 10.005H297.588L297.228 13.455H292.308ZM308.947 3.99L305.092 10.995L302.707 3.99H300.952L299.797 15H301.357L302.152 7.395L303.967 12.675H305.872L308.767 7.395L307.957 15H309.547L310.687 3.99H308.947ZM312.241 15L313.411 3.99H311.821L310.681 15H312.241ZM316.435 15H318.025L319.015 5.535H322.765L322.9 3.99H313.87L313.705 5.535H317.44L316.435 15Z" fill="#D9DADD"/>
      <path d="M39 5L43.5 9.5L39 14" stroke="#D9DADD" stroke-width="2"/>
      <path d="M47 5L51.5 9.5L47 14" stroke="#D9DADD" stroke-width="2"/>
      <path d="M55 5L59.5 9.5L55 14" stroke="#D9DADD" stroke-width="2"/>
      <path d="M2 22H34L2 60.5V22Z" stroke="#D9DADD" stroke-opacity="0.24"/>
      <path d="M10 30H18L10 40V30Z" fill="#006FEA"/>
      <path d="M5.5 882V900.5L313 1229V1208.5" stroke="#D9DADD" stroke-width="0.5"/>
    </svg>
    <sidebar-body>
      <p class="openness_proposal-main_idea_update">提交提案与想法</p>
      <img src="/img/openness-proposal/sidebar-body_opennesssidea.png" class="openness_proposal-main_idea">
      <img src="/img/openness-proposal/sidebar-body_proposal.png" class="openness_proposal-main_proposal">
    </sidebar-body>
    <sidebar-con>
      <p>联合现在的目标和使命是<br>面向网络推动互联网的正义与开放和创新</p>
      <descript><p>对此，我们面向网络征集对此有关的提案，并在之后数年时间内对提案进行实现。当提案数据超出 <a href="">影响因子</a> 后，联合现在（大会或机构负责人、理事会成员等）将会做出回应，并添加至工程计划中。</p></descript>
      <!-- Q&A -->
      <div class="layui-collapse" lay-accordion="" style="background: white;">
        <div v-for="(item, index) in QAList" class="item" :key="index" style="cursor: pointer;">
          <details :open="index === 0">
            <summary class="layui-colla-item">
              <h2 class="layui-colla-title">{{ item.title }}</h2>
            </summary>
            <div class="content">
              <div v-html="item.content"></div>
            </div>
          </details>
        </div>
      </div>
    </sidebar-con>
  </main>
</template>

<script>
  export default {
    name: "Siderbar",
    data() {
      return {
        QAList: [
        {
            title: '这些提案会被删除或隐藏',
            content: "<sidebar-condesc>包含对特定个体或群体有害的内容<call>(例如针对暴力、挑逗、仇恨、人身攻击、违反人类道德、伦理、色情)</call> 的提案会被删除。</sidebar-condesc>" +
              "<sidebar-condesc>与<call>内容相同的重复提案将</call>会被合并、隐藏、 删除， 只留下一份提案。</sidebar-condesc>" +
              "<sidebar-condesc><call>涵盖个人信息 、 虚假信息或诽谤他人</call>的内容将会被理事会删除或隐藏、编辑部分信息。</sidebar-condesc>"
          },
          {
            title: '以下提案可能很难实现或无法执行',
            content: "<sidebar-condesc>null</sidebar-condesc>"
          }
        ]
      }
    },
    methods() {
      layui.use(['dropdown', 'util', 'layer'], function(){
        var element = layui.element;
        var layer = layui.layer;

        //监听折叠
        element.on('collapse(test)', (data) => {
          layer.msg('展开状态：'+ data.show);
        });
      });
    }
  }
</script>

<style>
summary::marker {
  content: none;
}
summary:after {
  content: "";
  float: right;
  margin-top: -17px;
  margin-right: 12px;
  position: relative;
  background-image: url(/img/style/layui-colla-item.png);
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center left;
  width: 13px;
  height: 6px;
}
details[open] summary:after {
  content: "";
  float: right;
  margin-top: -17px;
  margin-right: 12px;
  position: relative;
  background-image: url(/img/style/layui-colla-item.png);
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center left;
  width: 13px;
  height: 6px;
  transform: rotate(-180deg);
}
</style>
