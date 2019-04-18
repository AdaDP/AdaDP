<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-AMS_HTML-full"></script>
  
# AdaDP
IJCAI 2019 rebuttal supplementary pictures

$`\sigma`$

![Compared with all algorithms](https://github.com/NJUIoT/AdaDP/blob/master/all_together-1.png)
#### Figure 1. The performance of AdaDP, DPSGD, the algorithm proposed in [Lee and Kifer, 2018] and the algorithm proposed in [Koskela, 2018] under high privacy level setting (<img src="https://latex.codecogs.com/png.latex?\epsilon=0.5" />). The noise level <img src="https://latex.codecogs.com/gif.latex?\sigma" /> is set to 8.0 and the lot size <img src="https://latex.codecogs.com/gif.latex?L" /> is set to 600. The gray line shows the privacy cost of AdaDP, DPSGD and the algorithm proposed in [Koskela, 2018]. The pink line shows the privacy cost of the algorithm proposed in [Lee and Kifer, 2018].

![Performance under extreme high privacy leve lsetting](https://github.com/NJUIoT/AdaDP/blob/master/mnist_eps=0.1-1.png)
#### Figure 2. The performance of AdaDP, DPSGD  high privacy level setting. The noise level <img src="https://latex.codecogs.com/png.latex?\sigma" /> is set to 8.0 and the lot size <img src="https://latex.codecogs.com/png.latex?L" /> is set to 600.

![Performance with only adaptive learning rate](https://github.com/NJUIoT/AdaDP/blob/master/only_adaptive_lr-1.png)
#### Figure 3. The performance of training without adaptive noise.  The noise level <img src="https://latex.codecogs.com/png.latex?\sigma" /> is set to 8.0 and the lot size <img src="https://latex.codecogs.com/png.latex.latex?L" /> is set to 600.


