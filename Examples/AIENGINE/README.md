# AI Engine Examples

Vitis Model Composer allows you to create AI Engine designs and generate code for them. The visualization and analysis capabilities of MATLAB and Simulink presents an excellent environment to debug any design and make sure the design functionally performs as expected.

<table style="width:100%">
<tr>
  <td align="center" colspan="2" style="bold" ><b><a href="./Importing_AIE_blocks/README.md">Importing Kernels and Graphs into Model Composer</a></b>
</tr>

<tr>
<td>
<a href="./Importing_AIE_blocks/AIE_Class_Kernel_FIR/README.md">Importing a kernel class as a block                      </a>
</td>
<td>
In this example we import an AI Engine class kernel into Vitis Model Composer as a block.
</td>
</tr> 
 
<tr>
<td>
<a href="./Importing_AIE_blocks/AIE_Graph/README.md">Importing a graph as a block</a>
</td>
<td>
In this example we import an AI Engine graph into Vitis Model Composer as a block.
</td>
</tr> 

<tr>
<td>
<a href="./Importing_AIE_blocks/AIE_ML_Graph_Import/README.md">Importing an AIE-ML graph as a block</a>  <img src="../../Images/new.PNG" width="50">
</td>
<td>
In this example we import a graph for AIE-ML devices (including memory tiles) into Vitis Model Composer as a block.
</td>
</tr> 
</table>
<br/>

 
 
<table style="width:100%">
<tr>
  <td align="center" colspan="2" style="bold" ><b>  <a href="./Run_Time_Parameters/README.md">Run time parameters (RTP)</a></b>
</tr>

<tr>
<td>
<a href="./Run_Time_Parameters/rtp_scalar/README.md">A design with a scalar RTP input</a>
</td>
<td>
This example showcases a design that includes an AI Engine kernel with a scalar input RTP.
</td>
</tr> 
 
<tr>
<td>
<a href="./Run_Time_Parameters/rtp_vector/README.md">A design with a vector RTP input</a>
</td>
<td>
This example showcases a design that includes an AI Engine kernel with a synchronous vector input RTP.
</td>
</tr> 
  
<tr>
<td>
<a href="./Run_Time_Parameters/rtp_vector_async/README.md">A design with a vector asynchronous RTP input</a>
</td>
<td>
This example showcases a design that includes an AI Engine kernel with a asynchronous vector input RTP.
</td>
</tr>   
  
</table>
<br/>
 
<table style="width:100%">
<tr>
  <td align="center" colspan="2" style="bold" ><b><a href="./DSPlib/README.md">DSP Functions</a></b>
</tr>

<tr>
<td>
<a href="./DSPlib/fft/README.md">Using the AI Engine FFT block from the library browser</a>
</td>
<td>
This example showcases a design that uses an AI Engine FFT block from the library browser.
</td>
</tr> 
 
<tr>
<td>
<a href="./DSPlib/fir/README.md">Using the AI Engine FIR block from the library browser</a>
</td>
<td>
This example showcases a design that uses an AI Engine FIR block from the library browser.
</td>
</tr>

<tr>
<td>
<a href="./DSPlib/stream_fft/README.md">Using the AI Engine FFT Stream block from the library browser</a>
</td>
<td>
This example showcases a design that uses an AI Engine Stream FFT block with SSR of 2 from the library browser.
</td>
</tr> 
 
<tr>
<td>
<a href="./DSPlib/matrix_multiply/README.md">Importing Matrix Multiply from DSPLib as a block</a>
</td>
<td>
This example showcases how you can import a DSPLib function as a block.
</td>
</tr>

<tr>
<td>
<a href="./DSPlib/Dynamic_FFT/README.md">Using the AI Engine Dynamic Point FFT</a>
</td>
<td>
This example showcases the use of the AI Engine Dynamic Point FFT block. 
</td>
</tr> 
  
<tr>
<td>
<a href="./DSPlib/fir_ssr/README.md">Using DSPLib AI Engine SSR FIR</a>
</td>
<td>
Using DSPLib AI Engine SSR FIR block to achieve 4 Gsps throughput. 
</td>
</tr> 
  
</table>
<br/>




<table style="width:100%">
<tr>
  <td align="center" colspan="2" style="bold" ><b>Other examples</b>
</tr>
 
 <tr>
 <td align="left">
   <a href="./SingleStreamSSR_FIR/README.md">Super Sample Rate FIR filter</a>
 </td>
 <td> This design showcases a Super Sample Rate FIR filter to process a 4GSPS input stream. In this design we also compare the output of our AI Engine subsystem with the output of a Simulink FIR block (our golden reference) both in time and in frequency. 
 </td> 
 </tr>
 
 <tr>
 <td align="left">
   <a href="./DualStreamSSR_FIR/README.md">Dual Stream Super Sample Rate FIR filter</a>
 </td>
 <td> This design showcases a Dual Stream Super Sample Rate FIR filter to process a 16GSPS input stream. In this design we also compare the output of the AI Engine subsystem with the output of a Simulink FIR block (the golden reference). 
 </td> 
 </tr>
 
  <tr>
 <td align="left">
 <a href="./Pseudo_Inverse_64x32/README.md">Pseudo Inverse 64x32 </a>
 </td>
 <td> This design showcases an AI Engine implementation of a 64x32 Pseudo Inverse in Vitis Model Composer. The AI Engine output is compared with the output of the pseudo inverse block in Simulink which is used as a reference.</td>
 </tr>
  
   <tr>
 <td align="left">
 <a href="./Filtering_in_frequency_domain/README.md">Filtering in frequency domain </a> <img src="../../Images/new.PNG" width="50">
 </td>
 <td> This design showcases filtering in frequency domain and also shows how to increase the throughput using different techniques.</td>
 </tr> 

   <tr>
 <td align="left">
 <a href="./Farrow_Filter/README.md">Farrow Filter</a> <img src="../../Images/new.PNG" width="50">
 </td>
 <td> This example demonstrates a Vitis Model Composer testbench for a fractional delay Farrow filter.</td>
 </tr> 
  
 </table>

# More AI Engine and Programmable Logic Examples
For more examples with AI Engine and Programmable Logic click [here](../AIENGINE_plus_PL).
