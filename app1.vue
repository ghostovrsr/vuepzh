<script>
export default {
  data() {
    return {
        login: '',
        pass: '',
    }
  },
}
</script>

<template>
<header>
    <div class="form">
        <form name="test" method="post" action="input1.php">
            <p><b>Логин</b><br>
                <input type="text" size="40">
            </p>
            <p><b>Пароль</b><br>
                <input type="text" size="40">
            </p>
            <p><input type="submit" value="Отправить"></p>
        </form>
    </div>
</header>
</template>

<style scoped>
</style>