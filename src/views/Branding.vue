<template>
    <div class="container-fluid">
        <header>
            <div class="nav_logo">
                <router-link to="/">
                    <div class="text-white">
                        <svg
                            width="23"
                            height="5"
                            viewBox="0 0 23 5"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M2 2.54999H21"
                                stroke="black"
                                stroke-width="4"
                                stroke-linecap="square"
                            />
                        </svg>
                        <svg
                            width="27"
                            height="36"
                            viewBox="0 0 27 36"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                fill-rule="evenodd"
                                clip-rule="evenodd"
                                d="M11.0159 35.3717C9.25588 35.3717 7.4799 35.3145 5.68789 35.2003C3.89588 35.0861 2.32789 34.8494 0.983887 34.4904V1.5403C1.68789 1.40974 2.43988 1.28734 3.23989 1.1731C4.03989 1.05886 4.85588 0.969098 5.68789 0.903818C6.51989 0.838537 7.34388 0.789578 8.15989 0.756938C8.97589 0.724297 9.75188 0.707977 10.4879 0.707977C12.5039 0.707977 14.3759 0.863016 16.1039 1.1731C17.8319 1.48318 19.3279 1.99725 20.5919 2.71534C21.8559 3.43342 22.8399 4.37997 23.5439 5.55502C24.2479 6.73006 24.5999 8.18253 24.5999 9.91246C24.5999 11.5118 24.2239 12.8827 23.4719 14.0251C22.7199 15.1675 21.6719 16.0814 20.3279 16.7669C22.3439 17.4523 23.8319 18.4641 24.7919 19.8024C25.7519 21.1406 26.2319 22.8379 26.2319 24.8942C26.2319 28.3867 24.9839 31.0061 22.4879 32.7523C19.9919 34.4985 16.1679 35.3717 11.0159 35.3717ZM6.93589 19.7045V30.035C7.60789 30.1003 8.32788 30.1493 9.09589 30.1819C9.86389 30.2145 10.5679 30.2309 11.2079 30.2309C12.4559 30.2309 13.6159 30.1493 14.6879 29.9861C15.7599 29.8229 16.6879 29.5373 17.4719 29.1293C18.2559 28.7213 18.8799 28.1745 19.3439 27.4891C19.8079 26.8037 20.0399 25.9224 20.0399 24.8453C20.0399 22.9195 19.3519 21.5813 17.9759 20.8305C16.5999 20.0798 14.6959 19.7045 12.2639 19.7045H6.93589ZM6.93589 14.8574H11.2079C13.5119 14.8574 15.3199 14.5229 16.6319 13.8537C17.9439 13.1846 18.5999 11.9851 18.5999 10.2552C18.5999 8.62317 17.9199 7.46446 16.5599 6.77902C15.1999 6.09357 13.4319 5.75086 11.2559 5.75086C10.3279 5.75086 9.50389 5.76718 8.78389 5.79982C8.06388 5.83246 7.44789 5.88142 6.93589 5.9467V14.8574Z"
                                fill="black"
                            />
                        </svg>
                    </div>
                </router-link>
            </div>
            <div class="nav-bar text-dark">
                <ul>
                    <li>
                        <h7>About</h7>
                    </li>
                    <li>
                        <h7>Website</h7>
                    </li>
                    <li>
                        <router-link to="branding">
                            <h7>Branding</h7>
                        </router-link>
                    </li>
                    <li>
                        <div
                            class="nav-hamburger nav-hamburger-section"
                            type="button"
                            data-bs-toggle="offcanvas"
                            data-bs-target="#offcanvasRight"
                            aria-controls="offcanvasRight"
                        >
                            <svg
                                width="20"
                                height="2"
                                viewBox="0 0 20 2"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M1.01671 0.630423H18.9834"
                                    stroke="black"
                                    stroke-linecap="round"
                                />
                            </svg>
                            <svg
                                width="20"
                                height="2"
                                viewBox="0 0 20 2"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M1.01671 0.630423H18.9834"
                                    stroke="black"
                                    stroke-linecap="round"
                                />
                            </svg>
                            <svg
                                width="20"
                                height="2"
                                viewBox="0 0 20 2"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M1.01671 0.630423H18.9834"
                                    stroke="black"
                                    stroke-linecap="round"
                                />
                            </svg>
                        </div>
                    </li>
                </ul>
            </div>
        </header>
    </div>

    <!-- canvas modal -->
    <div
        class="offcanvas offcanvas-end"
        tabindex="-1"
        id="offcanvasRight"
        aria-labelledby="offcanvasRightLabel"
    >
        <div class="offcanvas-header">
            <h5 id="offcanvasRightLabel"></h5>
            <button
                type="button"
                class="btn-close text-reset"
                data-bs-dismiss="offcanvas"
                aria-label="Close"
            ></button>
        </div>
        <div class="offcanvas-body">
            <!-- nav-bar -->
            <ul>
                <li>
                    <h5>About</h5>
                </li>
                <li>
                    <h5>Website</h5>
                </li>
                <li>
                    <h5>Branding</h5>
                </li>
            </ul>
            <!-- nav-bar data -->
            <div class="offcanvas-data">
                <body2>T. 02-2885-8586</body2>
                <body2>E. info@blockstudio.tw</body2>
                <body2>3F., No.2, Ln. 80, Sec. 4, Chengde Rd., Shilin Dist.,</body2>
                <body2>Taipei City 111, Taiwan</body2>
                <div class="offcanvas-media">
                    <div>
                        <svg
                            width="8"
                            height="12"
                            viewBox="0 0 8 12"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M4.93135 11.998V6.53399H6.77468L7.04868 4.39466H4.93135V3.03199C4.93135 2.41466 5.10335 1.99199 5.98935 1.99199H7.11202V0.0846574C6.56578 0.0261181 6.01671 -0.00214741 5.46735 -9.29282e-06C3.83802 -9.29282e-06 2.71935 0.994657 2.71935 2.82066V4.39066H0.888016V6.52999H2.72335V11.998H4.93135Z"
                                fill="white"
                            />
                        </svg>
                    </div>
                    <div>
                        <svg
                            width="14"
                            height="14"
                            viewBox="0 0 14 14"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M6.99998 3.7953C5.22654 3.7953 3.7953 5.22655 3.7953 6.99999C3.7953 8.77343 5.22654 10.2047 6.99998 10.2047C8.77342 10.2047 10.2047 8.77343 10.2047 6.99999C10.2047 5.22655 8.77342 3.7953 6.99998 3.7953ZM6.99998 9.0828C5.85311 9.0828 4.91717 8.14686 4.91717 6.99999C4.91717 5.85311 5.85311 4.91718 6.99998 4.91718C8.14686 4.91718 9.0828 5.85311 9.0828 6.99999C9.0828 8.14686 8.14686 9.0828 6.99998 9.0828ZM10.3359 2.91718C9.92186 2.91718 9.58748 3.25155 9.58748 3.66561C9.58748 4.07968 9.92186 4.41405 10.3359 4.41405C10.75 4.41405 11.0844 4.08124 11.0844 3.66561C11.0845 3.56729 11.0652 3.46991 11.0276 3.37905C10.9901 3.28819 10.9349 3.20564 10.8654 3.13611C10.7959 3.06659 10.7133 3.01147 10.6225 2.9739C10.5316 2.93633 10.4342 2.91705 10.3359 2.91718ZM13.2469 6.99999C13.2469 6.13749 13.2547 5.2828 13.2062 4.42186C13.1578 3.42186 12.9297 2.53436 12.1984 1.80311C11.4656 1.0703 10.5797 0.843739 9.57967 0.795301C8.71717 0.746864 7.86248 0.754676 7.00154 0.754676C6.13904 0.754676 5.28436 0.746864 4.42342 0.795301C3.42342 0.843739 2.53592 1.07186 1.80467 1.80311C1.07186 2.53593 0.845295 3.42186 0.796858 4.42186C0.74842 5.28436 0.756233 6.13905 0.756233 6.99999C0.756233 7.86093 0.74842 8.71718 0.796858 9.57811C0.845295 10.5781 1.07342 11.4656 1.80467 12.1969C2.53748 12.9297 3.42342 13.1562 4.42342 13.2047C5.28592 13.2531 6.14061 13.2453 7.00154 13.2453C7.86404 13.2453 8.71873 13.2531 9.57967 13.2047C10.5797 13.1562 11.4672 12.9281 12.1984 12.1969C12.9312 11.4641 13.1578 10.5781 13.2062 9.57811C13.2562 8.71718 13.2469 7.86249 13.2469 6.99999ZM11.8719 10.6844C11.7578 10.9687 11.6203 11.1812 11.4 11.4C11.1797 11.6203 10.9687 11.7578 10.6844 11.8719C9.86248 12.1984 7.91092 12.125 6.99998 12.125C6.08905 12.125 4.13592 12.1984 3.31405 11.8734C3.02967 11.7594 2.81717 11.6219 2.59842 11.4016C2.37811 11.1812 2.24061 10.9703 2.12655 10.6859C1.80155 9.86249 1.87498 7.91093 1.87498 6.99999C1.87498 6.08905 1.80155 4.13593 2.12655 3.31405C2.24061 3.02968 2.37811 2.81718 2.59842 2.59843C2.81873 2.37968 3.02967 2.24061 3.31405 2.12655C4.13592 1.80155 6.08905 1.87499 6.99998 1.87499C7.91092 1.87499 9.86405 1.80155 10.6859 2.12655C10.9703 2.24061 11.1828 2.37811 11.4015 2.59843C11.6219 2.81874 11.7594 3.02968 11.8734 3.31405C12.1984 4.13593 12.125 6.08905 12.125 6.99999C12.125 7.91093 12.1984 9.86249 11.8719 10.6844Z"
                                fill="white"
                            />
                        </svg>
                    </div>
                    <div>
                        <svg
                            width="14"
                            height="12"
                            viewBox="0 0 14 12"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M13.362 2.33199C13.6667 3.51999 13.6667 5.99999 13.6667 5.99999C13.6667 5.99999 13.6667 8.47999 13.362 9.66799C13.1927 10.3247 12.6973 10.8413 12.07 11.016C10.9307 11.3333 7.00001 11.3333 7.00001 11.3333C7.00001 11.3333 3.07134 11.3333 1.93001 11.016C1.30001 10.8387 0.805343 10.3227 0.63801 9.66799C0.333344 8.47999 0.333344 5.99999 0.333344 5.99999C0.333344 5.99999 0.333344 3.51999 0.63801 2.33199C0.807343 1.67532 1.30268 1.15866 1.93001 0.98399C3.07134 0.666656 7.00001 0.666656 7.00001 0.666656C7.00001 0.666656 10.9307 0.666656 12.07 0.98399C12.7 1.16132 13.1947 1.67732 13.362 2.33199ZM5.66668 8.33332L9.66668 5.99999L5.66668 3.66666V8.33332Z"
                                fill="white"
                            />
                        </svg>
                    </div>
                </div>
            </div>
            <!-- nav-bar logo -->
            <div class="offcanvas-logo">
                <svg
                    width="128"
                    height="16"
                    viewBox="0 0 128 16"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                >
                    <path
                        d="M8.9084 8H119.39"
                        stroke="#202020"
                        stroke-width="16"
                        stroke-linecap="square"
                    />
                </svg>
                <svg
                    width="147"
                    height="192"
                    viewBox="0 0 147 192"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                >
                    <path
                        fill-rule="evenodd"
                        clip-rule="evenodd"
                        d="M58.3342 192.364C48.1001 192.364 37.7731 192.047 27.3529 191.413C16.9327 190.779 7.81515 189.466 0 187.473V4.63267C4.09365 3.90819 8.46635 3.229 13.1182 2.59508C17.7701 1.96115 22.5149 1.46308 27.3529 1.10084C32.1908 0.738595 36.9822 0.466917 41.7271 0.285796C46.472 0.104675 50.9843 0.0141144 55.264 0.0141144C66.9867 0.0141144 77.872 0.874428 87.92 2.59508C97.9681 4.31572 106.667 7.16834 114.017 11.153C121.367 15.1377 127.089 20.3901 131.182 26.9104C135.276 33.4308 137.323 41.4905 137.323 51.09C137.323 59.9649 135.136 67.5718 130.764 73.9111C126.391 80.2503 120.297 85.3216 112.482 89.1251C124.205 92.9287 132.857 98.5433 138.439 105.969C144.021 113.395 146.812 122.813 146.812 134.224C146.812 153.604 139.556 168.139 125.042 177.829C110.528 187.519 88.2923 192.364 58.3342 192.364ZM34.6098 105.426V162.75C38.5174 163.113 42.704 163.384 47.1698 163.565C51.6356 163.747 55.7292 163.837 59.4507 163.837C66.7076 163.837 73.4527 163.384 79.6862 162.479C85.9197 161.573 91.3158 159.988 95.8747 157.724C100.434 155.46 104.062 152.427 106.76 148.623C109.458 144.82 110.807 139.929 110.807 133.952C110.807 123.266 106.807 115.84 98.8053 111.675C90.8041 107.509 79.7328 105.426 65.5911 105.426H34.6098ZM34.6098 78.5296H59.4507C72.8481 78.5296 83.3611 76.6732 90.9902 72.9602C98.6193 69.2472 102.434 62.5911 102.434 52.9917C102.434 43.9357 98.4797 37.506 90.5716 33.7024C82.6634 29.8989 72.3829 27.9972 59.7298 27.9972C54.3336 27.9972 49.5422 28.0877 45.3556 28.2688C41.1689 28.45 37.587 28.7216 34.6098 29.0839V78.5296Z"
                        fill="#202020"
                    />
                </svg>
            </div>
        </div>
    </div>

    <div class="branding">
        <div class="container-fluid">
            <!-- sliderShow -->
            <div class="row">
                <div class="col">
                    <div
                        id="carouselExampleInterval"
                        class="carousel slide"
                        data-bs-ride="carousel"
                    >
                        <div class="carousel-inner">
                            <div class="carousel-item active" data-bs-interval="3000">
                                <div class="branding_banner-image"></div>
                            </div>
                            <div class="carousel-item" data-bs-interval="3000">
                                <div class="branding_banner-image"></div>
                            </div>
                            <div class="carousel-item" data-bs-interval="3000">
                                <div class="branding_banner-image"></div>
                            </div>
                        </div>
                        <button
                            class="carousel-control-prev"
                            type="button"
                            data-bs-target="#carouselExampleInterval"
                            data-bs-slide="prev"
                        >
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button
                            class="carousel-control-next"
                            type="button"
                            data-bs-target="#carouselExampleInterval"
                            data-bs-slide="next"
                        >
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                    </div>
                </div>
            </div>
            <!-- Award-section -->
            <div class="row bg-fafafa">
                <div class="col-lg-6 col-md-12 col-sm-12 text-start">
                    <div class="branding_award-title">
                        <h2>Woden Public Realm Improvements Works Package 1 Including Lift & Stairs</h2>
                        <svg
                            width="279"
                            height="2"
                            viewBox="0 0 279 2"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <rect width="279" height="2" fill="black" />
                        </svg>
                        <div class="branding_award-logo">
                            <svg
                                width="176"
                                height="318"
                                viewBox="0 0 176 318"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <g opacity="0.12" clip-path="url(#clip0_11_471)">
                                    <path
                                        d="M13.3495 20.2261H137.201"
                                        stroke="#202020"
                                        stroke-width="16"
                                        stroke-linecap="square"
                                    />
                                    <path
                                        fill-rule="evenodd"
                                        clip-rule="evenodd"
                                        d="M72.1199 318.408C60.6473 318.408 49.0705 318.052 37.3892 317.34C25.708 316.628 15.4871 315.152 6.72614 312.913V107.46C11.3152 106.646 16.2171 105.883 21.4319 105.17C26.6468 104.458 31.9658 103.898 37.3892 103.491C42.8127 103.084 48.1839 102.779 53.503 102.576C58.8222 102.372 63.8805 102.27 68.6781 102.27C81.8195 102.27 94.0221 103.237 105.286 105.17C116.55 107.104 126.302 110.309 134.541 114.787C142.781 119.264 149.195 125.166 153.784 132.493C158.373 139.82 160.667 148.876 160.667 159.663C160.667 169.635 158.217 178.183 153.315 185.306C148.413 192.43 141.581 198.128 132.82 202.402C145.962 206.676 155.661 212.985 161.919 221.329C168.177 229.674 171.306 240.257 171.306 253.079C171.306 274.855 163.171 291.188 146.9 302.076C130.63 312.964 105.703 318.408 72.1199 318.408ZM45.5244 220.719V285.133C49.9048 285.54 54.5981 285.845 59.6044 286.049C64.6106 286.252 69.1996 286.354 73.3715 286.354C81.5066 286.354 89.068 285.845 96.0559 284.828C103.044 283.81 109.093 282.029 114.203 279.485C119.314 276.941 123.382 273.532 126.406 269.258C129.431 264.984 130.943 259.489 130.943 252.773C130.943 240.766 126.458 232.421 117.489 227.74C108.519 223.059 96.1081 220.719 80.255 220.719H45.5244ZM45.5244 190.496H73.3715C88.3902 190.496 100.176 188.41 108.728 184.238C117.28 180.066 121.556 172.586 121.556 161.8C121.556 151.624 117.124 144.399 108.259 140.125C99.3933 135.851 87.8687 133.714 73.6843 133.714C67.6351 133.714 62.2639 133.816 57.5706 134.019C52.8772 134.223 48.8619 134.528 45.5244 134.935V190.496Z"
                                        fill="#202020"
                                    />
                                </g>
                                <defs>
                                    <clipPath id="clip0_11_471">
                                        <rect width="176" height="318" fill="white" />
                                    </clipPath>
                                </defs>
                            </svg>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12 col-sm-12">
                    <div class="branding_award-content text-start">
                        <div class="container-fluid">
                            <div class="row">
                                <h4>Award</h4>
                            </div>
                            <div class="row">
                                <div class="col">
                                    <div class="branding_award-client">
                                        <svg
                                            width="23"
                                            height="2"
                                            viewBox="0 0 23 2"
                                            fill="none"
                                            xmlns="http://www.w3.org/2000/svg"
                                        >
                                            <rect width="23" height="2" fill="black" />
                                        </svg>
                                        <body2 class="text-lightGray01">CLIENT</body2>
                                        <body2>ACT Government</body2>
                                    </div>
                                </div>
                                <div class="col">
                                    <div class="branding_award-client">
                                        <svg
                                            width="23"
                                            height="2"
                                            viewBox="0 0 23 2"
                                            fill="none"
                                            xmlns="http://www.w3.org/2000/svg"
                                        >
                                            <rect width="23" height="2" fill="black" />
                                        </svg>
                                        <body2 class="text-lightGray01">STATUS</body2>
                                        <body2>Completed 2017s</body2>
                                    </div>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col">
                                    <div class="branding_award-client">
                                        <svg
                                            width="23"
                                            height="2"
                                            viewBox="0 0 23 2"
                                            fill="none"
                                            xmlns="http://www.w3.org/2000/svg"
                                        >
                                            <rect width="23" height="2" fill="black" />
                                        </svg>
                                        <body2 class="text-lightGray01">SUMMARY</body2>
                                        <body2>On time and on budget - 2017 MBA Award Winning Project</body2>
                                    </div>
                                </div>
                                <div class="col">
                                    <div class="branding_award-client">
                                        <svg
                                            width="23"
                                            height="2"
                                            viewBox="0 0 23 2"
                                            fill="none"
                                            xmlns="http://www.w3.org/2000/svg"
                                        >
                                            <rect width="23" height="2" fill="black" />
                                        </svg>
                                        <body2 class="text-lightGray01">LOCATION</body2>
                                        <body2>Woden Bus Interchange Bradely Street Phillip ACT 2606</body2>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Intro -->
            <div class="row">
                <div class="col text-start">
                    <div class="branding_intro-content">
                        <div class="branding_intro-title text-lightGray01">INTRO</div>
                        <div
                            class="branding_intro-paragraph"
                        >Acclaim Contractors Pty Ltd were engaged by the ACT Government to complete the Woden Public Realm Improvements (Works Package 1 Including Lift & Stairs) project under Contract No. 21646.340. The project was initiated to improve the user experience at the existing Woden Bus Interchange and provide a connection to the Woden Town Square. The works provided an improvement to public safety, pedestrian and cyclist movements, lighting and provide improved user access.</div>
                    </div>
                </div>
                <div class="col">
                    <div class="branding_intro-image image_piscum"></div>
                </div>
            </div>
            <!-- Intro2 -->
            <div class="row position-relative">
                <div class="col">
                    <div class="branding_intro-image02 image_piscum"></div>
                </div>
                <div class="col text-start">
                    <div class="branding_intro-content02">
                        <svg
                            width="23"
                            height="2"
                            viewBox="0 0 23 2"
                            fill="none"
                            class="mb-3"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <rect width="23" height="2" fill="black" />
                        </svg>
                        <div
                            class="branding_intro-paragraph02"
                        >The nominated works were described as the partial demolition of the upper and lower area including overhead walkway and roof slab, public toilets and cafe and the construction of new stairs and provision of an external public lift at the Woden Bus Interchange.The nominated works were described as the partial demolition of the upper and lower area including overhead walkway and roof slab, public toilets and cafe and the construction of new stairs and provision of an external public lift at the Woden Bus Interchange.</div>
                    </div>
                </div>
            </div>
            <!-- video-section -->
            <div class="row g-0">
                <div class="col">
                    <div class="branding_video-section">
                        <div class="branding_video-image image_piscum"></div>
                        <div class="branding_video-modal">
                            <button
                                type="button"
                                class="video-btn"
                                data-bs-toggle="modal"
                                data-bs-target="#videoModal"
                                data-bs-src="https://www.youtube.com/embed/EzDC8aAJln0"
                            >
                                <div class="btn-triangle ms-1">
                                    <svg
                                        width="30"
                                        height="36"
                                        viewBox="0 0 30 36"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path d="M30 18L0 35.3205L0 0.679491L30 18Z" fill="white" />
                                    </svg>
                                </div>
                            </button>
                            <div
                                class="modal fade"
                                id="videoModal"
                                tabindex="-1"
                                role="dialog"
                                aria-labelledby="dbschemaModalLabel"
                                aria-hidden="true"
                            >
                                <div class="modal-dialog modal-fullscreen" role="document">
                                    <div class="modal-content">
                                        <div class="modal-body">
                                            <button
                                                type="button"
                                                class="btn-close"
                                                data-dismiss="modal"
                                                aria-label="Close"
                                            >
                                                <span aria-hidden="true"></span>
                                            </button>

                                            <div class="ratio ratio-16x9">
                                                <iframe
                                                    class="embed-responsive-item"
                                                    src
                                                    id="video"
                                                    allowscriptaccess="always"
                                                    allow="autoplay"
                                                ></iframe>
                                            </div>
                                            <div class="modal-footer">
                                                <button
                                                    type="button"
                                                    class="btn btn-secondary"
                                                    data-bs-dismiss="modal"
                                                >Close</button>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- more-section -->
            <div class="row g-0">
                <div class="col">
                    <div class="home_more-section">
                        <svg
                            width="2"
                            height="137"
                            viewBox="0 0 2 137"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <rect x="0.5" width="1" height="137" fill="#4A4A4A" />
                        </svg>
                        <h4 class="pb-4">
                            Woden Public Realm Improvements Works Package
                            <br />1 Including Lift & Stairs.
                        </h4>
                    </div>
                </div>
            </div>
            <!-- Pagination -->
            <div class="row g-0">
                <div class="col-lg-6 col-md-6 col-sm-12">
                    <div class="branding_pagination-previous">
                        <div class="branding_pagination-content">
                            <svg
                                width="29"
                                height="8"
                                viewBox="0 0 29 8"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M28 7.46H0.900002L4.02692 1"
                                    stroke="#4A4A4A"
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                />
                            </svg>
                            <button1>Previous</button1>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-6 col-sm-12">
                    <div class="branding_pagination-next">
                        <div class="branding_pagination-content">
                            <button1>Next</button1>
                            <svg
                                width="29"
                                height="8"
                                viewBox="0 0 29 8"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M1 7.46H28.1L24.9731 1"
                                    stroke="white"
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                />
                            </svg>
                        </div>
                    </div>
                </div>
            </div>

            <div class="row">
                <div class="col"></div>
            </div>
        </div>
        <!-- footer -->
        <footer class="container-fluid text-white">
            <div class="row footer-content-padding">
                <!-- <div class="col-lg-1 col-md-12 col-sm-12"></div> -->
                <div class="col-lg-6 col-md-12 col-sm-12">
                    <div class="d-flex">
                        <div class="footer-logo d-flex flex-column mx-auto">
                            <svg
                                width="16"
                                height="4"
                                viewBox="0 0 16 4"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M1.25928 1.55005H13.2222"
                                    stroke="white"
                                    stroke-width="4"
                                    stroke-linecap="square"
                                />
                            </svg>
                            <svg
                                width="17"
                                height="22"
                                viewBox="0 0 17 22"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    fill-rule="evenodd"
                                    clip-rule="evenodd"
                                    d="M6.93607 21.6182C5.82792 21.6182 4.70971 21.5835 3.58141 21.514C2.4531 21.4446 1.46586 21.3007 0.619629 21.0825V1.05402C1.06289 0.974655 1.53637 0.900256 2.04007 0.830816C2.54378 0.761376 3.05755 0.706816 3.58141 0.667136C4.10526 0.627456 4.62407 0.597696 5.13785 0.577856C5.65163 0.558016 6.14022 0.548096 6.60363 0.548096C7.87297 0.548096 9.05162 0.642335 10.1396 0.830816C11.2276 1.0193 12.1696 1.33177 12.9654 1.76826C13.7613 2.20474 14.3808 2.78009 14.8241 3.49434C15.2673 4.20858 15.489 5.09145 15.489 6.14298C15.489 7.11514 15.2522 7.94841 14.7787 8.64282C14.3053 9.33722 13.6454 9.89273 12.7992 10.3094C14.0685 10.726 15.0054 11.3411 15.6099 12.1545C16.2143 12.9679 16.5165 13.9996 16.5165 15.2495C16.5165 17.3724 15.7307 18.9646 14.1592 20.026C12.5876 21.0875 10.1799 21.6182 6.93607 21.6182ZM4.36718 12.095V18.3743C4.7903 18.414 5.24363 18.4438 5.72718 18.4636C6.21074 18.4835 6.654 18.4934 7.05696 18.4934C7.84274 18.4934 8.57311 18.4438 9.24807 18.3446C9.92304 18.2454 10.5073 18.0718 11.001 17.8238C11.4946 17.5758 11.8875 17.2435 12.1796 16.8268C12.4718 16.4102 12.6179 15.8745 12.6179 15.2198C12.6179 14.0492 12.1847 13.2358 11.3183 12.7795C10.4519 12.3231 9.25312 12.095 7.72185 12.095H4.36718ZM4.36718 9.14874H7.05696C8.50764 9.14874 9.646 8.94538 10.4721 8.53866C11.2982 8.13193 11.7112 7.40282 11.7112 6.3513C11.7112 5.35929 11.283 4.65498 10.4267 4.23834C9.57044 3.82169 8.45726 3.61338 7.08718 3.61338C6.50288 3.61338 5.98408 3.6233 5.53074 3.64314C5.0774 3.66298 4.68956 3.69274 4.36718 3.73242V9.14874Z"
                                    fill="white"
                                />
                            </svg>
                        </div>
                        <div class="footer-nav-bar-section">
                            <div class="footer-nav-bar-list">
                                <ul class="d-flex justify-content-between">
                                    <li>
                                        <h7>About</h7>
                                    </li>
                                    <li>
                                        <h7>Website</h7>
                                    </li>
                                    <li>
                                        <h7>Branding</h7>
                                    </li>
                                </ul>
                            </div>
                            <div class="footer-nav-bar-data">
                                <ul class="d-flex flex-column text-start">
                                    <li>
                                        <body2>T. 02-2885-8586</body2>
                                    </li>
                                    <li>
                                        <body2>E. info@blockstudio.tw</body2>
                                    </li>
                                    <li>
                                        <body2>3F., No.2, Ln. 80, Sec. 4, Chengde Rd., Shilin Dist., Taipei City 111, Taiwans</body2>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12 col-sm-12">
                    <div class="footer-media d-flex justify-content-end">
                        <svg
                            width="8"
                            height="16"
                            viewBox="0 0 8 16"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M5.16415 15.4974V8.66739H7.46832L7.81082 5.99323H5.16415V4.2899C5.16415 3.51823 5.37915 2.9899 6.48665 2.9899H7.88999V0.60573C7.20718 0.532556 6.52086 0.497224 5.83415 0.499897C3.79749 0.499897 2.39915 1.74323 2.39915 4.02573V5.98823H0.109985V8.6624H2.40415V15.4974H5.16415Z"
                                fill="white"
                            />
                        </svg>
                        <svg
                            width="16"
                            height="16"
                            viewBox="0 0 16 16"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M7.99997 3.99423C5.78317 3.99423 3.99411 5.7833 3.99411 8.00009C3.99411 10.2169 5.78317 12.0059 7.99997 12.0059C10.2168 12.0059 12.0058 10.2169 12.0058 8.00009C12.0058 5.7833 10.2168 3.99423 7.99997 3.99423ZM7.99997 10.6036C6.56638 10.6036 5.39645 9.43369 5.39645 8.00009C5.39645 6.5665 6.56638 5.39658 7.99997 5.39658C9.43356 5.39658 10.6035 6.5665 10.6035 8.00009C10.6035 9.43369 9.43356 10.6036 7.99997 10.6036ZM12.1699 2.89658C11.6523 2.89658 11.2343 3.31455 11.2343 3.83212C11.2343 4.3497 11.6523 4.76767 12.1699 4.76767C12.6875 4.76767 13.1054 4.35165 13.1054 3.83212C13.1056 3.70922 13.0815 3.5875 13.0345 3.47392C12.9876 3.36035 12.9187 3.25715 12.8318 3.17025C12.7449 3.08334 12.6417 3.01444 12.5281 2.96748C12.4145 2.92052 12.2928 2.89642 12.1699 2.89658ZM15.8086 8.00009C15.8086 6.92197 15.8183 5.85361 15.7578 4.77744C15.6972 3.52744 15.4121 2.41806 14.498 1.504C13.582 0.587983 12.4746 0.30478 11.2246 0.244233C10.1465 0.183686 9.07809 0.193452 8.00192 0.193452C6.9238 0.193452 5.85544 0.183686 4.77927 0.244233C3.52927 0.30478 2.41989 0.589936 1.50583 1.504C0.589814 2.42001 0.306611 3.52744 0.246064 4.77744C0.185517 5.85556 0.195283 6.92392 0.195283 8.00009C0.195283 9.07626 0.185517 10.1466 0.246064 11.2227C0.306611 12.4727 0.591767 13.5821 1.50583 14.4962C2.42185 15.4122 3.52927 15.6954 4.77927 15.7559C5.85739 15.8165 6.92575 15.8067 8.00192 15.8067C9.08005 15.8067 10.1484 15.8165 11.2246 15.7559C12.4746 15.6954 13.584 15.4102 14.498 14.4962C15.414 13.5802 15.6972 12.4727 15.7578 11.2227C15.8203 10.1466 15.8086 9.07822 15.8086 8.00009ZM14.0898 12.6056C13.9472 12.961 13.7754 13.2267 13.5 13.5001C13.2246 13.7755 12.9609 13.9474 12.6054 14.0899C11.5781 14.4981 9.13864 14.4063 7.99997 14.4063C6.8613 14.4063 4.41989 14.4981 3.39255 14.0919C3.03708 13.9493 2.77145 13.7774 2.49802 13.502C2.22263 13.2267 2.05075 12.963 1.90817 12.6075C1.50192 11.5782 1.59372 9.13876 1.59372 8.00009C1.59372 6.86142 1.50192 4.42001 1.90817 3.39267C2.05075 3.0372 2.22263 2.77158 2.49802 2.49814C2.77341 2.2247 3.03708 2.05087 3.39255 1.9083C4.41989 1.50205 6.8613 1.59384 7.99997 1.59384C9.13864 1.59384 11.58 1.50205 12.6074 1.9083C12.9629 2.05087 13.2285 2.22275 13.5019 2.49814C13.7773 2.77353 13.9492 3.0372 14.0918 3.39267C14.498 4.42001 14.4062 6.86142 14.4062 8.00009C14.4062 9.13876 14.498 11.5782 14.0898 12.6056Z"
                                fill="white"
                            />
                        </svg>
                        <svg
                            width="18"
                            height="14"
                            viewBox="0 0 18 14"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M16.9525 2.41492C17.3333 3.89992 17.3333 6.99992 17.3333 6.99992C17.3333 6.99992 17.3333 10.0999 16.9525 11.5849C16.7408 12.4058 16.1216 13.0516 15.3375 13.2699C13.9133 13.6666 8.99996 13.6666 8.99996 13.6666C8.99996 13.6666 4.08913 13.6666 2.66246 13.2699C1.87496 13.0483 1.25663 12.4033 1.04746 11.5849C0.666626 10.0999 0.666626 6.99992 0.666626 6.99992C0.666626 6.99992 0.666626 3.89992 1.04746 2.41492C1.25913 1.59409 1.87829 0.948252 2.66246 0.729918C4.08913 0.333252 8.99996 0.333252 8.99996 0.333252C8.99996 0.333252 13.9133 0.333252 15.3375 0.729918C16.125 0.951585 16.7433 1.59659 16.9525 2.41492ZM7.33329 9.91658L12.3333 6.99992L7.33329 4.08325V9.91658Z"
                                fill="white"
                            />
                        </svg>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col">
                    <div
                        class="footer-copyright d-flex justify-content-center border-top border-white"
                    >
                        <body2>Block Studio©2018 Copyright. All Rights Reserved.</body2>
                    </div>
                </div>
            </div>
        </footer>
    </div>
</template>



<script>

export default {
    data() {
        return {
        };
    },
    props: [],
    mounted() {
        let loader = this.$loading.show({
            // Optional parameters
            container: this.fullPage ? null : this.$refs.formContainer,
            canCancel: true,
            onCancel: this.onCancel,
        });
        // simulate AJAX
        setTimeout(() => {
            loader.hide();
        }, 2000);

        // modalVideo js
        var videoBtn = document.querySelector(".video-btn");
        var videoModal = document.getElementById("videoModal");
        var video = document.getElementById("video");
        var videoSrc;
        videoBtn.addEventListener("click", function () {
            videoSrc = videoBtn.getAttribute("data-bs-src");
        });
        videoModal.addEventListener("shown.bs.modal", () => {
            video.setAttribute("src", videoSrc + "?autoplay=1&amp;modestbranding=1&amp;showinfo=0");
        });
        videoModal.addEventListener("hide.bs.modal", () => {
            video.setAttribute("src", videoSrc);

        });



    },
};
</script>


<style lang="scss" scoped>
@import "../assets/scss/main.scss";

header {
    background-color: white;
    padding-bottom: 19px;
    .nav-bar {
        ul {
            li {
                h7 {
                    &:hover {
                        border-bottom: 2px solid #000;
                    }
                }
            }
        }
        .nav-hamburger {
            z-index: 10;
        }
        .nav-hamburger-section {
            background-color: white;
            &:hover {
                background-color: #000;
                transition: ease-in-out;
                svg {
                    path {
                        stroke: #fff;
                    }
                }
            }
        }
    }
}

// canvas modal

.offcanvas {
    background-color: #2c2c2c;
    color: #fff;
    text-align: left;
    .offcanvas-header {
        .btn-close {
            background-color: #fff;
        }
    }
    .offcanvas-body {
        display: flex;
        flex-direction: column;
        // justify-content: space-between;
        padding: 0;
        ul {
            display: flex;
            flex-direction: column;
            justify-content: center;
            margin-top: auto;
            margin-bottom: auto;
            li {
                margin-top: 60px;
                h5 {
                    color: #fff;
                }
            }
        }
        .offcanvas-data {
            // position: absolute;
            // bottom: 0;
            background-color: #000;
            padding: 42px 40px 36px 40px;
            white-space: nowrap;
            .offcanvas-media {
                margin-top: 30px;
                display: flex;
                div {
                    margin-right: 42.64px;
                }
            }
        }
        .offcanvas-logo {
            display: flex;
            flex-direction: column;
            position: absolute;
            top: 20%;
            left: 50%;
            svg {
                &:last-child {
                    margin-top: 73px;
                }
            }
        }
    }
}

.modal-dialog {
    .btn-close {
        display: none;
    }
}
.branding {
    .branding_banner-image {
        height: 100vh;
        width: 100vw;
        background-size: cover;
        background-position: 50%;
        background-attachment: fixed;
        background-image: url("https://picsum.photos/1440/780?grayscale");
    }
    .branding_award-title {
        margin: 95px 109px 45px 109px;
        // margin-x 121px- col(12px)
        width: 580px;
        height: 230px;

        h2 {
            padding-bottom: 12px;
        }
        .branding_award-logo {
            display: flex;
            flex-direction: column;
            position: absolute;
            bottom: 50%;
            left: 0;
            transform: translate(25%, 50%);
            margin-top: 39px;
        }
    }
    .branding_award-content {
        margin: 95px 67px 45px 67px;
        // margin right 115px - container(24px) - col(12px) - col(12px)
    }

    .branding_intro-content {
        margin: 77px 0px 0 108px;
        .branding_intro-title {
            margin-bottom: 8px;
        }
        .branding_intro-paragraph {
        }
    }
    .branding_intro-content02 {
        background-color: white;
        z-index: 100;
        width: 690px;
        height: 301px;
        // transform: translate(-50%, -50%);
        position: absolute;
        bottom: 5%;
        left: 45%;
        svg {
            margin: 72px 50px 12px 50px;
        }
        .branding_intro-paragraph02 {
            margin: 0px 50px 59px 50px;
        }
    }
    .branding_intro-image {
        margin: 77px 103px 0 108px;
        width: 486px;
        height: 364.5px;
        background-size: cover;
        background-position: 50%;
        // background-attachment: fixed;
    }
    .branding_intro-image02 {
        margin: 122px 0px 96px 108px;
        width: 690px;
        height: 453px;
        background-size: cover;
        background-position: 50%;
        // background-attachment: fixed;
        position: relative;
    }
    .image_piscum {
        background-image: url("https://picsum.photos/1440/780?grayscale");
    }
    .branding_video-section {
        // width: 1246.15px;
        height: 675px;
        margin: 0 120px;
        position: relative;
        // background-color: #c4c4c4;
        .branding_video-image {
            width: 100%;
            height: 100%;
        }
        .video-btn {
            width: 88px;
            height: 88px;
            border-radius: 50%;
            background-color: $darkGray02;
            border: 1px solid $darkGray02;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        iframe {
            // width: 1200px;
            // height: 675px;
            width: 100%;
            height: 100%;
        }
    }
    .home_more-section {
        svg {
            margin-top: 93px;
            margin-bottom: 20px;
        }
    }
    .branding_pagination-previous,
    .branding_pagination-next {
        margin-top: 150px;
        border: 1px solid #000;
        height: 100px;
        button1 {
            width: 223px;
            padding: 0 16px;
            display: inline-block;
        }
    }

    .branding_pagination-next {
        background-color: $darkGray01;
        color: white;
    }

    .branding_pagination-content {
        margin: 40px 207px 36px 207px;
    }
}

.bg-fafafa {
    background: #fafafa;
    position: relative;
    height: 392px;
}

.text-lightGray01 {
    color: $lightGray01;
}

.container-fluid {
    padding-left: 0;
    padding-right: 0;
}
</style>
