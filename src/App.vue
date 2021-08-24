<template>
  <div class="pycnonotus-sinensis">
    <div class="header">
      <div class="header__hamburger" @click="hamClickHandler()">
        <span class="header__hamburger--first ham"></span>
        <span class="header__hamburger--second ham"></span>
        <span class="header__hamburger--third ham"></span>
      </div>
      <h1 class="header__title">白頭翁不吃小米</h1>
      <nav class="header__nav" :class="{ available: hamClicked }">
        <ul @click="navClickHandler($event)">
          <li>
            <a
              class="header__nav--link active link-feature"
              href="#feature"
              rel="noopener noreferrer"
              >白頭翁的特性</a
            >
          </li>
          <li>
            <a
              class="header__nav--link link-story"
              href="#story"
              rel="noopener noreferrer"
              >白頭翁的故事</a
            >
          </li>
          <li>
            <a
              class="header__nav--link link-picture"
              href="#picture"
              rel="noopener noreferrer"
              >白頭翁的美照</a
            >
          </li>
          <li>
            <a
              class="header__nav--link link-crisis"
              href="#crisis"
              rel="noopener noreferrer"
              >白頭翁的危機</a
            >
          </li>
        </ul>
        <span class="header__nav--copyright">&copy;</span>
      </nav>
      <a class="header__logo" href="#">
        <span class="header__logo--eye">●</span>
      </a>
    </div>
    <div class="main">
      <div class="main__banner">
        <h2 class="main__banner--title">白頭翁 (Chinese bulbul)</h2>
        <p class="main__banner--content">
          又名白頭鵯。以果實、昆蟲為主食,無法消化小米、穀類。平均壽命約 8~10
          年。
        </p>
      </div>
      <article class="main__article">
        <section class="main__article--feature" id="feature">
          <div class="feature">
            <h3 class="feature__title">外觀</h3>
            <p class="feature__content">
              白頭鵯體長約17到22公分,額至頭頂純黑色而富有光澤,兩眼
              上方至後枕白色,形成一白色枕環。耳羽後部有一白斑,此白環
              與白斑在黑色的頭部均極為醒目,老鳥的枕羽(後頭部)更潔白,
              所以又叫「白頭翁」。
            </p>
          </div>
          <div class="feature">
            <h3 class="feature__title">棲地</h3>
            <p class="feature__content">
              白頭翁和麻雀、綠繡眼合稱「城市三寶」,常成群出現在平原區
              灌木叢、丘陵樹林地帶,以及校園、公園、庭院、行道中的各種
              高高的電線與樹上。
            </p>
          </div>
          <div class="feature">
            <h3 class="feature__title">食性</h3>
            <p class="feature__content">
              以果樹的漿果和種子為主食,並時常飛入果園偷吃果實,還會吃
              嫩葉嫩芽,尤其是胡蝶蘭的嫩葉嫩芽葉,偶爾啄食昆蟲。
            </p>
          </div>
        </section>
        <section class="main__article--story" id="story">
          <h3 class="story__title">白頭翁的故事</h3>
          <p class="story__content">
            傳說，在大森林裡有一隻美麗的小鳥，它想學一點本領。這一天，它走出家門，決定去拜師學藝。它看見喜鵲阿姨造了一座既漂亮又寬敞明亮的房子，覺得造房子很有意思，決定學習這一行。起初，它跟著喜鵲非常認真地學習，可是學著學著，它就覺得造房子很沒意思，開始厭倦了。它說：“天天造房子，沒有什麼樂趣，還很累。”於是，便不再學造房子了。一天，它聽到黃鶯姐姐的歌聲那麼動聽，覺得唱歌很好玩兒，就去拜黃鶯姐姐為師學習唱歌。開始，它學得很認真，但是沒過多久又厭倦了。它說：“學唱歌要天天練嗓子，太辛苦了，我實在受不了。”於是，它不再學唱歌了。它又看到大雁叔叔能遠行萬里，就去拜大雁為師學飛行；它看見老鷹伯伯敏捷的動作，就去拜老鷹伯伯為師學習打獵；它看到啄木鳥醫生醫術高超，就去拜啄木鳥為師，學習醫治得病的樹木。它從森林的這邊走到森林的那邊，看見什麼，就去學什麼，拜了一位老師又一位老師，最後都是有始無終，沒有一件事情能堅持到底。日子一天一天過去，一年又一年過去，直到它的頭髮全白了，還沒有學到什麼本領。它開始認識到自己錯了，但是已經太晚了。它沒有什麼本領可以傳給自己的子孫後代，感到很慚愧。想到自己一生拜師學藝，不能堅持到底，結果一事無成，決定讓子孫記住這個教訓，它就把自己的一頭白髮傳給後代，讓它們世世代代都記住這個教訓。從此，人們給這種鳥起了一個名字——白頭翁。小朋友，白頭翁的故事告訴我們：做事情不能堅持到底，總是半途而廢，就會一事無成，學不到真正的本領。
          </p>
        </section>
        <section class="main__article--picture" id="picture">
          <div class="pic pic-1"></div>
          <p>&nbsp;</p>
          <div class="pic pic-2"></div>
          <p>&nbsp;</p>
          <div class="pic pic-3"></div>
        </section>
        <section class="main__article--crisis" id="crisis">
          <h3 class="crisis__title">白頭翁的危機</h3>
          <p class="crisis__content">
            曾經盛極一時的宗教放生風氣，許多團體將西半部捕捉的白頭翁帶到東部放生，數量龐大的白頭翁族群將直接迫使烏頭翁面臨嚴重雜交隱憂。由於雜交個體仍然具有繁殖能力，長久下去將影響數量較弱勢的烏頭翁生存，最終可能導致烏頭翁的滅絕。
          </p>
        </section>
      </article>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      hamClicked: false,
      scroll: "",
    };
  },
  mounted() {
    window.addEventListener("scroll", this.menu);
  },
  methods: {
    setNavActive(navItem) {
      let lis = document.getElementsByClassName("header__nav--link");
      for (let i = 0; i < lis.length; i++) {
        lis[i].classList.remove("active");
      }
      navItem.classList.add("active");
    },
    menu() {
      this.scroll =
        document.documentElement.scrollTop || document.body.scrollTop;
      console.log(this.scroll);
      if (this.scroll < "600") {
        this.setNavActive(document.querySelector(".link-feature"));
      } else if (this.scroll >= "600" && this.scroll <= "700") {
        this.setNavActive(document.querySelector(".link-story"));
      } else if (this.scroll >= "1000" && this.scroll <= "1700") {
        this.setNavActive(document.querySelector(".link-picture"));
      } else if (this.scroll >= "1900" && this.scroll <= "2000") {
        this.setNavActive(document.querySelector(".link-crisis"));
      }
    },
    hamClickHandler() {
      let hams = document.getElementsByClassName("ham");
      if (this.hamClicked) {
        for (let i = 0; i < hams.length; i++) {
          hams[i].classList.remove("clicked");
        }
        this.hamClicked = false;
      } else {
        for (let i = 0; i < hams.length; i++) {
          hams[i].classList.add("clicked");
        }
        this.hamClicked = true;
      }
    },
    navClickHandler(e) {
      let lis = document.getElementsByClassName("header__nav--link");
      for (let i = 0; i < lis.length; i++) {
        lis[i].classList.remove("active");
      }
      this.setNavActive(e.target);
      document.querySelector(".header__hamburger").click();
    },
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  margin: 0;
  padding: 0;
  list-style: none;
  text-decoration: none;
}

.pycnonotus-sinensis {
  display: flex;
  .header {
    width: 80%;
    height: 100vh;
    min-width: 275px;
    position: sticky;
    top: 0;
    z-index: 1;
    &__hamburger {
    }
    &__title {
      font-size: 24px;
      margin: 50px 0 75px;
    }
    &__nav {
      li {
        padding: 10px 0;
        position: relative;
        transition: 0.5s;
        &::before {
          transform: scale(0);
          transition: 0.3s;
          content: "";
          width: 95px;
          height: 3px;
          border-bottom: 3px solid #aa4040;
          position: absolute;
          bottom: 0;
        }
        &:hover {
          & .header__nav--link {
            color: #aa6666;
            font-weight: bold;
          }
          &::before {
            transform: scale(1);
          }
        }
      }
      &--link {
        color: black;
      }
      &--copyright {
        display: none;
      }
    }
    &__logo {
      width: 80px;
      height: 80px;
      background-color: white;
      border-radius: 100%;
      position: absolute;
      top: 25px;
      right: -40px;
      box-shadow: 0px 0px 10px 0px lightgrey;
      z-index: 1;
      &--eye {
        position: absolute;
        font-size: 20px;
        top: 35%;
        color: black;
      }
      &::before {
        content: "";
        width: 40px;
        height: 40px;
        box-sizing: border-box;
        border-top: 8px solid black;
        border-bottom: 8px solid black;
        border-radius: 60% 25% 50% 0%;
        position: absolute;
        top: 0;
        left: 0;
        transform: translate(50%, 50%);
      }
      &::after {
        content: "";
        width: 12px;
        height: 10px;
        box-sizing: border-box;
        border-top: 6px solid black;
        /* border-bottom: 8px solid black; */
        border-radius: 30% 700% 0% 0%;
        position: absolute;
        top: 32%;
        right: 20%;
        transform: translate(50%, 50%) rotate(-15deg);
      }
    }
  }
  .main {
    box-shadow: 0px 0px 5px 0px grey;
    &__banner {
      width: 100%;
      height: 70vh;
      background: right 40% center / 200% no-repeat
        url("http://i.imgur.com/KfUmCKk.jpg");
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      align-items: flex-end;
      text-align: right;
      filter: brightness(0.9);
      &--title {
        font-size: 44px;
        margin-right: 30px;
      }
      &--content {
        margin-right: 30px;
        margin-bottom: 30px;
      }
    }
    &__article {
      &--feature {
        display: flex;
        background-color: #ddccbb;
        padding: 60px 15px;
        .feature {
          display: flex;
          align-items: flex-start;
          flex: 1;
          margin: 0 25px;
          /* padding: 60px 25px;
          box-sizing: border-box; */
          &__title {
            writing-mode: vertical-lr;
            font-size: 34px;
            margin-right: 25px;
            position: relative;
            z-index: 1;
            &::before {
              content: "";
              width: 8px;
              height: 8px;
              border: 6px solid #c48576be;
              border-radius: 100%;
              position: absolute;
              right: -10%;
              bottom: -10%;
              z-index: -1;
            }
          }
          &__content {
            text-align: left;
          }
        }
      }
      &--story {
        height: 50vh;
        writing-mode: vertical-rl;
        margin: 50px auto;
        .story__title {
          margin-bottom: 10px;
        }
        .story__content {
          line-height: 1.8;
          text-align: left;
          text-indent: 32px;
        }
      }
      &--picture {
        position: relative;
        .pic {
          width: 100%;
          height: 50vh;
          &-1 {
            background: center / cover no-repeat
              url("https://live.staticflickr.com/1979/45224195531_f1691186d9_b.jpg");
          }
          &-2 {
            background: center / cover no-repeat
              url("https://cyberisland.teldap.tw/S/JuEzxgeirMtZolySsltwmTSlZY");
          }
          &-3 {
            background: center / cover no-repeat
              url("https://upload.wikimedia.org/wikipedia/commons/8/8e/%E7%99%BD%E9%A0%AD%E7%BF%81_%2826037412116%29.jpg");
          }
        }
        .pic {
          background-attachment: fixed;
        }
      }
      &--crisis {
        padding: 50px;
        display: flex;

        background-color: #ddccbb;
        .crisis {
          &__title {
            font-size: 32px;
            writing-mode: vertical-rl;
            margin-right: 20px;
            position: relative;
            z-index: 1;
            &::before {
              content: "";
              width: 8px;
              height: 8px;
              border: 6px solid #c48576be;
              border-radius: 100%;
              position: absolute;
              right: -10%;
              bottom: -5%;
              z-index: -1;
            }
          }
          &__content {
            margin: auto;
          }
        }
      }
    }
  }
}
.header__nav--link.active {
  color: #aa6666;
  font-weight: bold;
  &::before {
    content: "";
    width: 95px;
    height: 3px;
    border-bottom: 3px solid #aa4040;
    position: absolute;
    bottom: 0;
  }
}
@media screen and (max-width: 1200px) {
  .pycnonotus-sinensis {
    .main {
      &__article {
        &--feature {
          flex-direction: column;
          .feature {
            margin: 0 20px;
            & ~ .feature {
              margin-top: 50px;
            }
            &__title {
              margin: 0 20px 0 0;
              text-shadow: 0 0 1px black;
            }
          }
        }
        &--story {
          height: 70vh;
        }
      }
    }
  }
}
@media screen and (max-width: 768px) {
  .pycnonotus-sinensis {
    flex-direction: column;
    .header {
      width: 100%;
      height: auto;
      position: fixed;
      top: 0;
      background-color: white;
      z-index: 99;

      &__hamburger {
        width: 25px;
        position: absolute;
        left: 20px;
        top: 45px;
        span {
          display: block;
          height: 4px;
          background-color: black;
          margin-bottom: 5px;
          transition: all 0.3s;
        }
        &--first.clicked {
          transform: rotate(45deg) translate(8px, 8px);
        }
        &--second {
          width: 15px;
          &.clicked {
            opacity: 0;
          }
        }
        &--third.clicked {
          transform: rotate(-45deg) translate(5px, -5px);
        }
      }
      &__title {
        margin: 40px 0;
      }
      &__nav {
        display: none;
        &--copyright {
          display: block;
          margin: 15px 0;
        }
      }
      .available {
        display: block;
      }
      &__logo {
        right: 20px;
        top: 15px;
        transform: scale(0.75);
      }
    }
    .main {
      margin-top: 111px;
      &__banner {
        height: auto;
        min-height: 300px;
        &--title {
          margin-left: 35px;
          margin-right: 20px;
        }
        &--content {
          margin-left: 35px;
          margin-right: 20px;
        }
      }
      &__article {
        &--feature {
          flex-direction: column;
          .feature {
            margin: 0 20px;
            & ~ .feature {
              margin-top: 50px;
            }
            &__title {
              margin: 0 20px 0 0;
              text-shadow: 0 0 1px black;
            }
          }
        }
        &--story {
          height: auto;
          writing-mode: horizontal-tb;
          padding: 15px;
        }
      }
    }
  }
}
</style>
