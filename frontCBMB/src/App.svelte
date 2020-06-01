<script>
  import routes from "./routes.js";
  import Router from "svelte-spa-router";
  import { link } from "svelte-spa-router";
</script>

<style>

</style>
<a href="/" use:link>Home</a>
<a href="/test" use:link>Test</a>
<Router {routes} />
