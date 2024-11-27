<template>
    <div class="container">
        <h1 class="title">Trial2024</h1>
        <div class="footer">
            <a href="/privacy-policy" class="privacy-link">Privacy policy</a>
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexPage'
}
</script>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    justify-content: space-between;
    align-items: center;
}

.title {
    font-size: 2.5rem;
    margin-top: 2rem;
}

.footer {
    margin-bottom: 1rem;
}

.privacy-link {
    text-decoration: none;
    color: #007bff;
}

.privacy-link:hover {
    text-decoration: underline;
}
</style>