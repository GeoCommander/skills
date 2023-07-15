[Link Text](https://www.google.com){:class="preview-link" data-preview-url="https://www.google.com"}


<style>
  .preview-link::after {
    content: attr(data-preview-url);
    position: absolute;
    background: #fff;
    border: 1px solid #ccc;
    padding: 5px;
    display: none;
  }

  .preview-link:hover::after {
    display: block;
  }
</style>