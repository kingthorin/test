{%- if content contains 'mermaid' -%}
<script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.0.0/mermaid.min.js"></script>
<script>
const config = {
    startOnLoad:true,
    theme: 'forest',
    flowchart: {
        useMaxWidth:false,
        htmlLabels:true
        }
};
mermaid.initialize(config);
window.mermaid.init(undefined, document.querySelectorAll('.language-mermaid'));
</script>
{% endif %}

# Test

 [will fail DNS](https://shouldfailtolookup.com/)
 
 [will fail 404](https://owasp.org/www-community/fail)
 
 ```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
