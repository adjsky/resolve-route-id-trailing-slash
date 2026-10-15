<script lang="ts">
    import { resolve } from "$app/paths";

    console.log(resolve("/a/[param]", { param: "qwerty" }));
    console.log(resolve("/b/[param]", { param: "qwerty" }));
    console.log(resolve("/a/[param]/", { param: "qwerty" }));
    console.log(resolve("/b/[param]/", { param: "qwerty" }));
</script>