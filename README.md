<img src="Assets/the-university-of-sydney-3-logo-png-transparent.png" alt="USyd Logo" width="200"/>

# Periodic Table Elements With Attributes

**Author:** [Thomas Elton](https://github.com/tjelton)<sup>**a**</sup>

**Supervisors:** [Stephen George-Williams](https://www.sydney.edu.au/science/about/our-people/academic-staff/stephen-george-williams.html)<sup>**a**</sup>, 
[Reyne Pullen](https://www.sydney.edu.au/science/about/our-people/academic-staff/reyne-pullen.html)<sup>**a**</sup>

**Last Major Update:** 05-Mar-2022

<sup>**a**</sup>School of Chemistry, The University of Sydney, Sydney NSW 2006, Australia

# Abstract

As part of the CLEVER Molecule Genreator Unity Package [Coming Soon], common attributes for each element on the periodic table were required.
Whilst csv files including element name, symbol and atomic number are widely available, data including the covalent radii for each element, 
as well as the CPK colouring of each element was sparse. Here, R has been used to create a csv which includes all of these attribtues for each element.

# CSV

The csv file can be found [here](https://github.com/tjelton/Periodic-Table-Elements-With-Attributes/blob/main/Element-Attributes.csv).

# Data Dictionary

<table class="tg">
<thead>
  <tr>
    <th class="tg-fymr">Column Name</th>
    <th class="tg-fymr">Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">atomicNumber</td>
    <td class="tg-0lax">The atomic number of the element.</td>
  </tr>
  <tr>
    <td class="tg-0lax">symbol</td>
    <td class="tg-0lax">The symbol of the element as seen on the periodic table.</td>
  </tr>
  <tr>
    <td class="tg-0lax">name</td>
    <td class="tg-0lax">The full element name as seen on the periodic table.</td>
  </tr>
  <tr>
    <td class="tg-0lax">radii</td>
    <td class="tg-0lax">The average covalent radii for an element. Please see the documentation for more information.</td>
  </tr>
  <tr>
    <td class="tg-0lax">colour</td>
    <td class="tg-0lax">The CPK colour representation for the element.</td>
  </tr>
</tbody>
</table>

# Documentation

Documentation for how the csv was put together (including data sources), can be found [here](https://github.com/tjelton/Periodic-Table-Elements-With-Attributes/blob/main/Documentation.html).

# Used in the CLEVR Molecule Generator

The resulting csv is used as part of the **CLEVR Molecule Generator** Unity package [Coming Soon].
