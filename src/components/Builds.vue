<template>
    <input class="buildsList" type="text" name="example" list="exampleList">
    <datalist id="exampleList">
        <option value="Имя сборки">v.00.00.00 | 000 модов, 000 установлено, 000 доступно</option>
    </datalist>
    <button class="btn createBuild"><i class="bi bi-file-earmark-plus"></i></button>
    <button class="btn removeBuild"><i class="bi bi-file-earmark-x"></i></button>
    <button class="btn openBuildFolder"><i class="bi bi-folder2-open"></i></button>
    <p class="selBuildInfo">Активно: v.00.00.00, 000 модов</p>
    <div class="selectGameTypeBox">
        <p>Выбор ветки:</p>

        <div class="form_toggle">
        <div class="form_toggle-item item-1">
            <input checked id="stid" type="radio" name="GameVersionType" value="Stable">
            <label for="stid">Stable</label>
        </div>
        <div class="form_toggle-item item-2">
            <input id="expid" type="radio" name="GameVersionType" value="Experimental">
            <label for="expid">Experimental</label>
        </div>
        </div>
    </div>

    <div class="middleGameBox">
        <div class="gameVersionBox">
        <p>Версия игры:</p>
        <div class="gameVersionListBox rect">
            <ul>
            <li></li>
            </ul>
        </div>
        </div>

        <div class="installedModsBox">
        <p>Установленные моды:</p>
        <div class="installedModsListBox rect">
            <ul>
            <li></li>
            </ul>
        </div>
        </div>
    </div>
</template>

<script>
</script>