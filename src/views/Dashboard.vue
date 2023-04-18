<script setup>
 import '@fortawesome/fontawesome-free/css/all.css'
</script>
<template>
    <div class="sidebar">
        <div class="sidebar-menu">
            <ul>
                <li>
                    <a href="" class="active"><span style="color: #44C079;" class="material-symbols-outlined">calendar_today</span>
                    <span>Schedule</span></a>
                </li>
                <li>
                    <a href=""><span style="color: white;" class="material-symbols-outlined">add_notes</span>
                    <span>Publish</span></a>
                </li>
                <li>
                    <a href=""><span style="color: white;" class="material-symbols-outlined">analytics</span>
                    <span>Analytics</span></a>
                </li>
                <li>
                    <a href=""><span style="color: white;" class="material-symbols-outlined">settings</span>
                    <span>Settings</span></a>
                </li>
                <li>
                    <a href=""><span style="color: white;" class="material-symbols-outlined">contact_support</span>
                    <span>Support</span></a>
                </li>
                <li>
                    <a href=""><span style="color: white;" class="material-symbols-outlined">logout</span>
                    <span>Log out</span></a>
                </li>
            </ul>
            <div class="plat">
                <ul>
                        <span>platforms<i class="fa-sharp fa-regular fa-plus"></i></span>
                    <li>
                        <a href="" class=""><i class="fa-brands fa-facebook"></i>
                        <span>Facebook</span></a>
                    </li>
                    <li>
                        <a href="" class=""><i class="fa-brands fa-instagram"></i>
                        <span>Facebook</span></a>
                    </li>
                    <li>
                        <a href="" class=""><i class="fa-brands fa-tiktok"></i>
                        <span>Facebook</span></a>
                    </li>
                </ul>
            </div>
            <div class="Ellipse">
                <img src="../assets/images/Ellipse.svg" alt="">
                <span>Ethiopian Airlines <br> Commercial </span>
            </div>   
        </div>   
    </div>

    <div class="main-content">
        <header>
            <h1>Support</h1>
        </header>
    </div>

</template>
<style scoped>
    *{
        padding: 0;
        margin: 0;
        box-sizing: border-box;
        list-style-type: none;
        text-decoration: none;
    }
    .sidebar {
        width: 345px;
        position: fixed;
        height: 100%;
        background: #44C079;
        color: white;
        left: 0;
        top: 0;
    }
    .sidebar-menu {
        height: 90px;
        padding: 5rem 0rem 1rem 2rem;
        color: #fff;
    }
    .sidebar-menu span {
        display: inline-block;
        padding-right: 1rem;
    }
    .sidebar-menu li {
        width: 100%;
        margin-bottom: 1rem;
        padding-left: 2rem;
    }
    .sidebar-menu a {
        padding-left: 1rem;
        display: block;
        color: #fff;
        font-size: 1.1rem;
    }
    .sidebar-menu a span {
        font-size: 1rem;
        padding-right: 1rem;
    }
    .sidebar-menu a.active {
        background: #fff;
        padding-top: 1rem;
        padding-bottom: 1rem;
        color: #44C079;
        border-radius: 30px 0px 0px 30px;
    }
    .plat ul span i {
        padding-left: 180px;   
    }
    .plat a span {
        font-size: 1rem;
        padding-left: 0.5rem;
    }
    .Ellipse {
        background: rgba(255, 255, 255, 0.33);
        top: 50px;
    }
    .Ellipse img {
        width: 50px;
        height: 50px;
    }
    .main-content {
        margin-left: 345px;
    }
    header {
        display: flex;
        justify-content: space-between;
        padding: 1rem;
        background: #F3F3F3;
    }
    header h1 {
        padding-left: 40px;
    }
</style>