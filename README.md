# CppPrimer
Learning CppPrimer Recording

This is my C Plus Plus learning path, I will record the whole exercise in the repository. 

## It's illegal to let a pointer point to a reference / But legal to let declare a reference pointer

<pre><code>
// wrong example: pointer to reference
    double double_a = 1;
    double &reference_double_a = double_a;
    
    double &* double_pointer_to_reference = & reference_double_a;
</code></pre>
<pre><code>
// legal example
    double double_a = 1;
    double &reference_double_a = double_a;
    
    double *& double_pointer_to_reference = & reference_double_a;
</code></pre>