<template>
    <!-- Start footer-->
    <footer>
        <p>
           
        </p>
        <p>
            &copy; Created for
            <a href="" target="_blank">Code <i
                    class="fab fa-free-code-camp"></i></a>
        </p>
    </footer>
    <!--End footer-->
</template>

<style>
/* Footer */

footer {
    font-weight: 300;
    display: flex;
    justify-content: space-evenly;
    padding: 2rem;
    background: var(--main-gray);
    border-top: 4px solid var(--main-red);
}

footer>p {
    margin: 2rem;
}

footer i {
    vertical-align: middle;
}

@media (max-width: 28.75em) {
    footer {
        flex-direction: column;
        text-align: center;
    }
}

</style>