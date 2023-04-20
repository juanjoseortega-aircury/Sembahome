---
layout: page
comments: yes
permalink: /semba/
---
<div class="semba-content">
    <h2>SEMBA</h2>
    <br/>
    <p>SEMBA is a framework envisaged for simulations in the field of EMC. EMC problems have important challenges from a simulation point of view: results need to be obtained for large bandwidths or transient responses, usually involving extremely complex geometries. Moreover, many electrical scales are simultaneously present, which implies the need of sub-cell models, etc.  SEMBA contains the necessary tools to manage the whole simulation chain for an EMC problem, from a CAD design to the desired results, including pre-processors, meshers, solvers and post-processors.</p>
    <p>
    The <a href="{{ site.baseurl }}/ugrfdtd/">UGRFDTD</a> solver implements the latest advances  in FDTD methods. It has been extensively used in a variety of extremely challenging  problems such as the cases present in HIRF and lightning present in aircraft design.
    The meshers: <a href="{{ site.baseurl }}/zmesher/">zMesher</a> and <a href="{{ site.baseurl }}/conformal-mesher/">Conformal Mesher</a>, integrated within the framework are possibly the fastest in the world and can generate meshes of billions of cells in minutes using a desktop computer. The meshes preserve the electromagnetic physics of the problem and maintain the connectivity among the different surfaces present in the original CADs.
    The DGTD and other core capabilities are included within the opensource project <a href="{{ site.baseurl }}/opensemba/">OpenSEMBA</a>.
    </p>      
</div>
