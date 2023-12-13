## Events

```svelte
<script lang="ts">
    import { energy } from "svelte-energy";
</script>

<div use:energy={[
    [
        [0, { opacity: 0, x: 0, scale: 1 }],
        [0.5, { scale: 1.5, rotation: 0 }],
        [1, { scale: 1, x: 100 }],
        [2, { opacity: 1, x: 0, rotation: 360 }],
        [3, { opacity: 0 }],

        [0.25, { y: 0 }],
        [0.75, { y: 100 }],
        [1.5, { y: 0 }]
    ],
]} />
```