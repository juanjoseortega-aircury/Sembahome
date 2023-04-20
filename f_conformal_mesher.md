---
layout: page
comments: yes
permalink: /conformal-mesher/
---
<div class="conformal-mesher-content">
    <h2>Conformal Mesher</h2>
    <br/>
    <p>Conformal Mesher can obtain meshes that adapt optimally to the original geometry overcoming the classical stair-casing problem of the Finite Differences methods. The mesher is integrated in <a href="{{ site.baseurl }}/semba/">SEMBA</a>, where the <a href="{{ site.baseurl }}/ugrfdtd/">UGRFDTD</a> solver can use these meshes to perform simulations with a reduced memory consumption for a similar accuracy.</p>
    <!--Image Here-->
    <ul>
        <li>The Conformal Mesher can be tuned to trade-off optimal geometrical adaptation and solver performance.</li>
        <li>It is able to obtain meshes containing billions of cells using a desktop computer in minutes.</li>
        <li>Sub-cell features are meshed preserving its material characteristics.</li>
        <li>Allows to obtain structured meshes.</li>
    </ul>
    <img src="#">
    <p>
    The Conformal Mesher can be used as an extension of <a href="http://www.gidhome.com">GiD</a> where the meshes can be inspected. This interface allows to define materials and conditions over the geometry that are later assigned to the mesh. It also allows you to generate meshes in vtk format, which can be inspected with <a href="http://www.paraview.org">Paraview</a>.
    </p>
    <!--Image Here-->
    <img src="#">  
</div>