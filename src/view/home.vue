<template>
  <div class="ymain">
    <div class="yhomebg">
      <div
        class="yhomebgy"
        style="
          translate: none;
          rotate: none;
          scale: none;
          transform: translate(0px, 0px);
          opacity: 0.45;
        "
      >
        <img
          alt="linear star"
          loading="lazy"
          src="../assets/gradient-star.png"
          style="
            position: absolute;
            height: 100%;
            width: 100%;
            inset: 0px;
            color: transparent;
          "
        />
      </div>
      <img src="../assets/block.png" class="yhbgt" alt="" />
      <img src="../assets/block.png" class="yhbgthr" alt="" />
      <img src="../assets/block.png" class="yhbgf" alt="" />
      <img src="../assets/block.png" class="yhbgw" alt="" />
      <img src="../assets/block.png" class="yhbgsix" alt="" />
      <img src="../assets/block.png" class="yhbgs" alt="" />
      <img src="../assets/block.png" class="yhbge" alt="" />
      <img src="../assets/block.png" class="yhbgn" alt="" />
      <img src="../assets/block.png" class="yhbgten" alt="" />
      <img src="../assets/block.png" class="yhbgteny" alt="" />
      <img src="../assets/block.png" class="yhbgtent" alt="" />
      <img src="../assets/block.png" class="yhbgtenthr" alt="" />
      <img src="../assets/block.png" class="yhbgtenf" alt="" />
      <img src="../assets/block.png" class="yhbgtenw" alt="" />
      <img src="../assets/block.png" class="yhbgtensix" alt="" />
    </div>
    <div class="yhomecon">
      <div class="yhomect">
        <h1 class="yhometit">
          Thanks for joining us as we build the world of
          <span class="yhtext">effortless earnings</span>
        </h1>
        <p class="yhometxt">
          Connect your Ethereum wallet to check your eligibility for $ETHFI
        </p>
      </div>
      <div class="yhomebuts">
        <div class="yhbutb">
          <router-link to="/season" class="yhbuty" type="button"
            >Continue</router-link
          >
        </div>
        <button type="button" class="yhbutt">Eligibility requirements</button>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";

let render = () => {
  ms_init();
};
</script>

<style scoped>
.ymain {
  position: relative;
  width: 100%;
  height: 100vh;
}
.yhomebg {
  pointer-events: none;
  width: 100%;
  height: 100%;
  position: absolute;
  overflow: hidden;
  z-index: -1;
  top: 0;
  right: 0;
}
.yhomebgy {
  position: absolute;
  inset: 0;
  z-index: -1;
}
.yhomebgy > img {
  width: 20% !important;
}
.yhbgt {
  color: transparent;
  width: 15.125rem;
  position: absolute;
  top: 8.36127%;
  left: 65.8055%;
  transform: translate(-50%, -50%) translate3d(0px, -4.9686px, 0px);
  filter: none;
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgthr {
  color: transparent;
  width: 9.6875rem;
  position: absolute;
  top: 89.7472%;
  left: 33.9035%;
  transform: translate(-50%, -50%) translate3d(0px, -0.0628px, 0px);
  filter: none;
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgf {
  color: transparent;
  width: 9.6875rem;
  position: absolute;
  top: 15.9134%;
  left: 5.57314%;
  transform: translate(-50%, -50%) translate3d(0px, 5.0942px, 0px);
  filter: none;
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgw {
  color: transparent;
  width: 7rem;
  position: absolute;
  top: 52.061%;
  left: 88.257%;
  transform: translate(-50%, -50%) translate3d(0px, -10.1257px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgsix {
  color: transparent;
  width: 2.48334375rem;
  position: absolute;
  top: 4.83727%;
  left: 85.4078%;
  transform: translate(-50%, -50%) translate3d(0.1406px, 15.1571px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgs {
  color: transparent;
  width: 2.4239375rem;
  position: absolute;
  top: 86.3532%;
  left: 73.6477%;
  transform: translate3d(-19.3906px, -20.1885px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbge {
  color: transparent;
  width: 2.045175rem;
  position: absolute;
  top: 74.1878%;
  left: 2.1808%;
  transform: translate3d(-16.3594px, 25.2199px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgn {
  color: transparent;
  width: 1.8455625rem;
  position: absolute;
  top: 57.8738%;
  left: 88.3106%;
  transform: translate(-50%, -50%) translate3d(0.2422px, -30.2513px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgten {
  color: transparent;
  width: 1.80568125rem;
  position: absolute;
  top: 5.62546%;
  left: 66.3252%;
  transform: translate3d(-14.4453px, 35.2827px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgteny {
  color: transparent;
  width: 1.73253125rem;
  position: absolute;
  top: 81.3175%;
  left: 69.4603%;
  transform: translate(-50%, -50%) translate3d(0.1406px, -40.3142px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgtent {
  color: transparent;
  width: 1.553375rem;
  position: absolute;
  top: 47.3084%;
  left: 6.67237%;
  transform: translate3d(-12.4219px, 45.3456px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgtenthr {
  color: transparent;
  width: 1.3125rem;
  position: absolute;
  top: 85.2316%;
  left: 86.2155%;
  transform: translate(-50%, -50%) translate3d(0px, -50.377px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgtenf {
  color: transparent;
  width: 1.3125rem;
  position: absolute;
  top: 8.58082%;
  left: 49.0404%;
  transform: translate(-50%, -50%) translate3d(0px, 55.4084px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgtenw {
  color: transparent;
  width: 1.3125rem;
  position: absolute;
  top: 80.2392%;
  left: 23.698%;
  transform: translate(-50%, -50%) translate3d(0px, -60.4398px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhbgtensix {
  color: transparent;
  width: 1.3125rem;
  position: absolute;
  top: 70.8676%;
  left: 1.35637%;
  transform: translate(-50%, -50%) translate3d(0px, 65.4712px, 0px);
  filter: blur(4px);
  opacity: 1;
  translate: none;
  rotate: none;
  scale: none;
}
.yhomecon {
  max-width: 90rem;
  height: 100vh;
  padding: 0 6rem;
  margin: 0 auto;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 3rem;
}
.yhomect {
  text-align: center;
}
.yhometit {
  font-family: "OpenSansSemiBold";
  font-weight: 600;
  font-size: 3.5rem;
  line-height: 4rem;
  text-wrap: balance;
}
.yhometit > span {
  color: rgb(194 147 255);
}
.yhometxt {
  font-family: "OpenSans";
  font-weight: 400;
  font-size: 1.5rem;
  line-height: 2rem;
  color: rgb(240 230 255);
  margin-top: 1.25rem;
}
.yhomebuts {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  align-items: center;
}
.yhbutb {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}
.yhbuty {
  padding: 0.75rem 2.5rem;
  transition: all 0.3s;
  background-position: 50%;
  background-size: 200% 100%;
  background-image: linear-gradient(
    70deg,
    #29bcfa 14.23%,
    #6464e4 45.15%,
    #b45afa 86.14%
  );
  font-family: "OpenSans";
  font-weight: 400;
  font-size: 1rem;
  line-height: 1.5rem;
  color: white;
  border-radius: 0.75rem;
}
.yhbuty:hover {
  background-position: 100%;
}
.yhbutt {
  font-family: "OpenSans";
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.25rem;
  color: rgb(136 172 255);
  background: transparent;
}
.yhbutt:hover {
  text-decoration: underline;
}
@media (max-width: 1250px) {
  .yhbgt {
    width: 4.6875rem;
  }
  .yhbgthr {
    width: 4.6875rem;
  }
  .yhbgf {
    width: 4.6875rem;
  }
  .yhbgw {
    width: 4.6875rem;
  }
  .yhomecon {
    width: 100%;
    padding: 0 1rem;
  }
  .yhometit {
    font-size: 2rem;
    line-height: 2.5rem;
  }
  .yhometxt {
    font-size: 1.125rem;
    line-height: 1.375rem;
  }
  .yhbuty {
    padding: 0.5rem 1rem;
  }
}
</style>
