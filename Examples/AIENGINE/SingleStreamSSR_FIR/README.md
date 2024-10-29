# Single Stream SSR FIR
This model showcases a single stream super sample rate FIR filter to process a 4 GSPS stream built with 16 AI Engine kernels. In addition, we compare the output of the AI Engine design with a Simulink FIR filter block that we consider as our golden reference.

For more detials on the design of the FIR kernels click [here](https://github.com/Xilinx/Vitis-Tutorials/tree/2024.1/AI_Engine_Development/AIE/Design_Tutorials/02-super_sampling_rate_fir/SingleStreamSSR). 


![](images/SingleStreamSSR.PNG)

------------
Copyright 2020 Xilinx

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
