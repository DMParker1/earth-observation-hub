# Reading a landscape from space

One of my early uses of Earth observation in epidemiology came from work on infections of the central nervous system in Laos. We wanted to know whether patients with different infections came from different environmental settings, and whether conditions around their home villages changed in ways that might help explain when and where particular infections occurred.

This required turning satellite observations into epidemiologically useful measurements.

## From an image to an environmental measure

The first image below is a conventional RGB view of the landscape around Vientiane. The Mekong River is readily visible running through the center of the image, even during the dry season.

<p align="center">
  <img src="./media/VientianeRGB.jpg"
       alt="RGB satellite view of Vientiane and the surrounding Mekong River landscape"
       width="800">
</p>

The next two images show a remotely sensed measure sensitive to surface water and moisture over the same landscape, first in February and then in July.

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="./media/VientianeSWFeb.jpg"
           alt="Remotely sensed surface water and moisture conditions around Vientiane in February"
           width="100%">
      <br>
      <sub><b>February.</b> During the dry season, the Mekong River remains clearly identifiable while much of the surrounding landscape has a relatively low surface-water/moisture signal.</sub>
    </td>
    <td width="50%" valign="top">
      <img src="./media/VientianeSWJuly.jpg"
           alt="Remotely sensed surface water and moisture conditions around Vientiane in July"
           width="100%">
      <br>
      <sub><b>July.</b> During the rainy season, the surface-water/moisture signal extends much more broadly across the surrounding landscape.</sub>
    </td>
  </tr>
</table>

The distinction is important. The derived surface is not simply a map of where standing water is visible. At MODIS resolution, each pixel integrates information across a relatively large area, potentially containing combinations of open water, flooded or saturated agricultural land, vegetation, soil, roads, and other surfaces. The resulting index is therefore better interpreted as a relative measure of surface-water and moisture conditions than as a literal inventory of flooded locations.

For epidemiology, however, that measurement can be extremely useful. Satellite observations allow the same environmental characteristic to be measured repeatedly across a large landscape and through time. We can then link those measurements to the locations and timing of human disease.
