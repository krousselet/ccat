<template>
    <div class="france">
        <div class="blue"></div>
        <div class="white"></div>
        <div class="red"></div>
    </div>
</template>

<style lang="scss" scoped>
.france {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    height: 80px;

    .blue, .white.red {
        height: inherit;
        width: 33%;
    }

    .blue {
        background-color: #002157;
    }

    .red {
        background-color: #931116;
    }
}
</style>