<script setup>
</script>

<template>
  <div class="content">
            <div class="server-info">
                <h2> (運作時間: {{date}})</h2>
                <div class="info-grid">
                    <div>狀態</div>
                    <div>running</div>
                    
                    <div>CPU 使用量</div>
                    <div>0.00% 於 2 CPU</div>
                    
                    <div>記憶體使用量</div>
                    <div>
                        <div class="progress-bar">
                            <div class="progress-fill"></div>
                        </div>
                        68.11% (2.72 GiB 於 4.00 GiB)
                    </div>
                    
                    <div>硬碟磁碟大小</div>
                    <div>32.00 GiB</div>
                    
                    <div>IPs</div>
                    <div>192.168.68.58<br>fe80::f225:8616:66ab:640b</div>
                </div>
            </div>
            
            <div class="chart">
                <!-- 圖表占位符 -->
            </div>
        </div>
</template>
