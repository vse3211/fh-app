<template>
  <div class="child p5">
    <div class="leftBox">
      <button class="btn downloadsBtn">Downloads</button>
      <p class="labelAM"><b>Доступные моды:</b></p>
      <AvailableMods/>
    </div>
    <div class="middleBox">
      <Builds/>
      <Settings/>
    </div>
    <div class="rightBox">
      <div class="rect logs">
        <Logs/>
      </div>
      <div class="rightBottomBlock">
        <div class="rightBottomSubBlock" style="margin-right: 2px;">
          <label>История поиска:</label>
          <div class="rect">
            <SearchStory/>
          </div>
        </div>
        <div class="rightBottomSubBlock" style="margin-left: 3px;">
          <label>Требуемые моды:</label>
          <div class="rect">
            <RequiredMods/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import AvailableMods from '@/components/AvailableMods'
import Builds from '@/components/Builds'
import Settings from '@/components/Settings'
import Logs from '@/components/Logs'
import SearchStory from '@/components/SearchStory'
import RequiredMods from '@/components/RequiredMods'


export default {
  name: 'App',
  components: {
    //HelloWorld
    AvailableMods, Builds, Settings, Logs, SearchStory, RequiredMods
  }
}
</script>

<style>
@import './assets/css/styles.css';
@import './assets/css/checkbox.css';
@import 'https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.3/font/bootstrap-icons.css';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;
  color: #2c3e50;
  margin-top: 60px;*/
}
</style>
