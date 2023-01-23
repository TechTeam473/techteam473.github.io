---
title: Home
excerpt: "We're a six person team who share a love of computer science. We host a wide variety of skills and passions that allow us to make incredible things. Our current project is Fable, an open world RPG filled with magical calamities and governmental tensions."
---

<style>

    h1.main-text {
        font-family: 'Source Code Pro', monospace;
        opacity: 0;
        animation: fade-in 1s;
        animation-fill-mode: forwards;
        animation-delay: 0.5s;
        text-align: center;
    }

    div.button-container {
        height: 50%;
        opacity: 0;
        animation: fade-in 1s;
        animation-fill-mode: forwards;
        animation-delay: 1.5s;
    }

    div.button-container-child {
        width: 50%;
        height: 100%;
        float: left;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center; 
        text-align: center;
        font-family: 'Source Code Pro', monospace;
        font-size: 3em;
    }

    @keyframes fade-in {
        from {
            opacity: 0;
        }

        to {
            opacity: 1.0;
        }
    }

</style>

<h1 class="main-text"><em>Hello. Welcome to TechTeam473</em></h1>

<div class="button-container">
    <a href="/fable/">
        <div id="fable-button" class="button-container-child button--pulse">
            Fable
        </div>
    </a>
    <a href="/about/">
        <div id="about-button" class="button-container-child button--pulse">
            Our Team
        </div>
    </a>
</div>