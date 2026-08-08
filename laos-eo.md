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

## What does the satellite see on the ground?

Remote sensing compresses a complicated landscape into pixels and derived measurements. At the 250 m resolution of the MODIS data we were using, a single pixel could contain flooded rice fields, dense vegetation, exposed soil, field boundaries, roads, and other surfaces.

<p align="center">
  <img src="./media/Rice_field_507.JPG"
       alt="Rice-growing landscape near Vientiane, Laos, showing flooded and densely vegetated rice fields"
       width="800">
</p>

<sub>
<b>Field photograph.</b> Rice-growing landscape near Vientiane, Laos. Standing water is clearly visible in some fields, while adjacent fields contain dense rice vegetation. At MODIS resolution, these heterogeneous conditions contribute to the remotely sensed signal within the same or neighboring pixels.
</sub>

This was not just an abstract concern. As part of this work, we did ground truthing to better understand how conditions observed in the field corresponded to the remotely sensed measures. Large areas of flooded rice agriculture were relatively easy to identify in the MODIS-derived surface-water signal, while smaller isolated flooded fields were less distinct.

That experience was also a useful reminder that the derived measure should not be interpreted as a literal map of standing water. It was sensitive to relative surface water and moisture conditions across the area represented by a pixel. Understanding what a remotely sensed variable means therefore requires moving in both directions: **from the ground to the satellite, and from the satellite back to the ground.**
