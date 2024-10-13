<template>
    <div class="header">
    <img src="https://i.postimg.cc/Y2QzNrgh/8-DB16396-B844-4-B68-A195-98-FFDAC47-A90.png" width="80vw" style="margin-top: -8px; margin-left: -10px;">
    </div>

    <h4 style="font-family: Geologica; font-size: 28px; color: white;">Top Artist:</h4>
    <div class="Artist" style="margin-top: -10px;">
        <RouterLink to="/about"><img src="https://i.postimg.cc/RhpRN8Hn/18414583-6322-4-C9-D-948-A-00-D8-DAFC0-A7-F.jpg" width="150vw" style="border-radius: 20px;"></RouterLink>
        <RouterLink to="/about"><img src="https://i.postimg.cc/pX7Cvwvw/7-A4-D5-D9-A-C1-CA-4-D9-E-8-B68-8-D849-CCAF83-E.jpg" width="150vw" style="margin-left: 20px; border-radius: 20px;"></RouterLink>
        <RouterLink to="/about"><img src="https://i.postimg.cc/3x0FJVmH/623-CC5-F5-91-B4-498-C-901-C-824-BE76-B4-B74.jpg" width="150vw" style="margin-left: 20px; border-radius: 20px;"></RouterLink>
    </div>
    
    <h3 style="font-family: Geologica; font-size: 30px; color: white; margin-left: 15px;">Music:</h3>
    <div class="bio">
    <h2 style="margin-top: -1px; margin-left: 15px; font-family: Geologica; font-size: 26px; color: white;">Мальчик</h2>
    <p style="margin-top: -25px; margin-left: 15px; font-family: Geologica; color: grey;">Кис Кис</p>
    <audio controls style="margin-top: -15px;">
    <source src="../components/мальчик.mp3">
    </audio>
    </div>

    <div class="bio" style="margin-top: 25px;">
    <h2 style="margin-top: -1px; margin-left: 15px; font-family: Geologica; font-size: 26px; color: white;">Дора-Дура</h2>
    <p style="margin-top: -25px; margin-left: 15px; font-family: Geologica; color: grey;">Дора</p>
    <audio controls style="margin-top: -15px;">
    <source src="../components/dora-doradura.mp3">
    </audio>
    </div>

    <div class="bio" style="margin-top: 25px;">
        <h2 style="margin-top: -1px; margin-left: 15px; font-family: Geologica; font-size: 26px; color: white;">Барбисайз</h2>
        <p style="margin-top: -25px; margin-left: 15px; font-family: Geologica; color: grey;">Дора & Мэйби Бэйби</p>
        <audio controls style="margin-top: -15px;">
        <source src="../components/dora-mjejjbi-bjejjbi-barbisajjz.mp3">
        </audio>
    </div>

    <div class="bio" style="margin-top: 25px;">
        <h2 style="margin-top: -1px; margin-left: 15px; font-family: Geologica; font-size: 26px; color: white;">Санларан</h2>
        <p style="margin-top: -25px; margin-left: 15px; font-family: Geologica; color: grey;">Дора & Platina</p>
        <audio controls style="margin-top: -15px;">
        <source src="../components/platina-feat.-dora-san-laran.mp3">
        </audio>
    </div>

    <div class="bio" style="margin-top: 25px;">
        <h2 style="margin-top: -1px; margin-left: 15px; font-family: Geologica; font-size: 26px; color: white;">Роблокс</h2>
        <p style="margin-top: -25px; margin-left: 15px; font-family: Geologica; color: grey;">Lemaier feat. Gulyashik, Qurorr</p>
        <audio controls style="margin-top: -15px;">
        <source src="../components/Lemaier - Роблокс удалила мне мама.mp3">
        </audio>
    </div>

    <div class="bio" style="margin-top: 25px;">
        <h2 style="margin-top: -1px; margin-left: 15px; font-family: Geologica; font-size: 26px; color: white;">Холод</h2>
        <p style="margin-top: -25px; margin-left: 15px; font-family: Geologica; color: grey;">Shadowraze</p>
        <audio controls style="margin-top: -15px;">
        <source src="../components/shadowraze-kholod.mp3">
        </audio>
    </div>

    <div class="bio" style="margin-top: 25px;">
        <h2 style="margin-top: -1px; margin-left: 15px; font-family: Geologica; font-size: 26px; color: white;">Частушка</h2>
        <p style="margin-top: -25px; margin-left: 15px; font-family:Geologica; color: grey;">Karna.val</p>
        <audio controls style="margin-top: -15px;">
        <source src="../components/karna.val-chastushka.mp3">
        </audio>
    </div>
</template>
    
<style scoped>
    audio {
        width: 90vw;
        border-radius: 25px;
    }
    .bio {
        background-color: rgb(75, 77, 78);
        width: 90vw;
        height: 22vw;
        border-radius: 25px;
        margin-left: 15px;
        margin-top: 20px
    }
    .header {
        background-color: rgb(84, 89, 94);
        width: 100vw;
        height: 15vw;
        margin: 0;
        position: relative;
    }
    .Artist {
        display: flex;
        overflow-x: auto;
        margin-top: 50px;
    }
</style>
    