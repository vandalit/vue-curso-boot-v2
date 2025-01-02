<template>
    <div class="card shadow-sm">
        <img :src="imageUrl" class="card-img-top" :alt="title" />
        <div class="card-body">
            <h5 class="card-title">{{ title }}</h5>
            <p class="card-text">
                {{ description }}
            </p>
            <!-- Botón o link con clases de Bootstrap -->
            <button class="btn btn-primary">Ver más</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CourseCard',
    props: {
        title: String,
        description: String,
        imageUrl: String
    }
}
</script>

<style scoped>
/* Opcional: estilos propios */
</style>