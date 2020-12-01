<template>
      <!--Start Welcome section-->
    <section id="welcome-section" class="welcome-section">
        <h1>Hey im Eugen</h1>
        <p>a web developer</p>
    </section>
    <!--End Welcome section-->
</template>

<style>
   /* Welcome section */

        .welcome-section {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 100%;
            height: 100vh;
            background-color: #000;
            background-image: linear-gradient(62deg, #3a3d40 0%, #181719 100%);
        }

        .welcome-section>p {
            font-size: 3rem;
            font-weight: 200;
            font-style: italic;
            color: var(--main-red);
        }

</style>