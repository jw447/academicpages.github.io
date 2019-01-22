---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}
<style>
#more {display: none;}
</style>

## Compression Ratio Modeling and Estimation Across Error Bounds for Lossy Compression

Abstract—Scientific simulations on high-performance computing (HPC) systems generate vast amounts of floating-point data that need to be reduced in order to lower the storage and I/O cost. Lossy compressors trade data accuracy for reduction performance and have been demonstrated to be effective in reducing data volume. However, a key hurdle to wide adoption of lossy compressors is that the trade-off between data accuracy and compression performance, <span id="dots">...</span><span id="more">particularly the compression ratio, is not well understood. Consequently, domain scientists often need to exhaust many possible error bounds before they can figure out an appropriate setup. The current practice of using lossy compressors to reduce data volume is, therefore, through trial and error, which is not efficient for large datasets which take a tremendous amount of computational resources to compress. This paper aims to analyze and estimate the compression performance of lossy compressors on HPC datasets. In particular, we predict the compression ratios of two modern lossy compressors that achieve superior performance, SZ and ZFP, on HPC scientific datasets at various error bounds, based upon the compressors’ intrinsic metrics collected under a given base error bound. We evaluate the estimation scheme using nine real HPC datasets and the results confirm the effectiveness of our approach.</span><button onclick="myFunction()" id="myBtn">Read more</button>

<!-- ## Robust and scalable deep learning for X-ray synchrotron image analysis -->


<!--  ------------------------- -->

<script>
function myFunction() {
	var dots = document.getElementById("dots");
	var moreText = document.getElementById("more");
	var btnText = document.getElementById("myBtn");

	if (dots.style.display === "none") {
		dots.style.display = "inline";
		btnText.innerHTML = "Read more"; 
		moreText.style.display = "none";
	} else {
		dots.style.display = "none";
		btnText.innerHTML = "Read less"; 
		moreText.style.display = "inline";
	}
}
</script>
