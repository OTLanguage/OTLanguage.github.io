<template>
  <div class="main-top" id="main-top">
    <h1 class="main">OTLanguage 공식 페이지</h1>
    <ul class="otl-menu">
      <li>
        <div v-on:click="scroll('#otl')" v-html="otl"/>
        <br>OTLanguage
      </li>
      <li>
        <div v-on:click="scroll('#poison')" v-html="poison"/>
        <br>Poison
      </li>
      <li>
        <div v-on:click="scroll('#music')" v-html="music"/>
        <br>Music
      </li>
    </ul>
  </div>

  <div class="main-middle" style="padding-top: 50px">
    <div class="text-style">
      <h1 id="otl">OTLanguage</h1><hr>
      <h3> - 이모티콘으로 이루어진 난해한 프로그래밍 언어</h3>
      <p>
        OTLanguage는 주로 이모티콘으로 이루어진 난해한 언어 입니다.<br><br>
        OTLanguage라는 단어는 OTL이라는 절망하는 이모티콘과 Language라는 언어라는 뜻을 합치고 중복되는 L은 1개로 만들어서 OTLanguage가 되었습니다.<br/>
        이 언어는 기본 타입이 문자열이기 때문에 큰 따옴표(")나 작은 따옴표(')를 사용하지 않는 등의 특징이 있습니다.
      </p>
      <otl-menu main-link="/OTLanguage/" link1="introduce" link2="github" link3="download" link4="grammar" link5="information"/>
    </div>
    <div class="sub-banner">
      <otl-code class="otl-code">
        <otl-o>ㅇㅁㅇ</otl-o>&nbsp;변수<otl-g>:</otl-g>Hello<br/>
        <otl-p>ㅅㅁㅅ</otl-p>&nbsp;<otl-g>:</otl-g>변수&nbsp;World<br/>
        <otl-p>ㅆㅁㅆ</otl-p>&nbsp;HelloWorld<br/><br/>
        <otl-o>ㅇㅈㅇ</otl-o>&nbsp;정수<otl-g>:</otl-g>0<br/>
        0<otl-g>^</otl-g>10<otl-g>^</otl-g>1&nbsp;{<br/>
        &nbsp;&nbsp;&nbsp;정수<otl-g>:</otl-g>&nbsp;<otl-g>:</otl-g>정수&nbsp;&nbsp;<otl-g>ㅇ+ㅇ</otl-g>&nbsp;1<br/>
        &nbsp;&nbsp;&nbsp;0<otl-g>^:</otl-g>정수&nbsp;<otl-g>^</otl-g>1&nbsp;{<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<otl-p>ㅅㅁㅅ</otl-p>&nbsp;*<br/>
        &nbsp;&nbsp;&nbsp;}<br/>
        &nbsp;&nbsp;&nbsp;<otl-p>ㅆㅁㅆ</otl-p><br/>}
      </otl-code>
      <a class="banner" href="/OTLanguage"><img src="../assets/banner/OTLanguage-banner.png" alt="OTLanguage"></a>
    </div>
    <fieldset style="width: 90%; margin: 50px auto;">
      <legend style="font-size: 150%;">동작 구조</legend>
      <img src="../assets/svg/movement-OTL.svg" alt="movement" style="width: 100%">
    </fieldset>
    <!-- OTLanguage -->

    <div class="main-middle">
      <div class="text-style">
        <h1 id="poison">Poison</h1><hr>
        <h3> - OTLanguage로 구현하는 웹 프레임워크</h3>
        <p>
          Poison은 OTLanguage으로 구현하는 웹프레임워크 입니다.<br>
          해당 프레임워크는 영어 뜻 그대로 독이라는 뜻을 가지고 있습니다.
        </p>
        <otl-menu main-link="/Poison/" link1="introduce" link2="github" link3="download" link4="grammar" link5="information"/>
      </div>
    </div>
    <div class="sub-banner">
      <otl-code class="otl-code">
        <otl-o>&lt;ㅇㅅㅇ&gt;&nbsp;</otl-o>소개페이지:OTLanguage 페이지에 어서오세요.<br/>
        /&nbsp;<otl-p>&lt;ㅇㅅㅇ&lt;</otl-p>&nbsp;index.html<br/>
        /sub&nbsp;<otl-p>&lt;ㅇㅅㅇ&lt;</otl-p>&nbsp;sub.html<br/>
        <otl-o>ㅇㅁㅇ</otl-o>&nbsp;변수<otl-g>:</otl-g>_<br/>
        POST/<otl-p>&gt;ㅇㅅㅇ&gt;</otl-p>[변수:name]&nbsp;{<br/>
        &nbsp;&nbsp;&nbsp;ㅆㅁㅆ POST 실행<br/>
        &nbsp;&nbsp;&nbsp;ㅆㅁㅆ 받은 값 = :변수_<br/>
        }<br/>
        GET/<otl-p>&gt;ㅇㅅㅇ&gt;</otl-p>[변수:name]&nbsp;{<br/>
        &nbsp;&nbsp;&nbsp;ㅆㅁㅆ GET 실행<br/>
        &nbsp;&nbsp;&nbsp;ㅆㅁㅆ 받은 값 = :변수_<br/>
        }<br/>
        <otl-p>&lt;&lt;ㅇㅅㅇ&gt;&gt; 9090</otl-p><br/>
      </otl-code>
      <a class="banner" href="/Poison"><img src="@/assets/banner/Poison-banner.png" alt="OTLanguage"></a>
    </div>
    <!-- Poison -->
    <div class="main-middle">
      <div class="text-style" style="margin-top: 50px">
        <h1 id="music">Music</h1><hr>
        <h3> - OTLanguage로 만드는 음악</h3>
        <p>Music은 OTLanguage로 구현하는 음악 프로그램입니다.</p>
        <otl-menu main-link="/Music/" link1="introduce" link2="github" link3="download" link4="grammar" link5="information"/>
      </div>
    </div>
    <div class="sub-banner">
      <otl-code class="otl-code">
        <otl-p>ㅇ도ㅇ&nbsp;ㅇ레ㅇ</otl-p><br/>
        <br/>
        <otl-p>ㅇ파ㅇ</otl-p><br/>
        <otl-p>ㅇ레ㅇ</otl-p><br/>
        <otl-p>ㅇ도ㅇ&nbsp;ㅇ레ㅇ</otl-p><br/>
        <otl-p>ㅇ도ㅇ&nbsp;ㅇ레ㅇ</otl-p>
        <otl-p>ㅇ미ㅇ</otl-p><br/>
        <otl-p>ㅇ미ㅇ</otl-p><br/>
        <br/>
        <br/>
        <otl-p>ㅇ솔ㅇ</otl-p>
      </otl-code>
      <a class="banner" href="/Music"><img src="@/assets/banner/Music-banner.png" alt="OTLanguage"></a>
    </div>
    <!-- Music -->
    <div style="padding-bottom: 100px"/>
  </div>

</template>

<script>
import OtlCode from '@/components/edit/otl-code'
import OtlP from '@/components/code-color/otl-p'
import OtlO from '@/components/code-color/otl-o'
import OtlG from '@/components/code-color/otl-g'
import OtlMenu from '@/components/edit/otl-menu'

export default {
  name: "otl-main",
  components: {
    OtlCode, OtlP,
    OtlO, OtlG,
    OtlMenu
  },
  data() {
    return {
      otl: `<svg width="100" height="100" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg"><path d="M 4.6223162,33.419737 C 23.529722,22.603181 62.519305,0.4593497 62.519305,0.4593497 75.596281,-2.7323659 80.285458,11.424632 72.125173,20.792819 L 21.351335,49.674139 36.446256,115.59604 100.59968,126.21607 127.35886,62.754918 95.91111,33.096525 69.151932,59.258068 85.276042,82.829355 99.799195,68.453469 c 9.853675,-4.382093 18.419255,2.825117 13.265235,16.707124 L 89.507202,109.50895 c -3.006336,2.17594 -7.229026,2.24249 -11.435544,-0.38853 L 46.280828,62.884427 c -1.968627,-4.058066 -2.32237,-8.116119 0.686133,-12.174185 L 91.336895,8.2301057 c 2.70641,-2.3723256 5.412819,-1.2271521 8.119229,-0.1295654 L 146.68493,50.580677 c 3.97909,4.619282 3.93444,9.238565 2.17275,13.857848 L 115.35153,144.6068 c -2.06568,2.79992 -3.72211,5.94748 -9.83457,5.31003 L 27.98395,137.22459 c -2.855818,-0.38596 -5.645366,-0.15646 -9.377146,-8.67735 L 0.40600468,47.907599 C -0.70748043,41.932946 0.39670874,36.94848 4.6223162,33.419737 Z"/></svg>`,
      poison: `<svg width="100" height="100" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg"><g transform="matrix(0.88613759,0,0,0.88613759,-18.968351,-53.588852)"><path d="m 104.33842,60.476284 c -6.674347,-0.07634 -7.381359,2.518193 -8.773443,4.809769 L 82.355263,95.806362 c -2.093121,6.968838 0.418251,8.401648 2.355338,10.534228 l 24.308009,21.15994 c 5.20759,4.01012 8.57532,2.8833 11.71571,1.10525 l 27.84483,-16.838 c 2.19991,-1.74312 4.67717,-2.94568 4.24571,-9.74912 l -7.78253,-32.79942 c -0.50062,-3.866848 -2.71122,-6.322734 -8.02644,-6.212301 l -32.01431,-2.51541 c -0.22795,-0.0081 -0.44786,-0.01279 -0.66316,-0.01525 z m 3.9713,16.212961 22.33379,2.05044 5.03845,21.784975 -19.26957,11.95201 L 99.421939,97.612883 Z M 94.482588,124.44392 c -0.572273,-0.002 -1.198059,0.0642 -1.882746,0.19819 l -21.076087,1.33393 c -5.465118,0.78843 -6.540923,3.84174 -7.508118,6.95168 l -4.504871,18.24053 c -1.05856,6.24557 0.801944,9.24889 3.727381,11.0678 l 18.187177,11.06781 c 3.466692,0.97715 6.902325,1.73917 9.787231,-1.50163 l 16.243455,-13.62894 c 1.67629,-2.59436 3.26215,-5.2445 1.16623,-10.45039 l -8.12553,-19.30005 c -1.3543,-2.11311 -2.923844,-3.96727 -6.014122,-3.97893 z m -6.219923,16.04527 3.674024,9.34513 -7.675812,6.39524 -7.896863,-5.28236 2.332471,-9.51282 z m 37.197575,18.37774 c -1.0894,-0.004 -2.32127,0.27863 -3.78073,1.03665 l -13.92623,7.08126 c -4.16427,2.29453 -3.25381,5.09224 -3.46059,7.78253 l 2.16477,14.3607 c 0.59982,4.93996 3.41438,6.46796 6.49434,7.58435 l 13.52223,2.08855 c 3.21196,-0.0688 6.35956,0.74013 9.87108,-3.42248 l 7.20322,-14.31497 c 0.90201,-2.75116 1.89895,-5.49188 -1.18148,-8.65149 l -11.60138,-11.60137 c -1.66016,-0.87129 -3.22543,-1.93639 -5.30523,-1.94373 z m -1.50162,17.98899 2.4773,2.27912 -1.60834,3.22429 -3.2243,-0.54881 -0.59455,-3.30052 z m -23.218,18.74362 c -1.08654,0.0475 -2.207598,0.30358 -3.369121,0.83847 l -10.61808,5.976 c -3.273613,2.07973 -3.949553,5.53115 -3.460594,9.59667 l 2.561145,11.17452 c 1.654399,5.15528 3.996295,4.40047 6.136076,5.38146 l 11.639484,1.18148 c 3.08099,-0.006 6.21222,0.19721 8.37708,-3.57494 l 5.50341,-12.31026 c 0.61509,-2.51695 0.63881,-5.03691 -1.14336,-7.55385 l -10.4199,-9.47471 c -1.6749,-0.80482 -3.39523,-1.31406 -5.20614,-1.23484 z"/></g></svg>`,
      music: `<svg width="100" height="100" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg"><path d="M 58.821406,8.6355086e-4 C 57.193367,0.01264868 55.56055,0.46813536 54.217817,1.3610079 52.836892,2.2580695 51.76262,3.518876 50.869752,4.8555336 34.481287,26.407452 18.081514,47.961493 1.6950502,69.514718 0.65334767,71.079738 -0.00900351,72.896378 9.2508044e-5,74.766967 -0.00127889,76.716353 0.71222857,78.629287 1.7787517,80.270322 8.3738382,89.141778 14.957803,98.016108 21.55326,106.8873 c -0.01543,0.0118 -0.02636,0.03 -0.04189,0.0418 10.092441,13.21253 20.184715,26.42147 30.279061,39.63253 1.205486,1.39075 2.807944,2.49697 4.624514,3.01325 2.108325,0.61614 4.375751,0.49572 6.507802,0.0632 1.349626,-0.26827 2.654268,-0.6981 3.954904,-1.12996 25.143089,-7.8559 50.292119,-15.70857 75.436089,-23.5619 2.01329,-0.59118 3.97373,-1.50829 5.44061,-2.99232 1.17923,-1.17713 1.93785,-2.71612 2.1553,-4.33153 0.12353,-0.82409 0.10286,-1.6622 0.0418,-2.4901 -0.0289,-26.885832 -0.0525,-53.781327 -0.0836,-80.667049 -0.15032,-1.838213 -0.41784,-3.730147 -1.33923,-5.377803 -0.72617,-1.318723 -1.90254,-2.366618 -3.28527,-3.034169 -0.98214,-0.488011 -2.06487,-0.789636 -3.13882,-1.025339 -9.50994,-2.938783 -19.01127,-5.891982 -28.52133,-8.830477 -0.38966,-0.122008 -0.78211,-0.23372 -1.1718,-0.355729 C 96.821447,10.960366 81.254521,6.072658 65.664014,1.1936056 63.422362,0.64624086 61.158492,-0.02745291 58.821406,8.6355086e-4 Z M 63.236673,19.210292 c 12.787977,4.036899 25.5682,8.079138 38.356257,12.115748 -12.917288,2.766094 -25.836417,5.541669 -38.75385,8.307347 -1.697989,0.603505 -3.364777,1.45198 -4.519888,2.824914 -0.847464,0.996379 -1.3525,2.244242 -1.611246,3.494526 -0.05464,10.819186 -0.112392,21.635946 -0.167457,32.45514 -3.595497,0.239025 -7.202802,0.876926 -10.504558,2.301786 -2.740803,1.177139 -5.234541,2.950139 -7.010011,5.294105 -1.732099,2.253016 -2.718957,5.002176 -2.950482,7.784206 -0.02518,0.29806 -0.03107,0.600614 -0.04189,0.899849 C 30.977055,88.176964 25.919255,81.654552 20.862721,75.143623 Z m 58.465577,18.456114 c 3.29309,1.017262 6.58369,2.037833 9.87679,3.055095 0.045,22.901637 0.10179,45.796137 0.14647,68.697779 l -68.572569,21.59491 c -5.175584,-6.94193 -10.351136,-13.87871 -15.526647,-20.82068 3.237857,1.18503 6.780635,1.45788 10.211601,1.12996 2.598883,-0.25445 5.183716,-0.81949 7.616843,-1.73679 3.93757,-1.52596 7.10496,-4.59431 8.977004,-8.22365 0.812429,-1.597741 1.426297,-3.319281 1.527552,-5.105776 0.02893,-0.54233 -0.04285,-1.089547 -0.02142,-1.632176 -0.0084,-7.95549 -0.01393,-15.89934 -0.02143,-23.854846 l 26.596176,-5.796305 v 3.682852 c -3.826475,0.119458 -7.681718,0.874564 -11.069535,2.636589 -2.825734,1.455055 -5.263551,3.631855 -6.842609,6.319439 -2.264681,3.801675 -2.795273,8.520421 -1.443847,12.701666 0.775469,2.428766 2.208656,4.662476 4.185086,6.361291 2.781258,2.43466 6.338782,3.960196 10.002345,4.687266 4.04775,0.79357 8.29766,0.67851 12.26228,-0.46037 3.13768,-0.903381 6.11061,-2.516122 8.30738,-4.875591 1.77186,-1.890186 2.97632,-4.264001 3.47361,-6.75888 0.26453,-1.260861 0.33953,-2.545471 0.31392,-3.829326 z" /></svg>`,
    }
  },
  methods: {
    scroll(id) {
      const height = document.querySelector(id).offsetHeight
      const position = document.querySelector(id).offsetTop
      window.scrollTo({top:position - height, behavior:'smooth'})
    }
  }
}
</script>

<style scoped>
div.text-style {
  text-align: left;
  margin-left: 50px;
  margin-right: 50px;
}

div.main-middle {
  background-color: mediumpurple;
  margin: auto;
  /*padding: 100px 0;*/
  text-align: center;
  /*margin: auto;*/
  vertical-align: middle;
}

.otl-code {
  width: 40%;
  margin-left: 30px;
  margin-right: 30px;
  display: inline-block;
  text-align: left;
}

div.main-top {
  background: dimgray;
  padding: 50px 0 100px 0;
}

h1.main {
  text-align: center;
  padding-bottom: 20px;
}

ul.otl-menu > li {display: inline-block;}

a.banner {
  display: inline-block;
  width: 50%;
}

div.sub-banner {
  display: flex;
  align-items: center;
  text-align: center;
}

a.banner > img {
  width: 80%;
  height: auto;
}

ul.otl-menu > li {
  display: inline-block;
  border-radius: 50%;
  padding: 30px;
  margin: 10px;
  color: black;
  font-size: 150%;
}

ul.otl-menu > li:hover {
  fill: #A900FF;
}

ul.otl-menu > li {
  fill: black;
  color: black;
  font-size: 130%;
}

ul.otl-menu > li:hover {
  fill: #A900FF;
  color: #A900FF;
  -webkit-text-stroke: 1px black;
}
</style>