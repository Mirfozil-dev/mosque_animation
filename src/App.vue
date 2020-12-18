<template>
  <div id="app">
    <img class="clouds" src="./assets/the_clouds.png" alt="">
    <img class="moon" src="./assets/the_moon.png" alt="">
    <img class="towers" src="./assets/the_towers.png" alt="">
    <img class="little_towers" src="./assets/the_little_towers.png" alt="">
    <img class="mosque" src="./assets/the_mosque.png" alt="">
    <img class="bg" src="./assets/background.png" alt="">
    <img class="road" src="./assets/the_way.png" alt="">
    <button class="lets_go btn">Let's go</button>
    <button
        class="batafsil btn"
        @click="batafsil"
    >
      Batafsil
    </button>
    <button class="btn tel">
      <i class="fa-2x fas fa-phone-alt"></i>
    </button>
    <button class="btn message">
      <i class="fa-2x far fa-envelope"></i>
    </button>
    <button class="btn question">
      <i class="fa-2x far fa-question-circle"></i>
    </button>
    <button class="btn download">
      Download App
      <i class="fas fa-download"></i>
    </button>
    <button class="btn uz">
      UZ
    </button>
    <span class="btn devide-1"></span>
    <button class="btn ru">
      RU
    </button>
    <span class="btn devide-2"></span>
    <button class="btn en">
      EN
    </button>
    <button @click="aboutClicked = !aboutClicked" class="btn about_btn">About us</button>
    <button @click="back" class="back">
      <i class="fa-3x fas fa-long-arrow-alt-left"></i>
    </button>
    <div class="paragraph">
      <h1>Clicked</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores at atque consectetur debitis deserunt
        distinctio dolorum, eum ex explicabo hic iste itaque minus molestias nesciunt nihil officia, optio quaerat
        ratione rerum sapiente suscipit tempore, voluptas. Adipisci assumenda delectus error impedit laborum, magnam
        magni minus nostrum provident, quis quod ut? Alias error impedit necessitatibus nisi praesentium quia, quidem
        repellendus repudiandae unde voluptate. Ad, animi aut consequatur cumque eligendi fugiat fugit incidunt laborum
        laudantium libero magni minima mollitia nam non nulla odit placeat quis ratione similique tempora? Dignissimos
        error facilis minima odio quam! Aliquid, amet at culpa, esse fugit illo laudantium molestiae nisi nobis
        obcaecati quia reiciendis saepe, ut vitae voluptatem. Ab aliquid aperiam aspernatur assumenda blanditiis
        consectetur consequuntur deserunt ducimus maiores minima nesciunt odio porro possimus recusandae reiciendis rem
        repellendus, reprehenderit, repudiandae sint veniam. Consequuntur deserunt, excepturi exercitationem hic ipsum
        labore maiores minus nam nemo nisi nobis repellat vel, veritatis. Dolorum fugiat illum inventore nemo quae quia
        voluptas? Ab amet exercitationem hic nesciunt nobis provident soluta tempore totam! Aut culpa dignissimos
        molestiae neque obcaecati qui quidem. Ab ad aliquam amet architecto at blanditiis cumque debitis dolor dolorem
        eaque et explicabo ipsam ipsum iure iusto, labore, maiores nisi perferendis porro, possimus quasi rem
        repudiandae sed sint soluta voluptas voluptates. Accusantium dolorum error labore nostrum officiis veniam,
        voluptatibus? Commodi consequuntur culpa debitis delectus, dignissimos dolore eaque inventore laboriosam modi,
        necessitatibus reprehenderit suscipit tenetur voluptatibus! Accusantium adipisci amet architecto asperiores
        cupiditate distinctio dolor, dolorem ex inventore iure maxime nam numquam obcaecati placeat quo quos sapiente
        veniam voluptatibus.</p>
    </div>
    <div class="about_p">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem distinctio necessitatibus praesentium quis?
        Dolores inventore ipsam quibusdam soluta sunt. Aliquam animi aut autem beatae commodi, consequatur eveniet
        labore laudantium neque nihil nisi perspiciatis quas qui quo reiciendis rerum sit? Assumenda consequatur culpa
        ducimus eos esse iste iure, nam necessitatibus nesciunt omnis perferendis quidem ratione repellendus tempora ut
        veniam vero. Aliquid ea labore quia saepe sequi tempore vitae? Adipisci aperiam eum, incidunt, laudantium
        maiores nesciunt odit quae saepe similique, sit soluta totam voluptas voluptatibus! Aliquam assumenda
        consequuntur corporis culpa cumque cupiditate deleniti deserunt dolore doloribus error esse est excepturi
        explicabo hic illo in inventore ipsa ipsum, labore maxime molestiae mollitia necessitatibus nobis, numquam odit
        porro provident quae quis quo sapiente sed soluta suscipit tempore temporibus ullam vero voluptates? Dolorem
        error esse necessitatibus quisquam. Amet animi cum debitis dignissimos dolore dolorem eaque earum eius expedita
        fugiat hic id, incidunt ipsum iusto laborum molestias mollitia necessitatibus nisi nobis numquam, odit porro
        quis quisquam ratione reiciendis saepe sit soluta suscipit tempora tenetur, totam ullam ut veritatis. Amet
        aperiam aspernatur corporis cum dignissimos distinctio, est fugiat illum inventore itaque mollitia nisi nobis
        quae, quam quidem quod rem reprehenderit sunt tempore ut velit veniam voluptatem! Accusantium aliquam, amet
        autem doloremque est exercitationem facilis id ipsum iste libero mollitia omnis perferendis, quibusdam, quidem
        quis reiciendis saepe tempore tenetur vel vero. Ab animi asperiores, dolore eius exercitationem in inventore
        laudantium nisi nostrum numquam ratione repudiandae sequi? Exercitationem impedit magni minus nostrum sapiente?
        Corporis, dolorem eum modi molestiae nesciunt officia possimus rem vero. Ab deserunt ducimus esse ex fugit,
        incidunt ipsam iste magni minus nesciunt officia, provident, quam quas repellendus rerum sit suscipit tempora
        voluptas voluptatem voluptatibus. Animi aperiam hic perferendis rem soluta! Cupiditate doloribus eos, error
        expedita hic libero modi officia perspiciatis quidem rem repellat tempora totam vel. Amet commodi consectetur
        consequatur eligendi illum, officiis perferendis velit voluptates. Cupiditate fugit laudantium, non nostrum
        obcaecati officia quam quasi ratione! Amet, at autem commodi consectetur culpa deserunt eos eveniet facere
        itaque libero necessitatibus nulla officia pariatur porro qui quo repellat temporibus totam veritatis vero. A,
        commodi deleniti deserunt illo qui sapiente vitae voluptatem voluptatum. Beatae, consequuntur ipsum iste minima
        obcaecati pariatur repellendus rerum soluta voluptatem! Aperiam dolores nihil omnis temporibus veniam
        voluptates. Dolores, minima molestias natus sunt veritatis voluptatem. Alias aspernatur, blanditiis culpa
        dolorem, doloremque ducimus eius explicabo maiores minima molestias, numquam odio omnis quasi ratione rem
        repudiandae sed soluta veritatis. Aperiam asperiores culpa facilis, illum ipsum iusto laborum molestiae
        mollitia, natus neque, optio pariatur porro quas tenetur ut velit veritatis vitae! Ad aliquam dignissimos
        distinctio doloremque ea earum, eligendi error esse facilis labore minus mollitia nulla, sapiente sed tempora
        tempore unde? Alias asperiores at commodi culpa cupiditate dicta doloribus ducimus ea excepturi fuga fugit harum
        inventore ipsa ipsam maxime molestias nesciunt nihil nobis odio optio perferendis provident qui quos, sapiente
        tenetur, velit voluptas voluptate voluptatem voluptatibus voluptatum. Ab accusantium ad beatae dignissimos enim
        eveniet, excepturi fugit illo ipsa, nulla numquam officia, officiis perferendis provident quos veniam voluptatem
        voluptates voluptatum!</p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {},
  data() {
    return {
      aboutClicked: false,
    };
  },
  watch: {
    aboutClicked(val) {
      if (val === false) {
        this.aboutBack();
      } else {
        this.aboutUs();
      }
    },
  },
  methods: {
    flatRoad() {
      let road = document.querySelector('.road');
      road.classList.add('move-road');
    },
    toggleBatafsil() {
      let btn = document.querySelector('.batafsil');
      btn.classList.toggle('clicked');
    },
    moveMosque() {
      let mosque = document.querySelector('.mosque');
      mosque.style.left = '100px';
      let towers = document.querySelector('.towers');
      towers.style.left = '100px';
      let littleTowers = document.querySelector('.little_towers');
      littleTowers.style.left = '100px';
    },
    moveMosqueDown() {
      let mosque = document.querySelector('.mosque');
      mosque.classList.add('mosque-down');
      let towers = document.querySelector('.towers');
      towers.classList.add('towers-down');
      let littleTowers = document.querySelector('.little_towers');
      littleTowers.style.top = '400px';
    },
    moveBg() {
      let bg = document.querySelector('.bg');
      bg.style.transform = 'scale(1.6)';
    },
    smallMosque() {
      let mosque = document.querySelector('.mosque');
      mosque.style.width = '70%';
      let towers = document.querySelector('.towers');
      towers.style.width = '70%';
    },
    removeBtns() {
      let btns = document.querySelectorAll('.btn');
      btns.forEach(elem => elem.classList.add('d-none'));
    },
    moveMoon() {
      let moon = document.querySelector('.moon');
      moon.style.transform = 'translate(550px, -550px)';
    },
    shopParagraph() {
      let paragraph = document.querySelector('.paragraph');
      paragraph.style.opacity = '1';
      let back = document.querySelector('.back');
      back.style.opacity = '1';
    },
    batafsil() {
      this.toggleBatafsil();
      this.moveMosque();
      setTimeout(() => this.moveBg(), 0);
      setTimeout(() => this.moveMosqueDown(), 1000);
      setTimeout(() => this.flatRoad(), 1000);
      setTimeout(() => this.removeBtns(), 0);
      setTimeout(() => this.smallMosque(), 0);
      setTimeout(() => this.moveMoon(), 0);
      setTimeout(() => this.shopParagraph(), 1000);
    },
    back() {
      let road = document.querySelector('.road');
      let mosque = document.querySelector('.mosque');
      let towers = document.querySelector('.towers');
      // let littleTowers = document.querySelector('.little_towers');
      let bg = document.querySelector('.bg');
      let btns = document.querySelectorAll('.btn');
      let moon = document.querySelector('.moon');
      let paragraph = document.querySelector('.paragraph');
      let back = document.querySelector('.back');
      road.classList.remove('move-road');
      mosque.style.left = '400px';
      towers.style.left = '400px';
      mosque.classList.remove('mosque-down');
      towers.classList.remove('towers-down');
      bg.style.transform = 'scale(1)';
      paragraph.style.opacity = '0';
      back.style.opacity = '0';
      moon.style.transform = 'translate(0px, 0px)';
      btns.forEach(elem => elem.classList.remove('d-none'));
    },
    aboutBack() {
      let btn = document.querySelector('.about_btn');
      btn.style.borderBottom = 'none';
      let batafsil = document.querySelector('.batafsil');
      batafsil.style.opacity = '1';
      let mosque = document.querySelector('.mosque');
      let towers = document.querySelector('.towers');
      let moon = document.querySelector('.moon');
      mosque.style.transform = 'translate(0, 0)';
      towers.style.transform = 'translate(0, 0)';
      moon.style.transform = 'translate(0, 0)';
      let bg = document.querySelector('.bg');
      bg.style.transform = 'scale(1)';
      let aboutP = document.querySelector('.about_p');
      aboutP.style.opacity = '0';
    },
    moveRight() {
      let mosque = document.querySelector('.mosque');
      let towers = document.querySelector('.towers');
      let moon = document.querySelector('.moon');
      mosque.style.transform = 'translate(170px, 70px)';
      towers.style.transform = 'translate(170px, 70px)';
      moon.style.transform = 'translate(170px, 70px)';
    },
    aboutUs() {
      let btn = document.querySelector('.about_btn');
      btn.style.borderBottom = 'solid white';
      let batafsil = document.querySelector('.batafsil');
      batafsil.style.opacity = '0';
      this.moveRight();
      let bg = document.querySelector('.bg');
      bg.style.transform = 'scale(1.4)';
      let aboutP = document.querySelector('.about_p');
      aboutP.style.opacity = '1';
    },
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  font-family: Calibri, sans-serif;
  box-sizing: border-box;
}

#app {
  width: 100%;
  height: 100vh;
  overflow: hidden;
  position: relative;
}

.clicked {
  background: #fff !important;
  color: rebeccapurple !important;
}

.paragraph {
  position: absolute;
  z-index: 2;
  width: 70%;
  height: 70%;
  top: 60px;
  opacity: 0;
  padding: 5px;
  border-radius: 5px;
  transition: 1s opacity;
  bottom: 0;
  color: rebeccapurple;
  left: 200px;
  right: 0;
  background: white;
}

/* width */
::-webkit-scrollbar {
  width: 5px;
  margin-right: 100px;
}

/* Track */
::-webkit-scrollbar-track {
  box-shadow: inset 0 0 5px grey;
  border-radius: 10px;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: rebeccapurple;
  border-radius: 10px;
}

.about_p {
  position: absolute;
  z-index: 3;
  width: 40%;
  top: 70px;
  left: 70px;
  opacity: 0;
  overflow-y: auto;
  transition: 1s opacity;
  height: 60%;
  padding: 40px 5px 0 5px;
  border-radius: 40px;
  background: white;
}

.paragraph h1 {
  text-align: center;
}

.back {
  top: 20px;
  outline: none;
  left: 200px;
  opacity: 0;
  transition: 1s opacity;
  position: absolute;
  z-index: 2;
  color: white;
  background: none;
  border: none;
}

.bg, .road {
  width: 100%;
  height: 100%;
  position: absolute;
}

.d-none {
  display: none !important;
}

.bg {
  z-index: 0;
  transition: 1s;
}

.road {
  z-index: 1;
  transition: 1s;
}

.moon {
  width: 85%;
  height: 100%;
  left: 230px;
  animation: fromTop 4s;
  position: absolute;
  z-index: 2;
  transition: 2s;
}

.towers {
  width: 80%;
  height: 100%;
  left: 280px;
  transition: 1s;
  animation: fromBottom 3s;
  position: absolute;
  z-index: 3;
}

.little_towers {
  width: 90%;
  height: 100%;
  top: 90px;
  left: 200px;
  transition: 1s;
  animation: littleTowers 4s;
  position: absolute;
  z-index: 2;
}

.mosque-down {
  top: 100px;
  left: 200px;
  animation: mosqueDown 1s !important;
}

.towers-down {
  top: 350px;
  left: 200px;
  animation: towersDown 1s !important;
}

.move-road {
  top: 70px;
  animation: road 1s;
  transform: scaleX(10);
}

.mosque {
  width: 80%;
  height: 100%;
  left: 280px;
  transition: 1s !important;
  animation: fromBottom 3s;
  position: absolute;
  z-index: 3;
}

.clouds {
  width: 100%;
  height: 100%;
  animation: fromTop 2s;
  position: absolute;
  z-index: 2;
}

.devide-1, .devide-2 {
  position: absolute;
  bottom: 17px;
  z-index: 3;
  transition: 3s !important;
  width: 2px;
  height: 16px;
  background: grey;
  animation: opacity 4s;
}

.devide-1 {
  right: 34px;
}

.devide-2 {
  right: 65px;
}

.uz, .ru, .en {
  position: absolute;
  z-index: 3;
  color: white;
  transition: 3s !important;
  font-size: 1rem;
  bottom: 15px;
  background: none;
  border: none;
  animation: opacity 4s;
}

.uz {
  right: 10px;
}

.ru {
  right: 39px;
}

.en {
  right: 70px;
}

.download {
  position: absolute;
  color: white;
  background: none;
  outline: none;
  bottom: 10px;
  left: 250px;
  transition: 3s !important;
  border: none;
  z-index: 1;
  animation: opacity 4s;
}

.tel, .message, .question {
  position: absolute;
  color: white;
  outline: none;
  background: none;
  transition: 3s !important;
  border: none;
  left: 5px;
  z-index: 1;
  animation: opacity 4s;
}

.tel {
  bottom: 80px;
}

.message {
  bottom: 45px;
}

.question {
  bottom: 10px;
}

.batafsil {
  width: 140px;
  height: 50px;
  outline: none;
  border-radius: 30px;
  border: solid #ffffff;
  background: none;
  font-size: 1.3rem;
  color: white;
  position: absolute;
  transition: 1s !important;
  z-index: 3;
  left: 370px;
  bottom: 110px;
  animation: opacity 4s;
}

.lets_go {
  position: absolute;
  width: 130px;
  height: 40px;
  border: none;
  border-radius: 20px;
  font-size: 1.3rem;
  outline: none;
  top: 40px;
  right: 50px;
  transition: 3s !important;
  color: rebeccapurple;
  font-weight: bold;
  z-index: 2;
  animation: opacity 4s;
}

.about_btn {
  position: absolute;
  width: 130px;
  height: 40px;
  border: none;
  font-size: 1.3rem;
  outline: none;
  top: 40px;
  background: none;
  transition: 3s !important;
  right: 360px;
  color: #fff;
  font-weight: bold;
  z-index: 3;
  animation: opacity 4s;
}

@keyframes fromTop {
  from {
    bottom: 550px;
  }
  to {
    bottom: 0;
  }
}

@keyframes fromBottom {
  from {
    top: 550px;
  }
  to {
    top: 0;
    transition: 4s !important;
  }
}

@keyframes littleTowers {
  from {
    top: 300px;
    opacity: 0;
  }
  to {
    top: 90px;
    opacity: 1;
  }
}

@keyframes opacity {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@keyframes mosqueDown {
  from {
    top: 0;
  }
  to {
    top: 100px;
  }
}

@keyframes road {
  from {
    transform: scaleX(0);
  }
  to {
    transform: scaleX(4);
    top: 70px;
  }
}

@keyframes towersDown {
  from {
    top: 0;
  }
  to {
    top: 350px;
  }
}
</style>
