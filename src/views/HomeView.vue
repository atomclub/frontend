<script setup lang="ts">
import GithubIcon from "@/assets/Github_Logo.svg"
import BiliIcon from "@/assets/BiliBili_TV_Icon.svg"
import TiktokIcon from "@/assets/tiktok.svg"
</script>

<template>
  <main>
    <div class="overview">
      <div class="logo">
        <img src="@/assets/logo.png" id="logo" weight="360" height="360"/>
      </div>
      <div class="divider"></div>
      <div class="introduction">
        <h1 class="name">HeartBeat 心乐社</h1>
        <i>HEARTBEAT CLUB</i>
        <p>用心倾乐，乐涌于心。</p>
        <div class="links">
          <a href="https://space.bilibili.com/1043671230">
            <BiliIcon class="bili"></BiliIcon>
          </a>
          <a><TiktokIcon></TiktokIcon></a>
        </div>
      </div>
    </div>
  </main>
  <p>HeartBeat心乐社创立于2012年，是潮实高中部的第二批社团之一，也是校内唯一的大型音乐社团。<br></p>
  <p>HeartBeat心乐社是一个充满激情与创造力的社团。我们致力于提供一个平台，让全校的音乐爱好者们能够汇聚一堂，共同学习、交流和分享音乐的魅力。
    <br><br>分部HeartBeat心乐社包含歌手部、乐手部和企划部三个部门。三个部门各司其职，共同组成了HeartBeat心乐社。</p>

</template>

<style scoped>
main {
  margin: 2rem;
  padding: 2rem;
}

p,
ul {
  font-size: 1.2rem;
}

.divider {
  width: 1px;
  height: 100%;
  margin: 0 3rem;
  background-color: var(--color-border);
}

.overview {
  display: flex;
  align-items: center;
  width: 70%;
  height: 40vh;
  margin: 10vh auto;
}

.logo {
  flex: 1;
  margin: 2rem 0;
}

.introduction {
  flex: 1;
  text-align: center;
}

.logo svg {
  margin: auto;
  border-radius: 50%;
  width: 10rem;
  height: 10rem;
  display: block;
}

.links {
  margin-top: 3rem;
}

.links a svg {
  width: 3rem;
  height: 3rem;
  color: var(--color-heading);
}

.links a svg.bili {
  color: rgb(0 179 250);
}

@media screen and (max-width: 900px) {
  .overview {
    display: block;
  }

  .divider {
    display: none;
  }

  main {
    margin: 1rem 0;
  }

  .logo img {
    display: block;
    width: 110px;
    align-items: center;
    height: auto;
    margin: 0 auto;
  }

}

</style>
