<template>
    <div class="container-fluid"> 
        <div class="Notification">
            <div class="settings">
                <h1 class="h1">Notification Settings</h1>
            </div>
            <!--icons for device -->

            <!--The icons are SVG  -->
            <div class="Receive ms-1">
            <p><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path d="M12.0201 2.91016C8.71009 2.91016 6.02009 5.60016 6.02009 8.91016V11.8002C6.02009 12.4102 5.76009 13.3402 5.45009 13.8602L4.30009 15.7702C3.59009 16.9502 4.08009 18.2602 5.38009 18.7002C9.69009 20.1402 14.3401 20.1402 18.6501 18.7002C19.8601 18.3002 20.3901 16.8702 19.7301 15.7702L18.5801 13.8602C18.2801 13.3402 18.0201 12.4102 18.0201 11.8002V8.91016C18.0201 5.61016 15.3201 2.91016 12.0201 2.91016Z" stroke="#3AC2CB" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round"/> <path d="M13.8699 3.19994C13.5599 3.10994 13.2399 3.03994 12.9099 2.99994C11.9499 2.87994 11.0299 2.94994 10.1699 3.19994C10.4599 2.45994 11.1799 1.93994 12.0199 1.93994C12.8599 1.93994 13.5799 2.45994 13.8699 3.19994Z" stroke="#3AC2CB" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/> <path d="M15.02 19.0601C15.02 20.7101 13.67 22.0601 12.02 22.0601C11.2 22.0601 10.44 21.7201 9.90002 21.1801C9.36002 20.6401 9.02002 19.8801 9.02002 19.0601" stroke="#3AC2CB" stroke-width="1.5" stroke-miterlimit="10"/>
            </svg>Where to receive notifications</p>

                <div class="apple-watch">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30" fill="none">
                        <g clip-path="url(#clip0_2671_2027)">
                        <path d="M19.2854 5.23828H8.80964C6.97154 5.23828 5.47607 6.73521 5.47607 8.57533V21.4251C5.47607 23.2652 6.97154 24.7621 8.80964 24.7621H19.2854C21.1235 24.7621 22.6189 23.2652 22.6189 21.4251V8.57533C22.6189 6.73521 21.1235 5.23828 19.2854 5.23828ZM21.6665 21.4251C21.6665 22.7402 20.5983 23.8097 19.2853 23.8097H8.80957C7.49658 23.8097 6.42836 22.7402 6.42836 21.4251V8.57533C6.42836 7.26018 7.49658 6.19071 8.80957 6.19071H19.2853C20.5983 6.19071 21.6665 7.26025 21.6665 8.57533V21.4251Z" fill="#3AC2CB"/> <path d="M20.2302 5.62918L19.5332 1.79499C19.35 0.788225 18.4059 0 17.3836 0H10.7113C9.68915 0 8.74481 0.788225 8.56164 1.79499L7.86465 5.62918C7.83926 5.76821 7.87728 5.91085 7.96761 6.01932C8.05794 6.12779 8.19187 6.1905 8.33312 6.1905H19.7617C19.9029 6.1905 20.0368 6.12765 20.1273 6.01932C20.2177 5.91092 20.2556 5.76821 20.2302 5.62918ZM8.90371 5.23807L9.49858 1.96519C9.59861 1.41602 10.1538 0.952358 10.7112 0.952358H17.3835C17.9409 0.952358 18.4961 1.4165 18.5961 1.96519L19.1911 5.23807H8.90371Z" fill="#3AC2CB"/> <path d="M20.1273 23.9807C20.037 23.8723 19.903 23.8096 19.7618 23.8096H8.33321C8.19202 23.8096 8.05809 23.8724 7.96762 23.9807C7.87715 24.0891 7.83927 24.2318 7.86466 24.3709L8.56172 28.2051C8.74497 29.2118 9.68923 30.0001 10.7113 30.0001H17.3836C18.406 30.0001 19.3501 29.2118 19.5333 28.2051L20.2302 24.3709C20.2556 24.2318 20.2177 24.0891 20.1273 23.9807ZM18.5963 28.0347C18.4963 28.5836 17.9411 29.0476 17.3837 29.0476H10.7114C10.154 29.0476 9.59876 28.5839 9.4988 28.0347L8.9038 24.7619H19.1912L18.5963 28.0347Z" fill="#3AC2CB"/> <path d="M23.1658 10H22.1427C21.8797 10 21.6665 10.213 21.6665 10.4762V14.7619C21.6665 15.0251 21.8797 15.2381 22.1427 15.2381H23.1658C23.9145 15.2381 24.5236 14.629 24.5236 13.8803V11.3579C24.5236 10.6092 23.9145 10 23.1658 10ZM23.5713 13.8802C23.5713 14.1039 23.3895 14.2857 23.1658 14.2857H22.6189V10.9524H23.1658C23.3895 10.9524 23.5713 11.1341 23.5713 11.3578V13.8802Z" fill="#3AC2CB"/> <path d="M9.14589 7.28254C8.95993 7.09658 8.65852 7.09658 8.47255 7.28254L7.28205 8.47304C7.09609 8.65901 7.09609 8.96041 7.28205 9.14638C7.37503 9.23936 7.49697 9.28589 7.61869 9.28589C7.74048 9.28589 7.86241 9.23936 7.95532 9.14638L9.14582 7.95588C9.33186 7.76991 9.33186 7.46851 9.14589 7.28254Z" fill="#3AC2CB"/> <path d="M11.0505 7.28254C10.8646 7.09658 10.5632 7.09658 10.3772 7.28254L7.75813 9.90161C7.57216 10.0876 7.57216 10.389 7.75813 10.575C7.85111 10.6679 7.97304 10.7145 8.09476 10.7145C8.21655 10.7145 8.33848 10.6679 8.4314 10.575L11.0505 7.95588C11.2365 7.76991 11.2365 7.46851 11.0505 7.28254Z" fill="#3AC2CB"/>
                        </g>
                        <defs> <clipPath id="clip0_2671_2027"> <rect width="30" height="30" fill="white"/> </clipPath> </defs>
                    </svg>
                    <p class="text-watch">Apple Watch</p>
                </div>
                <div class="app">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30" fill="none"> <path d="M21.1059 0H8.89395C7.61566 0 6.57568 1.03998 6.57568 2.3182V27.6817C6.57568 28.96 7.61566 29.9999 8.89395 29.9999H21.106C22.3843 29.9999 23.4243 28.96 23.4243 27.6817V2.3182C23.4242 1.03998 22.3843 0 21.1059 0V0ZM12.1515 0.878906H17.8484V1.37883C17.8484 1.65451 17.6241 1.87875 17.3484 1.87875H12.6515C12.3758 1.87875 12.1516 1.65445 12.1516 1.37883V0.878906H12.1515ZM22.5453 27.6818C22.5453 28.4754 21.8996 29.1211 21.1059 29.1211H8.89395C8.10029 29.1211 7.45459 28.4754 7.45459 27.6818V2.3182C7.45459 1.52455 8.10029 0.878906 8.89395 0.878906H11.2727V1.37883C11.2727 2.13914 11.8913 2.75766 12.6515 2.75766H17.3484C18.1088 2.75766 18.7273 2.13908 18.7273 1.37883V0.878906H21.106C21.8996 0.878906 22.5454 1.52461 22.5454 2.3182V27.6818H22.5453Z" fill="#3AC2CB"/> <path d="M17.3483 27.2422H12.6514C12.4087 27.2422 12.2119 27.4389 12.2119 27.6816C12.2119 27.9243 12.4087 28.1211 12.6514 28.1211H17.3483C17.591 28.1211 17.7878 27.9243 17.7878 27.6816C17.7878 27.4389 17.591 27.2422 17.3483 27.2422Z" fill="#3AC2CB"/> <path d="M10.3031 10.7423H13.1213C13.8816 10.7423 14.5002 10.1238 14.5002 9.3635V5.60588C14.5002 4.84557 13.8816 4.22705 13.1213 4.22705H10.3031C9.54283 4.22705 8.92432 4.84563 8.92432 5.60588V9.36344C8.92432 10.1238 9.54283 10.7423 10.3031 10.7423ZM9.80322 5.60588C9.80322 5.3302 10.0275 5.10596 10.3031 5.10596H13.1213C13.397 5.10596 13.6212 5.33025 13.6212 5.60588V9.36344C13.6212 9.63912 13.397 9.86336 13.1213 9.86336H10.3031C10.0275 9.86336 9.80322 9.63906 9.80322 9.36344V5.60588Z" fill="#3AC2CB"/> <path d="M16.8788 5.10596H19.697C19.9727 5.10596 20.1969 5.33025 20.1969 5.60588C20.1969 5.84857 20.3937 6.04533 20.6364 6.04533C20.8791 6.04533 21.0758 5.84857 21.0758 5.60588C21.0758 4.84557 20.4573 4.22705 19.697 4.22705H16.8788C16.1185 4.22705 15.5 4.84563 15.5 5.60588V9.36344C15.5 10.1238 16.1186 10.7423 16.8788 10.7423H19.697C20.4573 10.7423 21.0758 10.1237 21.0758 9.36344V7.48463C21.0758 7.24193 20.8791 7.04518 20.6364 7.04518C20.3937 7.04518 20.1969 7.24193 20.1969 7.48463V9.36344C20.1969 9.63912 19.9726 9.86336 19.697 9.86336H16.8788C16.6031 9.86336 16.3789 9.63906 16.3789 9.36344V5.60588C16.3789 5.33025 16.6032 5.10596 16.8788 5.10596Z" fill="#3AC2CB"/> <path d="M10.3031 18.2574H13.1213C13.8816 18.2574 14.5002 17.6388 14.5002 16.8786V13.121C14.5002 12.3607 13.8816 11.7422 13.1213 11.7422H10.3031C9.54283 11.7422 8.92432 12.3608 8.92432 13.121V16.8786C8.92432 17.6388 9.54283 18.2574 10.3031 18.2574ZM9.80322 13.121C9.80322 12.8453 10.0275 12.6211 10.3031 12.6211H13.1213C13.397 12.6211 13.6212 12.8454 13.6212 13.121V16.8786C13.6212 17.1543 13.397 17.3785 13.1213 17.3785H10.3031C10.0275 17.3785 9.80322 17.1542 9.80322 16.8786V13.121Z" fill="#3AC2CB"/> <path d="M19.697 11.7422H16.8788C16.1185 11.7422 15.5 12.3608 15.5 13.121V16.8786C15.5 17.6389 16.1186 18.2574 16.8788 18.2574H19.697C20.4573 18.2574 21.0758 17.6388 21.0758 16.8786V13.121C21.0758 12.3608 20.4573 11.7422 19.697 11.7422ZM20.1969 16.8786C20.1969 17.1543 19.9726 17.3785 19.697 17.3785H16.8788C16.6031 17.3785 16.3789 17.1542 16.3789 16.8786V13.121C16.3789 12.8453 16.6032 12.6211 16.8788 12.6211H19.697C19.9727 12.6211 20.1969 12.8454 20.1969 13.121V16.8786Z" fill="#3AC2CB"/> <path d="M14.5002 24.3937V22.515C14.5002 22.2723 14.3034 22.0755 14.0607 22.0755C13.818 22.0755 13.6212 22.2723 13.6212 22.515V24.3937C13.6212 24.6694 13.397 24.8936 13.1213 24.8936H10.3031C10.0275 24.8936 9.80322 24.6693 9.80322 24.3937V20.6362C9.80322 20.3605 10.0275 20.1362 10.3031 20.1362H13.1213C13.397 20.1362 13.6212 20.3605 13.6212 20.6362C13.6212 20.8788 13.818 21.0756 14.0607 21.0756C14.3034 21.0756 14.5002 20.8788 14.5002 20.6362C14.5002 19.8758 13.8816 19.2573 13.1213 19.2573H10.3031C9.54283 19.2573 8.92432 19.8759 8.92432 20.6362V24.3937C8.92432 25.154 9.54289 25.7725 10.3031 25.7725H13.1213C13.8816 25.7725 14.5002 25.154 14.5002 24.3937Z" fill="#3AC2CB"/> <path d="M19.697 19.2573H16.8788C16.1185 19.2573 15.5 19.8759 15.5 20.6362V24.3937C15.5 25.154 16.1186 25.7725 16.8788 25.7725H19.697C20.4573 25.7725 21.0758 25.154 21.0758 24.3937V20.6362C21.0758 19.8759 20.4573 19.2573 19.697 19.2573ZM20.1969 24.3938C20.1969 24.6695 19.9726 24.8937 19.697 24.8937H16.8788C16.6031 24.8937 16.3789 24.6694 16.3789 24.3938V20.6362C16.3789 20.3605 16.6032 20.1363 16.8788 20.1363H19.697C19.9727 20.1363 20.1969 20.3606 20.1969 20.6362V24.3938Z" fill="#3AC2CB"/> <path d="M11.2422 7.92432H12.1816C12.4243 7.92432 12.621 7.72756 12.621 7.48486C12.621 7.24217 12.4243 7.04541 12.1816 7.04541H11.2422C10.9995 7.04541 10.8027 7.24217 10.8027 7.48486C10.8027 7.72756 10.9995 7.92432 11.2422 7.92432Z" fill="#3AC2CB"/> <path d="M18.7577 13.6211H17.8184C17.5757 13.6211 17.3789 13.8179 17.3789 14.0605C17.3789 14.3032 17.5757 14.5 17.8184 14.5H18.7577C19.0004 14.5 19.1972 14.3032 19.1972 14.0605C19.1972 13.8179 19.0004 13.6211 18.7577 13.6211Z" fill="#3AC2CB"/> <path d="M11.2422 22.0757C10.9995 22.0757 10.8027 22.2724 10.8027 22.5151C10.8027 22.7578 10.9995 22.9546 11.2422 22.9546H12.1816C12.4243 22.9546 12.621 22.7578 12.621 22.5151C12.621 22.2724 12.4243 22.0757 12.1816 22.0757H11.2422Z" fill="#3AC2CB"/> <path d="M18.7577 15.5H17.8184C17.5757 15.5 17.3789 15.6968 17.3789 15.9395C17.3789 16.1821 17.5757 16.3789 17.8184 16.3789H18.7577C19.0004 16.3789 19.1972 16.1821 19.1972 15.9395C19.1972 15.6968 19.0004 15.5 18.7577 15.5Z" fill="#3AC2CB"/>
                    </svg>
                    <p class="text-watch">App</p>
                </div>
                <div class="email">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30" fill="none">
                    <path d="M23.75 12.5317V6.25002C23.75 4.87125 22.6288 3.75 21.25 3.75H2.49996C1.12119 3.75 0 4.87119 0 6.25002V18.75C0 20.1288 1.12119 21.25 2.50002 21.25H16.5165C17.3354 24.1313 19.9847 26.25 23.125 26.25C24.3335 26.25 25.5219 25.932 26.5631 25.3296C26.8616 25.1569 26.9641 24.7748 26.7908 24.4757C26.618 24.1767 26.2354 24.0735 25.9369 24.2481C25.086 24.74 24.1137 25 23.125 25C20.0231 25 17.5 22.4768 17.5 19.375C17.5 16.2732 20.0232 13.75 23.125 13.75C26.2267 13.75 28.75 16.2732 28.75 19.375V20C28.75 20.6891 28.189 21.25 27.5 21.25C26.8109 21.25 26.25 20.6891 26.25 20V17.5C26.25 17.1546 25.9704 16.875 25.625 16.875C25.4569 16.875 25.3058 16.943 25.1936 17.0508C24.6412 16.5585 23.9213 16.25 23.125 16.25C21.402 16.25 20 17.652 20 19.375C20 21.098 21.402 22.5 23.125 22.5C24.0564 22.5 24.8846 22.0822 25.4576 21.4335C25.9104 22.0767 26.6553 22.5 27.5 22.5C28.8788 22.5 30 21.3788 30 20V19.375C30 15.7951 27.2487 12.8489 23.75 12.5317ZM2.50002 4.99998H21.25C21.276 4.99998 21.2978 5.01328 21.3235 5.01486L12.3889 12.3486C12.071 12.5488 11.6101 12.5073 11.4032 12.3804L2.4273 5.01475C2.45268 5.01322 2.47424 4.99998 2.50002 4.99998ZM22.5 12.5317C19.0013 12.8489 16.25 15.7951 16.25 19.375C16.25 19.586 16.2629 19.7938 16.2816 20H2.50002C1.81096 20 1.25004 19.4391 1.25004 18.7501V6.25002C1.25004 6.07301 1.28912 5.90584 1.3558 5.75314L10.6654 13.3875C11.0291 13.6249 11.4472 13.7501 11.8751 13.7501C12.2865 13.7501 12.6887 13.6341 13.0427 13.4144C13.0781 13.3955 13.1116 13.3729 13.1434 13.3467L22.3942 5.75303C22.4609 5.90584 22.5001 6.07301 22.5001 6.25008V12.5317H22.5ZM23.125 21.25C22.0911 21.25 21.25 20.409 21.25 19.375C21.25 18.3411 22.0911 17.5 23.125 17.5C24.159 17.5 25 18.3411 25 19.375C25 20.409 24.159 21.25 23.125 21.25Z" fill="#3AC2CB"/>
                    </svg>
                    <p class="text-watch">Email</p>
                </div>
                <div class="phone">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30" fill="none">
                    <path d="M21.2252 0H8.77451C7.66672 0 6.76562 0.901099 6.76562 2.00889V27.9911C6.76562 29.0988 7.66672 30 8.77451 30H21.2252C22.333 30 23.2341 29.0989 23.2341 27.9911V2.00889C23.2341 0.901099 22.333 0 21.2252 0ZM22.4838 27.9911C22.4838 28.6852 21.919 29.25 21.2249 29.25H8.77451C8.0804 29.25 7.51562 28.6852 7.51562 27.9911V24.6023H22.4838V27.9911ZM22.4838 23.8523H7.51562V4.15686H22.4838V23.8523ZM22.4838 3.40686H7.51562V2.00889C7.51562 1.31477 8.0804 0.75 8.77451 0.75H21.2249C21.919 0.75 22.4838 1.31477 22.4838 2.00889V3.40686Z" fill="#3AC2CB"/> <path d="M14.9999 25.4473C14.1487 25.4473 13.4561 26.1399 13.4561 26.9911C13.4561 27.8424 14.1487 28.5346 14.9999 28.5346C15.8511 28.5346 16.5438 27.842 16.5438 26.9908C16.5438 26.1396 15.8511 25.4473 14.9999 25.4473ZM14.9999 27.785C14.5623 27.785 14.2061 27.4288 14.2061 26.9911C14.2061 26.5535 14.5623 26.1973 14.9999 26.1973C15.4375 26.1973 15.7938 26.5535 15.7938 26.9911C15.7938 27.4288 15.4375 27.785 14.9999 27.785Z" fill="#3AC2CB"/>
                    </svg>
                    <p class="text-watch">Phone</p>
                </div>
                <div class="desktop">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30" fill="none">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M5 4.375C3.27411 4.375 1.875 5.77411 1.875 7.5V20C1.875 21.7259 3.27411 23.125 5 23.125H12.7388L11.4887 25.625H8.75C8.40483 25.625 8.125 25.9049 8.125 26.25C8.125 26.5951 8.40483 26.875 8.75 26.875H11.8615C11.8702 26.8751 11.8789 26.8751 11.8876 26.875H18.1125C18.1211 26.8751 18.1298 26.8751 18.1385 26.875H21.25C21.5951 26.875 21.875 26.5951 21.875 26.25C21.875 25.9049 21.5951 25.625 21.25 25.625H18.5112L17.2612 23.125H25C26.7259 23.125 28.125 21.7259 28.125 20V7.5C28.125 5.77411 26.7259 4.375 25 4.375H5ZM17.1138 25.625L15.8638 23.125H14.1362L12.8862 25.625H17.1138ZM16.2364 21.875C16.2451 21.8749 16.2539 21.8749 16.2626 21.875H25C26.0355 21.875 26.875 21.0355 26.875 20V7.5C26.875 6.46446 26.0355 5.625 25 5.625H5C3.96446 5.625 3.125 6.46446 3.125 7.5V20C3.125 21.0355 3.96446 21.875 5 21.875H13.7374C13.7461 21.8749 13.7549 21.8749 13.7635 21.875H16.2364Z" fill="#3AC2CB"/>
                    </svg>
                    <p class="text-watch">Desktop</p>
                </div>
            </div> 
            <!--List of recieved notifications -->
            <div class="orders">
       <ul> 
        <li v-for="Order in Orders" :key="Order">{{ Order }}</li> 
       </ul>
                <!--Checkboxes choosing -->
                <div class="form-checkbox col-sm-3 col-md-6 mb-5">
                    <div v-for="n in 5" :key="n" class="form-check">
                    <div v-for="n in 10" :key="n">
                        <input class="form-check-input" type="checkbox" id="flexCheckDefault">
                        <label class="form-check-label" for="flexCheckDefault"></label>
                    </div>
                    </div>
                </div>
            </div>

            <!--The icon of audio is SVG  -->
            <div class="audio ms-1">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path d="M6.28016 21.9998C8.00328 21.9998 9.40016 20.6029 9.40016 18.8798C9.40016 17.1566 8.00328 15.7598 6.28016 15.7598C4.55703 15.7598 3.16016 17.1566 3.16016 18.8798C3.16016 20.6029 4.55703 21.9998 6.28016 21.9998Z" stroke="#3AC2CB" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/> <path d="M20.8399 16.8003V4.60034C20.8399 2.00034 19.2099 1.64034 17.5599 2.09034L11.3199 3.79034C10.1799 4.10034 9.3999 5.00034 9.3999 6.30034V8.47034V9.93034V18.8703" stroke="#3AC2CB" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/> <path d="M17.7201 19.9197C19.4432 19.9197 20.8401 18.5228 20.8401 16.7997C20.8401 15.0766 19.4432 13.6797 17.7201 13.6797C15.997 13.6797 14.6001 15.0766 14.6001 16.7997C14.6001 18.5228 15.997 19.9197 17.7201 19.9197Z" stroke="#3AC2CB" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/> <path d="M9.3999 9.52039L20.8399 6.40039" stroke="#3AC2CB" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              </svg><p class="text-audio ms-1">Audio</p>
            </div>
            <div class="form-check-audio ms-2">
                    <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label ms-2" id="label" for="flexCheckDefault">Play The Sound Every Time When A Notification Arrives</label>
            </div>
                    <br>
                    <p class="Receive mt-0 ms-2">Choose An Audio</p>
                    
                    <!--The Radios tones -->
                <div class="form-check-choose-audio col-sm-3 col-md-3 col-lg-4 ms-1 mb-3">
                    <div v-for="sound in sounds" :key="sound.id" class="form-Sound mb-2">
                        <label class="form-check-label">
                            <input v-on:click="playSound(sound)" class="form-check-input-radio mb-4 me-1" type="radio" :id="sound.id" name="soundSelection"/>
                            <span class="checkmark"></span> {{ sound.label }}
                        </label>
                    </div>
                </div>

                    <!--button save all-->
            <div>
              <button class="btn_save ms-2">Save</button>
            </div>
        </div>
    </div>
</template>

<script>

export default {
data(){
    return{

        Orders: [
            "The order has been shipped from the store", 
            "Request pending evaluation", "There are discounts", 
            "{Order number} has been successfully paid", 
            "Send coupons", 
            "Password changed successfully", 
            "Provide quantity of a product", 
            "The request was rejected by the store", 
            "Your request to create a store was rejected, try again", 
            "Receive messages"
        ],
        sounds: [
            { id: "CoinsSound", label: "Coins", file: require('@/components/tones/coins/coins-497.mp3'), },
            { id: "CheckedSound", label: "Checked", file: require('@/components/tones/checked/message-tone-checked-off.mp3') },
            { id: "CapisciSound", label: "Capisci", file: require('@/components/tones/Capisci/capisci-521.mp3') },
            { id: "ArpeggioSound", label: "Arpeggio", file: require('@/components/tones/Arpeggio/arpeggio-467.mp3') },
            { id: "WhenToneSound", label: "When Tone", file: require('@/components/tones/when tone/when-604.mp3') },
            { id: "PedanticSound", label: "Pedantic", file: require('@/components/tones/Pedantic/pedantic-490.mp3') },
            { id: "PullOutSound", label: "Pull Out", file: require('@/components/tones/pull out/pull-out-551.mp3') },
            { id: "SeeIDidSound", label: "See I Did", file: require('@/components/tones/see i did/i-did-it-message-tone.mp3') },
            { id: "SwfitSound", label: "Swift", file: require('@/components/tones/swfit/notification-tone-swift-gesture.mp3') }
        ]
    };
  },

  // Sound effect logic
  methods: {
    playSound(sound) {
      const audio = new Audio(sound.file);
      audio.play();
    }
  }
};

</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap");

.h1 {
    color: var(--fafafa, #FAFAFA);
    font-size: 24px;
}

.orders {
    color: #FFF;
    font-size: 16px;
    line-height: 47px;
    margin-top: 5px;
    display: flex;
}

.Receive  {
    color: var(--a-4-b-4-cb, #A4B4CB);
    font-size: 18px;
    text-transform: capitalize;
    font-weight: 400;
    margin-top: 49px;   
    display: flex; 
}

.apple-watch{
    margin-left: 407px;
    text-align: center;
}
.app{
    margin-left: 148px;
    text-align: center;
}
.email{
    margin-left: 183px;
    text-align: center;
}
.phone{
    margin-left: 171px;
    text-align: center;
}
.desktop{
    margin-left: 162px;
    text-align: center;
}

.text-watch{
    color: #3AC2CB;
}

.form-checkbox{
    display: flex;
    margin-top: 8px;
    margin-left: 101px;
}
.form-check {
    margin-left: 202px;
    text-align: center;
}
.form-check-input:checked {
    background-color: #3AC2Cb;
    box-shadow: none;
}
.form-check-input{
    background-color: #040D21;
    border-color: #3AC2CB;
    border-radius: 5px;
    
}
#label {
    color: var(--fafafa, #FAFAFA);
    font-size: 18px;
    text-transform: capitalize;
    margin-left: 10px;
    margin-right: 29px;
    margin-bottom: 23px;
}

.form-check-label{
    color: var(--fafafa, #FAFAFA);
    font-size: 14px;
}

.audio  {
    color: var(--a-4-b-4-cb, #A4B4CB);
    font-size: 18px;
    display: flex; 
}

.btn_save{
    width: 180px;
    height: 48px;
    background-color:#3AC2CB;
    border-radius: 10px;
    border-style: none;
    color: var(--fafafa, #FAFAFA);
    font-size: 20px;
}

/* Styles for the container */
.form-check-choose-audio {
    display: flex;
    flex-wrap: wrap;
}

/* Styles for each item */
.form-Sound {
    width: 25%; /* Each item will take 25% of the container's width to display 4 items in a row */
    padding: 5px;
}

/* Custom radio button styles */
.form-check-input-radio {
    position: absolute;
    opacity: 0;
    cursor: pointer;
}

.checkmark {
    position: relative;
    display: inline-block;
    width: 17px;
    height: 17px;
    border: 1px solid #3AC2CB;
    border-radius: 5px;
    margin-right: 5px;
}

/* Show the custom checkmark when the radio button is checked */
.form-check-input-radio:checked ~ .checkmark {
    background-color: #3AC2CB;
}

/* Style the inner checkmark shape */
.checkmark:after {
    content: "";
    position: absolute;
    display: none;
}

/* Show the checkmark shape when the radio button is checked */
.form-check-input-radio:checked ~ .checkmark:after {
    display: block;
    left: 6px;
    top: 2px;
    width: 5px;
    height: 10px;
    border: solid #FAFAFA;
    border-width: 0 3px 3px 0;
    transform: rotate(45deg);
}
</style>