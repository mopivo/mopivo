## Hi there 👋

<svg viewBox="0 0 1440 320" width="1440" height="320" xmlns="http://www.w3.org/2000/svg">
    <style>
        .wave {
            animation: wave-animation 8s linear infinite;
        }

        @keyframes wave-animation {
            0% {
                transform: translateX(0%);
            }
            100% {
                transform: translateX(100%);
            }
        }
    </style>
    
    <defs>
        <path 
            id="wave" 
            d="M0,160 
               C320,300 420,300 740,160 
               C1060,20 1120,20 1440,160 
               V0 H0"
            fill="#0099ff" 
            fill-opacity="0.2"
        />
    </defs>
    
    <use class="wave" href="#wave"/>
    <use class="wave" x="-100%" href="#wave"/>
</svg>

