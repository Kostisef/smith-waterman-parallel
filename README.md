# smith-waterman-parallel
A parallel implementation of Smith-Waterman algorithm for determining similar regions between two strings of nucleic acid sequences or protein sequences.

Wiki: https://en.wikipedia.org/wiki/Smith%E2%80%93Waterman_algorithm

There three different aproaches:

* Serial (the standard implementation for taking measuerments as a baseline)
* Parallel using OpenMP library
* Parallel using OpenMP with Vectorization



<p align="center">
  <img src="https://user-images.githubusercontent.com/37264702/135074069-20525425-ea64-4e7f-8db5-7d8a370bd292.png" width="250" />
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://user-images.githubusercontent.com/37264702/135074056-71315a00-96f3-4bb2-8cec-0ccf590cea3b.png" width="300" /> 
</p>


<h3>Smith-Waterman with OpenMP</h3>
<p align="center">
  <img src="https://user-images.githubusercontent.com/37264702/135074610-28e47ead-53a8-4274-ab0e-f3df6b3a039b.png"/> 
</p>

<h3>Smith-Waterman with OpenMP & Vectorization</h3>
<p align="center">
  <img src="https://user-images.githubusercontent.com/37264702/135075365-d4d88c83-7d3e-42ba-b653-386d8075beab.png"/>
</p>
