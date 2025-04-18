<template>
    <DefaultSection>
        <DefaultContent class="!max-w-[1920px]">
            <picture>
                <source media="(min-width: 1440px)" srcset="/images/home/banners/Revear-Hero-DesktopXL.png" />
                <source media="(min-width: 1080px)" srcset="/images/home/banners/Revear-Hero-Desktop.png" />
                <source media="(min-width: 660px)" srcset="/images/home/banners/Revear-Hero-Tablet.png" />
                <NuxtImg src="/images/home/banners/Revear-Hero-Mobile.png" alt="Revear Hero"
                    class="w-full object-cover" />
            </picture>
        </DefaultContent>
    </DefaultSection>
</template>