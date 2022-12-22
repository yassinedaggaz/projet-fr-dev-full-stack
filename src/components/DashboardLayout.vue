<template>
    <v-layout>

        <v-navigation-drawer color="#14213D" permanent>
            <v-list-item @click="(carousel = 0)" :active="(carousel==0)" class="mt-10">
                <span class="ml-2">
                    Introduction
                </span>
                <template v-slot:prepend>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.6761 19.9589C12.9508 20.0228 12.976 20.3827 12.7084 20.4719L11.1284 20.9919C7.15839 22.2719 5.06839 21.2019 3.77839 17.2319L2.49839 13.2819C1.21839 9.31187 2.27839 7.21187 6.24839 5.93187L6.77238 5.75834C7.17525 5.62493 7.56731 6.02899 7.45292 6.43766C7.39622 6.64023 7.34167 6.85164 7.28839 7.07188L6.30839 11.2619C5.20839 15.9719 6.81839 18.5719 11.5284 19.6919L12.6761 19.9589Z" fill="#292D32"/>
                        <path d="M17.1702 3.20854L15.5002 2.81854C12.1602 2.02854 10.1702 2.67854 9.00018 5.09854C8.70018 5.70854 8.46018 6.44854 8.26018 7.29854L7.28018 11.4885C6.30018 15.6685 7.59018 17.7285 11.7602 18.7185L13.4402 19.1185C14.0202 19.2585 14.5602 19.3485 15.0602 19.3885C18.1802 19.6885 19.8402 18.2285 20.6802 14.6185L21.6602 10.4385C22.6402 6.25854 21.3602 4.18854 17.1702 3.20854ZM15.2902 13.3285C15.2002 13.6685 14.9002 13.8885 14.5602 13.8885C14.5002 13.8885 14.4402 13.8785 14.3702 13.8685L11.4602 13.1285C11.0602 13.0285 10.8202 12.6185 10.9202 12.2185C11.0202 11.8185 11.4302 11.5785 11.8302 11.6785L14.7402 12.4185C15.1502 12.5185 15.3902 12.9285 15.2902 13.3285ZM18.2202 9.94854C18.1302 10.2885 17.8302 10.5085 17.4902 10.5085C17.4302 10.5085 17.3702 10.4985 17.3002 10.4885L12.4502 9.25854C12.0502 9.15854 11.8102 8.74854 11.9102 8.34854C12.0102 7.94854 12.4202 7.70854 12.8202 7.80854L17.6702 9.03854C18.0802 9.12854 18.3202 9.53854 18.2202 9.94854Z" fill="#292D32"/>
                    </svg>
                </template>
            </v-list-item>
            <v-list-item @click="(carousel = 1)" :active="(carousel == 1)">
                <span class="ml-2">
                    Description
                </span>
                <template v-slot:prepend>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.6761 19.9589C12.9508 20.0228 12.976 20.3827 12.7084 20.4719L11.1284 20.9919C7.15839 22.2719 5.06839 21.2019 3.77839 17.2319L2.49839 13.2819C1.21839 9.31187 2.27839 7.21187 6.24839 5.93187L6.77238 5.75834C7.17525 5.62493 7.56731 6.02899 7.45292 6.43766C7.39622 6.64023 7.34167 6.85164 7.28839 7.07188L6.30839 11.2619C5.20839 15.9719 6.81839 18.5719 11.5284 19.6919L12.6761 19.9589Z" fill="#292D32"/>
                        <path d="M17.1702 3.20854L15.5002 2.81854C12.1602 2.02854 10.1702 2.67854 9.00018 5.09854C8.70018 5.70854 8.46018 6.44854 8.26018 7.29854L7.28018 11.4885C6.30018 15.6685 7.59018 17.7285 11.7602 18.7185L13.4402 19.1185C14.0202 19.2585 14.5602 19.3485 15.0602 19.3885C18.1802 19.6885 19.8402 18.2285 20.6802 14.6185L21.6602 10.4385C22.6402 6.25854 21.3602 4.18854 17.1702 3.20854ZM15.2902 13.3285C15.2002 13.6685 14.9002 13.8885 14.5602 13.8885C14.5002 13.8885 14.4402 13.8785 14.3702 13.8685L11.4602 13.1285C11.0602 13.0285 10.8202 12.6185 10.9202 12.2185C11.0202 11.8185 11.4302 11.5785 11.8302 11.6785L14.7402 12.4185C15.1502 12.5185 15.3902 12.9285 15.2902 13.3285ZM18.2202 9.94854C18.1302 10.2885 17.8302 10.5085 17.4902 10.5085C17.4302 10.5085 17.3702 10.4985 17.3002 10.4885L12.4502 9.25854C12.0502 9.15854 11.8102 8.74854 11.9102 8.34854C12.0102 7.94854 12.4202 7.70854 12.8202 7.80854L17.6702 9.03854C18.0802 9.12854 18.3202 9.53854 18.2202 9.94854Z" fill="#292D32"/>
                    </svg>
                </template>
            </v-list-item>
            <v-list-item @click="(carousel = 2)" :active="(carousel == 2)">
                <span class="ml-2">
                    Mission
                </span>
                <template v-slot:prepend>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.6761 19.9589C12.9508 20.0228 12.976 20.3827 12.7084 20.4719L11.1284 20.9919C7.15839 22.2719 5.06839 21.2019 3.77839 17.2319L2.49839 13.2819C1.21839 9.31187 2.27839 7.21187 6.24839 5.93187L6.77238 5.75834C7.17525 5.62493 7.56731 6.02899 7.45292 6.43766C7.39622 6.64023 7.34167 6.85164 7.28839 7.07188L6.30839 11.2619C5.20839 15.9719 6.81839 18.5719 11.5284 19.6919L12.6761 19.9589Z" fill="#292D32"/>
                        <path d="M17.1702 3.20854L15.5002 2.81854C12.1602 2.02854 10.1702 2.67854 9.00018 5.09854C8.70018 5.70854 8.46018 6.44854 8.26018 7.29854L7.28018 11.4885C6.30018 15.6685 7.59018 17.7285 11.7602 18.7185L13.4402 19.1185C14.0202 19.2585 14.5602 19.3485 15.0602 19.3885C18.1802 19.6885 19.8402 18.2285 20.6802 14.6185L21.6602 10.4385C22.6402 6.25854 21.3602 4.18854 17.1702 3.20854ZM15.2902 13.3285C15.2002 13.6685 14.9002 13.8885 14.5602 13.8885C14.5002 13.8885 14.4402 13.8785 14.3702 13.8685L11.4602 13.1285C11.0602 13.0285 10.8202 12.6185 10.9202 12.2185C11.0202 11.8185 11.4302 11.5785 11.8302 11.6785L14.7402 12.4185C15.1502 12.5185 15.3902 12.9285 15.2902 13.3285ZM18.2202 9.94854C18.1302 10.2885 17.8302 10.5085 17.4902 10.5085C17.4302 10.5085 17.3702 10.4985 17.3002 10.4885L12.4502 9.25854C12.0502 9.15854 11.8102 8.74854 11.9102 8.34854C12.0102 7.94854 12.4202 7.70854 12.8202 7.80854L17.6702 9.03854C18.0802 9.12854 18.3202 9.53854 18.2202 9.94854Z" fill="#292D32"/>
                    </svg>
                </template>
            </v-list-item>
            <v-list-item @click="(carousel = 3)" :active="(carousel == 3)">
                <span class="ml-2">
                    Qualités requises
                </span>
                <template v-slot:prepend>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.6761 19.9589C12.9508 20.0228 12.976 20.3827 12.7084 20.4719L11.1284 20.9919C7.15839 22.2719 5.06839 21.2019 3.77839 17.2319L2.49839 13.2819C1.21839 9.31187 2.27839 7.21187 6.24839 5.93187L6.77238 5.75834C7.17525 5.62493 7.56731 6.02899 7.45292 6.43766C7.39622 6.64023 7.34167 6.85164 7.28839 7.07188L6.30839 11.2619C5.20839 15.9719 6.81839 18.5719 11.5284 19.6919L12.6761 19.9589Z" fill="#292D32"/>
                        <path d="M17.1702 3.20854L15.5002 2.81854C12.1602 2.02854 10.1702 2.67854 9.00018 5.09854C8.70018 5.70854 8.46018 6.44854 8.26018 7.29854L7.28018 11.4885C6.30018 15.6685 7.59018 17.7285 11.7602 18.7185L13.4402 19.1185C14.0202 19.2585 14.5602 19.3485 15.0602 19.3885C18.1802 19.6885 19.8402 18.2285 20.6802 14.6185L21.6602 10.4385C22.6402 6.25854 21.3602 4.18854 17.1702 3.20854ZM15.2902 13.3285C15.2002 13.6685 14.9002 13.8885 14.5602 13.8885C14.5002 13.8885 14.4402 13.8785 14.3702 13.8685L11.4602 13.1285C11.0602 13.0285 10.8202 12.6185 10.9202 12.2185C11.0202 11.8185 11.4302 11.5785 11.8302 11.6785L14.7402 12.4185C15.1502 12.5185 15.3902 12.9285 15.2902 13.3285ZM18.2202 9.94854C18.1302 10.2885 17.8302 10.5085 17.4902 10.5085C17.4302 10.5085 17.3702 10.4985 17.3002 10.4885L12.4502 9.25854C12.0502 9.15854 11.8102 8.74854 11.9102 8.34854C12.0102 7.94854 12.4202 7.70854 12.8202 7.80854L17.6702 9.03854C18.0802 9.12854 18.3202 9.53854 18.2202 9.94854Z" fill="#292D32"/>
                    </svg>
                </template>
            </v-list-item>
            <v-list-item @click="(carousel = 4)" :active="(carousel == 4)">
                <span class="ml-2">
                    Formation
                </span>
                <template v-slot:prepend>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.6761 19.9589C12.9508 20.0228 12.976 20.3827 12.7084 20.4719L11.1284 20.9919C7.15839 22.2719 5.06839 21.2019 3.77839 17.2319L2.49839 13.2819C1.21839 9.31187 2.27839 7.21187 6.24839 5.93187L6.77238 5.75834C7.17525 5.62493 7.56731 6.02899 7.45292 6.43766C7.39622 6.64023 7.34167 6.85164 7.28839 7.07188L6.30839 11.2619C5.20839 15.9719 6.81839 18.5719 11.5284 19.6919L12.6761 19.9589Z" fill="#292D32"/>
                        <path d="M17.1702 3.20854L15.5002 2.81854C12.1602 2.02854 10.1702 2.67854 9.00018 5.09854C8.70018 5.70854 8.46018 6.44854 8.26018 7.29854L7.28018 11.4885C6.30018 15.6685 7.59018 17.7285 11.7602 18.7185L13.4402 19.1185C14.0202 19.2585 14.5602 19.3485 15.0602 19.3885C18.1802 19.6885 19.8402 18.2285 20.6802 14.6185L21.6602 10.4385C22.6402 6.25854 21.3602 4.18854 17.1702 3.20854ZM15.2902 13.3285C15.2002 13.6685 14.9002 13.8885 14.5602 13.8885C14.5002 13.8885 14.4402 13.8785 14.3702 13.8685L11.4602 13.1285C11.0602 13.0285 10.8202 12.6185 10.9202 12.2185C11.0202 11.8185 11.4302 11.5785 11.8302 11.6785L14.7402 12.4185C15.1502 12.5185 15.3902 12.9285 15.2902 13.3285ZM18.2202 9.94854C18.1302 10.2885 17.8302 10.5085 17.4902 10.5085C17.4302 10.5085 17.3702 10.4985 17.3002 10.4885L12.4502 9.25854C12.0502 9.15854 11.8102 8.74854 11.9102 8.34854C12.0102 7.94854 12.4202 7.70854 12.8202 7.80854L17.6702 9.03854C18.0802 9.12854 18.3202 9.53854 18.2202 9.94854Z" fill="#292D32"/>
                    </svg>
                </template>
            </v-list-item>
            <v-list-item @click="(carousel = 5)" :active="(carousel == 5)">
                <span class="ml-2">
                    Revenue
                </span>
                <template v-slot:prepend>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.6761 19.9589C12.9508 20.0228 12.976 20.3827 12.7084 20.4719L11.1284 20.9919C7.15839 22.2719 5.06839 21.2019 3.77839 17.2319L2.49839 13.2819C1.21839 9.31187 2.27839 7.21187 6.24839 5.93187L6.77238 5.75834C7.17525 5.62493 7.56731 6.02899 7.45292 6.43766C7.39622 6.64023 7.34167 6.85164 7.28839 7.07188L6.30839 11.2619C5.20839 15.9719 6.81839 18.5719 11.5284 19.6919L12.6761 19.9589Z" fill="#292D32"/>
                        <path d="M17.1702 3.20854L15.5002 2.81854C12.1602 2.02854 10.1702 2.67854 9.00018 5.09854C8.70018 5.70854 8.46018 6.44854 8.26018 7.29854L7.28018 11.4885C6.30018 15.6685 7.59018 17.7285 11.7602 18.7185L13.4402 19.1185C14.0202 19.2585 14.5602 19.3485 15.0602 19.3885C18.1802 19.6885 19.8402 18.2285 20.6802 14.6185L21.6602 10.4385C22.6402 6.25854 21.3602 4.18854 17.1702 3.20854ZM15.2902 13.3285C15.2002 13.6685 14.9002 13.8885 14.5602 13.8885C14.5002 13.8885 14.4402 13.8785 14.3702 13.8685L11.4602 13.1285C11.0602 13.0285 10.8202 12.6185 10.9202 12.2185C11.0202 11.8185 11.4302 11.5785 11.8302 11.6785L14.7402 12.4185C15.1502 12.5185 15.3902 12.9285 15.2902 13.3285ZM18.2202 9.94854C18.1302 10.2885 17.8302 10.5085 17.4902 10.5085C17.4302 10.5085 17.3702 10.4985 17.3002 10.4885L12.4502 9.25854C12.0502 9.15854 11.8102 8.74854 11.9102 8.34854C12.0102 7.94854 12.4202 7.70854 12.8202 7.80854L17.6702 9.03854C18.0802 9.12854 18.3202 9.53854 18.2202 9.94854Z" fill="#292D32"/>
                    </svg>
                </template>
            </v-list-item>
            <v-list-item @click="(carousel = 6)" :active="(carousel == 6)">
                <span class="ml-2">
                    Conclusion
                </span>
                <template v-slot:prepend>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.6761 19.9589C12.9508 20.0228 12.976 20.3827 12.7084 20.4719L11.1284 20.9919C7.15839 22.2719 5.06839 21.2019 3.77839 17.2319L2.49839 13.2819C1.21839 9.31187 2.27839 7.21187 6.24839 5.93187L6.77238 5.75834C7.17525 5.62493 7.56731 6.02899 7.45292 6.43766C7.39622 6.64023 7.34167 6.85164 7.28839 7.07188L6.30839 11.2619C5.20839 15.9719 6.81839 18.5719 11.5284 19.6919L12.6761 19.9589Z" fill="#292D32"/>
                        <path d="M17.1702 3.20854L15.5002 2.81854C12.1602 2.02854 10.1702 2.67854 9.00018 5.09854C8.70018 5.70854 8.46018 6.44854 8.26018 7.29854L7.28018 11.4885C6.30018 15.6685 7.59018 17.7285 11.7602 18.7185L13.4402 19.1185C14.0202 19.2585 14.5602 19.3485 15.0602 19.3885C18.1802 19.6885 19.8402 18.2285 20.6802 14.6185L21.6602 10.4385C22.6402 6.25854 21.3602 4.18854 17.1702 3.20854ZM15.2902 13.3285C15.2002 13.6685 14.9002 13.8885 14.5602 13.8885C14.5002 13.8885 14.4402 13.8785 14.3702 13.8685L11.4602 13.1285C11.0602 13.0285 10.8202 12.6185 10.9202 12.2185C11.0202 11.8185 11.4302 11.5785 11.8302 11.6785L14.7402 12.4185C15.1502 12.5185 15.3902 12.9285 15.2902 13.3285ZM18.2202 9.94854C18.1302 10.2885 17.8302 10.5085 17.4902 10.5085C17.4302 10.5085 17.3702 10.4985 17.3002 10.4885L12.4502 9.25854C12.0502 9.15854 11.8102 8.74854 11.9102 8.34854C12.0102 7.94854 12.4202 7.70854 12.8202 7.80854L17.6702 9.03854C18.0802 9.12854 18.3202 9.53854 18.2202 9.94854Z" fill="#292D32"/>
                    </svg>
                </template>
            </v-list-item>
            
            <template v-slot:prepend>
                <a href="https://isetsf.rnu.tn/" target="_blank" class="logoHeader"></a>
            </template>
            <template v-slot:append>
                <div class="pa-3 pt-0">
                    <v-dialog v-model="dialog" transition="dialog-bottom-transition" width="50%">
                        <template v-slot:activator="{ props }">
                            <v-btn block rounded="lg" color="#2A1E91" text-color="white" v-bind="props">
                                <svg class="mr-2" width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M9.81838 0.589844C4.89961 0.589844 0.90918 4.57523 0.90918 9.49434C0.90918 14.4181 4.89961 18.4082 9.81834 18.4082C14.7398 18.4082 18.7268 14.4181 18.7268 9.49434C18.7269 4.57523 14.7398 0.589844 9.81838 0.589844ZM10.4532 14.4517C10.2463 14.6358 10.0065 14.7283 9.73487 14.7283C9.45381 14.7283 9.20864 14.6374 8.99937 14.4553C8.78977 14.2735 8.68476 14.019 8.68476 13.692C8.68476 13.4019 8.78638 13.1577 8.98897 12.9598C9.19156 12.7619 9.44007 12.663 9.73487 12.663C10.025 12.663 10.2691 12.7619 10.4674 12.9598C10.6652 13.1577 10.7645 13.4018 10.7645 13.692C10.7641 14.0143 10.6605 14.2676 10.4532 14.4517ZM13.0334 8.05519C12.8744 8.34999 12.6856 8.6042 12.4666 8.81854C12.2482 9.03285 11.8555 9.39305 11.2887 9.89947C11.1324 10.0424 11.0066 10.1678 10.9124 10.2758C10.8182 10.3841 10.7477 10.483 10.7018 10.5729C10.6555 10.6628 10.6199 10.7527 10.5948 10.8426C10.5696 10.9321 10.5317 11.0901 10.4804 11.3158C10.3932 11.7947 10.1192 12.0341 9.6587 12.0341C9.41923 12.0341 9.21801 11.956 9.054 11.7994C8.89065 11.6428 8.80916 11.4103 8.80916 11.1018C8.80916 10.7151 8.86919 10.38 8.98893 10.0967C9.10801 9.81324 9.26731 9.56473 9.4652 9.35042C9.66341 9.13612 9.93036 8.88188 10.2668 8.58707C10.5616 8.32916 10.7745 8.13466 10.9057 8.00349C11.0371 7.87204 11.1475 7.72581 11.237 7.56481C11.3273 7.40349 11.3715 7.22875 11.3715 7.03994C11.3715 6.67137 11.235 6.3608 10.9607 6.10759C10.6867 5.85438 10.3332 5.72759 9.9002 5.72759C9.39344 5.72759 9.02049 5.85537 8.78102 6.11093C8.54155 6.3665 8.33933 6.74279 8.1733 7.24018C8.01635 7.76072 7.71919 8.02094 7.28217 8.02094C7.02425 8.02094 6.8066 7.93005 6.62919 7.74826C6.4521 7.56646 6.36355 7.36961 6.36355 7.15766C6.36355 6.7203 6.50408 6.27692 6.78482 5.82785C7.06588 5.37877 7.47572 5.00681 8.01466 4.71234C8.55327 4.41754 9.18215 4.26995 9.9002 4.26995C10.568 4.26995 11.1572 4.39336 11.6684 4.63989C12.1795 4.88605 12.5746 5.22112 12.8533 5.64502C13.1316 6.0686 13.2711 6.5291 13.2711 7.02649C13.2718 7.41727 13.1923 7.76039 13.0334 8.05519Z" fill="white" />
                                </svg>
                                à propos
                            </v-btn>
                        </template>
                        <v-card color="#14213D">
                            <v-card-text style="color: #FFFFFF;">
                                les références :<br/>
                                ▬ <a href="https://www.data-transitionnumerique.com/developpeur-full-stack-fiche-metier/" target="_blank"> Développeur full stack : fiche métier (salaire, missions, compétences …)</a><br/>
                                ▬ <a href="https://www.coover.fr/metiers/digital/developpeur" target="_blank"> Devenir développeur web : Formation, salaire et conseils</a><br/>
                                ▬ <a href="http://skyvuesolutions.com/blog/FOCUS%20SUR%20LES%20METIERS%20D'AVENIR%20:%20Devellopeur%20Full%20Stack" target="_blank">FOCUS SUR LES METIERS D'AVENIR : Devellopeur Full Stack.</a><br/>
                                ▬ <a href="https://blog.hubspot.fr/website/developpeur-full-stack" target="_blank">Qu'est-ce qu'un développeur full stack ?</a><br/>
                                ▬ <a href="https://www.synonyme-du-mot.com/les-articles/quels-sont-les-differents-types-de-developpeur" target="_blank">Quels sont les différents types de développeur ?</a><br/>
                                ▬ <a href="https://fabskill.com/fr/job/974/d%C3%A9veloppeur-full-stack-junior" target="_blank">Développeur Full Stack (Junior) | Expensya</a><br/>
                                
                                Outils de développement utilisé :<br/>
                                ▬ <a href="https://vuejs.org/" target="_blank"> Vuejs</a><br/>
                                ▬ <a href="https://next.vuetifyjs.com/en/" target="_blank">Vuetify</a><br/>
                            </v-card-text>
                        </v-card>
                    </v-dialog>
                </div>
            </template>
        </v-navigation-drawer>
        <v-app-bar style="background-color: #14213D;" color="#14213D">
            <v-row no-gutters>
                <v-col cols="4.5">
                    <v-sheet class="d-flex fill-height justify-center align-center"
                        style="background-color: transparent; color: #FFFFFF;">
                        PROJET SUR LES METIERS D'AVENIR : Développeur Full Stack.
                    </v-sheet>
                </v-col>
                <v-col cols="4.5">
                    <v-sheet class="d-flex justify-center align-center"
                        style="background-color: transparent; color: #FFFFFF;">
                        Matière : technologie de recherche d'emploi et marketing de soi
                    </v-sheet>
                    <v-sheet class="d-flex justify-center align-center"
                        style="background-color: transparent; color: #FFFFFF;">
                        Date : 13/12/2022
                    </v-sheet>
                </v-col>
                <v-col cols="3">
                    <v-sheet class=" d-flex fill-height justify-center align-center"
                        style="background-color: transparent;">
                        <v-chip size="x-large" variant="outlined" style="color: #FFFFFF;"
                            href="https://www.linkedin.com/in/yassinedaggaz" target="_blank">
                            <h4>Yassine Daggaz - DSI31</h4>
                            <template v-slot:prepend>
                                <v-avatar class="green-darken-4" size="35">
                                    <img src="../assets/My-avatar.png" style="width: 35px;">
                                </v-avatar>
                            </template>
                        </v-chip>
                    </v-sheet>
                </v-col>
            </v-row>
        </v-app-bar>
        <v-main>
            <v-card style="width: 100%; float: right; height: 100%;" plat>
                <v-carousel v-model="carousel" height="100%" :show-arrows="false" hide-delimiters>
                    <v-carousel-item :value="parseInt('0')">
                        <v-sheet color="#0c2557" height="100%" tile >
                            <div class="d-flex fill-height justify-center align-center">
                                <div>
                                    <introdution/>
                                </div>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                    <v-carousel-item :value="parseInt('1')">
                        <v-sheet color="#0c2557" height="100%" tile>
                            <div class="d-flex fill-height justify-center align-center">
                                <div class="ma-2">
                                    <description />
                                </div>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                    <v-carousel-item :value="parseInt('2')">
                        <v-sheet color="#0c2557" height="100%" tile>
                            <div class="d-flex fill-height justify-center align-center">
                                <div>
                                    <mission/>
                                </div>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                    <v-carousel-item :value="parseInt('3')">
                        <v-sheet color="#0c2557" height="100%" tile>
                            <div class="d-flex fill-height justify-center align-center">
                                <div class="text-h2">
                                    <qualites/>
                                </div>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                    <v-carousel-item :value="parseInt('4')">
                        <v-sheet color="#0c2557" height="100%" tile>
                            <div class="d-flex fill-height justify-center align-center">
                                <div >
                                    <Formation/>
                                </div>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                    <v-carousel-item :value="parseInt('5')">
                        <v-sheet color="#0c2557" height="100%" tile>
                            <div class="d-flex fill-height justify-center align-center">
                                <div class="text-h2">
                                    <revenue/>
                                </div>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                    <v-carousel-item :value="parseInt('6')">
                        <v-sheet color="#0c2557" height="100%" tile>
                            <div class="d-flex fill-height justify-center align-center">
                                <div class="text-h2">
                                    <conclusion/>
                                </div>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                </v-carousel>
            </v-card>
        </v-main>
    </v-layout>
</template>
<script>
import introdution from './introduction.vue'
import description from './description.vue';
import Formation from './Formation.vue';
import mission from './mission.vue';
import qualites from './qualites.vue';
import conclusion from './conclusion.vue';
import revenue from './revenue.vue';

export default {
    components: {
        introdution, description, Formation,mission,qualites,conclusion,revenue
    },
    data() {
        return {
            carousel: 0,
            dialog: false,
        }
    },
    mounted(){
        

    },
    methods(){
        
    }
}
</script>
<style>
.v-list-item {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    color: #ffffff !important;
    stroke: #ffffff;
    height: 70px;
    line-height: 18px;
    text-align: start;
}

.v-list-item--active {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    stroke: #114EF7;
    color: #114EF7 !important;
    border: #114EF7 !important;
}

.logoHeader {
    background: url('../assets/logo-isetsf.png') no-repeat;
    width: 100%;
    background-position: center;
    height: 74px;
    display: block;
}

.v-navigation-drawer {
    border-color: transparent !important;
}

.v-card {
    border-radius: 0px !important;
}


a{
    color: #ffffff;
}
</style>