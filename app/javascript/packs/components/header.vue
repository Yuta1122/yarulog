<template>
    <div>
        <ul id="dropdown" class="dropdown-content">
            <li><router-link to="/about">About</router-link></li>
            <li><router-link to="/">Want</router-link></li>
            <li><router-link to="/done">Done</router-link></li>
            <li><router-link to="/couldnot">Couldnot</router-link></li>
            <li><router-link to="/add">Add</router-link></li>
        </ul>
        <nav>
            <div class="nav-wrapper container">
                <a href="/" class="brand-logo left">やるLOG</a>
                <ul class="right hide-on-med-and-down">
                    <li><router-link to="/about">About</router-link></li>
                    <li><router-link to="/">Want</router-link></li>
                    <li><router-link to="/done">Done</router-link></li>
                    <li><router-link to="/couldnot">Couldnot</router-link></li>
                    <li><router-link to="/add">Add</router-link></li>
                </ul>
                <ul class="right hide-on-large-only">
                    <li>
                        <a class="dropdown-button" href="#!" data-activates="dropdown">
                            Menu<i class="material-icons right">arrow_drop_down</i>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>