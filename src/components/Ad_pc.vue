<template>
    
    <div class="cont">
        
        <div class="blur_img"></div>
        <img class="backimg" src="@/assets/Background.png" alt="#">
        <div class="text">
            <h1>ИДЕАЛЬНЫЙ ПК</h1><h3>Лучшие компьютеры, которые вы можете найти! Подбери себе идеальную готовую сборку для работы, для стриминга, для любых нужд.
        </h3>
        </div>
    
        <img class="m_pc" src="@/assets/Main_pc.png" alt="#">
        <div class="back"></div>
        <div class="header">
            <h2>Breaker-1</h2>
        <div class="links">
            <ul>
                <li>Город</li>
                <li>О нас</li>
                <li>Магазин</li>
                

            </ul>
            <svg class="bucket" width="37" height="40" viewBox="0 0 37 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M1 10.4819H35.1029L33.2083 38.9271H2.89461L1 10.4819Z" stroke="white" stroke-opacity="0.8" stroke-width="2" stroke-linejoin="round"/>
                <path d="M10.4727 14.6958V1H25.6295V14.6958" stroke="white" stroke-opacity="0.8" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M10.4727 30.4988H25.6295" stroke="white" stroke-opacity="0.8" stroke-width="2" stroke-linecap="round"/>
                </svg>
            <div class="avatar"></div>
        </div>
        </div>
    </div>
    
    
    
</template>

<script>
    export default{

    }
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');

    li{
        margin-left: 20px;
        display: inline;
        list-style: none;
        font-family: 'Comfortaa';
        font-style: normal;
        font-weight: 400;
        font-size: 28px;
        line-height: 31px;
        color: #dddddd;
        transition: 0.1s;
        cursor: pointer;
    }

    .underline{
        
    }
    li:hover{
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        backdrop-filter: blur(15px);

        
        color: white;
        
    }
    .bucket:hover{
        color: #FFFFFF;
        text-shadow: 0px 0px 9px rgba(255, 255, 255, 0.72);
    }

    .bucket{
        cursor: pointer;
        margin: 0 0 0 20px;
    }
    .avatar{
        width: 64px;
        height: 64px;
        margin-left: 20px;
        box-shadow: 1px -1px 5px 1px rgba(0, 194, 255, 0.72), -1px 1px 5px 1px rgba(189, 0, 255, 0.72);
        border-radius: 44px;
    }
    .links{
        margin-right: 50px;
        display: flex;
        align-items: center;

    }
    .header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        background: rgba(29, 32, 62, 0.3);
        position: absolute;
        width: 100%;
        height: 100px;
        
    }
    h1{
        font-family: 'Arial';
        font-style: normal;
        font-weight: 700;
        font-size: 96px;
        text-align: center;
        color: white;
        line-height: 0;
        
    }

    h2{
        color: white;
        font-family: 'Arial';
        font-size: 30px;
        margin-left: 50px;
        font-family: 'Arial';
    }

    h3{
        padding-left: 450px;
        padding-right: 450px;
        font-family: 'Comfortaa';
        font-style: normal;
        font-weight: 300;
        font-size: 32px;
        line-height: 36px;
        color: white;
        
        
        text-align: center;
    }
    .text{
        top: 200px;
        margin-left: auto;
        margin-right: auto;
        left: 0;
        right: 0;
        position: absolute;
    }
    .m_pc{
        top: 500px;
        margin-left: auto;
        margin-right: auto;
        left: 0;
        right: 0;
        text-align: center;
        position: absolute;
        width: 728px;
        height: 728px;
        cursor: pointer;
        transition: 0.5s;
    }
    .m_pc:hover{
        width: 792px;
        height: 792px;

    }
    .cont{
        height: 1258px;
        width: 1920px;
        display: flex;
    }
    .blur_img{
        background: rgba(29, 32, 62, 0.5);
        backdrop-filter: blur(10px);
        width: 1920px;
        height: 720px;
        position: absolute;

    }
    .backimg{
        
        width: 1920px;
        height: 720px;
    }
    .back{
        width: 2240px;
        height: 611.5px;
        background-color: #1D203E;;
    }
</style>