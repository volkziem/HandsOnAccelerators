
# MATLAB live scripts for *Hands-on Accelerator Physics using MATLAB* 
-----------------------------------------------------------

The book was published by
[CRCpress](https://www.crcpress.com/9781138589940) in March 2019 and all
MATLAB scripts referred to in the book are available form the
[publisher\'s web page](https://www.crcpress.com/9781138589940) 

The live scripts (with file extension .mlx) in this repository are specially prepared
MATLAB files that contain text explanations, images as well as
executable MATLAB code. Just load them from your MATLAB installation.
You can also look at a webpage online or download a pdf. Both are
automatically generated from the running live script and contain
everything, input as well as output, including plots.


#### Chapter 2: Reference system

-   [3D-geometry of a beam line](file://apb/GeometryModeler.html), includes a
    simple OpenSCAD modeler: [live script](apb/GeometryModeler.mlx) and
    [pdf](apb/GeometryModeler.pdf).

#### Chapter 3: Transverse beam optics

-   [Write your own beam optics code](apb/BeamOpticsTutorial.html),
    define beam lines, calculate transfer matrices, and display
    trajectories: [live script](apb/BeamOpticsTutorial.mlx) and
    [pdf](apb/BeamOpticsTutorial.pdf).
-   [Beamoptics in 2D](apb/BeamOptics2D.html), including beta functions,
    matching the tune, and a transition section: [live
    script](apb/BeamOptics2D.mlx) and [pdf](apb/BeamOptics2D.pdf).
-   Instead of repeating all used service functions at the end of each
    script, I have collected them in the zip file
    [BeamOpticsSupportFiles.zip](apb/BeamOpticsSupportFiles.zip) which
    contains three subdirectories, one each for the 2D, 3D, and 4D
    versions of the software. Unpack the zip file in the directory where
    the live script resides. Here are the descriptions of the files in
    the respective subdirectories.
    -   [2D support functions](apb/BeamOpticsSupportFunctions2D.html)
        and as [pdf.](apb/BeamOpticsSupportFunctions2D.pdf) Include in
        live script with \"addpath ./2D\".
    -   [3D support functions](apb/BeamOpticsSupportFunctions3D.html)
        and as [pdf.](apb/BeamOpticsSupportFunctions3D.pdf) Include in
        live script with \"addpath ./3D\".
    -   [4D support functions](apb/BeamOpticsSupportFunctions4D.html)
        and as [pdf.](apb/BeamOpticsSupportFunctions4D.pdf) Include in
        live script with \"addpath ./4D\".
-   [Chromaticity](apb/Chromaticity.html) of FODO cells: [live
    script](apb/Chromaticity.mlx) and [pdf](apb/Chromaticity.pdf).
-   [Dispersion suppressor](apb/DispersionSuppressor.html) at the end of
    a 90-degree/cell FODO arc: [live
    script](apb/DispersionSuppressor.mlx) and
    [pdf](apb/DispersionSuppressor.pdf).
-   [Match the phase advances (or tunes)](apb/MatchTheTunes.html) in a
    FODO cell in both planes simultaneously: [live
    script](apb/MatchTheTunes.mlx) and [pdf](apb/MatchTheTunes.pdf).
-   [Match the beta functions at a waist](apb/MatchToWaist4D.html) in a
    FODO lattice in both planes simultaneously: [live
    script](apb/MatchToWaist4D.mlx) and [pdf](apb/MatchToWaist4D.pdf).
-   [Triplet beam line](apb/TripletBeamLineWithSmallSpot.html) with
    small spot at the end: [live
    script](apb/TripletBeamLineWithSmallSpot.mlx) and
    [pdf](apb/TripletBeamLineWithSmallSpot.pdf).
-   [Point-to-point focusing](apb/PointToPointFocusing.html) and the
    imaging equation for a lens: [live
    script](apb/PointToPointFocusing.mlx) and
    [pdf](apb/PointToPointFocusing.pdf).
-   Additional scripts:
    -   5D support functions are available at my
        [github](https://github.com/volkziem/MobiusRing) repository
        (GPLv3).
    -   Design of a Mobius Ring is available at
        [github](https://github.com/volkziem/MobiusRing) (GPLv3).

#### Chapter 4: Magnets

-   [C-shaped dipole magnet](apb/pdeCmagnet.html), uses the PDE toolbox
    to define the geometry, boundary conditions, and material properties
    of a typical C-shaped dipole magnet. Then solves the model for the
    vector potential and post-processes the solution in order to obtain
    the field inside the gap: [live script](apb/pdeCmagnet.mlx) and
    [pdf](apb/pdeCmagnet.pdf).
-   [The upper half of the C-magnet](apb/CmagnetUpperHalf.html)
    exploiting the up-down symmetry: [live
    script](apb/CmagnetUpperHalf.mlx) and
    [pdf](apb/CmagnetUpperHalf.pdf).
-   [C-magnet with shims](apb/CmagnetUpperHalfWithShims.html) (only the
    upper half): [live script](apb/CmagnetUpperHalfWithShims.mlx) and
    [pdf](apb/CmagnetUpperHalfWithShims.pdf).
-   [Quadrupole magnet](apb/pdeQuadrupole.html) (one quadrant only):
    [live script](apb/pdeQuadrupole.mlx) and
    [pdf](apb/pdeQuadrupole.pdf).
-   [Super-conducting Dipole 1](apb/SCdipoleTwoCircles.html), defined by
    intersecting circles: [live script](apb/SCdipoleTwoCircles.mlx) and
    [pdf](apb/SCdipoleTwoCircles.pdf).
-   [Super-conducting Dipole 2](apb/SCdipoleCircleSegments.html),
    defined by two circular segments: [live
    script](apb/SCdipoleCircleSegments.mlx) and
    [pdf](apb/SCdipoleCircleSegments.pdf).
-   [Super-conducting Quadrupole](apb/SCquadrupole.html), defined by
    four circular segments: [live script](apb/SCquadrupole.mlx) and
    [pdf](apb/SCquadrupole.pdf).

#### Chapter 5: Longitudinal dynamics and acceleration

-   [Pill-box explorer](apb/PillboxExplorerTM.html) for TM-modes: [live
    script](apb/PillboxExplorerTM.mlx) and
    [pdf](apb/PillboxExplorerTM.pdf).
-   [Large amplitude oscillations in longitudinal phase
    space](apb/LargeAmplitudeOscillations.html), based on closed-form
    solution of the equations of motion for a mathematical pendulum:
    [live script](apb/LargeAmplitudeOscillations.mlx) and
    [pdf](apb/LargeAmplitudeOscillations.pdf).
-   [Filamentation of a starting distribution to a matched
    distribution](apb/LongitudinalMatching.html) in longitudinal phase
    space: [live script](apb/LongitudinalMatching.mlx) and
    [pdf](apb/LongitudinalMatching.pdf).
-   [Bunch tomography](apb/LongitudinalBunchTomography.html) in
    longitudinal phase space: [live
    script](apb/LongitudinalBunchTomography.mlx) and
    [pdf](apb/LongitudinalBunchTomography.pdf).
-   [Debunching and rebunching](apb/RebunchingSimulation.html) on a
    higher harmonic: [live script](apb/RebunchingSimulation.mlx) and
    [pdf](apb/RebunchingSimulation.pdf).
-   [Bunch rotation](apb/LongitudinalBunchRotation.html) in longitudinal
    phase space: [live script](apb/LongitudinalBunchRotation.mlx) and
    [pdf](apb/LongitudinalBunchRotation.pdf).
-   [Bunch muncher](apb/BunchMuncher.html) simulation: [live
    script](apb/BunchMuncher.mlx) and [pdf](apb/BunchMuncher.pdf).

#### Chapter 6: Radio-frequency systems

-   [Rectangular TE](apb/TEwaveguide.html)-waveguide: [live
    script](apb/TEwaveguide.mlx) and [pdf](apb/TEwaveguide.pdf).
-   [Circular TE](apb/TEcircular.html)-waveguide: [live
    script](apb/TEcircular.mlx) and [pdf](apb/TEcircular.pdf).
-   [Circular TM](apb/TMcircular.html)-waveguide: [live
    script](apb/TMcircular.mlx) and [pdf](apb/TMcircular.pdf).
-   [TEM-mode](apb/TEMcoax.html) in a coaxial waveguide: [live
    script](apb/TEMcoax.mlx) and [pdf](apb/TEMcoax.pdf).
-   [Pill-box cavity with beam pipe](apb/PillboxCavityWithBeampipe.html)
    simulation: [live script](apb/PillboxCavityWithBeampipe.mlx) and
    [pdf](apb/PillboxCavityWithBeampipe.pdf).

#### Chapter 7: Diagnostics

-   [Potential of an off-center beam in a circular beam
    pipe](apb/BPMInCircularBeamPipe.html), find the position of the
    image charge that makes the beam pipe an equipotential surface.
    [live script](apb/BPMInCircularBeamPipe.mlx) and
    [pdf](apb/BPMInCircularBeamPipe.pdf).
-   [Octagonal BPM](apb/OctagonalBPM.html) and the field of a displaced
    beam: [live script](apb/OctagonalBPM.mlx) and
    [pdf](apb/OctagonalBPM.pdf).

#### Chapter 8: Imperfections and corrections

-   [One-to-one steering](apb/OneToOneSteering.html) in a transfer line:
    [live script](apb/OneToOneSteering.mlx) and
    [pdf](apb/OneToOneSteering.pdf).
-   [Orbit correction](apb/OrbitCorrectionRing.html) in a ring: [live
    script](apb/OrbitCorrectionRing.mlx) and
    [pdf](apb/OrbitCorrectionRing.pdf).

#### Chapter 9: Targets and Luminosity

-   [Van-der-Meer scans](apb/BeamBeamTracking.html) and beam-beam
    collisions: [live script](apb/BeamBeamTracking.mlx) and
    [pdf](apb/BeamBeamTracking.pdf).
-   [Beam-beam collisions](apb/BeamBeamDisruption.html) with disruption
    in CLIC: [live script](apb/BeamBeamDisruption.mlx) and
    [pdf](apb/BeamBeamDisruption.pdf).

#### Chapter 10: Synchrotron radiation and free-electron lasers

-   [Phase-space of small-signal
    FEL](apb/PhaseSpaceOfSmallSignalFEL.html) and the small-signal gain:
    [live script](apb/PhaseSpaceOfSmallSignalFEL.mlx) and
    [pdf](apb/PhaseSpaceOfSmallSignalFEL.pdf).
-   [SASE free-electron laser](apb/SaseFreeElectronLaser.html)
    simulation: [live script](apb/SaseFreeElectronLaser.mlx) and
    [pdf](apb/SaseFreeElectronLaser.pdf).
-   [Free-electron laser oscillator](apb/FELoscillator.html) simulation:
    [live script](apb/FELoscillator.mlx) and
    [pdf](apb/FELoscillator.pdf).

#### Chapter 11: Non-linear dynamics

-   [Phase-space plots](apb/OneDimensionalTracking.html) and tracking in
    one dimensions: [live script](apb/OneDimensionalTracking.mlx) and
    [pdf](apb/OneDimensionalTracking.pdf).
-   [Dynamic Aperture](apb/DynamicApertureInBothPlanes.html) determined
    by tracking in two transverse planes: [live
    script](apb/DynamicApertureInBothPlanes.mlx) and
    [pdf](apb/DynamicApertureInBothPlanes.pdf).

#### Chapter 12: Collective effects

-   [Beam transport with space charge](apb/SachererIntegrator.html)
    using an integrator for the Sacherer equations: [live
    script](apb/SachererIntegrator.mlx) and
    [pdf](apb/SachererIntegrator.pdf).
-   [Dispersion Integral](apb/DispersionIntegralForGaussian.html) for
    Gaussian momentum distributions: [live
    script](apb/DispersionIntegralForGaussian.mlx) and
    [pdf](apb/DispersionIntegralForGaussian.pdf).
-   [Bunch-lengthening](apb/BunchLengtheningSimulation.html) simulation:
    [live script](apb/BunchLengtheningSimulation.mlx) and
    [pdf](apb/BunchLengtheningSimulation.pdf).

#### Chapter 13: Accelerator subsystems

-   [Vacuum calculations](apb/VacuumCalculations.html) with a minimal
    version of the vaktrak algorithm: [live
    script](apb/VacuumCalculations.mlx) and
    [pdf](apb/VacuumCalculations.pdf).
