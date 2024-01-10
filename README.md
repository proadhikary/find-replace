# find-replace
This does the usual find &amp; replace, but the catch is, addressing a uniformity issue wherein identical words within a sentence exhibit varying letter casings, the objective is to substitute each occurrence with the corresponding casing as per the original's regular expression pattern, ensuring consistency in letter casing throughout.

Link: https://proadhikary.github.io/find-replace/

Suppose the given text contains:
``
Rahul
rahul
raHul
``

And, you want to replace that all of names the document has. If our target word is `rahul`, which you want to replace with nihar. In that case the output should be:
``
Nihar
nihar
niHar
``
