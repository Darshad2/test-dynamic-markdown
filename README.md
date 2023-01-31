# test-dynamic-markdown

<script>
    const urlParams = new URLSearchParams(window.location.search);
    const parameter = urlParams.get('_a');

    document.getElementById("parameter-display").innerHTML = "The parameter value is: " + parameter;
</script>

<div id="parameter-display"></div>
