# find-replace
This does the usual find &amp; replace, but the catch is, addressing a uniformity issue wherein identical words within a sentence exhibit varying letter casings, the objective is to substitute each occurrence with the corresponding casing as per the original's regular expression pattern, ensuring consistency in letter casing throughout.


Suppose the given text contains:
``
Rahul
rahul
raHul
``

I want to replace that name completely. So need to focus on all of them.

Target word is `rahul`, which I want to replace that with nihar. In that case the output should be:
``
Nihar
nihar
niHar
``
