<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div>{{ message }}</div>
                <div class="card">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        I'm an example component.
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import { ref } from "vue";
    export default {
        setup() {
            const message = ref("Hello Laravel Vue 3");

            return {
              message
            };
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
