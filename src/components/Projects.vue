<template>
        <!--Star Projeck section-->
    <section id="Projects" class="projects-section">
        <h2 class="projects-section-header">These are some of my projects</h2>
        <div class="projects-grid">
            <a href="https://codepen.io/" target="_blank" class="project project-tile">
                <img class="project-image"
                    src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/tribute.jpg"
                    alt="project" />
                <p class="project-title">
                    <span class="code">&lt;</span>
                    Tribute Page
                    <span class="code">&#47;&gt;</span>
                </p>
            </a>
            <a href="https://codepen.io/" target="_blank" class="project project-tile">
                <img class="project-image"
                    src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/random-quote-machine.png"
                    alt="project" />
                <p class="project-title">
                    <span class="code">&lt;</span>
                    Random Quote Machine
                    <span class="code">&#47;&gt;</span>
                </p>
            </a>
            <a href="https://codepen.io/" target="_blank" class="project project-tile">
                <img class="project-image"
                    src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/calc.png"
                    alt="project" />
                <p class="project-title">
                    <span class="code">&lt;</span>
                    JavaScript Calculator
                    <span class="code">&#47;&gt;</span>
                </p>
            </a>
            <a href="https://codepen.io/" target="_blank" class="project project-tile">
                <img class="project-image"
                    src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/map.jpg"
                    alt="project" />
                <p class="project-title">
                    <span class="code">&lt;</span>
                    Map Data Across the Globe
                    <span class="code">&#47;&gt;</span>
                </p>
            </a>
            <a href="https://codepen.io/" target="_blank" class="project project-tile">
                <img class="project-image"
                    src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/wiki.png"
                    alt="project" />
                <p class="project-title">
                    <span class="code">&lt;</span>
                    Wikipedia Viewer
                    <span class="code">&#47;&gt;</span>
                </p>
            </a>
            <a href="https://codepen.io/" target="_blank" class="project project-tile">
                <img class="project-image"
                    src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/tic-tac-toe.png"
                    alt="project" />
                <p class="project-title">
                    <span class="code">&lt;</span>
                    Tic Tac Toe Game
                    <span class="code">&#47;&gt;</span>
                </p>
            </a>
        </div>
        <a href="https://codepen.io/" class="btn btn-show-all" target="_blank">Show all<i
                class="fas fa-chevron-right"></i></a>
    </section>
    <!--End Project section-->
</template>

<style>
 /* Projects section */

        .projects-section {
            text-align: center;
            padding: 10rem 2rem;
            background: var(--main-blue);
        }

        .projects-section-header {
            max-width: 640px;
            margin: 0 auto 6rem auto;
            border-bottom: 0.2rem solid var(--main-white);
        }

        @media (max-width: 28.75em) {
            .projects-section-header {
                font-size: 4rem;
            }
        }

        /* "Automagic" image grid using no media queries */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            grid-gap: 4rem;
            width: 100%;
            max-width: 1280px;
            margin: 0 auto;
            margin-bottom: 6rem;
        }

        @media (max-width: 30.625em) {
            .projects-section {
                padding: 6rem 1rem;
            }

            .projects-grid {
                grid-template-columns: 1fr;
            }
        }

        .project {
            background: var(--main-gray);
            box-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
            border-radius: 2px;
        }

        .code {
            color: var(--main-gray);
            transition: color 0.3s ease-out;
        }

        .project:hover .code {
            color: #ff7f50;
        }

        .project-image {
            height: calc(100% - 6.8rem);
            width: 100%;
            object-fit: cover;
        }

        .project-title {
            font-size: 2rem;
            padding: 2rem 0.5rem;
        }

        .btn {
            display: inline-block;
            padding: 1rem 2rem;
            border-radius: 2px;
        }

        .btn-show-all {
            font-size: 2rem;
            background: var(--main-gray);
            transition: background 0.3s ease-out;
        }

        .btn-show-all:hover {
            background: var(--main-red);
        }

        .btn-show-all:hover>i {
            transform: translateX(2px);
        }

        .btn-show-all>i {
            margin-left: 10px;
            transform: translateX(0);
            transition: transform 0.3s ease-out;
        }
</style>