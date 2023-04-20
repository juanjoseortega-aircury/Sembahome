---
layout: page
comments: yes
permalink: /zmesher/
---
<div class="zmesher-content">
    <h2>zMesher</h2>
    <br/>
    <p>The zMesher is an structured regular and Cartesian mesher, integrated in <a href="{{ site.baseurl }}/semba/">SEMBA</a>, which is specifically designed to deal with extremely complex geometries having the physical nature of the problem in mind. ZMesher has in mind the physic of the electromagnetic problem and will make decisions that preserve the electric size and the ohmic connections of the geometry.</p>
    <ul>
        <li>It will preserve the electric size of the geometry, preserving ohmic connections among objects.</li>
        <li>It is possibly the fastest in the world, the closest competitor is one order of magnitude slower.</li>
        <li>It has minimal memory requirements, under 1 GB for typical meshes. Meshes with billions of cells in a few minutes.</li>
        <li>Treats complex wirings, preserving topology and connectivities of wires.</li>
        <li>Can work with dirty geometries, reducing the preprocessing and CAD cleaning time to a minimum.</li>
        <li>Deeply tested in several architectures, operating systems and compilers.</li>
    </ul>
    <p>The ZMesher can be used as an extension of <a href="http://www.gidhome.com" target="_blank">GiD</a> where the meshes can be inspected. This interface allows to define materials and conditions over the geometry that are later assigned to the mesh. It also allows you to generate meshes in vtk format, which can be inspected with <a href="https://www.paraview.org/" target="_blank">Paraview</a></p>
</div>