### Hi,there🐧

色々やってる  
ペンギンかわええ  

* [Profile](https://satooru.me)
* [Others](https://satooru.nagoya)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SatooRu65536&layout=compact&hide=html)


<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        width: 100vw;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: lightblue;
    }

    /* ペンギン */

    .🐧 {
        position: absolute;
        bottom: 15px;
        animation: surfing-y 2s infinite ease-in-out;
        animation-direction: alternate;
        transform-origin: bottom 70%;
    }

    .penguin-body {
        height: 30px;
        width: 20px;
        border-radius: 30%;
        border-top-left-radius: 40%;
        border-top-right-radius: 40%;
        background-color: #292929;
        position: relative;

        animation: surfing 2s infinite ease-in-out;
        animation-direction: alternate;
        transform-origin: bottom center;
    }

    .penguin-body::after {
        content: "";
        position: absolute;
        bottom: 1.2px;
        left: 3.5px;
        height: 15px;
        width: 13px;
        background-color: #f3f3f3;
        border-radius: 48%;
    }

    .penguin-eyes::before,
    .penguin-eyes::after {
        content: "";
        background-color: #f3f3f3;
        position: absolute;
        animation: move-eyes 3s infinite steps(1);
        animation-delay: 0.5s;
    }

    .penguin-eyes::before {
        left: 5px;
    }

    .penguin-eyes::after {
        right: 5px;
    }

    .penguin-mouth {
        position: absolute;
        top: 10px;
        left: 8px;
        width: 0;
        height: 0;
        border-left: 2px solid transparent;
        border-right: 2px solid transparent;
        border-top: 2px solid orange;
        z-index: 2;
    }

    .penguin-wings::before,
    .penguin-wings::after {
        content: "";
        position: absolute;
        top: 14px;
        width: 0;
        height: 0;
        border-top: 4px solid transparent;
        border-bottom: 6px solid transparent;
        z-index: -1;
    }

    .penguin-wings::before {
        animation: move-wing-left 3s infinite;
    }

    .penguin-wings::after {
        animation: move-wing-right 3s infinite;
    }

    .penguin-leg::before,
    .penguin-leg::after {
        content: "";
        width: 5px;
        height: 3px;
        background-color: orange;
        position: absolute;
        border-radius: 30%;
        bottom: -1px;
    }

    .penguin-leg::before {
        left: 2px;
    }

    .penguin-leg::after {
        right: 2px;
    }

    .surfboard {
        width: 50px;
        height: 10px;
        background-color: #f3f3f3;
        border-radius: 50%;
        position: absolute;
        top: 85%;
        left: -70%;
        z-index: -10;
    }

    .surfboard::before {
        content: "";
        width: 40px;
        height: 1px;
        background-color: #292929;
        position: absolute;
        border-radius: 20%;
        top: 45%;
        left: 10%;
        z-index: -1;
    }

    @keyframes move-eyes {
        0% {
            width: 1.5px;
            height: 3.5px;
            border-radius: 50%;
            top: 6px;
        }

        50% {
            width: 2px;
            height: 0.5px;
            top: 8px;
            border-top-left-radius: 3px;
            border-top-right-radius: 3px;
        }

        100% {
            width: 1.5px;
            height: 3.5px;
            border-radius: 50%;
            top: 6px;
        }
    }

    @keyframes move-wing-left {
        0% {
            border-left: 6px solid #292929;
            transform: rotate(25deg);
            left: -2px;
        }

        50% {
            left: -3.5px;
            top: 13px;
            transform: rotate(40deg);
        }

        100% {
            border-left: 6px solid #292929;
            transform: rotate(25deg);
            left: -2px;
        }
    }

    @keyframes move-wing-right {
        0% {
            border-right: 6px solid #292929;
            transform: rotate(-25deg);
            right: -2px;
        }

        50% {
            right: -3.5px;
            top: 13px;
            transform: rotate(-40deg);
        }

        100% {
            border-right: 6px solid #292929;
            transform: rotate(-25deg);
            right: -2px;
        }
    }

    @keyframes surfing {
        0% {
            transform: rotate(-10deg);
        }

        100% {
            transform: rotate(10deg);
        }
    }

    @keyframes surfing-y {
        0% {
            transform: translateY(-10px);
        }

        100% {
            transform: translateY(5px);
        }
    }

    /* 波 */

    .wave {
        width: 100vw;
        margin: 0 auto;
        overflow: hidden;
        position: fixed;
        bottom: -5px;
        z-index: -10;
    }

    .wave svg use {
        fill: #3168dd;
        animation: wave linear 4s infinite;
    }

    .wave svg use:nth-of-type(1),
    .wave svg use:nth-of-type(2),
    .wave svg use:nth-of-type(3),
    .wave svg use:nth-of-type(4),
    .wave svg use:nth-of-type(5),
    .wave svg use:nth-of-type(6) {
        opacity: 0.1;
    }

    .wave svg use:nth-of-type(1) {
        animation-duration: 5s;
    }

    .wave svg use:nth-of-type(2) {
        animation-duration: 4s;
    }

    .wave svg use:nth-of-type(3) {
        animation-duration: 3s;
    }

    .wave svg use:nth-of-type(4) {
        animation-duration: 5s;
    }

    .wave svg use:nth-of-type(5) {
        animation-duration: 4s;
    }

    .wave svg use:nth-of-type(6) {
        animation-duration: 3s;
    }

    @keyframes wave {
        0% {
            transform: translate(0%);
        }

        100% {
            transform: translate(-50%);
        }
    }
</style>

<body>
    <div class="🐧">
        <div class="penguin-body">
            <div class="penguin-face">
                <div class="penguin-eyes"></div>
                <div class="penguin-mouth"></div>
            </div>
            <div class="penguin-wings"></div>
            <div class="penguin-leg"></div>
            <div class="surfboard"></div>
        </div>
    </div>
    <div class="wave">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 100" width="1200" height="200">
            <defs>
                <path id="wave"
                    d="M2100,25c-100-33.33-200-33.33-300,0-100,33.33-200,33.33-300,0-100-33.33-200-33.33-300,0-100,33.33-200,33.33-300,0-100-33.33-200-33.33-300,0-100,33.33-200,33.33-300,0C200-8.33,100-8.33,0,25V125H2400V25c-100,33.33-200,33.33-300,0Z" />
            </defs>
            <use xlink:href="#wave" />
            <use xlink:href="#wave" x="-30" y="10" />
            <use xlink:href="#wave" x="-60" />
            <use xlink:href="#wave" x="-60" />
            <use xlink:href="#wave" x="-60" />
            <use xlink:href="#wave" x="-60" />
        </svg>
    </div>
</body>