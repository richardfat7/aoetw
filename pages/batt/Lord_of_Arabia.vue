<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>阿拉伯之主</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            <b>阿拉伯之主</b>為<nuxt-link to="/batt/Saladina"
              >沙拉丁戰役</nuxt-link
            >的第二關劇情關卡，此關描述法國十字軍騎士<nuxt-link
              to="/units/hero/Reynald_de_Chatillon"
              >沙底隆的雷諾</nuxt-link
            >襲擊紅海的<nuxt-link to="/batt">戰役</nuxt-link>。
          </p>
        </div>
        <h2>玩家</h2>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>基本資訊</h3>
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc1" width="14%">起始時代：</td>
              <td class="tc2" width="14%">
                <nuxt-link to="/techs/age/Feudal_Age">封建時代</nuxt-link>
              </td>
              <td class="tc1" width="14%">起始資源：</td>
              <td class="tc2">
                200<nuxt-link to="/resource/Wood">木頭</nuxt-link
                >／500<nuxt-link to="/resource/Food">食物</nuxt-link
                >／200<nuxt-link to="/resource/Gold">黃金</nuxt-link
                >／100<nuxt-link to="/resource/Stone">石頭</nuxt-link>
              </td>
              <td class="tc1" width="14%">人口上限：</td>
              <td class="tc2" width="5%">75</td>
            </tr>
          </table>

          <h3>AI</h3>

          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc4" colspan="4" style="background: #2980b9;">
                玩家本身
              </td>
            </tr>
            <tr>
              <td class="tc6">
                <div class="p3"></div>
                玩家1
              </td>
              <td class="tc6" colspan="3">
                <nuxt-link to="/civs/Saracens">薩拉森人</nuxt-link>（綠色）
              </td>
            </tr>
            <tr>
              <td class="tc4" colspan="4" style="background: #27ae60;">同盟</td>
            </tr>
            <tr>
              <td class="tc6" width="12%">
                <div class="p8"></div>
                玩家2
              </td>
              <td class="tc6" width="38%">麥地那（橘色）薩拉森</td>
              <td class="tc6" width="12%">
                <div class="p4"></div>
                玩家3
              </td>
              <td class="tc6" width="38%">阿魁巴（黃色）薩拉森</td>
            </tr>
            <tr>
              <td class="tc4" colspan="4" style="background:#ea6153;">敵對</td>
            </tr>
            <tr>
              <td class="tc6">
                <div class="p1"></div>
                玩家4
              </td>
              <td class="tc6">
                雷諾的海盜（藍色）<nuxt-link to="/civs/Franks"
                  >法蘭克</nuxt-link
                >
              </td>
              <td class="tc6">
                <div class="p5"></div>
                玩家5
              </td>
              <td class="tc6">雷諾的武士（藍綠色）法蘭克</td>
            </tr>
            <tr>
              <td class="tc6">
                <div class="p2"></div>
                玩家6
              </td>
              <td class="tc6" colspan="3">雷諾的強盜 （紅色） 法蘭克</td>
            </tr>
          </table>

          <br />
          <dl class="dl-horizontal">
            <dt>開場：</dt>
            <dd>
              4位<nuxt-link to="/units/Camel">駱駝騎兵</nuxt-link
              >、3位<nuxt-link to="/units/Villager">村民</nuxt-link
              >、3位<nuxt-link to="/units/Light_Cavalry">輕騎兵</nuxt-link>。
            </dd>
            <dt>大地之母單位：</dt>
            <dd>無。</dd>
          </dl>
          <h2>主要任務</h2>
          <div class="hrn1"></div>
          <div class="n1">
            <ol>
              <li>
                要打敗雷諾的武士、強盜、和海盜，以防止他們破壞你同盟的<nuxt-link
                  to="/building/Town_Center"
                  >城鎮中心</nuxt-link
                >。
              </li>
              <li>不能讓阿魁巴和麥地那這兩個盟友被打敗。</li>
            </ol>
          </div>
        </div>
        <h2>任務提示</h2>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>薩拉森首都已經所剩無幾了。你必須建立自己的基地與軍隊。</li>
            <li>
              保持你與同盟國之間的貿易路線暢通，他們將會酬謝你。並指派單位去護衛同盟國的<nuxt-link
                to="/units/Trade_Cart"
                >貿易車隊</nuxt-link
              >。
            </li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                阿拉伯之主
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Lord_of_arabia.png" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">情景信息</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">版本</td>
            <td class="unit4">
              <nuxt-link to="/games/aok">帝王世紀</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">戰役</td>
            <td class="unit4">
              <nuxt-link to="/batt/Saladina">沙拉丁</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3"><nuxt-link to="/civs">文明</nuxt-link></td>
            <td class="unit4">
              <nuxt-link to="/civs/Saracens">薩拉森人</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                戰役關卡編號
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">章節</td>
            <td class="unit4">
              <nuxt-link to="/games/aok">帝王世紀</nuxt-link>第三章之二
            </td>
          </tr>
          <tr>
            <td class="unit3">上一關</td>
            <td class="unit4">
              <nuxt-link to="/batt/An_Arabian_Knight">阿拉伯騎士</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">下一關</td>
            <td class="unit4">
              <nuxt-link to="/batt/The_Horns_of_Hattin">海丁的號角</nuxt-link>
            </td>
          </tr>
        </table>

        <div class="thanks">感謝！此頁面由裕暉、亞諭協助編輯。</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allbatt',
  components: {}
}
</script>
<style></style>
