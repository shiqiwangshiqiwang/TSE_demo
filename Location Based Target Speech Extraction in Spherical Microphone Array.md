# Location Based Target Speech Extraction in Spherical Microphone Array 

Wang Shiqi, 2023.04.11



## 仿真数据:

**观测信号**

![image-20230411142959903](img/image-20230411142959903.png)

<audio src="rotSepNet_output/simu_mix.wav" controls="controls">
Your browser does not support the audio element.
</audio>

**参考目标信号**

![image-20230411143234092](img/image-20230411143234092.png)

<audio src="rotSepNet_output/simu_ref.wav" controls="controls">
Your browser does not support the audio element.
</audio>

**估计目标信号**

![image-20230411143244142](img/image-20230411143244142.png)

<audio src="rotSepNet_output/simu_output.wav" controls="controls">
Your browser does not support the audio element.
</audio>

**估计目标信号（因果模型）**

![image-20230411143251826](img/image-20230411143251826.png)

<audio src="rotSepNet_output/simu_output_casual.wav" controls="controls">
Your browser does not support the audio element.
</audio>



## 真实数据，消声室

**观测信号**

![image-20230411143724569](img/image-20230411143724569.png)

<audio src="rotSepNet_output/real_anechoic_mix.wav" controls="controls">
Your browser does not support the audio element.
</audio>

**估计目标信号（声源1）**

![image-20230411143741453](img/image-20230411143741453.png)

<audio src="rotSepNet_output/real_anechoic_output1.wav" controls="controls">
Your browser does not support the audio element.
</audio>

**估计目标信号（声源2）**

![image-20230411143755779](img/image-20230411143755779.png)

<audio src="rotSepNet_output/real_anechoic_output2.wav" controls="controls">
Your browser does not support the audio element.
</audio>



## 真实数据，混响室

**观测数据**

![image-20230411144101638](img/image-20230411144101638.png)

<audio src="rotSepNet_output/real_reverberation_mix.wav" controls="controls">
Your browser does not support the audio element.
</audio>

**估计目标信号（声源1）**

![image-20230411144111464](img/image-20230411144111464.png)

<audio src="rotSepNet_output/real_reverberation_output1.wav" controls="controls">
Your browser does not support the audio element.
</audio>

**估计目标信号（声源2）**

![image-20230411144124000](img/image-20230411144124000.png)

<audio src="rotSepNet_output/real_reverberation_output2.wav" controls="controls">
Your browser does not support the audio element.
</audio>