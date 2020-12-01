<template>

    <!--Start contact section-->
    <section id="contact" class="contact-section">

        <div class="contact-section-header">
            <h2>Let's work together...</h2>
            <p>How do you take your coffee?</p>
        </div>
        <div class="contact-links">
            <a href="https://facebook.com/" target="_blank" class="btn contact-details"><i
                    class="fab fa-facebook-square"></i> Facebook</a>
            <a id="profile-link" href="https://github.com/" target="_blank" class="btn contact-details"><i
                    class="fab fa-github"></i> GitHub</a>
            <a href="https://twitter.com/" target="_blank" class="btn contact-details"><i
                    class="fab fa-twitter"></i> Twitter</a>
            <a href="mailto:example@example.com" class="btn contact-details"><i class="fas fa-at"></i> Send a mail</a>
            <a href="tel:555-555-5555" class="btn contact-details"><i class="fas fa-mobile-alt"></i> Call me</a>
        </div>
    </section>
    <!--End contact sections-->

</template>

<style>
/* Contact section */

.contact-section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    width: 100%;
    height: 80vh;
    padding: 0 2rem;
    background: var(--main-gray);
}

.contact-section-header>h2 {
    font-size: 6rem;
}

@media (max-width: 28.75em) {
    .contact-section-header>h2 {
        font-size: 4rem;
    }
}

.contact-section-header>p {
    font-style: italic;
}

.contact-links {
    display: flex;
    justify-content: center;
    width: 100%;
    max-width: 980px;
    margin-top: 4rem;
    flex-wrap: wrap;
}

.contact-details {
    font-size: 2.4rem;
    text-shadow: 2px 2px 1px #1f1f1f;
    transition: transform 0.3s ease-out;
}

.contact-details:hover {
    transform: translateY(8px);
}
</style>