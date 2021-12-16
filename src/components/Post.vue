<template>
    <div class="post">
        <h2>{{ post.author }}</h2>
        <p>{{ post.content }}</p>
    </div>
</template>
<script>
export default {
    data() {
        return {
            names: [
                "Matt Maribojoc",
                "Lebron James",
                "Bill Gates",
                "Childish Gambino",
            ]
        }
    },
    props: {
        post: Object
    },
    methods: {
        getPosts(number) {
            let ret = [];

            for (var i = 0; i < number; i++) {
                ret.push({
                    author: this.names[i % this.names.length],
                    content:
                        "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.",
                });
            }

            return ret;
        }
    },

}
</script>
<style scoped>
.post {
    background: #fff;
    padding: 1.5em;
}

.post:not(:last-child) {
    border-bottom: 1px solid #ddd;
}

.post h2 {
    font-size: 1.3em;
    padding-bottom: 0.25rem;
}

.post p {
    color: #888;
}
</style>
