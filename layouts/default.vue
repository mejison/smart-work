<template>
  <div class="wrapper">
    <Nuxt />
  </div>
</template>

<style>
/* common */
.wrapper {
  background: url("/assets/images/background.png");
  background-position: 0px 0px;
  background-repeat: no-repeat;
  font-family: "HK Grotesk Regular", Arial, Helvetica, sans-serif;
}

.text-custom-blue {
  color: #335eea;
}

.bg-custom-blue {
  background-color: #335eea;
}

.text-custom-gray {
  color: #506690;
}

.bg-custom-gray {
  background-color: #506690;
}

.text-custom-gray-light {
  color: #6b7c93;
}

.text-custom-black {
  color: #161b2d;
}

.text-custom-green-light {
  color: #52c2a1;
}

.font-custom-bold {
  font-family: "HK Grotesk Bold";
}

/* fonts */
@font-face {
  font-family: "HK Grotesk Regular";
  font-style: normal;
  font-weight: normal;
  src: local("HK Grotesk Regular"),
    url("/assets/fonts/HKGrotesk-Regular.woff") format("woff");
}

@font-face {
  font-family: "HK Grotesk Italic";
  font-style: normal;
  font-weight: normal;
  src: local("HK Grotesk Italic"),
    url("/assets/fonts/HKGrotesk-Italic.woff") format("woff");
}

@font-face {
  font-family: "HK Grotesk Light";
  font-style: normal;
  font-weight: normal;
  src: local("HK Grotesk Light"),
    url("/assets/fonts/HKGrotesk-Light.woff") format("woff");
}

@font-face {
  font-family: "HK Grotesk Medium";
  font-style: normal;
  font-weight: normal;
  src: local("HK Grotesk Medium"),
    url("/assets/fonts/HKGrotesk-Medium.woff") format("woff");
}

@font-face {
  font-family: "HK Grotesk Bold";
  font-style: normal;
  font-weight: normal;
  src: local("HK Grotesk Bold"),
    url("/assets/fonts/HKGrotesk-Bold.woff") format("woff");
}
</style>
