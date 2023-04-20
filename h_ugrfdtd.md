---
layout: page
comments: yes
permalink: /ugrfdtd/
---
<div class="ugrfdtd-content">
    <h2>ugrfdtd</h2>
    <br/>
    <p>UGRFDTD is a state-of-the-art parallel FDTD simulator (partially developed under the <a href="http://hirfse.axessim.eu/" target="_blank">HIRF-SE</a> European 7PM project with contributions from AIRBUS DS.</p>
    <p>Find <a href="#">here</a> a short presentation and further info on the UGRFDTD SOLVER</p>
    <p>UGRFDTD is a general-purpose time-domain simulator, specially suited to deal with HIRF, Lightning, NEMP… electrically-large EMC problems involving complex structures, complex materials and cables.</p>
    <p>It supports input files based both on a native ASCII input and on a HDF format using the open standard <a href="https://code.google.com/archive/p/amelet-hdf/" target="_blank">AMELET-HDF.</a></p>
    <p>In order to clean, mesh and assign the electromagnetic properties to the problem under solution UGRFDTD can employ can employ both</p>
    <ul>
        <li>Proprietary GUI and meshing tools under <a href="http://www.gidhome.com" target="_blank">GiD</a> using the <a href="{{ site.baseurl }}/semba/">SEMBA</a> extension.</li>
        <li>GUI and meshing tools developed under <a href="http://hirfse.axessim.eu/" target="_blank">HIRF-SE</a> .</li>
    </ul>
    <p>In a nutshell, UGRFDTD <a href="{{ site.baseurl }}/ugrfdtd/">capabilities</a> are</p>
    <ol>
        <li>Cluster working capabilites through MPI.</li>
        <li>Multiple threads per processor through OpenMP.</li>
        <li>Closed/symmetric problems by means of PEC and PMC conditions.</li>
        <li>Open problems by means of PML boundary conditions (CPML formulation) or by Mur ABCs.</li>
        <li>Non-uniformly meshed domains by means of mesh-grading techniques.</li>
        <li>Conformal meshing.</li>
        <li>Bulk lossless and lossy dielectrics.</li>
        <li>Materials with frequency dependent relative permittivity and/or permeability, with an arbitrary number of complex-conjugate pole-residue pairs.</li>
        <li>Bulk anisotropic lossless and lossy dielectrics.</li>
        <li>Equivalent models of multilayered skin-depth materials</li>
        <li>
        Branched multiwires
            <ul style="list-style-type:'- ' ;">
                <li>Junctions of wires of different radii.</li>
                <li>Junctions of multiwires</li>
                <li>Wire bundles</li>
                <li>Loaded with p.u.l resistance and inductance wires</li>
                <li>Grounding through lumped elements </li>
            </ul>
        </li>
        <li>Plane wave illumination with arbitrary time variation.</li>
        <li>Hertztian dipole sources</li>
        <li>Equivalent Huygens surfaces</li>
        <li>Low frequency thin composites and lossy surfaces </li>
        <li>Thin slots.</li>
        <li>Time, frequency and transfer function probes </li>
        <li><a href="{{ site.baseurl }}/ugrfdtd/">Time animations in volumes through Paraview</a></li>
        <li>Near-to-far field transformation.</li>
    </ol>
</div>