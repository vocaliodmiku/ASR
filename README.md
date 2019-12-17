# ASR

这里存放了本人个人学习资料，其各个文件如下：  
其中带colab的标志是基于了解的基础上，建议在Google Colab上运行。

* Speech Processing Basic.ipynb 

  从音频中提取MFCC/fbanks特征。trial.wav为样本音频
 
* [kaldi_yesno_tutorial.ipynb](https://colab.research.google.com/drive/1pm8UpE54GUR5ei9mw_JQ_UMbVF_0CIUj)  #colab  

  关于kaldi中yesno的一个比较细致的浏览，也是对kaldi运行框架的有个初步认识

* [kaldi_thchs30_tutorial.ipynb](https://colab.research.google.com/drive/1afXkA1izzMBzwidb6OaIC---3ViOx_d2)  #colab  

  基于上一个notebook的thchs30的一个tutorial  
  
* [nasal.ipynb] # colab

  论文复现[Excitation Source and Vocal Tract System Based Acoustic Features for Detection of Nasals in Continuous Speech](https://www.isca-speech.org/archive/Interspeech_2019/pdfs/2785.pdf)  
  主要是对一下两个方法的理解与实现，可能会用于未来的工作当中
  *  ZFF(zero frequency filtered)
  *  ZTW(Zero-time windowing)
