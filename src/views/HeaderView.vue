<template>

<div class="min-h-screen flex-col">
    <div class="text-sm bg-[#f6f8fa]">

        <nav class="bg-[#f6f8fa] flex justify-between items-center py-1.5">
    
            <!-- left start -->
            <div class="mx-3 my-3 flex items-center space-x-4 pl-1.5">
                <div class="flex items-center border border-gray-400 rounded-md px-2 py-1.5">
                    <button  type="button" data-view-component="true" >  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" >
                        <path d="M1 2.75A.75.75 0 0 1 1.75 2h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 2.75Zm0 5A.75.75 0 0 1 1.75 7h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 7.75ZM1.75 12h12.5a.75.75 0 0 1 0 1.5H1.75a.75.75 0 0 1 0-1.5Z"></path>
                        </svg>
                    </button>
                </div>
                
                <a href="#">
                    <!-- <svg t="1718261901708" class="w-10 h-10"  viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="11463" ><path d="M512 0C229.283787 0 0.142041 234.942803 0.142041 524.867683c0 231.829001 146.647305 428.553077 350.068189 497.952484 25.592898 4.819996 34.976961-11.38884 34.976961-25.294314 0-12.45521-0.469203-45.470049-0.725133-89.276559-142.381822 31.735193-172.453477-70.380469-172.453477-70.380469-23.246882-60.569859-56.816233-76.693384-56.816234-76.693385-46.493765-32.58829 3.540351-31.948468 3.540351-31.948467 51.356415 3.71097 78.356923 54.086324 78.356923 54.086324 45.683323 80.19108 119.817417 57.072162 148.993321 43.593236 4.649376-33.91059 17.915029-57.029508 32.50298-70.167195-113.675122-13.222997-233.151301-58.223843-233.1513-259.341366 0-57.285437 19.919806-104.163095 52.678715-140.846248-5.246544-13.265652-22.820334-66.626844 4.990615-138.884127 0 0 42.996069-14.076094 140.760939 53.787741 40.863327-11.644769 84.627183-17.445825 128.177764-17.6591 43.465272 0.213274 87.271782 6.014331 128.135109 17.6591 97.679561-67.906489 140.59032-53.787741 140.59032-53.787741 27.938914 72.257282 10.407779 125.618474 5.118579 138.884127 32.844219 36.683154 52.593405 83.560812 52.593405 140.846248 0 201.586726-119.646798 245.990404-233.663158 258.957473 18.341577 16.208835 34.721032 48.199958 34.721032 97.210357 0 70.167195-0.639822 126.7275-0.639823 143.960051 0 14.033439 9.213443 30.370239 35.190235 25.209005 203.250265-69.527373 349.769606-266.123484 349.769605-497.867175C1023.857959 234.942803 794.673558 0 512 0" fill="#3E75C3" p-id="11464"></path></svg> -->
                    <svg height="32" aria-hidden="true" viewBox="0 0 16 16" version="1.1" width="32" data-view-component="true">
                        <path d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z"></path>
                    </svg>
                </a>
                <a href="#" class="text-sm hover:text-gray-400">czheisenberg</a>
                <span >/</span>
                <a href="#" class="text-sm hover:text-gray-400 font-semibold">springboot-vue3-learn</a>

            </div>
            <!-- left end -->
            
            <!-- right start -->
            <div class="flex items-center space-x-4">
                <ul class="flex items-center space-x-1.5">
                    <li class="text-black">
                        <div class="flex items-center border border-gray-400 rounded-md px-2 py-1.5">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-4">
                                <path stroke-linecap="round" stroke-linejoin="round" d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
                            </svg>
                            <input class="bg-[#f6f8fa] w-72 focus:outline-none px-1" type="text" placeholder="Type / to Search">
                            <svg t="1718266555376" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="10971" width="16" height="16"><path d="M490.666667 128h42.666666v768h-42.666666V128z" fill="#595959" p-id="10972"></path></svg>
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="m6.354 8.04-4.773 4.773a.75.75 0 1 0 1.061 1.06L7.945 8.57a.75.75 0 0 0 0-1.06L2.642 2.206a.75.75 0 0 0-1.06 1.061L6.353 8.04ZM8.75 11.5a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5h-5.5Z"></path>
                            </svg>
                        </div>
                    </li>
                    <li class="-px-3">
                        <svg t="1718266555376" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="10971" width="16" height="22"><path d="M490.666667 128h42.666666v768h-42.666666V128z" fill="#595959" p-id="10972"></path></svg>   
                    </li>
                    <li class="hover:text-gray-400">
                        <div class="flex items-center border border-gray-400 rounded-md px-2 py-1.5">
                            <a href="#" class="flex items-center">
                                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                    <path d="M7.75 2a.75.75 0 0 1 .75.75V7h4.25a.75.75 0 0 1 0 1.5H8.5v4.25a.75.75 0 0 1-1.5 0V8.5H2.75a.75.75 0 0 1 0-1.5H7V2.75A.75.75 0 0 1 7.75 2Z"></path>
                                </svg>
                                &nbsp;&nbsp;
                                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                    <path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path>
                                </svg>
                            </a>
                        </div>
                    </li>
                    <li class="hover:text-gray-400 ">
                        <div class="flex items-center border border-gray-400 rounded-md px-2 py-1.5">
                            <a href="#">
                                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                    <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path><path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Z"></path>
                                </svg>
                            </a>
                        </div>
                    </li>
                    <li class="hover:text-gray-400">
                        <div class="flex items-center border border-gray-400 rounded-md px-2 py-1.5">
                            <a href="#">
                                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                    <path d="M1.5 3.25a2.25 2.25 0 1 1 3 2.122v5.256a2.251 2.251 0 1 1-1.5 0V5.372A2.25 2.25 0 0 1 1.5 3.25Zm5.677-.177L9.573.677A.25.25 0 0 1 10 .854V2.5h1A2.5 2.5 0 0 1 13.5 5v5.628a2.251 2.251 0 1 1-1.5 0V5a1 1 0 0 0-1-1h-1v1.646a.25.25 0 0 1-.427.177L7.177 3.427a.25.25 0 0 1 0-.354ZM3.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm0 9.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm8.25.75a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Z"></path>
                                </svg>
                            </a>
                        </div>
                        
                    </li>
                    <li class="hover:text-gray-400">
                        <div class="flex items-center border border-gray-400 rounded-md px-2 py-1.5">
                            <a href="#">
                                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                    <path d="M2.8 2.06A1.75 1.75 0 0 1 4.41 1h7.18c.7 0 1.333.417 1.61 1.06l2.74 6.395c.04.093.06.194.06.295v4.5A1.75 1.75 0 0 1 14.25 15H1.75A1.75 1.75 0 0 1 0 13.25v-4.5c0-.101.02-.202.06-.295Zm1.61.44a.25.25 0 0 0-.23.152L1.887 8H4.75a.75.75 0 0 1 .6.3L6.625 10h2.75l1.275-1.7a.75.75 0 0 1 .6-.3h2.863L11.82 2.652a.25.25 0 0 0-.23-.152Zm10.09 7h-2.875l-1.275 1.7a.75.75 0 0 1-.6.3h-3.5a.75.75 0 0 1-.6-.3L4.375 9.5H1.5v3.75c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25Z"></path>
                                </svg>
                            </a>
                        </div>
                    </li>
                    <li class="hover:text-gray-400">
                        <a href="#">
                            <img class="w-8 rounded-3xl mr-3" src="https://avatars.githubusercontent.com/u/52897817?v=4" alt="" data-view-component="true">
                        </a>
                    </li>
                </ul>

                
            </div>
            <!-- right end -->
        </nav>

        <!-- menu start -->
        <div class="flex items-center space-x-4 my-2 px-2 border-b">
            <ul class="flex items-center space-x-6 mx-4 font-thin">
                <li class="pb-4 flex items-center border-b-2 border-red-500">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" >
                                <path d="m11.28 3.22 4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L13.94 8l-3.72-3.72a.749.749 0 0 1 .326-1.275.749.749 0 0 1 .734.215Zm-6.56 0a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042L2.06 8l3.72 3.72a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L.47 8.53a.75.75 0 0 1 0-1.06Z"></path>
                            </svg>
                            &nbsp;&nbsp;Code
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" >
                                <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path><path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Z"></path>
                            </svg>
                            &nbsp;&nbsp;lssue
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M1.5 3.25a2.25 2.25 0 1 1 3 2.122v5.256a2.251 2.251 0 1 1-1.5 0V5.372A2.25 2.25 0 0 1 1.5 3.25Zm5.677-.177L9.573.677A.25.25 0 0 1 10 .854V2.5h1A2.5 2.5 0 0 1 13.5 5v5.628a2.251 2.251 0 1 1-1.5 0V5a1 1 0 0 0-1-1h-1v1.646a.25.25 0 0 1-.427.177L7.177 3.427a.25.25 0 0 1 0-.354ZM3.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm0 9.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm8.25.75a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Z"></path>
                            </svg>
                            &nbsp;&nbsp;Pull requests
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Zm4.879-2.773 4.264 2.559a.25.25 0 0 1 0 .428l-4.264 2.559A.25.25 0 0 1 6 10.559V5.442a.25.25 0 0 1 .379-.215Z"></path>
                            </svg>
                            &nbsp;&nbsp;Actions
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25ZM6.5 6.5v8h7.75a.25.25 0 0 0 .25-.25V6.5Zm8-1.5V1.75a.25.25 0 0 0-.25-.25H6.5V5Zm-13 1.5v7.75c0 .138.112.25.25.25H5v-8ZM5 5V1.5H1.75a.25.25 0 0 0-.25.25V5Z"></path>
                            </svg>
                            &nbsp;&nbsp;Project
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M0 1.75A.75.75 0 0 1 .75 1h4.253c1.227 0 2.317.59 3 1.501A3.743 3.743 0 0 1 11.006 1h4.245a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-4.507a2.25 2.25 0 0 0-1.591.659l-.622.621a.75.75 0 0 1-1.06 0l-.622-.621A2.25 2.25 0 0 0 5.258 13H.75a.75.75 0 0 1-.75-.75Zm7.251 10.324.004-5.073-.002-2.253A2.25 2.25 0 0 0 5.003 2.5H1.5v9h3.757a3.75 3.75 0 0 1 1.994.574ZM8.755 4.75l-.004 7.322a3.752 3.752 0 0 1 1.992-.572H14.5v-9h-3.495a2.25 2.25 0 0 0-2.25 2.25Z"></path>
                            </svg>
                            &nbsp;&nbsp;Wiki
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M7.467.133a1.748 1.748 0 0 1 1.066 0l5.25 1.68A1.75 1.75 0 0 1 15 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.697 1.697 0 0 1-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 0 1 1.217-1.667Zm.61 1.429a.25.25 0 0 0-.153 0l-5.25 1.68a.25.25 0 0 0-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.196.196 0 0 0 .154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.251.251 0 0 0-.174-.237l-5.25-1.68ZM8.75 4.75v3a.75.75 0 0 1-1.5 0v-3a.75.75 0 0 1 1.5 0ZM9 10.5a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
                            </svg>
                            &nbsp;&nbsp;Secruity
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex items-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M1.5 1.75V13.5h13.75a.75.75 0 0 1 0 1.5H.75a.75.75 0 0 1-.75-.75V1.75a.75.75 0 0 1 1.5 0Zm14.28 2.53-5.25 5.25a.75.75 0 0 1-1.06 0L7 7.06 4.28 9.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.25-3.25a.75.75 0 0 1 1.06 0L10 7.94l4.72-4.72a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path>
                            </svg>
                            &nbsp;&nbsp;lnsights
                        </a>
                    </div>
                </li>
                <li class="pb-4 flex items-center">
                    <div class="flex items-center hover:bg-gray-100">
                        <a href="#" class="flex item-center">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M8 0a8.2 8.2 0 0 1 .701.031C9.444.095 9.99.645 10.16 1.29l.288 1.107c.018.066.079.158.212.224.231.114.454.243.668.386.123.082.233.09.299.071l1.103-.303c.644-.176 1.392.021 1.82.63.27.385.506.792.704 1.218.315.675.111 1.422-.364 1.891l-.814.806c-.049.048-.098.147-.088.294.016.257.016.515 0 .772-.01.147.038.246.088.294l.814.806c.475.469.679 1.216.364 1.891a7.977 7.977 0 0 1-.704 1.217c-.428.61-1.176.807-1.82.63l-1.102-.302c-.067-.019-.177-.011-.3.071a5.909 5.909 0 0 1-.668.386c-.133.066-.194.158-.211.224l-.29 1.106c-.168.646-.715 1.196-1.458 1.26a8.006 8.006 0 0 1-1.402 0c-.743-.064-1.289-.614-1.458-1.26l-.289-1.106c-.018-.066-.079-.158-.212-.224a5.738 5.738 0 0 1-.668-.386c-.123-.082-.233-.09-.299-.071l-1.103.303c-.644.176-1.392-.021-1.82-.63a8.12 8.12 0 0 1-.704-1.218c-.315-.675-.111-1.422.363-1.891l.815-.806c.05-.048.098-.147.088-.294a6.214 6.214 0 0 1 0-.772c.01-.147-.038-.246-.088-.294l-.815-.806C.635 6.045.431 5.298.746 4.623a7.92 7.92 0 0 1 .704-1.217c.428-.61 1.176-.807 1.82-.63l1.102.302c.067.019.177.011.3-.071.214-.143.437-.272.668-.386.133-.066.194-.158.211-.224l.29-1.106C6.009.645 6.556.095 7.299.03 7.53.01 7.764 0 8 0Zm-.571 1.525c-.036.003-.108.036-.137.146l-.289 1.105c-.147.561-.549.967-.998 1.189-.173.086-.34.183-.5.29-.417.278-.97.423-1.529.27l-1.103-.303c-.109-.03-.175.016-.195.045-.22.312-.412.644-.573.99-.014.031-.021.11.059.19l.815.806c.411.406.562.957.53 1.456a4.709 4.709 0 0 0 0 .582c.032.499-.119 1.05-.53 1.456l-.815.806c-.081.08-.073.159-.059.19.162.346.353.677.573.989.02.03.085.076.195.046l1.102-.303c.56-.153 1.113-.008 1.53.27.161.107.328.204.501.29.447.222.85.629.997 1.189l.289 1.105c.029.109.101.143.137.146a6.6 6.6 0 0 0 1.142 0c.036-.003.108-.036.137-.146l.289-1.105c.147-.561.549-.967.998-1.189.173-.086.34-.183.5-.29.417-.278.97-.423 1.529-.27l1.103.303c.109.029.175-.016.195-.045.22-.313.411-.644.573-.99.014-.031.021-.11-.059-.19l-.815-.806c-.411-.406-.562-.957-.53-1.456a4.709 4.709 0 0 0 0-.582c-.032-.499.119-1.05.53-1.456l.815-.806c.081-.08.073-.159.059-.19a6.464 6.464 0 0 0-.573-.989c-.02-.03-.085-.076-.195-.046l-1.102.303c-.56.153-1.113.008-1.53-.27a4.44 4.44 0 0 0-.501-.29c-.447-.222-.85-.629-.997-1.189l-.289-1.105c-.029-.11-.101-.143-.137-.146a6.6 6.6 0 0 0-1.142 0ZM11 8a3 3 0 1 1-6 0 3 3 0 0 1 6 0ZM9.5 8a1.5 1.5 0 1 0-3.001.001A1.5 1.5 0 0 0 9.5 8Z"></path>
                            </svg>
                            &nbsp;&nbsp;Settings
                        </a>
                    </div>
                </li>
            </ul>
        </div>
        <!-- menu end -->
    </div>
    

    <!-- container start -->
    <div class="container m-auto">
        <!-- menu2 start -->
        <div class="border-b pb-3">
        <div class="flex justify-between">
            <div class="flex items-center">
                <div class="flex items-center space-x-2 h-10">
                    <a href="#">
                        <img class="w-6 rounded-3xl" src="https://avatars.githubusercontent.com/u/52897817?v=4" alt="" data-view-component="true">
                    </a>
                    <a href="#" class="font-bold hover:border-b border-black">springboot-vue3-learn</a>
                    <div class="text-xs border rounded-xl px-1.5 py-0.5">Public</div>
                </div>
                
            </div>
            <div class="flex items-center h-10">
                <ul class="flex items-center space-x-2">
                    <li>
                        <div class="flex items-center space-x-1.5 bg-gray-50 border border-gray-300 rounded-md px-2.5 py-1.5">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="m11.294.984 3.722 3.722a1.75 1.75 0 0 1-.504 2.826l-1.327.613a3.089 3.089 0 0 0-1.707 2.084l-.584 2.454c-.317 1.332-1.972 1.8-2.94.832L5.75 11.311 1.78 15.28a.749.749 0 1 1-1.06-1.06l3.969-3.97-2.204-2.204c-.968-.968-.5-2.623.832-2.94l2.454-.584a3.08 3.08 0 0 0 2.084-1.707l.613-1.327a1.75 1.75 0 0 1 2.826-.504ZM6.283 9.723l2.732 2.731a.25.25 0 0 0 .42-.119l.584-2.454a4.586 4.586 0 0 1 2.537-3.098l1.328-.613a.25.25 0 0 0 .072-.404l-3.722-3.722a.25.25 0 0 0-.404.072l-.613 1.328a4.584 4.584 0 0 1-3.098 2.537l-2.454.584a.25.25 0 0 0-.119.42l2.731 2.732Z"></path>
                            </svg>
                            <p class="text-sm">Pin</p>
                        </div>
                    </li>
                    <li>
                        <div class="flex items-center space-x-1.5 bg-gray-50 border border-gray-300 rounded-md px-2.5 py-1.5">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M8 2c1.981 0 3.671.992 4.933 2.078 1.27 1.091 2.187 2.345 2.637 3.023a1.62 1.62 0 0 1 0 1.798c-.45.678-1.367 1.932-2.637 3.023C11.67 13.008 9.981 14 8 14c-1.981 0-3.671-.992-4.933-2.078C1.797 10.83.88 9.576.43 8.898a1.62 1.62 0 0 1 0-1.798c.45-.677 1.367-1.931 2.637-3.022C4.33 2.992 6.019 2 8 2ZM1.679 7.932a.12.12 0 0 0 0 .136c.411.622 1.241 1.75 2.366 2.717C5.176 11.758 6.527 12.5 8 12.5c1.473 0 2.825-.742 3.955-1.715 1.124-.967 1.954-2.096 2.366-2.717a.12.12 0 0 0 0-.136c-.412-.621-1.242-1.75-2.366-2.717C10.824 4.242 9.473 3.5 8 3.5c-1.473 0-2.825.742-3.955 1.715-1.124.967-1.954 2.096-2.366 2.717ZM8 10a2 2 0 1 1-.001-3.999A2 2 0 0 1 8 10Z"></path>
                            </svg>
                            <p class="text-xs">Unwatch</p>
                            <p class="text-xs border rounded-2xl px-1.5 py-0.5 bg-gray-100">1</p>
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg>
                        </div>
                    </li>

                    <li>
                        <div class="flex items-center space-x-1.5 bg-gray-50 border border-gray-300 rounded-md px-2.5 py-1.5">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M5 5.372v.878c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75v-.878a2.25 2.25 0 1 1 1.5 0v.878a2.25 2.25 0 0 1-2.25 2.25h-1.5v2.128a2.251 2.251 0 1 1-1.5 0V8.5h-1.5A2.25 2.25 0 0 1 3.5 6.25v-.878a2.25 2.25 0 1 1 1.5 0ZM5 3.25a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Zm6.75.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm-3 8.75a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Z"></path>
                            </svg>
                            <p class="text-xs">Fork</p>
                            <p class="text-xs border rounded-2xl px-1.5 py-0.5 bg-gray-100">0</p>
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg>
                        </div>
                    </li>

                    <li>
                        <div class="flex items-center space-x-1.5 bg-gray-50 border border-gray-300 rounded-md px-2.5 py-1.5">
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                                <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
                            </svg>
                            <p class="text-xs">Star</p>
                            <p class="text-xs border rounded-2xl px-1.5 py-0.5 bg-gray-100">0</p>
                            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
        <!-- menu2 end -->
    </div>
        
       <br>

        <div class="container m-auto flex flex-col lg:flex-row w-full">
            <!-- content start -->
            <div class="w-full lg:w-3/4 mr-3">
                <div class="flex justify-between items-center mr-3">
                    <ul class="flex items-center">
                        <li class="mx-2">
                            <a href="#">
                                <div class="flex items-center space-x-1.5 bg-gray-50 border border-gray-300 rounded-md px-2.5 py-1.5 hover:bg-gray-100">
                                    <svg aria-hidden="true" focusable="false" role="img" class="octicon octicon-git-branch" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" style="display:inline-block;user-select:none;vertical-align:text-bottom;overflow:visible"><path d="M9.5 3.25a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.493 2.493 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25Zm-6 0a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Zm8.25-.75a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Z"></path></svg>
                                    <p class="text-sm">master</p>
                                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg>
                                </div>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <div class="flex items-center space-x-1.5  border-gray-300 rounded-md px-2.5 py-1.5 hover:bg-gray-100">
                                    <svg aria-hidden="true" focusable="false" role="img" class="octicon octicon-git-branch" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" style="display:inline-block;user-select:none;vertical-align:text-bottom;overflow:visible"><path d="M9.5 3.25a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.493 2.493 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25Zm-6 0a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Zm8.25-.75a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Z"></path></svg>
                                    <p class="text-xs">1</p>
                                    <p class="text-xs">Branch</p>
                                </div>
                            </a>
                        </li>
                        <li class="mx-2">
                            <a href="#">
                                <div class="flex items-center space-x-1.5  border-gray-300 rounded-md px-2.5 py-1.5 hover:bg-gray-100">
                                    <svg aria-hidden="true" focusable="false" role="img" class="octicon octicon-tag" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" style="display:inline-block;user-select:none;vertical-align:text-bottom;overflow:visible"><path d="M1 7.775V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 0 1 0 2.474l-5.026 5.026a1.75 1.75 0 0 1-2.474 0l-6.25-6.25A1.752 1.752 0 0 1 1 7.775Zm1.5 0c0 .066.026.13.073.177l6.25 6.25a.25.25 0 0 0 .354 0l5.025-5.025a.25.25 0 0 0 0-.354l-6.25-6.25a.25.25 0 0 0-.177-.073H2.75a.25.25 0 0 0-.25.25ZM6 5a1 1 0 1 1 0 2 1 1 0 0 1 0-2Z"></path></svg>
                                    <p class="text-xs">0</p>
                                    <p class="text-xs">Tags</p>
                                </div>
                            </a>
                        </li>
                    </ul>
                    <ul class="flex items-center">
                        <li class="text-black">
                            <div class="flex items-center border border-gray-400 rounded-md  px-2 py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
                                </svg>
                                <input class=" focus:outline-none px-1" type="text" placeholder="Go to file">
                                <kbd class="bg-gray-100 rounded-md px-1.5">t</kbd>
                            </div>
                        </li>
                        <li class="mx-2">
                            <a href="#">
                                <div class="flex items-center space-x-1.5 bg-gray-50 border border-gray-300 rounded-md px-2.5 py-1.5 hover:bg-gray-100">
                                    <p class="text-md">Add file</p>
                                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg>
                                </div>
                            </a>
                        </li>
                        <li class="mx-2">
                            <a href="#">
                                <div class="flex items-center space-x-1.5 bg-[#1f883d] border border-gray-300 rounded-md px-2.5 py-1.5 text-white">
                                    <svg aria-hidden="true" focusable="false" role="img" class="octicon octicon-plus" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" style="display:inline-block;user-select:none;vertical-align:text-bottom;overflow:visible"><path d="M7.75 2a.75.75 0 0 1 .75.75V7h4.25a.75.75 0 0 1 0 1.5H8.5v4.25a.75.75 0 0 1-1.5 0V8.5H2.75a.75.75 0 0 1 0-1.5H7V2.75A.75.75 0 0 1 7.75 2Z"></path></svg>
                                    <p class="text-md">Code</p>
                                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg>
                                </div>
                            </a>
                        </li>
                    </ul>
                </div>

                <!-- commit start -->
                <div class="ml-2 mr-5 mt-3">
                    <div class=" bg-gray-100 rounded-md rounded-b-none border border-gray-300 flex justify-between h-14">
                        <!-- left-->
                        <div class="space-x-2 py-4 px-2 flex items-center">
                            <a href="#"><img class="w-6 rounded-3xl" src="https://avatars.githubusercontent.com/u/52897817?v=4" alt="" data-view-component="true"></a>
                            <a href="#" class="text-xs font-semibold hover:border-b hover:underline">czheisenberg</a>
                            <a href="#" class="text-xs text-gray-500 hover:underline hover:text-blue-500">day8: 修复直接新增显示无电子书id的bug</a>
                        </div>
                        <!-- right -->
                        <div class="space-x-2 py-4 px-2 flex items-center">
                            <a href="#" class="text-xs text-gray-500 hover:underline hover:text-blue-500">6ca5e80</a>
                            <p class="pb-2.5">.</p>
                            <p class="text-xs text-gray-500">last week</p>
                            <a href="#" class="flex items-center hover:bg-gray-200 rounded-md">
                                <svg class="w-7" t="1718329659689" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="8109"><path d="M503 191.008c-94.6 0.2-184 43.6-242.7 117.8v-45c0-7.3-3.9-14.1-10.3-17.8-6.4-3.7-14.2-3.7-20.5 0-6.4 3.7-10.3 10.5-10.3 17.8v105.4c0 11.1 9 20.2 20.2 20.2h108.5c12 0 21.7-9.7 21.7-21.7s-9.7-21.7-21.7-21.7h-66.6c75.2-109.4 218.9-147.6 338.5-90s179.2 193.9 140.5 320.9c-38.7 127-164.3 206.7-295.7 187.8s-229.3-130.9-230.6-263.6c0-7.3-3.9-14.1-10.3-17.8-6.4-3.7-14.2-3.7-20.5 0-6.4 3.7-10.3 10.5-10.3 17.8 0 171.3 138.8 310.1 310.1 310.1s310.1-138.8 310.1-310.1-138.8-310.1-310.1-310.1z" fill="#777777" p-id="8110"></path><path d="M503 339.808c-11.1 0-20.2 9-20.2 20.2v176.8l55 58.9c3.8 4 9.2 6.3 14.7 6.2 6 0 11.8-2.2 16.3-6.2 3.8-3.8 6-9 6-14.3 0-5.4-2.2-10.6-6-14.3l-49.5-52.8v-155.1c-0.2-9.5-7-17.5-16.3-19.4z" fill="#777777" p-id="8111"></path></svg>
                                <p class="text-xs">95 Commits</p>
                            </a>
                        </div>
                    </div>
                    <!-- content start -->
                    <div class="bg-white">
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="text-blue-400" aria-hidden="true" focusable="false" role="img" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" style="display: inline-block; user-select: none; vertical-align: text-bottom; overflow: visible;"><path d="M1.75 1A1.75 1.75 0 0 0 0 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0 0 16 13.25v-8.5A1.75 1.75 0 0 0 14.25 3H7.5a.25.25 0 0 1-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75Z"></path></svg>
                                <p>.mvn/wrapper</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">my second commit</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">3 weeks ago</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="text-blue-400" aria-hidden="true" focusable="false" role="img" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" style="display: inline-block; user-select: none; vertical-align: text-bottom; overflow: visible;"><path d="M1.75 1A1.75 1.75 0 0 0 0 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0 0 16 13.25v-8.5A1.75 1.75 0 0 0 14.25 3H7.5a.25.25 0 0 1-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75Z"></path></svg>
                                <p>src</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">day7: 修复上一个遗留bug</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">2 weeks ago</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="text-blue-400" aria-hidden="true" focusable="false" role="img" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" style="display: inline-block; user-select: none; vertical-align: text-bottom; overflow: visible;"><path d="M1.75 1A1.75 1.75 0 0 0 0 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0 0 16 13.25v-8.5A1.75 1.75 0 0 0 14.25 3H7.5a.25.25 0 0 1-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75Z"></path></svg>
                                <p>web</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">day8: 修复直接新增显示无电子书id的bug</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">last weeks</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="w-4 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" />
                                </svg>

                                <p>.gitignore</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">my first commit</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">3 weeks ago</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="w-4 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" />
                                </svg>
                                <p>README.md</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">Update README.md</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">3 weeks ago</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="w-4 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" />
                                </svg>
                                <p>mvnw</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">my second commit</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">3 weeks ago</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="w-4 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" />
                                </svg>
                                <p>mvnw.cmd</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">my second commit</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">3 weeks ago</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="w-4 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" />
                                </svg>
                                <p>pom.xml</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">day4: 集成Validation,为列表接口增加参数校验</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">2 weeks ago</p>
                            </div>
                        </div>
                        <div class="flex items-center px-3 py-2 justify-between border-b border-l border-r rounded-md rounded-r-none rounded-l-none hover:bg-gray-50">
                            <div class="flex items-center space-x-3">
                                <svg class="w-4 text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" />
                                </svg>
                                <p>wiki.sql</p>
                            </div>
                            <div>
                                <a class="text-sm text-gray-500 hover:underline hover:text-blue-500">day7: 文档内容表的设计与代码生成</a>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">2 weeks ago</p>
                            </div>
                        </div>
                    </div>
                    <!-- content end -->

                    <div class=" rounded-md rounded-b-none border border-gray-300 h-14 mt-4">
                        <div class="flex justify-between">
                            <!-- left-->
                            <div class="space-x-2 flex items-center">
                                <a href="#" class="space-x-2 py-4 px-2 flex items-center hover:bg-gray-100 rounded-lg">
                                    <svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 0 0 6 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 0 1 6 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 0 1 6-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0 0 18 18a8.967 8.967 0 0 0-6 2.292m0-14.25v14.25"></path></svg>
                                    <p>README</p>
                                </a>
                            </div>
                            <!-- right -->
                            <div class="space-x-2 py-4 px-2 flex items-center">
                                <a href="#" class="hover:bg-gray-100 rounded-md">
                                    <svg class="w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="m16.862 4.487 1.687-1.688a1.875 1.875 0 1 1 2.652 2.652L6.832 19.82a4.5 4.5 0 0 1-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 0 1 1.13-1.897L16.863 4.487Zm0 0L19.5 7.125" />
                                    </svg>
                                </a>
                            </div>
                        </div>
                        <div class="h-20 border-l border-r border-b rounded-md rounded-t-none">
                            
                        </div>
                    </div>

                </div>
                
                <!-- commit end -->

                
                

                
            </div>
            <!-- content end -->

            <!-- sidebar start -->
            <div class="w-full lg:w-1/4 lg:mt-0">
                <div class="flex items-center justify-between h-10">
                    <p class="font-semibold text-sm">About</p>
                    <svg aria-label="Edit repository metadata" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true">
                        <path d="M8 0a8.2 8.2 0 0 1 .701.031C9.444.095 9.99.645 10.16 1.29l.288 1.107c.018.066.079.158.212.224.231.114.454.243.668.386.123.082.233.09.299.071l1.103-.303c.644-.176 1.392.021 1.82.63.27.385.506.792.704 1.218.315.675.111 1.422-.364 1.891l-.814.806c-.049.048-.098.147-.088.294.016.257.016.515 0 .772-.01.147.038.246.088.294l.814.806c.475.469.679 1.216.364 1.891a7.977 7.977 0 0 1-.704 1.217c-.428.61-1.176.807-1.82.63l-1.102-.302c-.067-.019-.177-.011-.3.071a5.909 5.909 0 0 1-.668.386c-.133.066-.194.158-.211.224l-.29 1.106c-.168.646-.715 1.196-1.458 1.26a8.006 8.006 0 0 1-1.402 0c-.743-.064-1.289-.614-1.458-1.26l-.289-1.106c-.018-.066-.079-.158-.212-.224a5.738 5.738 0 0 1-.668-.386c-.123-.082-.233-.09-.299-.071l-1.103.303c-.644.176-1.392-.021-1.82-.63a8.12 8.12 0 0 1-.704-1.218c-.315-.675-.111-1.422.363-1.891l.815-.806c.05-.048.098-.147.088-.294a6.214 6.214 0 0 1 0-.772c.01-.147-.038-.246-.088-.294l-.815-.806C.635 6.045.431 5.298.746 4.623a7.92 7.92 0 0 1 .704-1.217c.428-.61 1.176-.807 1.82-.63l1.102.302c.067.019.177.011.3-.071.214-.143.437-.272.668-.386.133-.066.194-.158.211-.224l.29-1.106C6.009.645 6.556.095 7.299.03 7.53.01 7.764 0 8 0Zm-.571 1.525c-.036.003-.108.036-.137.146l-.289 1.105c-.147.561-.549.967-.998 1.189-.173.086-.34.183-.5.29-.417.278-.97.423-1.529.27l-1.103-.303c-.109-.03-.175.016-.195.045-.22.312-.412.644-.573.99-.014.031-.021.11.059.19l.815.806c.411.406.562.957.53 1.456a4.709 4.709 0 0 0 0 .582c.032.499-.119 1.05-.53 1.456l-.815.806c-.081.08-.073.159-.059.19.162.346.353.677.573.989.02.03.085.076.195.046l1.102-.303c.56-.153 1.113-.008 1.53.27.161.107.328.204.501.29.447.222.85.629.997 1.189l.289 1.105c.029.109.101.143.137.146a6.6 6.6 0 0 0 1.142 0c.036-.003.108-.036.137-.146l.289-1.105c.147-.561.549-.967.998-1.189.173-.086.34-.183.5-.29.417-.278.97-.423 1.529-.27l1.103.303c.109.029.175-.016.195-.045.22-.313.411-.644.573-.99.014-.031.021-.11-.059-.19l-.815-.806c-.411-.406-.562-.957-.53-1.456a4.709 4.709 0 0 0 0-.582c-.032-.499.119-1.05.53-1.456l.815-.806c.081-.08.073-.159.059-.19a6.464 6.464 0 0 0-.573-.989c-.02-.03-.085-.076-.195-.046l-1.102.303c-.56.153-1.113.008-1.53-.27a4.44 4.44 0 0 0-.501-.29c-.447-.222-.85-.629-.997-1.189l-.289-1.105c-.029-.11-.101-.143-.137-.146a6.6 6.6 0 0 0-1.142 0ZM11 8a3 3 0 1 1-6 0 3 3 0 0 1 6 0ZM9.5 8a1.5 1.5 0 1 0-3.001.001A1.5 1.5 0 0 0 9.5 8Z"></path>
                    </svg>
                </div>
                <!-- project name and Readme, Activity, Stars, Watching, Fork start -->
                <div class="mt-2 border-b border-gray-300 pb-4">
                    <div class="text-sm">spring boot-vue3-learn</div>
                    <div class="text-sm mt-4">
                        <ul class="space-y-2">
                            <li>
                                <a href="#" class="flex items-center space-x-3 hover:text-blue-500 text-gray-500">
                                    <svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 0 0 6 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 0 1 6 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 0 1 6-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0 0 18 18a8.967 8.967 0 0 0-6 2.292m0-14.25v14.25" />
                                    </svg>

                                    <p>Readme</p>
                                </a>
                            </li>
                            <li>
                                <a href="#" class="flex items-center space-x-3 hover:text-blue-500 text-gray-500">
                                    <svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3v11.25A2.25 2.25 0 0 0 6 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0 1 18 16.5h-2.25m-7.5 0h7.5m-7.5 0-1 3m8.5-3 1 3m0 0 .5 1.5m-.5-1.5h-9.5m0 0-.5 1.5m.75-9 3-3 2.148 2.148A12.061 12.061 0 0 1 16.5 7.605" />
                                    </svg>

                                    <p>Activity</p>
                                </a>
                            </li>
                            <li>
                                <a href="#" class="flex items-center space-x-3 hover:text-blue-500 text-gray-500">
                                    <svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M11.48 3.499a.562.562 0 0 1 1.04 0l2.125 5.111a.563.563 0 0 0 .475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 0 0-.182.557l1.285 5.385a.562.562 0 0 1-.84.61l-4.725-2.885a.562.562 0 0 0-.586 0L6.982 20.54a.562.562 0 0 1-.84-.61l1.285-5.386a.562.562 0 0 0-.182-.557l-4.204-3.602a.562.562 0 0 1 .321-.988l5.518-.442a.563.563 0 0 0 .475-.345L11.48 3.5Z" />
                                    </svg>
                                    <p>Stars</p>
                                </a>
                            </li>
                            <li>
                                <a href="#" class="flex items-center space-x-3 hover:text-blue-500 text-gray-500">
                                    <svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 0 1 0-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178Z" />
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z" />
                                    </svg>
                                    <p>Watching</p>
                                </a>
                            </li>
                            <li>
                                <a href="#" class="flex items-center space-x-3 hover:text-blue-500 text-gray-500">
                                    <svg class="w-5" t="1718326070646" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4271"><path d="M236.544 98.816c76.288 0 137.728 61.44 137.728 136.704 0 58.368-37.376 108.544-89.088 128 4.096 20.992 15.36 46.592 43.008 82.944 46.08 58.88 137.728 99.84 183.808 160.768 46.08-60.928 137.728-101.888 183.808-160.768 28.16-36.352 38.912-61.952 43.008-82.944-53.76-20.48-89.088-71.168-89.088-128 0-75.264 61.952-136.704 137.728-136.704s137.728 61.44 137.728 136.704c0 59.904-39.424 111.616-94.208 130.048-3.584 23.552-19.456 67.584-48.64 105.472-46.08 60.928-108.544 93.696-163.328 145.92-34.304 28.672-54.272 66.56-58.368 87.552 51.712 19.456 89.088 69.632 89.088 128 0 75.264-61.952 136.704-137.728 136.704s-137.728-61.44-137.728-136.704c0-58.368 37.376-108.544 89.088-128-4.096-20.992-26.624-57.856-63.488-87.552-54.784-53.76-112.64-84.992-158.208-146.432-29.184-37.888-45.056-81.92-48.64-105.472-56.32-18.944-94.208-71.168-94.208-130.048-0.512-75.264 61.44-136.192 137.728-136.192m1.024 89.6c-26.112 0-47.616 21.504-47.616 47.616s21.504 47.616 47.616 47.616c26.112 0 47.616-21.504 47.616-47.616s-21.504-47.616-47.616-47.616m548.864 0c-26.112 0-47.616 21.504-47.616 47.616 0 26.112 21.504 47.616 47.616 47.616 26.112 0 47.616-21.504 47.616-47.616 0-26.112-20.992-47.616-47.616-47.616M512 786.432c-26.112 0-47.616 21.504-47.616 47.616 0 26.112 21.504 47.616 47.616 47.616 26.112 0 47.616-21.504 47.616-47.616 0-26.112-21.504-47.616-47.616-47.616z" p-id="4272" fill="#cdcdcd"></path></svg>
                                    <p>Forks</p>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- project name and Readme, Activity, Stars, Watching, Fork end -->

                <!-- Release start -->
                <div class="mt-3 border-b border-gray-300 pb-4">
                    <div class="text-sm font-semibold">Releases</div>
                    <div class="text-sm mt-4">
                        <ul class="space-y-2">
                            <li>
                                <p class="text-xs text-gray-500">No releases published</p>
                            </li>
                            <li>
                                <a href="#">
                                    <p class="text-xs text-blue-500 underline underline-offset-4">Create a new release</p>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- Release end -->

                <!-- Packages start -->
                <div class="mt-3 border-b border-gray-300 pb-4">
                    <div class="text-sm font-semibold">Packages</div>
                    <div class="text-sm mt-4">
                        <ul class="space-y-2">
                            <li>
                                <p class="text-xs text-gray-500">No packages published</p>
                            </li>
                            <li>
                                <a href="#">
                                    <p class="text-xs text-blue-500 underline underline-offset-4">Published your first package</p>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- Packages end -->

                <!-- Languages start -->
                <div class="mt-3 border-b border-gray-300 pb-4">
                    <div class="text-sm font-semibold">Languages</div>
                    <div class="text-sm mt-4">
                        <ul class="space-y-2">
                            <li>
                                <div class="relative">
                                    <div class="mb-4 flex h-2 overflow-hidden rounded bg-gray-100 text-xs">
                                        <div style="width: 74.5%" class="bg-orange-400 transition-all duration-500 ease-out"></div>
                                        <div style="width: 22.5%" class="bg-green-500 transition-all duration-500 ease-out"></div>
                                        <div style="width: 2.4%" class="bg-blue-500 transition-all duration-500 ease-out"></div>
                                        <div style="width: 0.6%" class="bg-gray-200 transition-all duration-500 ease-out"></div>
                                    </div>
                                    <div class="flex items-center space-x-6">
                                        <div class="flex items-center space-x-2">
                                            <div class="rounded-full bg-orange-400 px-1 py-1"></div>
                                            <div>Java 74.5%</div>
                                        </div>
                                        <div class="flex items-center space-x-2">
                                            <div class="rounded-full bg-green-400 px-1 py-1"></div>
                                            <div>Java 74.5%</div>
                                        </div>
                                    </div>
                                </div>
                            </li>
                            <li>
                                <div class="flex items-center space-x-6">
                                    <div class="flex items-center space-x-2">
                                        <div class="rounded-full bg-blue-400 px-1 py-1"></div>
                                        <div>TypeScript 2.4%</div>
                                    </div>
                                    <div class="flex items-center space-x-2">
                                        <div class="rounded-full bg-gray-200 px-1 py-1"></div>
                                        <div>Other 0.6%</div>
                                    </div>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- Languages end -->

            </div>
            <!-- sidebar end -->
        </div>
    </div>
    <!-- container end -->

</div>

    

</template>

<script>

</script>