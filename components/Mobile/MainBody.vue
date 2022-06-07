<template>
  <main>
    <!-- 移动端显示 -->
    <mobile>
      <hello>Hi, 请登录</hello>
      <navs>
        <li><this>提案</this></li>
        <li>大会</li>
        <li>计划</li>
      </navs>
      <banner>
        <banner-title><p>42 个负责提案<span>查看全部 <icon style="font-weight: bold">></icon></span></p></banner-title>
        <!-- Swiper -->
        <div class="swiper mySwiperc">
          <div class="swiper-wrapper">
            <div class="swiper-slide" style="background-image: url(/img/mobile/banner/banner-swiper_1653403146.png);background-repeat: no-repeat;background-position: left center;background-size: 120%;margin-right: 30px;">
              <tops>
                <img src="/img/mobile/banner/banner-logo.png" style="float: left;width: 6rem;">
                <data>2022<br><span>4/17</span></data>
                <!-- 开发计划标题 -->
                <div class="swiper-openness_engineering_group_platform_description">
                  <p class="swiper-openness_engineering_group_platform_description_this">OEG<br><span>工程计划组</span><descript>工程计划</descript></p>
                  <p class="swiper-openness_engineering_group_platform_description_next">OCT<br><span>TW224-4/1</span><descript>OPENNESS COMMUNITY & IDEA  开发申报</descript></p>
                </div>
                <logo style="background-image: url(/img/mobile/banner/banner-swiper_1653401550.png)" />
              </tops>
              <infos>
                <titles>CURTURAL INNOVATION<br></titles>
                <desc>VIRTUAL CHARACTERS</desc>
                <div class="swiper-openness_engineering_group_schedule_rate">
                  <ul>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li class="this"></li>
                  </ul>
                </div>
              </infos>
            </div>
            <div class="swiper-slide" style="background-image: url(/img/mobile/banner/banner-swiper_qianqu.png);background-repeat: no-repeat;background-position: left center;background-size: 120%;margin-right: 30px;">
              <tops>
                <img src="/img/mobile/banner/banner-logo.png" style="float: left;width: 6rem;">
                <data>2022<br><span>4/17</span></data>
                <!-- 开发计划标题 -->
                <div class="swiper-openness_engineering_group_platform_description">
                  <p class="swiper-openness_engineering_group_platform_description_this">OEG<br><span>工程计划组</span><descript>工程计划</descript></p>
                  <p class="swiper-openness_engineering_group_platform_description_next">OCT<br><span>TW224-4/1</span><descript>OPENNESS COMMUNITY & IDEA  开发申报</descript></p>
                </div>
                <logo style="background-image: url(/img/mobile/banner/banner-swiper_qianqulogo.png)" />
              </tops>
              <infos>
                <titles>CURTURAL INNOVATION<br></titles>
                <desc>VIRTUAL CHARACTERS</desc>
                <div class="swiper-openness_engineering_group_schedule_rate">
                  <ul>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li class="this"></li>
                  </ul>
                </div>
              </infos>
            </div>
            <div class="swiper-slide" style="background-image: url(/img/mobile/banner/banner-swiper_jiaolong.png);background-repeat: no-repeat;background-position: left center;background-size: 120%;margin-right: 30px;">
              <tops>
                <img src="/img/mobile/banner/banner-logo.png" style="float: left;width: 6rem;">
                <data>2022<br><span>4/17</span></data>
                <!-- 开发计划标题 -->
                <div class="swiper-openness_engineering_group_platform_description">
                  <p class="swiper-openness_engineering_group_platform_description_this">OEG<br><span>工程计划组</span><descript>工程计划</descript></p>
                  <p class="swiper-openness_engineering_group_platform_description_next">OCT<br><span>TW224-4/1</span><descript>OPENNESS COMMUNITY & IDEA  开发申报</descript></p>
                </div>
                <logo style="background-image: url(/img/mobile/banner/banner-swiper_jiaolonglogo.png)" />
              </tops>
              <infos>
                <titles>CURTURAL INNOVATION<br></titles>
                <desc>VIRTUAL CHARACTERS</desc>
                <div class="swiper-openness_engineering_group_schedule_rate">
                  <ul>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li class="this"></li>
                  </ul>
                </div>
              </infos>
            </div>
            <div class="swiper-slide" style="opacity: 0;"></div>
          </div>
        </div>
        <!-- Initialize Swiper -->
        <script>
          var swiper = new Swiper(".mySwiperc", {
            slidesPerView: "auto",
            spaceBetween: 30,
            pagination: {
              el: ".swiper-paginationc",
              clickable: true,
            },
          });
        </script>
      </banner>
      <!-- 主要内容 -->
      <main-con>
        <titles>提案进度</titles>
        <center>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennessidea.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/jiaolong.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column this"></div>
                <div class="column this"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/qinglou.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/qianqu.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
                <div class="column this"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
          <list>
            <img src="/img/mobile/main-con/opennesscommunity.png" class="main-con_list_logo">
            <list-main>
              <names>OPENNESS COMMUNITY <span>JOINT NOWADAYS</span></names>
              <div class="columns">
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
                <div class="column"></div>
              </div>
            </list-main>
            <p class="main-con_next">></p>
          </list>
        </center>
      </main-con>
      <bottom_information>
        <layout class="con-md-3">
          <div>
            <img src="/img/mobile/bottom-information/home.png" class="bottom_information-icon">
            <p class="this">首页</p>
          </div>
          <div>
            <img src="/img/mobile/bottom-information/strategy.png" class="bottom_information-icon">
            <p>策略</p>
          </div>
          <div>
            <img src="/img/mobile/bottom-information/conference.png" class="bottom_information-icon">
            <p>会议</p>
          </div>
        </layout>
      </bottom_information>
    </mobile>
  </main>
</template>

<script>
export default {
  name: "MainBody"
}
</script>

<style scoped>

</style>
