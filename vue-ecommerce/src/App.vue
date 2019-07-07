<template>
  <div id="app">
    <HelloWorld/>
    <AppleWatch id="watch"/>
    <Filters id="filters"/>
    <Navbar id="navbar"/>
    <JblSpeaker id="speaker"/>
    <AppleIphone id="iphone"/>
    <HeadPhones id="headphone"/>
    <MacBook id="macbook" />
    <AppleIpad id="ipad" />
    <HomePod id="homepod"/>
    <BlueTooth id="bluetooth"/>
    <MagicMouse id="mouse"/>
    <Footer id="footer"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AppleWatch from './components/AppleWatch.vue'
import Filters from './components/Filters.vue'
import Navbar from './components/Navbar.vue'
import JblSpeaker from './components/JblSpeaker.vue'
import AppleIphone from './components/AppleIphone.vue'
import HeadPhones from './components/HeadPhones.vue'
import MacBook from './components/MacBook.vue'
import AppleIpad from './components/AppleIpad.vue'
import HomePod from './components/HomePod.vue'
import BlueTooth from './components/BlueTooth.vue'
import MagicMouse from './components/MagicMouse.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'app',
  components: {
    HelloWorld, AppleWatch, Filters, Navbar, 
    JblSpeaker, AppleIphone, HeadPhones, MacBook,
    AppleIpad, HomePod, BlueTooth, MagicMouse, Footer 
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 3px;
}
#watch {
  margin-left: 480px;
  margin-top: 18%;
}
#filters {
  position: absolute;
  left: 210px;
  top: 26%;
}
#navbar {
  position: absolute;
  top: 40px;
  right: 10px;
}
#speaker {
  position: absolute;
  margin-left: 767px;
  top: 280px;
  
}
#iphone {
  position: absolute;
  margin-left: 1057px;
  top: 280px;
}
#headphone {
  position: absolute;
  margin-left: 480px;
  top: 750px;
}
#macbook {
  position: absolute;
  margin-left: 768px;
  top: 750px;
}
#ipad {
  position: absolute;
  margin-left: 1058px;
  top: 750px;
}
#homepod {
  position: absolute;
  margin-left: 480px;
  top: 1227px;
}
#bluetooth {
  position: absolute;
  margin-left: 768px;
  top: 1227px;
}
#mouse {
  position: absolute;
  margin-left: 1058px;
  top: 1227px;
}
#footer {
  position: absolute;
  margin-left: 620px;
  top: 1650px;
}
</style>
