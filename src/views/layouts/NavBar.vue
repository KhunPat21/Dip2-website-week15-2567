<script setup>
import router from '@/router';
import { RouterLink } from 'vue-router'

const logOut = async () => {
    localStorage.clear()
    await router.push({ name: 'signin' })
}

</script>

<template>
    <nav class="navbar navbar-expand-lg navbar-dark shadow" style="background: #00c3ff;">
        <div class="container">
            <RouterLink :to="{ name: 'home' }" class="navbar-brand">โลกอนาคต</RouterLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <RouterLink :to="{ name: 'home' }" class="nav-link active" aria-current="page"><i
                                class="bi bi-house-fill me-1"></i>หน้าแรก</RouterLink>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{ name: 'signin' }" class="nav-link" href="#"><i
                                class="bi bi-bank me-1"></i>เข้าสู่ระบบ</router-link>
                    </li>

                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="https://dododo-76f0.onrender.com/DoRaeMon" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            <i class="bi bi-bank2 me-1"></i>เรื่องราวของโดราเอม่อน
                        </a>

                        <ul class="dropdown-menu">
                            <li>
                                <RouterLink :to="{ name: 'wonders' }" class="dropdown-item">เรื่องราวของโดราเอม่อน
                                </RouterLink>
                            </li>
                            <li>
                                <RouterLink :to="{ name: 'add-wonder' }" class="dropdown-item">สมัครสมาชิก
                                </RouterLink>
                            </li>
                            <li><a class="dropdown-item" href="">เเนะนำเรื่อง</a></li>
                         
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="https://www.animesiam.com/doraemon-the-movie/">เว็บไซต์ โดราเอม่อน</a></li>
                        </ul>
                    </li>

                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            <i class="bi bi-bank2 me-1"></i>เกี่ยวกับเรา
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="https://th.wikipedia.org/wiki/%E0%B9%82%E0%B8%94%E0%B8%A3%E0%B8%B2%E0%B9%80%E0%B8%AD%E0%B8%A1%E0%B8%AD%E0%B8%99" target="_blank">ประวัติความเป็นมา</a></li>
                            
                            
                        </ul>
                    </li>

                    <li class="nav-item dropdown">
                        
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#" @click="logOut"><i
                                class="bi bi-box-arrow-right me-1"></i>ออกจากระบบ</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Sarabun&display=swap');

.navbar {
    font-family: 'Sarabun', sans-serif;
}
</style>
