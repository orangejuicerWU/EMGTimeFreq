$$$ Documentation of EMGTimeFreq $$$ 
Author: Orangejuiceer  
Email:wuchengzhen0214@vip.qq.com  
Updata:2024.04.24  
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
# Form of the Function: [IEMG,AEMG,RMS,MPF,MF] = EMGTimeFreq(EMG,fs,tag)  
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
# Input Arguments: 
EMG : the EMG signal (one channel,1*channel).It’s better to be filtered and zero-centered.  
      muti-channels soon!  
fs : the sampling rate of EMG signal, the default value is 2048 (Hz). 
tag : if tag is 1,it will plot PS, the default value is 0.  
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%  
# some examples:  
[IEMG,AEMG,RMS,MPF,MF] = EMGTimeFreq(EMG,fs,tag)  
[IEMG,AEMG,RMS,MPF,MF] = EMGTimeFreq(EMG,fs)  
[IEMG,AEMG,RMS,MPF,MF] = EMGTimeFreq(EMG)  
