<template>
  <link
    href="https://fonts.googleapis.com/css2?family=Koulen&family=Macondo&display=swap"
    rel="stylesheet"
  />
  <div>
    <div class="container">
      
      <p class="text">Lerne Koreanisch!</p>
      <p class="text2">한국어 배우기</p>
      <p class="text3">🙂</p>
    </div>

    <div class="scroll-container">
      <div class="album-cover">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <img
                src="../../public/images/vowels/a1.gif"
                alt="Avatar"
                style="width: 200px; height: 200px"
              />
            </div>
            <div class="flip-card-back">
              <table class="card">
                <router-link to="/a1" class="link">
                  <tr>
                    <h2>[a], wie V a ter</h2>
                  </tr>
                  <tr>
                    <h2>wie V[a]ter</h2>
                  </tr>
                </router-link>
              </table>
            </div>
          </div>
        </div>

        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <img
                src="../../public/images/vowels/a2.gif"
                alt="Avatar"
                style="width: 200px; height: 200px"
              />
            </div>
            <div class="flip-card-back">
              <table>
                <!-- <router-link to="/a12" class="link"> -->
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[eo]</h2>
                  </tr>
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wie S o nne</h2>
                  </tr>
                  <br />
                <!-- </router-link> -->
              </table>
            </div>
          </div>
        </div>

        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <img
                src="../../public/images/vowels/a3.gif"
                alt="Avatar"
                style="width: 200px; height: 200px"
              />
            </div>
            <div class="flip-card-back">
              <table>
                <!-- <router-link to="/a3" class="link"> -->
                  <tr>
                    <h2>[o]</h2>
                  </tr>
                  <tr>
                    <h2>wie in oben</h2>
                  </tr>
                  <br />
                <!-- </router-link> -->
              </table>
            </div>
          </div>
        </div>
      </div>

      <div class="album-cover">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <img
                src="../../public/images/vowels/a4.gif"
                alt="Avatar"
                style="width: 200px; height: 200px"
              />
            </div>
            <div class="flip-card-back">
              <table class="card">
                <!-- <router-link to="/a4" class="link"> -->
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;[u]</h2>
                  </tr>
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;wie in "gut"</h2>
                  </tr>
                <!-- </router-link> -->
              </table>
            </div>
          </div>
        </div>

        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <img
                src="../../public/images/vowels/a5.gif"
                alt="Avatar"
                style="width: 200px; height: 200px"
              />
            </div>
            <div class="flip-card-back">
              <table>
                <!-- <router-link to="/a5" class="link"> -->
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[eu]</h2>
                  </tr>
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wie im englischen "tak e n"</h2>
                  </tr>
                  <br />
                <!-- </router-link> -->
              </table>
            </div>
          </div>
        </div>

        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <img
                src="../../public/images/vowels/a6.gif"
                alt="Avatar"
                style="width: 200px; height: 200px"
              />
            </div>
            <div class="flip-card-back">
              <table>
                <!-- <router-link to="/a6" class="link"> -->
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[i]</h2>
                  </tr>
                  <tr>
                    <h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wie in "Idee"</h2>
                  </tr>
                  <br />
                <!-- </router-link> -->
              </table>
            </div>
          </div>
        </div>
      </div>


    </div>
  </div>
</template>

<script>


export default {
  name: "HomeView",
  components: {
    
  },
};
</script>

<style>
img {
  margin: 0 auto;
}
body {
  width: 99%;
  height: 100%;
}
.container {
  display: flex;
  margin-bottom: 20px;
  margin-top: -65px;
}
::-webkit-scrollbar {
  width: 10px;
}
::-webkit-scrollbar-track {
  box-shadow: inset 0 0 5px grey;
  border-radius: 10px;
}

::-webkit-scrollbar-thumb {
  background: rgb(210 64 255);
  border-radius: 10px;
}
.text {
  color: #00ffc0;
  font-family: "Koulen", cursive;
  font-size: 56px;
  width: 100%;
  margin-top: -43px;
  margin-left: 124px;
  border-radius: 12px;
}
.text2 {
  color: #94ff00;
  font-family: "Koulen", cursive;
  font-size: 40px;
  width: 100%;
  margin-top: 18px;
  margin-left: -385px;
  border-radius: -8px;
}
.text3 {
    color: #00caff;
    font-family: "Koulen", cursive;
    font-size: 30px;
    width: 100%;
    margin-top: 62px;
    margin-left: -495px;
    border-radius: -8px;
}
.album-cover {
  margin-left: -13px;
  display: flex;
}
.cover {
  width: 200px;
  height: 200px;
}
.flip-card {
  background-color: transparent;
  width: 200px;
  height: 200px;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.4s;
  transform-style: preserve-3d;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 85%;
  height: 85%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: #bbb;
  color: black;
}

.flip-card-back {
  background-color: #29d0a7;
  color: white;
  transform: rotateY(180deg);
  font-family: "Macondo", cursive;
  font-size: 12px;
  padding: 15px;
  height: 76%;
  width: 76%;
  border: 10px solid #6d6dff;
}
.link {
  text-decoration: none;
  margin-left: 0 auto;
}
.link2 {
  text-decoration: none;
  margin-left: 13px;
}

@media only screen and (max-width: 800px) {
  .album-cover {
    flex-direction: column;
    margin-left: 105px;
  }
  .container {
    margin-left: 50px;
  }
  .text {
    margin-top: 5px;
    font-size: 39px;
    margin-left: -1px;
  }
  .text2 {
    font-size: 30px;
    margin-top: 60px;
  }
  .text3 {
    margin-top: 110px;
  }
  body {
    
    width: 99%;
    height: 100%;
  }
  .top-content {
    margin: 0 auto;
    width: 390px;
  }
  .top-box[data-v-7ba5bd90] {
    margin: 0 auto;
    width: 90%;
  }
}
</style>