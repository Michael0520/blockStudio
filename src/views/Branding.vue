<template>
    <header>
        <div class="nav_logo">
            <svg
                width="23"
                height="5"
                viewBox="0 0 23 5"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
            >
                <path d="M2 2.54999H21" stroke="black" stroke-width="4" stroke-linecap="square" />
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
        <div class="nav-bar text-dark">
            <ul>
                <li>
                    <h7>About</h7>
                </li>
                <li>
                    <h7>Website</h7>
                </li>
                <li>
                    <h7>Branding</h7>
                </li>
                <li>
                    <div class="nav-hamburger">
                        <svg
                            width="20"
                            height="2"
                            viewBox="0 0 20 2"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M1.01671 0.630423H18.9834"
                                stroke="white"
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
                                stroke="white"
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
                                stroke="white"
                                stroke-linecap="round"
                            />
                        </svg>
                    </div>
                </li>
            </ul>
            <div class="nav-hamburger-section"></div>
        </div>
    </header>
</template>

<script>
export default {
    data() {
        return {};
    },
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
    },
};
</script>

<style lang="scss">
header {
    .nav-bar {
        ul {
            li {
                &:hover {
                    border-bottom: 2px solid #000;
                }
            }
        }
    }
}
</style>
