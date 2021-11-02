||
--|--
**Video** | [Browser,what are you doing?](https://youtu.be/Gk9a77ogn6ke)
**tags** | #content-injection #Content-Security-Policy
**From** | Intigriti
**Date** | 2021-11-01
**Key topics** | Content injection

---
#### Content-injection 
Changes the content of site.
website/page.php?html=test 
website/page.php?html=<script>alert(document.domain);</script> 

## Content-Security-Policy
A CSP is a kind of mitigation to mitigate injection attacks such as Xss.

**How it works** - You define a policy that says *What can be loaded on script*.
#attribute **script-src** is used for what is allowed.
**strict-dynamic** - source expression specifies that the trust explicitly given to a script present, shall be propagated to all scripts loaded by that root script. 
