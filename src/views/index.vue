<template>
  <div>
    <nav class="ui inverted attached segment m-padded-tb-mini">
      <div class="ui container">
        <div class="ui inverted secondary stackable menu">
          <h2 class="ui teal header item">Blog</h2>
          <a href="#" class="m-item item m-mobile-hide"
            ><i class="home icon"></i> 首页</a
          >
          <a href="#" class="m-item item m-mobile-hide"
            ><i class="idea icon"></i> 分类</a
          >
          <a href="#" class="m-item item m-mobile-hide"
            ><i class="tags icon"></i> 标签</a
          >
          <a href="#" class="m-item item m-mobile-hide"
            ><i class="clone icon"></i> 归档</a
          >
          <a href="#" class="m-item item m-mobile-hide"
            ><i class="info icon"></i> 关于我</a
          >
          <div class="right m-item item m-mobile-hide">
            <div class="ui icon inverted transparent input">
              <input type="text" placeholder="搜索..." />
              <i class="search link icon"></i>
            </div>
          </div>
        </div>
      </div>
      <a
        href="#"
        class="ui menu toggle black icon button m-right-top m-mobile-show"
      >
        <i class="sidebar icon"></i>
      </a>
    </nav>

    <!--中间内容-->
    <div class="m-container-small m-padded-tb-large">
      <div class="ui container">
        <div class="ui top attached segment">
          <div class="ui horizontal link list">
            <div class="item">
              <img
                src="https://unsplash.it/100/100?image=1005"
                alt=""
                class="ui avatar image"
              />
              <div class="content"><a href="#" class="header">王思涵</a></div>
            </div>
            <div class="item"><i class="calendar icon"></i>2020-1-1</div>
            <div class="item"><i class="eye icon"></i>2345</div>
          </div>
        </div>
        <div class="ui attached segment">
          <!--图片-->
          <img
            src="https://unsplash.it/800/450?image=1005"
            alt=""
            class="ui fluid rounded image"
          />
        </div>
        <div class="ui attached padded segment">
          <!--内容-->
          <div class="ui right aligned basic segment">
            <div class="ui orange basic label">原创</div>
          </div>

          <h2 class="ui center aligned header">这是一个大大的标题</h2>
          <br />
          <!--正文-->
          <div id="content" class="m-padded-lr m-padded-tb-large">
            <p>
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
            </p>
            <h2>这是h2标题</h2>
            <p>
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
            </p>
            <h2>这是h2标题</h2>
            <p>
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
            </p>
            <h2>这是h2标题</h2>
            <p>
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
              这里是p标签的正文内容 这里是p标签的正文内容 这里是p标签的正文内容
            </p>
          </div>

          <!--标签-->
          <div class="m-padded-lr">
            <div class="ui basic teal left pointing label">方法论</div>
          </div>

          <!--赞赏-->
          <div class="ui center aligned basic segment">
            <button id="payButton" class="ui orange basic circular button">
              赞赏
            </button>
          </div>
          <div class="ui payQR flowing popup transition hidden">
            <div class="ui orange basic label">
              <div class="ui images" style="font-size: inherit !important">
                <div class="image">
                  <img
                    src="https://cnhyk.oss-cn-beijing.aliyuncs.com/wechat.jpg"
                    alt=""
                    class="ui rounded bordered image"
                    style="width: 120px"
                  />
                  <div>支付宝</div>
                </div>
                <div class="image">
                  <img
                    src="https://cnhyk.oss-cn-beijing.aliyuncs.com/wechat.jpg"
                    alt=""
                    class="ui rounded bordered image"
                    style="width: 120px"
                  />
                  <div>微信</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="ui attached positive message">
          <!--博客信息-->
          <div class="ui grid">
            <div class="eleven wide column">
              <ul class="list">
                <li>作者：大西瓜</li>
                <li>发表时间</li>
                <li>版权声明</li>
                <li>米西米西划不拉几</li>
              </ul>
            </div>
            <div class="five wide column">
              <img
                src="https://cnhyk.oss-cn-beijing.aliyuncs.com/wechat.jpg"
                alt=""
                class="ui right floated rounded bordered image"
                style="width: 110px"
              />
            </div>
          </div>
        </div>
        <div class="ui bottom attached segment">留言区</div>
      </div>
    </div>

    <br />
    <br />
    <br />
    <!--底部footer-->
    <footer class="ui inverted vertical segment m-padded-tb-massive">
      <div class="ui center aligned container">
        <div class="ui inverted divided stackable grid">
          <div class="three wide column">
            <div class="ui inverted link list">
              <div class="item">
                <h4 class="ui inverted header m-text-thin m-text-spaced">
                  我的微信
                </h4>
                <br />
                <img
                  src="https://cnhyk.oss-cn-beijing.aliyuncs.com/wechat.jpg"
                  class="ui rounded image"
                  alt=""
                  style="width: 110px"
                />
              </div>
            </div>
          </div>
          <div class="three wide column">
            <h4 class="ui inverted header m-text-thin m-text-spaced">
              最新博客
            </h4>
            <div class="ui inverted link list">
              <a href="#" class="item">用户故事（User Story）</a>
              <a href="#" class="item">用户故事（User Story）</a>
              <a href="#" class="item">用户故事（User Story）</a>
            </div>
          </div>
          <div class="four wide column">
            <h4 class="ui inverted header m-text-thin m-text-spaced">
              联系方式
            </h4>
            <div class="ui inverted link list">
              <a href="#" class="item">E-mail：messageutil@163.com</a>
              <a href="#" class="item">QQ:1746987387</a>
              <a
                href="https://github.com/wangsihan1"
                class="item"
                target="_blank"
                >Github：wangsihan1</a
              >
            </div>
          </div>
          <div class="six wide column">
            <h4 class="ui inverted header m-text-thin m-text-spaced">About</h4>
            <p class="m-text-thin m-text-spaced m-opacity-mini">
              梅花不争春，独开汉水滨边，吹香弄影，黯淡了一山春色，成就了一世美名。
            </p>
          </div>
        </div>
        <div class="ui inverted section divider"></div>
        <!--分割线-->
        <p class="m-text-thin m-text-spaced m-opacity-mini">
          Copyright © 2020 - 2021 blog Designed by WSH
        </p>
        <p>
          <a
            class="m-text-thin m-text-spaced m-opacity-mini"
            href="https://beian.miit.gov.cn/"
            style="color: #ffffff"
            target="_blank"
            >豫ICP备19019066号</a>
        </p>
      </div>
    </footer>
  </div>
</template>

<script src="https://cdn.jsdelivr.net/npm/jquery@3.2/dist/jquery.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.js"></script>
<script>
export default {
  data () {
    return {
    }
  },
  methods: {
  }
}
</script>

<style>
</style>
