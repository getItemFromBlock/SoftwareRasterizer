# Rasterizer project
THe goal of this project was to create a rasterizer program, running on CPU.
This project was done as a part of our 3d render engine classes.

## Summary
<ul>
    <li><a href = "#keys"> Keys </a></li>
    <li><a href = "#version"> Various Version </a></li>
    <li><a href = "#ui"> Ui </a></li>
    <li><a href = "#gallery"> Gallery </a></li>
    <li><a href = "#credits"> Credits </a></li>
</ul>

## Keys
<div id = "keys">
<li><b>W A S D</b> : Move.
<li><b>Mouse</b> : Rotate Camera.
<li><b>E</b> : Fly up.
<li><b>Q</b> : Fly down.
<li><b>Left Shift</b> : go faster.
<li><b>F1</b> : Enable/Disable WireFrame.
<li><b>F2</b> : Enable/Disable MSAA filtering.
</div>
<br><br>

## Various versions
<div id = "version">
<ul>
    <li><b>Version 1</b>: <br>
    A triangle is displayed, with a color interpolated between the 3 points (RGB).
    <li><b>Version 2</b>: <br>
    A red Cube and a blue sphere are displayed to show the z-buffer.
    <li><b>Version 3</b>: <br>
    A red Cube and a blue sphere are displayed to show the lighting under the Phong model.
    <li><b>Version 4</b>: <br>
    A red Cube and a blue sphere are displayed to show the illumination under the Blinn-Phong model in per-pixels. The Cube and the Sphere are rotated in order to show the correct calculation of the normals.
    <li><b>Version 5</b>: <br>
    Show the projection by rendering the precedent Cube and Sphere.
    <li><b>Version 6</b>: <br>
    A Cube Textured is displayed to show the texturing of the triangles.
    <li><b>Version 7</b>: <br>
    Activate the Wireframe on the previous cube. It can be disabled with the F1 key.
    <li><b>Version 8</b>: <br>
    Makes a large cube opaque, and another smaller cube 50% transparent that rotates on itself.
    <li><b>Version 9</b>: <br>
    Renders a 3d model of a guard to show everything we've done before.
    <li><b>Version 10</b>: <br>
    Render a scene to show the anti-aliasing
    <li><b>In all versions</b>: <br>
    <ul>
        <li>All models/meshs can be displayed, change position, rotation, scale, texture, color, shader and bilinear filtering.
        <li>The MSAA value can be change.
        <li>Perspective correction can be disabled/enabled.
        <li>The wireframe can be disabled/enabled.
        <li>Orthographic vision can be disabled/enabled.
        <li>Can add Lights/Show Lights.
        </ul>
</ul>
</div>
<br><br>

## Ui

<div id = "ui">
<p> Possiblity to change scale of every windows. </p>
    In the interface, the tab:
<ul>
    <li><b> Scene</b> : allows you to add lights, delete them, change the ambient, diffuse and specular parameters. The lights can have different colors and different luminosity. You can also show light.</li>
    <li><b> Config</b> : allows to display the wireFrame render, the orthographic vision, the perspective correction, the light in per pixels and you can change the MSAA value. Also displays the number of FPS. And allow you to   change the color of the background. You can also lock the scale horizontaly, verticaly and in 4/3. You can also change the filter with the slider (default : No filter). There is more than 10 filters (see in <a href = "#filter"> gallery </a>)</li>
    <li><b> Triangles</b> : Displays the number of triangles in total, and the number of triangles drawn. Also displays the number of triangles per models, When you click on a models buttons you can: see the name of the mesh, change the position, the rotation, the scale of the models, the color, the shader, and the texture. Can also choose to show or not the meshs and enable or not the bilinear filtering of every Models. There is 4 shaders (see in <a href = "#shader"> gallery </a>)
    <li> <b>Versions</b> : Allows you to change versions.</li>
    <li> <b>Framebuffer</b> : Displays the scene.</li>
</ul>
</div>

### Gallery
<div id = "gallery">
<ul>
    <li><div id = "filters">
        <details open>
            <summary>
                14 filters :
            </summary>
            <ol><b>
                <li>No filter<br></li>
                <li>Inverted<br></li>
                <li>Red Only<br></li>
                    <img src="assets/ScreenShots_Gifs/Red.png" width="" height="500">
                <li>Green Only<br>
                <li>Blue Only<br>
                <li>Pixelizer<br>
                <li>Posterize<br>
                <li>GBC (from GameBoy Color):<br>
                    <img src="assets/ScreenShots_Gifs/GBC.png" width="" height="500"></li>
                <li>UpsideDown<br>
                <li>GrayScale<br>
                <li>Hash<br>
                <li>VHS<br>
                    <img src="assets/ScreenShots_Gifs/vhs.png" width="" height="500"></li>
                <li>Pumpkin view (source: Minecraft) </li>
                <li>Creeper view (source: Minecraft) </li>
            </b></ol>
        </details>
    </div></li>
    <li> <div id = "shaders">
        <details open>
            <summary>
                4 shaders:  
            </summary>
            <ul>
                <li>Default <br>
                <li>Wave <br>
                    <img src="assets/ScreenShots_Gifs/wave.gif" width="" height="250"></li>
                <li>Cel <br>
                    <img src="assets/ScreenShots_Gifs/cel.png" width="" height="250"></li>
                <li>Glitch <br>
                    <img src="assets/ScreenShots_Gifs/glitch.gif" width="" height="250"></li>
            </ul>
        </details>
    </div></li>
</div>

### Credits
<div if = "credits">
<li><u><b> <a href="https://gitlabstudents.isartintra.com/q.lepine">Lepine Quentin
<li><a href="https://gitlabstudents.isartintra.com/r.bourgogne"> Bourgogne Romain

<br /> 
<li><a href="https://www.isart.fr"> Isart Digital </u> </b> <br>
<img src="assets/Textures/logo.png" width="" height="200"></li>
</div>