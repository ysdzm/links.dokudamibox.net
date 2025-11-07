# dokudamibox.net

<script type='module'>
    import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
    mermaid.initialize({ startOnLoad: false });
    await mermaid.run({
        querySelector: 'pre > code.language-mermaid',
    });
</script>

```mermaid
flowchart LR
    root["<a href='https://dokudamibox.net'>dokudamibox.net</a>"]
    blog["<a href='https://blog.dokudamibox.net'>blog.dokudamibox.net</a>"]

    root --- blog
```
