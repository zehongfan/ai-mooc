<template>
    <div>
        <wbc-nav></wbc-nav>
        <div id="contentBox">
            <wbc-content></wbc-content>
            <wbc-contentSecond></wbc-contentSecond>
        </div>

    </div>
</template>

<script>
import header from "@/components/firstPage/initialHeader"
import content from "@/components/firstPage/initialContent"
import contentSecond from "@/components/firstPage/contentSecond"

export default {

        components: { //定义组件
        'wbc-nav':header,
        'wbc-content':content,
        'wbc-contentSecond':contentSecond,
    },
}
</script>


<style scoped>
#contentBox{
    width: 100%;
}
</style>
