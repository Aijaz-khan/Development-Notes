To Copy in Clipboard Javascript code.

<script src="https://cdnjs.cloudflare.com/ajax/libs/clipboard.js/1.5.10/clipboard.min.js"></script>
  new Clipboard('#copy-code-sp', {
        text: function() {
            return "Content";
        }
    });
