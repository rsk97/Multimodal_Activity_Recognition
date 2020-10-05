# Multimodal_Activity_Recognition
A multi-modal model to understand activity recognition

##### Group Members : Arvind Deshraj, G.Arshad, JUNAID N.Z, Rohan Sukumaran, Siddharth Kumar, Hareesh Devarkonda

##### Medium Blog Link : https://medium.com/@arshad.g16/human-activity-recognition-har-using-multi-modal-attention-8c81ceff6745


##### Introduction

A multi-modal multi-level attention model is used for achieving the task. Multi-modal refers to usage of more than one modality, eg: Image + Audio or Audio + Text etc.  
We use the Charades Dataset, that contains data from two modalities - Action Video and Text( the script accompanying the video)


##### Programming Language Used : Python

##### Dataset Used: Charades Dataset	(http://ai2-website.s3.amazonaws.com/data/Charades_v1_rgb.tarR)

##### Dependencies:
 		* pandas
 		* glob
 		* os
 		* matplotlib
 		* PIL
 		* numpy
 		* math
 		* tensorflow
 		* nltk

##### Instructions
 	i)   Download the charades dataset into the same directory as the code.
  
 	ii)  Create a new conda enviornment (Refer https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)
  
 	iii) Install all the module dependencies to this newly created enviornment
  
 	iv)  Install jupyter notebook locally (Refer https://jupyter.readthedocs.io/en/latest/install.html)
  
 	iv)  Run jupyter notebook locally (Refer https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)
  
 	v)   Run the file 'image_embedding.ipynb' to generate the file 'img_ebd.npy'. This would process and extract the respective frames from the dataset and store it into the file 'img_ebd.npy'.
  
 	vi)  Now run the file 'CGM.ipynb' to train/test the model.

##### References
    1) C. Chiu, J. Zhan, F. Zhan, &quot;Uncovering suspicious activity from partially paired and
       incomplete multimodal data&quot;, IEEE Access, vol. 5, pp. 13689-13698, 2017.
    
    2) A. Shahroudy, T. T. Ng, Q. Yang, G. Wang, &quot;Multimodal multipart learning for action
       recognition in depth videos&quot;, IEEE Trans. Pattern Anal. Mach. Intell., vol. 38, no. 10,
       pp. 2123-2129, Oct. 2016.

    3) Fortin, Mathieu Pagé and Brahim Chaib-draa. “Multimodal Multitask Emotion
       Recognition using Images, Texts and Tags.” WCRML &#39;19 (2019).
    
    4) Shiqing Zhang, Shiliang Zhang, Tiejun Huang, and Wen Gao. 2016. Multimodal
       Deep Convolutional Neural Network for Audio-Visual Emotion Recognition. In
       Proceedings of the 2016 ACM on International Conference on Multimedia Retrieval
       (ICMR &#39;16). ACM, New York, NY, USA, 281-284.

    5) K. Chen, T. Bui, C. Fang, Z. Wang, and R. Nevatia. AMC: Attention guided multi-
        modal correlation learning for image search. In CVPR, 2017.

    6) Hori, C., Hori, T., Lee, T.Y., Zhang, Z., Harsham, B., Hershey, J.R., Marks, T.K.,
       Sumi, K.: Attention-based multimodal fusion for video description. In: 2017 IEEE
       International Conference on Computer Vision (ICCV).

    7) Ma, Haojie, Wenzhong Li, Xiao Zhang, Songcheng Gao, and Sanglu Lu.
       &quot;AttnSense: multi-level attention mechanism for multimodal human activity
       recognition.&quot; In Proceedings of the 28th International Joint Conference on Artificial
       Intelligence, pp. 3109-3115. AAAI Press, 2019.

