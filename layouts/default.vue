<template>
    <div>
        <header></header>
            <nav>
                <ul>
                    <li>
                        <nuxt-link to="/">Home</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="/about">About</nuxt-link>
                    </li>
                </ul>
            </nav>
        <slot />
        <footer><p> made by wyni </p></footer>
    </div>
</template>