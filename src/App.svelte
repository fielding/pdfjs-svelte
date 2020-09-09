<script>
  import PdfViewer from "./pdf-viewer/viewer.svelte";

  const src = (new URLSearchParams(location.search).get('src') || ''); // can specify local pdf by commenting this out or replacing the '' fallback
</script>

<PdfViewer {src} />
