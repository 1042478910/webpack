<template>
    <div class="home">
        <h1>home
            <div :class="$style.home">title</div>
        </h1>
    </div>
</template>

<script>
export default {
    data() {
        return {

        };
    }
};
</script>
 
<style lang="scss" module>
@import "../../css/reset.scss";
.home {
    color: blue;
    font-size: 60px;
}
</style>
