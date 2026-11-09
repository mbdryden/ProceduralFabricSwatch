# ProceduralFabricSwatch
Final Project for Computer Graphics CS334/ECE30834. Objective: Create a swatch of fabric from knit/crochet pattern and yarn input.
Motivation: To get an idea of what a knit/crochet project might look like based off a pattern and type of yarn. It’s fairly common for craft stores to have “swatches” such as these hanging up so customers have an idea of what different yarns might look like “worked up.” With this simulation, a fiber artist can get an idea of what the yarn looks like before they buy/during planning without having to rely on store swatches.

Expected Demo: Live rendering of different pattern/yarn combinations.

Main Technical Components: 
Pattern grammar and parser
Stitch geometry (as 3D splines? TBD)
Yarn shaders
3D view of swatch

What else team member will do:

Yubeen: Yarn appearance and rendering. Develop procedural materials for the generated swatches, with adjustable yarn color and surface roughness. Add visual details such as twisted stands and fine stray fibers to make the yarn look realistic.

Brooke: Stitch geometry and pattern generation. Build reusable 3D templates for selected stitch types. Define how the yarn loops pass through one another, then assemble the stitches into a swatch based on the input pattern.

Together:
Integration and Demo: Combine the stitch geometry with the yarn materials into a 3D preview that shows how the finished swatch would look.
(optional) Interactive Swatch Deformation: if time allows, making interactive simulation that user can click and drag the swatch to pull and stretch it.

Sources:
Construction / Geometry
Jonathan Kaldor, Doug L. James, and Steve Marschner; Simulating Knitted Cloth at the Yarn Level
Modeling yarn as B-spline tube (stitch curves)
Yuksel Jonathan M. Kaldor Doug L. James Steve Marschner; Stitch Meshes for Modeling Knitted Clothing with Yarn-level Detail
Replicating patterns and drape
KALDOR, J., JAMES, D. L., AND MARSCHNER, S; Efficient Yarn-based Cloth with Adaptive Contact Linearization
Reducing GPU usage in yarn-yarn contact

Appearance
Shuang Zhao, Fujun Luan, Kavita Bala; Fitting procedural yarn models for realistic cloth rendering
Flyaway fibers, making it look like actual fiber
Pramook Khungurn, Daniel Schroeder, Shuang Zhao, Kavita Bala, Steve Marschner; Matching real fabrics with micro-appearance models.
Lighting fibers
SR Marschner; Light Scattering from Human Hair Fibers
I SADEGHI; A Practical Microcylinder Appearance Model for Cloth Rendering
Highlights on fiber and effects of multicolored yarn
