<template>
    <div class="app-header">
        <a href="#popup-box" class="app-header__button button">Open pop-up button</a>
    </div>
        <div id="popup-box" class="modal">
            <div class="content">
                <p class="app-header__p">Pop-up</p>
                <a class="app-header__a" href="#">
                    X
                </a>
            </div>
        </div>
</template>

<script>

export default {
    name: "AppHeader"
}

</script>

<style scoped>
.app-header {
    height: 100px;
    display: flex;
    align-items: center;
    background-color: #7FAFF6;
}

.app-header__button {
    margin-left: 30px;
}

.app-header__a {
    position: absolute;
    top: 10px;
    right: 10px;
    color: #FFFFFF;
    font-size: 30px;
    text-decoration: none;
    background-color: #7FAFF6;
    border-radius: 5px;
    width: 43px;
    height: 39px;
    text-align: center;
}

.app-header__p {
    font-family: Roboto;
    font-size: 53px;
    font-weight: 400;
    line-height: 62.11px;
    text-align: left;
}

.box a {
    padding: 15px;
    background-color: #fff;
    border-radius: 3px;
    text-decoration: none;
}

.modal {
    position: fixed;
    inset: 0;
    display: none;
    align-items: center;
    justify-content: center;
}

.content {
    position: relative;
    width: 400px;
    height: 400px;
    background: white;
    padding: 1em 2em;
    border-radius: 4px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.modal:target {
    display: flex;
}
</style>