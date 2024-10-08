<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div class="header">
        <div class="logo">WEI Real Environment 8.2.2</div>
        <div class="header-right">
            <button class="terminal-btn">
                <span class="terminal-icon">></span>
                終端機
            </button>
            <div class="user-info">wei-coding@pam</div>
        </div>
    </div>
    
    <div class="main-container">
        <div class="sidebar">
            <div class="menu-item">資料中心</div>
            <div class="menu-item">LXC 容器</div>
            <div class="menu-item">節點</div>
            <div class="menu-item">虛擬機</div>
            <div class="menu-item">SDN</div>
            <div class="menu-item">儲存</div>
        </div>
        
        <RouterView />
    </div>

  
</template>

<style scoped>

</style>
