<template>
    <div id="app">
        <toolbar></toolbar>
        <note-list></note-list>
        <editor></editor>
    </div>
</template>

<script>
    import Toolbar from '@/components/Toolbar'
    import NoteList from '@/components/NoteList'
    import Editor from '@/components/Editor'

    export default {
        components: {
            Toolbar,
            NoteList,
            Editor
        }
    }
</script>

<style lang="less">
    @import "assets/iconfont/iconfont.css";

    @font-serif: SimSun, "宋体", serif;
    @font-sans-serif: PingFang SC, Hiragino Sans GB, Microsoft YaHei, WenQuanYi Micro Hei, Arial, sans-serif;

    html, #app {
        font-family: @font-sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        color: #2c3e50;
        height: 100%;
    }

    body {
        margin: 0;
        padding: 0;
        border: none;
        height: 100%;
        max-height: 100%;
        position: relative;
    }
</style>
