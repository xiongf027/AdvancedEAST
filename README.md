# SimpleEast
SimpleEast is derivied from the AdvancedEast and it's cut down for several times. So, the parameters are shrunk and the time is saved.
Besides it should applied for extracting the table texts.

# Project files
* config file:  
      cfg.py, control parameters
* loss file:  
      losses.py, define the model of loss function
* post-processing:  
      nms.py, generate coordinates according binary img  
      revise.py revise some results from different aspects  
* predict:  
      predict.py the whole process from one img to one json result  
* interface:  
      img2json.py

# DFG
![Image text](https://github.com/xiongf027/AdvancedEAST/blob/master/image/DFD.png)
