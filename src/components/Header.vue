<template>
    <div class="header container-fluid">
        <Navbar />
        <div class="wrapper__intro">
            <h2 class="weight--bold">I'm Candice</h2>
            <h4>Freelance Front end Developer and Web Designer</h4>
        </div>
        <div class="container-fluid header__content">
            <div class="btn__group">
                <button type="button" class="btn btn-secondary">Projects</button>
                <button type="button" class="btn btn-outline-light">Contact Me</button>
            </div>
        </div>
    </div>
</template>

<script>
import '../scss/_global.scss';
import '../scss/header.scss';
import Navbar from './Navbar'

export default {
    name: 'Header',
    components: {
        Navbar
    }
}
</script>