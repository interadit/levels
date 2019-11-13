<template>
    <div id="sidebar-header">
        <div class="logo"></div>
        <div class="name">Shinchi</div>
        <div class="group">Minami</div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
#sidebar-header {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 250px;
    background: radial-gradient(#f03c39, #920025);
    color: #fefefe;

    .logo {
          background-image: url('../assets/logo.png');
          background-position: center;
          background-size: cover;
          width: 120px;
          height: 120px;
    }

    .name {
        font-size: 1.4rem;
    }
}
</style>