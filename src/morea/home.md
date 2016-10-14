---
title: "Home"
morea_id: home
morea_type: home
---

<div class="section-background-0" itemscope="" itemtype="http://schema.org/SoftwareApplication">
 <div class="container">
   <div class="row">
    <div class="col-sm-10">
        <h2><strong>Welcome to SAX-VSM homepage!</strong></h2>
        <h4>A Java library that implements SAX-VSM algorithm for interpretable time series classification.</h4>
        <h5><em>(Most of the website's content is inherited from <a href="https://code.google.com/p/jmotif/">JMotif project</a>.
        Here are quick links to the <a href="https://github.com/jMotif/sax-vsm_classic">source code</a> and
        <a href="http://www2.hawaii.edu/~senin/assets/papers/sax-vsm-icdm13-short.FINAL_DRAFT.pdf">the paper</a>)</em>.</h5>
        <h5><em>(I am still working on this website, sorry.)</em>.</h5>
    </div>
    <div class="col-sm-2">
        <img style="margin-top: 50px; margin-bottom: 15px" src="morea/assets/logo.png" width="151px" class="img-responsive center-block">
    </div>
   </div>
 </div>
</div>

<div class="row top-buffer">

 <div class="section-background-1">
  <div class="container">
   <div class="row">

         <div class="col-sm-10">
            <h3><strong>Algorithms discussed here:</strong></h3>
            
            <h4>SAX steps:</h4>
                <ul>
                <li><a href="morea/algorithm/znorm.html">Z normalization of timeseries</a></li>
                <li><a href="morea/algorithm/PAA.html">PAA: Piecewise Aggregate Approximation of time series</a></li>
                <li><a href="morea/algorithm/SAX.html">SAX: Symbolic Aggregate Approximation of time series</a></li>
                <li><a href="morea/algorithm/SlidingWindowSAX.html">Time series discretization via sliding window</a></li>
                </ul>
            
            <h4>Patterns discovery with SAX:</h4>
                <ul>
                <li><a href="morea/patterns/motifs.html">Motif detection with SAX</a></li>
                <li>Discord detection with SAX</li>
                <li><a href="morea/algorithm/SAXBitmap.html">SAX bitmap patterns visualization</a></li>
                </ul>
            
            <h4>Vector space model (VSM):</h4>
                <ul>
                <li>TF*IDF statistics</li>
                <li>Cosine similarity</li>
                </ul>
            
            <h4>SAX-VSM in action:</h4>
                <ul>
                <li>Time series classification</li>
                <li>Hierarchical clustering</li>
                <li>Spherical K-Means</li>
                </ul>
         </div>
         
   </div>
 </div>
</div>

<!-- Add a github ribbon. -->
<link rel="stylesheet" href="css/gh-fork-ribbon.css">
<div class="github-fork-ribbon-wrapper right">
  <div class="github-fork-ribbon">
    <a href="https://github.com/jMotif/sax-vsm_classic">SAX-VSM on GitHub</a>
  </div>
</div>