<script setup>
import NavBarComponent from '../components/NavBarComponent.vue';
</script>

<template>
    <main>
        <div>
            <header>
                <nav>
                    <NavBarComponent />
                </nav>
            </header>
        </div>
        <div class="hero bg-base-100">
            <div class="hero-content text-center prose">
                <div class="max-w-md">
                    <h1>Discover your Vision</h1>
                    <p>
                        Welcome to Ross A.M. Pro. Here you can search my offerings,
                        experience, and interests. Click below to take a look.
                    </p>
                    <button class="btn btn-primary">Get Started</button>
                </div>
            </div>
        </div>
    </main>
</template>
