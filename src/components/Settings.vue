<template>
<div class="modsFolderBox">
    <label>Папка модов:</label>
    <button class="btn"></button>
</div>
<div class="gameFolderBox">
    <label>Папка игры:</label>
    <button class="btn"></button>
</div>
<div class="onTopBox">
    <label>Режим окна:</label>
    <div class="form_toggle">
      <div class="form_toggle-item item-1">
        <input checked id="onTop" type="radio" name="onTopMode" value="off">
        <label for="onTop">Обычный</label>
      </div>
      <div class="form_toggle-item item-2">
        <input id="notTop" type="radio" name="onTopMode" value="on">
        <label for="notTop">Поверх всех окон</label>
      </div>
    </div>
</div>
</template>

<script>
</script>